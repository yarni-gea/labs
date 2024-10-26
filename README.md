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

      tipe_tiket = input("masukkan tipe tiket (reguler/vip): ").lower()
      
      is_member = ("Apakah anda memilkii kartu member? ((ya/tidak): ").lower()

      # harga tiket

      Harga_regguler = 50000

      harrga_vip = 100000

      # Tentukan harga tiket

      harga_tiket = harga_reguler if tipe_tiket == `reguler` else harga_vip

      # jika member, berikan diskon 20%
      if is_member == `ya` :
            harga_tiket *=0.8 # diskon 20%

      # tampilkan total harga 
      print(f"total harga yang harus dibayar: Rp.{int(harga_tiket)} ")



      

penjelasan program:

1. pengguna di minta untuk memilih tipe tiket: reguler (Rp.50.0000) atau vip
   (Rp.100.000)
   
2. pengguna juga diminta untuk menyatakan apaka mereka memiliki karrtu
   member atau tidak.
   
3.jika pengguna  memiliki kartu member, mereka mendapatkan  diskon 20%

4.program menghitung total harga tiket berdasarkan tipe tiket dan status
   member.
   
5.program menampiilkan harga tiket yang harus di bayar oleh pengguna.

# flowchart

# flowchart adalah sebagai berikut :

![image](https://github.com/user-attachments/assets/e4e4f243-bf85-45a7-91ea-13f7c5f4983c)

# screenshot hasil eksekusi program :

<img width="437" alt="image" src="https://github.com/user-attachments/assets/cb5fa26b-40b5-429b-950f-761b82bb3b91">



