# Looping (Perulangan)

## Latihan1
### [Latihan1.py](https://github.com/irvanar/labpy03/blob/main/Latihan1.py)
* Tampilkan **n** bilangan acak yang lebih kecil dari 0.5
* Nilai **n** di isi pada saat runtime
* Anda dapat mengkombinasikan **while** dan **for** untuk menyelesaikannya
* Gunakan fungsi *random()* yang dapat di import terlebih dahulu
-----------
### Syntax Latihan1
```Python
print ("Masukan Nilai N: 5")
import random
jumlah = 5
a = 0
for x in range(jumlah):
    i = random.uniform(.0,.5)
    a+=1
    print("Data Ke : ",a,"==>",i)
print("Selesai")
```
### Hasil
![image](https://user-images.githubusercontent.com/84762007/147787222-6120aa08-d014-4742-9369-b274b30bf2b3.png)

-----------
## Latihan2
### [Latihan2.py](https://github.com/irvanar/labpy03/blob/main/Latihan2.py)
* Buat program untuk menampilkan bilangan **Terbesar** dari **n** buah data yang diinputkan.
* Masukan angka *0* untuk berhenti.
-----------

### Syntax Latihan2
```Python
max=0
while True:
    a=int(input("Masukan Bilangan : "))
    if max < a:
        max = a
    if a==0:
        break
print("Bilangan Terbesar adalah :",max)
```
### Hasil
![image](https://user-images.githubusercontent.com/84762007/147787270-2f0ac361-572f-4c58-b310-be3d10794b65.png)

-----------
## Program1
### [Program1.py](https://github.com/irvanar/labpy03/blob/main/program1.py)
* Buat repository baru **labpy03** 
* Masukkan *latihan1.py* dan *latihan2.py* ke dalam repository. 
* Buat program sederhana dengan perulangan: *program1.py*

Seorang pengusaha menginvestasikan uangnya untuk memulai usahanya dengan modal awal 100 juta, pada bulan pertama dan kedua belum mendapatkan laba. pada bulan ketiga baru mulai mendapatkan laba sebesar 1% dan pada bulan ke 5, pendapatan meningkat 5%, selanjutnya pada bulan ke 8 mengalami penurunan keuntungan sebesar 2%, sehingga laba menjadi 3%. Hitung total keuntungan selama 8 bulan berjalan usahanya.

* Buat file **README.md**, yang berisi penjelasan alur algoritma program *latihan1.py*, *latihan2.py*, dan *program1.py* beserta screenshot hasilnya.
* Kemudian commit dan push ke repository (github) 
* Kirim url repository ke classroom. 
-----------

### Syntax Program1
```Python
a=1000000000
for x in range(1,9):
    if(x>=1 and x<=2):
        b=a*0
        print("Laba bulan ke-",x, " : ",b)
    if(x>=3 and x<=4):
        c=a*0.1
        print("Laba bulan ke-",x, " : ",c)
    if(x>=5 and x<=7):
        d=a*0.5
        print("Laba bulan ke-",x, " : ",d)
    if(x==8):
        e=a*0.2
        print("Laba bulan ke-",x, " : ",e)
total = b+b+c+c+d+d+e
print("\nTotal : ",total)
```
### Hasil
![image](https://user-images.githubusercontent.com/84762007/147787467-b0d449a0-c4f3-48bd-83e7-88cd34fd1f95.png)

-----------
