# NAMA : ROSWANDA NURAINI

# NIM : 312210328

# KELAS : TI.22.A.3

# LAB 2: Struktur Kondisi

# LATIHAN 1 Program Menentukan Dua Bilangan Terbesar

![Screenshot (84)](https://user-images.githubusercontent.com/115516632/199914778-99912aca-7e54-4bf9-a624-12c78476add7.png)

Hasilnya

![Screenshot (82)](https://user-images.githubusercontent.com/115516632/199894626-fed75d13-13d2-4e60-86fc-a032bedbc29f.png)

# LATIHAN 2 Program Mengurutkan 3 Variabel dari Terkecil ke Terbesar

![Screenshot (102)](https://user-images.githubusercontent.com/115516632/200083322-349a3a11-e274-4939-98fc-fd79e5c4c6b7.png)

Hasilnya

![Screenshot (95)](https://user-images.githubusercontent.com/115516632/199908710-05183374-fd5c-49c0-9167-c213ef4195f2.png)

# LAB 3: Perulangan

# LATIHAN 1 Perulangan Bertingkat

![Screenshot (100)](https://user-images.githubusercontent.com/115516632/200083871-b6b2e72b-87b0-4546-9711-7f11a826dc8f.png)

-> penjelasan
1. pendeklarasian variable

2. untuk perulangan baris dan kolom menggunakan nested for

3. untuk menampilkan hasil dari perulangan
   - agar terlihat rapih menggunakan format string rata ke kanan sebanyak 5 karakter
   - agar tidak membuat banyak garis baru menggunakan end=''(baris)
   - penggunaan print()untuk membuat baris baru (kolom)

Hasilnya

![Screenshot (101)](https://user-images.githubusercontent.com/115516632/200084245-566ea08b-a800-485e-a58f-d107ae4acc6f.png)

# LATIHAN 2 Menampilkan N Bilangan Acak yang Lebih Kecil dari 0.5

![Screenshot (96)](https://user-images.githubusercontent.com/115516632/200084799-3fd00bfc-d65f-4cf1-b768-cb3858fd9aef.png)

-> penjelasan alur program
1. print ('tampilkan n bilanga acak yang lebih kecil dari 0.5) untuk menampilkan atau mencetak kalimat tampilkan N bilangan acak yang lebih kecil dari 0.5

2. jumlah=int(input("masukkan jumlah N :")) untuk menentukan jumlah input yang diinginkan sesuai dengan tipe data yaitu interger tipe data bilangan bulat 

3. import random*

4. for i in range (jumlah) : untuk pengulangan dengan range jumlah 

5. print("data ke"),1+i,"=>",(random.unifrom(0.1,0.5))) untuk menampilkan atau mencetak urutan data sesuai jumlah inputan dengan hasil di bawah 0.5

Hasilnya

![Screenshot (97)](https://user-images.githubusercontent.com/115516632/200085598-fa3718fc-c829-45f5-ba76-e55859ccd47f.png)

## Modul Praktikum 2

# Tugas Praktikum 2

![Screenshot (79)](https://user-images.githubusercontent.com/115516632/200090309-a26a37f3-8d24-42bf-8b0f-92f21bd41e0c.png)

-> penjelasan

untuk kasus dengan banyak kondisi,if tetap dapat digunakan dengan menggunakan if bersarang (nasted if).sebagai contoh saya akan membuat program sederhana menampilkan bilangan terbesar dari 3 buah bilangan.

A.untuk mencari bilangan terbesar dari 3 bilangan algoritmanya yang dimasukkan akan membandingkan terlebih dahulu apakah a>b.

B.jika a>b,maka ada 2 kadidat bilangan terbesar,yaitu a dan c sehingga perlu dilakukan pengujian yang manakah dari a dan c yang lebih besar dengan melakukan membandingkan nilai b dan c. jika nilai b ternyata lebih besar dari c, maka bilangan terbesar adalah a.nilai terbesar adalah c jika ternyata c lebih besar dari dari a.

C.jika kondisi a>b tidak terpenuhui(atau b<=a),maka 2 kadidat bilangan terbesar adalah b dan c.jika nilai c ternyata lebih kecil dari a,maka b adalah nilai terbesar,sedangakan jika c yang lebih besar dari b,maka yang terbesar adalah c.

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

Hasilnya

![Screenshot (80)](https://user-images.githubusercontent.com/115516632/200091494-1b67872e-8b81-49bc-8018-82af0dd5654d.png)

## Modul Pratikum 3

# Latihan 1 Program Sederhana untuk Menampilkan N Bilangan Acak yang Lebih Kecil dari 0.5

# A. Algoritma Program untuk Menampilkan N Bilangan Acak yang Lebih Kecil dari 0.5

1. Masukkan jumlah N pengulangan

2. Proses pengulangan sesuai jumlah pengulangan yang diinputkan 

3. Tampilkan pengulangan dengan nilai di bawah 0.5

4. Selesai










