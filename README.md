# membuat kode program dari flowchart pertemuan ke-5 

tugas pertemuan ke 6

nama yarni gea 

kelas:TI.24.A3

nim: 312410413

Bilangan terbesar dari 

1. bilangan terbesar.py

program pertama yang akan di buat

adalah program untuk menampilkan

bilangan terbesar 3 dari bilangan yang di

inputkan 

berikut flowchartnya 

![image](https://github.com/user-attachments/assets/34fc0cdd-81a5-49e4-8206-76fd6518720a)


 ## program akan meminta kita

## memasukkan 3 angka untuk

## dibandingkan 

<img width="388" alt="image" src="https://github.com/user-attachments/assets/dbd1a955-3396-4065-829d-e007ebc62070">

penjelasan

def mencari_bilangan_terbesar(a, b, c):

if a > b :

     if a > c

         return a, "A adalah bilangan terbesar" 

     else:

          return c, "c adalah terbesar"

else:

     if b > c:

          return b, "B adlalah terbesar"

     else:

          return c, "C adalah terbesar"

 input bilangan A, B,  C 

print("masukkan tiga bilangan:")  

a = float(input("A: "))

b = float(input("B: "))

c = floaat(input("C: "))

# menentukan bilangan terbesar 

largest, message = mencari_bilanga_terbesar(a, b, c)

# menampilkan hasil 

print(f"\n{message}")

print(f"Bilangan terbesar adalah: {largest}"]

1. kita menedefenisika function

   mencari_bilangan_terbesar yang

   mengambil tiga paramrter(a,b,b)

2. funtion tersebut menggunakan

   nested if-else statement untuk

   membandingkan angka yanng di
 
   inputkan

3. kemudian akan menampilkan mana

   bilangan terbesar

4. lalu program utamanya kita

   masukkan angka yang harus

   dimasukkan oleh user

5.lalu kita panggil kembali function

   mencari_bilangan_terbesar 

6. lalu output bilangan tersebut dari

   ketiga bilangan yang di input akan

   muncul

# 2. bilanganN.py

program kedua adalah 

membandinggkan bilangan yang di input,

input akan terus berjalan kecuali user

memasukkan nilai 0 

![image](https://github.com/user-attachments/assets/03ba14fe-993e-4089-b8f2-329fdf75bd20)

program akan meminta kita  untuk

memasukkan angka untuk

di bandingkan,`input akan terus diminta 

sebelum user memasukkan angka 0: 

<img width="361" alt="image" src="https://github.com/user-attachments/assets/00d9719d-61fb-4702-ac16-81494344f8a8">

penjelasan code

def find_largest_number():

Mendefinisikan fungsi bernama find_largest_number yang akan menangani logika utama program.

largest = float('-inf')  # Inisialisasi dengan nilai negatif tak terhingga

Menginisialisasi variabel largest dengan nilai negatif tak terhingga. Ini memastikan bahwa angka pertama yang dimasukkan akan selalu lebih besar.

*Maksud dari -infinity(Negatif tak hingga) adalah nilai negatif berapapun.

count = 0

Menginisialisasi variabel count untuk menghitung jumlah bilangan yang dimasukkan.

Memulai loop tak terbatas. Akan terus berjalan sampai dihentikan oleh break.

num = float(input(f"Masukkan bilangan ke-{count + 1} (atau 0 untuk selesai): "))

Meminta input dari pengguna, mengkonversinya ke float, dan menyimpannya dalam variabel num.

Jika input adalah 0, keluar dari loop.

count += 1
Menambah penghitung jumlah bilangan yang dimasukkan.

if num > largest:
            largest = num
Jika bilangan yang baru dimasukkan lebih besar dari largest saat ini, update largest.

return largest, count
Setelah loop selesai, kembalikan bilangan terbesar dan jumlah input.

print("Program untuk menentukan bilangan terbesar dari N bilangan")
print("Masukkan angka 0 untuk mengakhiri input\n")
Mencetak instruksi untuk pengguna.

largest, count = find_largest_number()
Memanggil fungsi find_largest_number() dan menyimpan hasilnya.

if count > 0:
Memeriksa apakah ada bilangan yang dimasukkan.

print(f"\nJumlah bilangan yang dimasukkan: {count}")
    print(f"Bilangan terbesar adalah: {largest}")
Jika ada bilangan yang dimasukkan, cetak jumlah input dan bilangan terbesar.

else:
    print("\nTidak ada bilangan yang dimasukkan.")
Jika tidak ada bilangan yang dimasukkan (pengguna langsung memasukkan 0), program akan dijalankan dan menampilkan output perbandingan.

About
No description, website, or topics provided.
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 1 watching
Forks
 1 fork
Report repository
Releases
No releases published
Packages
No packages published
Languages
Python
100.0%
Footer
© 2024 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact
Manage cookies




 


   











    
 




