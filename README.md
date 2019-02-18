# Labpy03

# Latihan1.py
```python
import random
n = input("masukan nilai N:")

for x in range (1,6):
  print("data ke:",x,"=>",random.uniform(0.0,0.5))
print("Selesai")
```

* masukan nilai N=5

* gunakan for range, untuk mengulang data

* cetak data dan memasukan random.uniform kurang dari 0.5

* jika selesai maka RUN

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
* masukan max=0

* gunakan while True, untuk perulangan tak terbatas, setelah itu masukan bilangan

* if jika memasukan angka 0 maka akan berhenti

* setelah memasukan angka 0 maka otomatis nilai max akan muncul


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

![screenshot 37](https://user-images.githubusercontent.com/46512670/52928535-d38c8200-3372-11e9-89d7-f1230cc39e09.png)
