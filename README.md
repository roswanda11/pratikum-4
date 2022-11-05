# NAMA : ROSWANDA NURAINI

# NIM : 312210328

# KELAS : TI.22.A.3


# LAB 2: Struktur Kondisi

# LATIHAN 1 Program Menentukan Dua Bilangan Terbesar

![Screenshot (84)](https://user-images.githubusercontent.com/115516632/199914778-99912aca-7e54-4bf9-a624-12c78476add7.png)

## Hasilnya

![Screenshot (82)](https://user-images.githubusercontent.com/115516632/199894626-fed75d13-13d2-4e60-86fc-a032bedbc29f.png)

# LATIHAN 2 Program Mengurutkan 3 Variabel dari Terkecil ke Terbesar

![Screenshot (102)](https://user-images.githubusercontent.com/115516632/200083322-349a3a11-e274-4939-98fc-fd79e5c4c6b7.png)

## Hasilnya

![Screenshot (95)](https://user-images.githubusercontent.com/115516632/199908710-05183374-fd5c-49c0-9167-c213ef4195f2.png)

# LAB 3: Perulangan

# LATIHAN 1 Perulangan Bertingkat

![Screenshot (103)](https://user-images.githubusercontent.com/115516632/200093615-ead8941b-0c00-470a-9b0f-94b148a39ebc.png)

### -> penjelasan

1. Pendeklarasian variable

2. Untuk perulangan baris dan kolom menggunakan nested for

3. Untuk menampilkan hasil dari perulangan
   - Agar terlihat rapih menggunakan format string rata ke kanan sebanyak 5 karakter
   - Agar tidak membuat banyak garis baru menggunakan end=''(baris)
   - Penggunaan print()untuk membuat baris baru (kolom)

## Hasilnya

![Screenshot (104)](https://user-images.githubusercontent.com/115516632/200093425-0163e68b-7ea8-42d5-b46b-8b3758c969bf.png)

# LATIHAN 2 Menampilkan N Bilangan Acak yang Lebih Kecil dari 0.5

![Screenshot (96)](https://user-images.githubusercontent.com/115516632/200084799-3fd00bfc-d65f-4cf1-b768-cb3858fd9aef.png)

### -> penjelasan alur program

1. print ('tampilkan n bilanga acak yang lebih kecil dari 0.5) untuk menampilkan atau mencetak kalimat tampilkan N bilangan acak yang lebih kecil dari 0.5

2. jumlah=int(input("masukkan jumlah N :")) untuk menentukan jumlah input yang diinginkan sesuai dengan tipe data yaitu interger tipe data bilangan bulat 

3. import random*

4. for i in range (jumlah) : untuk pengulangan dengan range jumlah 

5. print("data ke"),1+i,"=>",(random.unifrom(0.1,0.5))) untuk menampilkan atau mencetak urutan data sesuai jumlah inputan dengan hasil di bawah 0.5

## Hasilnya

![Screenshot (97)](https://user-images.githubusercontent.com/115516632/200085598-fa3718fc-c829-45f5-ba76-e55859ccd47f.png)

## Modul Praktikum 2

# Tugas Praktikum 2 Program Sederhana dengan Menampilkan Bilangan Terbesar dari Tiga Bilangan

![Screenshot (79)](https://user-images.githubusercontent.com/115516632/200090309-a26a37f3-8d24-42bf-8b0f-92f21bd41e0c.png)

### -> penjelasan

Untuk kasus dengan banyak kondisi,if tetap dapat digunakan dengan menggunakan if bersarang (nasted if).sebagai contoh saya akan membuat program sederhana menampilkan bilangan terbesar dari 3 buah bilangan.

A. Untuk mencari bilangan terbesar dari 3 bilangan algoritmanya yang dimasukkan akan membandingkan terlebih dahulu apakah a>b.

B. Jika a>b,maka ada 2 kadidat bilangan terbesar,yaitu a dan c sehingga perlu dilakukan pengujian yang manakah dari a dan c yang lebih besar dengan melakukan membandingkan nilai b dan c. jika nilai b ternyata lebih besar dari c, maka bilangan terbesar adalah a.nilai terbesar adalah c jika ternyata c lebih besar dari dari a.

C. Jika kondisi a>b tidak terpenuhui(atau b<=a),maka 2 kadidat bilangan terbesar adalah b dan c.jika nilai c ternyata lebih kecil dari a,maka b adalah nilai terbesar,sedangakan jika c yang lebih besar dari b,maka yang terbesar adalah c.

perhatikan hasil flowchart berikut ini:

![Screenshot (105)](https://user-images.githubusercontent.com/115516632/200091054-2e820d1d-7094-4b09-8f56-9ca14c73bd99.png)

perhatikan struktur algoritma dengan pseudecode berikut ini:

1.start

2.gunakaan inisial a,b,c sebagai intenjer.

3.read a

4.read b

5.read c

6.if a>b and a<c:

7.cetak "a terbesar dari bilangan yang diinputkan"

8.elif b>a and b>c:

9.cetak "b terbesar dari bilangan yang diinputkan"

10.else

11.cetak "c terbesar dari bilangan yang diiinputkan"

12.cetak " nilai terbesar yang diinputkan"

13.stop

## Hasilnya

![Screenshot (80)](https://user-images.githubusercontent.com/115516632/200091494-1b67872e-8b81-49bc-8018-82af0dd5654d.png)

## Modul Pratikum 3

# Latihan 1 Program Sederhana untuk Menampilkan N Bilangan Acak yang Lebih Kecil dari 0.5

## A. Algoritma Program untuk Menampilkan N Bilangan Acak yang Lebih Kecil dari 0.5

1. Masukkan jumlah N pengulangan

2. Proses pengulangan sesuai jumlah pengulangan yang diinputkan 

3. Tampilkan pengulangan dengan nilai di bawah 0.5

4. Selesai

## B. Flowchart Program

![flowchart n bilangan 0 5](https://user-images.githubusercontent.com/115516632/200092961-38f7ea61-421b-476c-8f5c-80d7cfe3ae0b.png)

## C. Program untuk Menampilkan N Bilangan Acak yang Lebih Kecil dari 0.5

![Screenshot (108)](https://user-images.githubusercontent.com/115516632/200093066-9b0e64db-67d7-4c96-b063-12aa506ba969.png)

### -> penjelasan alur program

1. print ('tampilkan n bilanga acak yang lebih kecil dari 0.5) untuk menampilkan atau mencetak kalimat tampilkan N bilangan acak yang lebih kecil dari 0.5

2. jumlah=int(input("masukkan jumlah N :")) untuk menentukan jumlah input yang diinginkan sesuai dengan tipe data yaitu interger tipe data bilangan bulat 

3. import random*

4. for i in range (jumlah) : untuk pengulangan dengan range jumlah 

5. print("data ke"),1+i,"=>",(random.unifrom(0.1,0.5))) untuk menampilkan atau mencetak urutan data sesuai jumlah inputan dengan hasil di bawah 0.5

## Hasilnya

![Screenshot (109)](https://user-images.githubusercontent.com/115516632/200093363-b992633d-f9a7-4d1d-91ea-56fa2ee25e14.png)

# Latihan 2 Program Sederhana untuk Menampilkan Bilangan Terbesar dari N Buah Data yang Diinputkan

## A. Algoritma Program untuk Menampilkan Bilangan Terbesar dari N Buah Data yang Diinputkan

1. Mulai
  
2. Input bilangan N
    
3. Jika max < a maka akan lanjut pengulangan 4.Jika a==0 maka akan berhenti proses pengulangan
    
4. Dan mencetak hasil nilai maxium dari N yang di isikan
    
5. Selesai

## B. Flowchart Program

![flowchart lat2](https://user-images.githubusercontent.com/115516632/200094137-9ccb1d5c-b251-4906-b82d-d9f20a936f6e.png)

## C. Program untuk Menampilkan Bilangan Terbesar dari N Buah Data yang Diinputkan

![Screenshot (100)](https://user-images.githubusercontent.com/115516632/200095070-2f1d64d8-83e6-45dc-addc-e87a1b8a4bbb.png)

### -> penjelasan alur program

1. print ('Menampilkan Bilangan Terbesar Dari N Buah Data Yang Diinputkan') Untuk menampilkan kalimat Menampilkan Bilangan Terbesar Dari N Buah Data Yang Diinputkan

2. max= 0 kode max disini untuk menentukan nilai max nya dalah 0

3. while true: Untuk perulangan hingga waktu yang tidak di tentukan atau selamanya

4. a=int(input("Masukan Bilangan :")) a untuk menginput tipe data interger ( bilangan bulat )

5. if max < a max=a jika max kurang dari a maka max = a

6. if a==0: break jika a= 0 maka akan berhenti dengan syarat break yang terpenuhi

7. print("Bilangan Tebesar Adalah :", max) Menampilkan *Bilangan Tebesar Adalah : Nilai maxiumnya

## Hasilnya

![Screenshot (101)](https://user-images.githubusercontent.com/115516632/200095392-9ad0cbf2-81ce-44f3-8076-e6094307a2ed.png)

# Program 1: Program Sederhana untuk Menghitung Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan

## A. Algoritma Program untuk Menghitung Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan

1. Mulai
2. Input modal misalkan x = 100.000.000 ( deklarasikan )
3. Input presentase untung a=0x, b=0x, c=0.01x, d=0.01x, e=0.05x, f=0.05x, g=0.05x, h=0.03x
4. For i in range (len (y)) pengulangan
5. Print (“laba bulan ke-“,i+1,”sebesar:” ,y[i])
6. Menghitung jumlah laba keseluruhan Z= (a+b+c+d+e+f+g+h)
7. Print (“jumlah laba selama 8 bulan adalah:”)
8. Selesai

## B. Flowchart Program 1

![flowchart program 1](https://user-images.githubusercontent.com/115516632/200095918-061b9233-446c-42de-820e-18943f616d77.png)

## C. Program Untuk Menghitung Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan

![Screenshot (98)](https://user-images.githubusercontent.com/115516632/200096036-462a054a-e4de-427a-a3b8-501d0020b520.png)

### -> penjelasan alur program

1. print ('Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan') Untuk Menampilkan kalimat Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan

2. x=100000000 Dengan pemisalan atau dideklarasikan x adalah 100000000

3. print (" Modal Awal:",x) Menampilkan kalimat Modal Awal : dan data yang berisi di x yaitu 100000000

4. a=0x, b=0x, c=0.01x, d=0.01x, e=0.05x, f=0.05x, g=0.05x, h=0.03x Untuk Mendeklarasikan presentase laba tiap bulan dan di kali dengan x atau data inputan modal investasi yaitu 100000000

5. y=[a,b,c,d,e,f,g,h] untuk menentukan syarat y= yang berisi a,b,c,d,e,f,g,h

6. For i in range (len (y)) Print (“laba bulan ke-“,i+1,”sebesar:” ,y[i]) untuk perulangan data dengan isi data yaitu Ydengan menampilkan urutan laba perbulan sesuai range yang di tentukan dengan hasil ke untukan yang di inpput dari data Y

7. Z= (a+b+c+d+e+f+g+h) Print (“jumlah laba selama 8 bulan adalah:”) Z berisi data penjumlahan data angka yang ada didalam kode a,b,c,d,e,f,g,h yang akan di tampilakan atau dicetak di jumlah laba selama 8 bulan

## Hasilnya 

![Screenshot (99)](https://user-images.githubusercontent.com/115516632/200096224-3a4f7da6-fbe0-44bc-8ef5-d056d513cfce.png)


#### SEKIAN TERIMAKASIH ####
