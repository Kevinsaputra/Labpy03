# Labpy03

# Latihan1.py
```python
import random
n = input("masukan nilai N:")

for x in range (1,6):
  print("data ke:",x,"=>",random.uniform(0.0,0.5))
print("Selesai")
```

* random berfungsi mengembalikan bilangan float random x, dimana 0 < x < 1. 
  Fungsi random() tidak memiliki parameter masukan.
* range digunakan untuk menghasilkan urutan dari angka tanpa harus mendeklarasikan dari list variablenya.
* uniform(x,y) digunakan untuk menampilkan bilangan float random dengan batas awal bilangan x, dan batas akhir bilangan y.
  pada codingan diatas saya membatasi bilangan awal 0.0 dan batas bilangan akhirnya 0.5
  
![screenshot 35](https://user-images.githubusercontent.com/46512670/52928433-35002100-3372-11e9-82f9-99707e38bd2e.png)

# Latihan02.py
```python
max = 0
while True:
	a = int(input("Masukan Bilangan:"))
	if a == 0:
		break
	if a>max:
		max=a
print("Bilangan terbesar adalalah:",max) 
```
* Fungsi max() adalah fungsi build-in untuk mencari nilai tertinggi. fungsi ini dapat diberikan sebuah parameter berupa angka.
* Perulangan while disebut uncounted loop (perulangan yang tak terhitung), yaitu perulangan yang dilakukan berdasarkan kondisi    tertentu selama nilai kondisi bernilai TRUE.
* Pernyataan break dan continue Pernyataan break digunakan untuk menghentikan proses perulangan pada kondisi tertentu, sedangkan pernyataan continue digunakan untuk melanjutkan pada iterasi selanjutnya pada kondisi tertentu.
* Pada codingan di atas saya menggunakan break.

![screenshot 36](https://user-images.githubusercontent.com/46512670/52928532-ca031a00-3372-11e9-82ad-bded874015a8.png)

# Latihan03.py
```python
a = 100000000

for x in range(1,9):
    if(x>=1 and x<=2):
       b = a*0
       print("Laba Bulan ke-",x," :",b)
    if(x>=3 and x<=4):
       c = a*0.1
       print("Laba Bulan ke-",x," :",c)
    if(x>=5 and x<=7):
       d = a*0.5
       print("Laba Bulan ke-",x," :",d)
    if(x==8):
       e = a*0.2
       print("Laba Bulan ke-",x," :",e)
total = b+b+c+c+d+d+d+e
print("\ntotal : ", total)
```
* Perulangan for disebut juga sebagai counted loop (perulangan yang terhitung), yaitu perintah yang dieksekusi secara berulang berdasarkan jumlah perulangan tertentu
* range digunakan untuk menghasilkan urutan dari angka tanpa harus mendeklarasikan dari list variablenya.
* if dalam Python dijalankan untuk memeriksa apakah kondisi ini adalah bernilai benar atau salah. Jika kondisi ini bernilai true, maka python akan menjalankan statemen didalam blok kondisi tersebut dan sebaliknya jika kondisi bernilai false maka statemen didalam blok tersebut tidak akan dijalankan
* print \ntotal berfungsi untuk menampilkan hasil penjumlahan.

![screenshot 37](https://user-images.githubusercontent.com/46512670/52928535-d38c8200-3372-11e9-89d7-f1230cc39e09.png)
