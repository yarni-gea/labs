## laporan praktikum 02
# nama: yarni gea
# nim : 312410413
# kelas: TI.24.A3

1.program pemesanan tiket 

Deskripsi program:
program ini menghitung harga tiket bioskop berdasarkan tipe tiket yang di pilih
pengguna (reguler atau vip) dan status member pengguna.jika pengguna adalah member, meraka akan mendapatkan diskon dari harga tiket.

# Kasus 1: Program Pemesanan Tiket Bioskop

# input user 
tipe_tiket = input("masukkan tipe tiket (reguler/VIP): ").lower()
is_member = input("apakah anda memiliki kartu member? (ya/tidak): ")

# Harga tiket
harga_reguler =  50000
harga_vip = 10000

# Tentukan harga tiket
harga_tiket = harga_reguler if tipe_tiket == `reguler` else harga_vip

# jika member, berikan harga diskon 20%
if is_member == `ya`:
   harga_tiket *= 0.8 #diskon 20%

# Tampilkan total harga 
print(f"total harga yang harus dibayar: RP{int(harga_tiket)}")

   

