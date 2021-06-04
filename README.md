# Pemograman Web
~~~
Nama  : Arif Samsudin
NIM   : 311910255
Kelas : TI 19 C1
~~~
# 1. Persiapan
Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah
database server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan
melalui XAMPP.
# Menjalankan MySQL Server
Untuk menjalankan MySQL Server dari menu XAMPP Contol.
![1  Persiapan](https://user-images.githubusercontent.com/81839328/120868349-16afa500-c5be-11eb-93e4-07492d84acc0.JPG)

# Mengakses MySQL Client menggunakan PHP MyAdmin
Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka
melalui browser: http://localhost/phpmyadmin/

# 2. Membuat Database: Studi Kasus Data Barang
![Capture](https://user-images.githubusercontent.com/81839328/120868532-7312c480-c5be-11eb-9436-c93aad7bf14a.JPG)

# 3.Membuat Database
~~~
CREATE DATABASE latihan1;
~~~

# 4. Membuat Tabel
~~~
CREATE TABLE data_barang (
id_barang int(10) auto_increment Primary Key,
kategori varchar(30),
nama varchar(30),
gambar varchar(100),
harga_beli decimal(10,0),
harga_jual decimal(10,0),
stok int(4)
);
~~~
![2  membuat tabel](https://user-images.githubusercontent.com/81839328/120868798-03e9a000-c5bf-11eb-9643-29a9065ea70b.JPG)

# 5. Menambahkan Data
~~~
INSERT INTO data_barang (kategori, nama, gambar, harga_beli, harga_jual, stok)
VALUES ('Elektronik', 'HP Samsung Android', 'hp_samsung.jpg', 2000000, 2400000, 5),
('Elektronik', 'HP Xiaomi Android', 'hp_xiaomi.jpg', 1000000, 1400000, 5),
('Elektronik', 'HP OPPO Android', 'hp_oppo.jpg', 1800000, 2300000, 5);
~~~
![3  Menambahkan data](https://user-images.githubusercontent.com/81839328/120868891-4317f100-c5bf-11eb-83a2-ae9f289da62b.JPG)
![3  hasil](https://user-images.githubusercontent.com/81839328/120868900-49a66880-c5bf-11eb-8d8f-d0d141d6dc9a.JPG)

