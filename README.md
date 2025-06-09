# PROJEK API SEDERHANA
**Ini adalah sebuah projek API sederhana yang dibuat menggunakan PHP native untuk mengelola sebuah data pengguna. API ini mendukung Method CRUD (Create, Read, Update, Delete).**

## Teknologi
* **PHP 8.1**
* **Apache (via XAMPP)**
* **MySQL  (via XAMPP)**

## Instalasi
**1.  Pertama Clone dulu Repository ini:
2.  Letakkan folder Clone tadi ke Htdocs di dalam Folder Xampp
3.  Buat database baru di phpMyAdmin dengan nama `chataibeckend2`.
4.  Import file `database.sql` (jika ada) ke dalam database tersebut.
5.  Sesuaikan koneksi database di dalam file `config.php`.
6.  Jalankan server Apache dan MySQL melalui Xampp.
7.  API siap diakses melalui `http://localhost/response-api-sederhana/`.**

## Endpoints API

Berikut adalah daftar endpoint yang tersedia:
(◣_◢)
---

### 1. Menampilkan Semua Pengguna
* **Method:** `GET`
* **Endpoint:** `/users`
* **Contoh URL:** `http://localhost/response-api-sederhana/index.php?path=users`
 ![GET POSTMAN](https://github.com/user-attachments/assets/1e27534f-17c6-4358-9d36-605d2ef78d53)


### 2. Membuat Pengguna Baru
* **Method:** `POST`
* **Endpoint:** `/users`
* **Contoh URL:** `http://localhost/response-api-sederhana/index.php?path=users`
*  **Bisa kita ilihat bahwa user baru yang ditambahkan melalui method POST akan masuk ke dalam database**
 ![POSTMAN POST](https://github.com/user-attachments/assets/879aa177-9b13-433d-b2b5-3414f3fdaecb)
* **Dan ini data yang sudah kita input tadi dengan method 'POST'**
 ![database](https://github.com/user-attachments/assets/cddcb3c8-4a7a-4ccc-8bd9-423ede0c89c9)
  

### 3. Mengupdate Data Pengguna
* **Method:** `PUT`
* **Endpoint:** `/users`
* **Contoh URL:** `http://localhost/response-api-sederhana/index.php?path=users`
![PUT POSTMAN](https://github.com/user-attachments/assets/58a1ce20-6092-4346-a09e-4e490f9c88b6)


### 4. Menghapus Data Pengguna
* **Method:** `DELETE`
* **Endpoint:** `/users`
* **Contoh URL:** `http://localhost/response-api-sederhana/index.php?path=users/7`
* ![DELETE POSTMAN](https://github.com/user-attachments/assets/c28f1f42-b414-41dd-ae77-1dea2ccf1bff)
* **Setelah Method DELETE di request maka perubahan dapat dilihat pada database**
![DATABASE BARU DI DELETE](https://github.com/user-attachments/assets/36f9a571-f40f-4050-b0e4-4f0699a71af3)

  



  

  


