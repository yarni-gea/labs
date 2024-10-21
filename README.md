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

mendefensikan fungsi  bernama

find_largest_number yang akan 

menangani logika utama program.

    largest = float('-inf')  

menginisialisasi variabel largest dengan 

nilai negatif tak terhingga. ini

memastikan bahwa angka selalu lebih besar.

*maksud dari -infinity(negatif tak hingga)

adalah nilai negatif berapapun.

    count = 0

menginisialisasi variabel count untuk

menghitung jumlah bilangan yang 

dimasukkan

    while true:

memulai loop tak terbatas. Akan terus

berjalan sampai dihentikan oleh break.

     num = float(input(f"masukkan bilangan ke-{count + 1} (atau 0untuk selesai):"))

meminta input dari pengguna,

mengkonversinya ke float, dan

menyimpannya dalam variabel num.

     if num == 0:

                 break

jika input adalah o, keluar dari loop.

        count += 1

menambah penghitung jumlah bilangan

lebih besar dari largest saat ini, update

largest.

        return largest, count

setelah loop selesai, kembalikkan

bilangan tersebut dan jumlah input.

       print("program untuk menentukan bilangan terbesar dari N bilangan")
       print("masukkan angka 0 untuk mengakhiri input\n")

mencetak instruksi untuk pengguna.

       largest, count = find_largest_number()

memanggil fungsi find_largest_number()

dan menyimpan hasilnya.

      if count > 0:
mememriksa apakah ada bilangan yang

dimasukkan.

        print(f"\njumlah bilangan yang dimauskkan: {count}")
               print(f"Bilangan terbesar adalah: {largest}")

jika ada bilangan yang dimasukkan,

cetak jumlah input dan bilangan terbesar.

       else:

            print("\ntidak ada bilangan yang dimasukkan.")


       

         


        



           
            





 

