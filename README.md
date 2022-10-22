# tugas python pertemuan5

Tugas Bahasa Pemrograman Pertemuan-5<br><br>
Nama : Muhammad Shiddiq <br>
NIM : 312210125<br>
Kelas : TI.22.B1<br>

## Install Python
1. download python pada web Remis python [di sini](https://python.org)

![download python](https://user-images.githubusercontent.com/47426095/196260682-ab4d3c1a-b0d9-47ea-8737-db2b81b58410.PNG)

2. buka lalu centang bagian *add python to PATH* lalu klik install now
![install python](https://user-images.githubusercontent.com/47426095/196260923-3c52d21d-89d4-465d-b0d2-ae11e1906d6c.PNG)
![install python2](https://user-images.githubusercontent.com/47426095/196261110-f1242a77-73a2-46e8-91d4-c428e9bdfd7e.PNG)


3. Instalasi Selesai, klik close

![install success](https://user-images.githubusercontent.com/47426095/196261213-d2d12ebd-893a-4e82-9715-28422d4fcc7b.PNG)


## Latihan 1
* buat file latihan1.py

![Screenshot (35)](https://user-images.githubusercontent.com/115475520/197347169-b7cba137-2e49-49c2-99a9-7639bec53116.png)

* tulis kode seperti contoh

![Screenshot (36)](https://user-images.githubusercontent.com/115475520/197347257-9b7f32ae-1141-4c4d-bedd-78c09502d54c.png)

```python
#menampilkan tulisan 'Hello' di layar
print("Hello")
#menampilkan tulisan 'Saya sedang belajar python' di layar
print("Saya sedang belajar python")
```
* klik tombol run

![run python](https://user-images.githubusercontent.com/47426095/196226867-b202f7d9-79ae-4577-b93f-8279d92d42a5.PNG)

* maka akan muncul program yang dijalankan

![Screenshot (32)](https://user-images.githubusercontent.com/115475520/197347040-1f436484-6c82-4730-8590-48e35bf31cbe.png)
```
Hello
Saya sedang belajar python
```


## Latihan 2
* buat file latihan2.py

![Screenshot (37)](https://user-images.githubusercontent.com/115475520/197347365-72986f5c-9ba9-4d0f-811a-09e4eb430ab5.png)

* tulis kode seperti contoh

![Screenshot (38)](https://user-images.githubusercontent.com/115475520/197347394-d25ba60a-bf03-4ba5-8a5c-8f1e0cdaaeaa.png)

``` python
# menjumlahkan dua bilangan menggunakan variabel a & b
a = 8
b = 6

print("Variabel a =",a)
print("Variabel b =",b)
print("hasil penjumlahan a + b =", a+b)
```


* klik tombol run

![run python](https://user-images.githubusercontent.com/47426095/196226867-b202f7d9-79ae-4577-b93f-8279d92d42a5.PNG)

* maka akan muncul program yang dijalankan

![Screenshot (39)](https://user-images.githubusercontent.com/115475520/197347445-0576e5b8-be6b-4e8f-897c-f042b38264b1.png)

```
Variabel a = 8
Variabel b = 6
hasil penjumlahan a + b = 14
```


## Latihan 3
* buat file latihan3.py

![Screenshot (40)](https://user-images.githubusercontent.com/115475520/197347571-35ee3b5c-99ef-4c3d-9691-1c0cc5927c82.png)

* tulis kode seperti contoh

![Screenshot (41)](https://user-images.githubusercontent.com/115475520/197347596-d06440d0-8101-4441-b869-61feacb11a1a.png)

```python
#input nilai variabel
a = input("masukan nilai pertama: ")
b = input("masukan nilai kedua: ")

#cetak nilai variabel
print("variabel a = ", a)
print("variabel b = ", b)

#cetak hasil kedua operasi variabel dengan string format
print("Hasil Penggabungan {1} & {0} = ".format(a,b) + str(a)+str(b))

#konversi nilai variabel 
a = int(a);
b = int(b);

print("Hasil penjumlahan {1} + {0} = %d".format(a,b) %(a+b))
print("Hasil pembagian {1} / {0} = %d".format(a,b) %(a/b))
```
* klik tombol run

![run python](https://user-images.githubusercontent.com/47426095/196228887-fddb8a47-afc5-4476-af01-e03a07e849ab.PNG)

* maka akan muncul program yang dijalankan, jangan lupa masukan angka

![Screenshot (42)](https://user-images.githubusercontent.com/115475520/197347633-7b44d437-4a59-41d8-97eb-2846fb91da9d.png)

```
masukan nilai pertama: 8
masukan nilai kedua: 8
variabel a =  8
variabel b =  8
Hasil Penggabungan 8 & 8 = 88
Hasil penjumlahan 8 + 8 = 16
Hasil pembagian 8 / 8 = 1
```
