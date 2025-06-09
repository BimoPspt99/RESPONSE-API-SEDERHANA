# Proyek API Sederhana (response-api-sederhana)

Ini adalah proyek API sederhana yang dibuat menggunakan PHP native untuk mengelola data pengguna (Users). API ini mendukung operasi CRUD (Create, Read, Update, Delete).

## Teknologi
* PHP 8.1
* Server Apache (via XAMPP)
* MySQL / MariaDB

## Instalasi
1.  Pertama Clone dulu Repository ini:
2.  Letakkan folder Clone tadi ke Htdocs di dalam Folder Xampp
3.  Buat database baru di phpMyAdmin dengan nama `chataibeckend2`.
4.  Import file `database.sql` (jika ada) ke dalam database tersebut.
5.  Sesuaikan koneksi database di dalam file `config.php`.
6.  Jalankan server Apache dan MySQL melalui Xampp.
7.  API siap diakses melalui `http://localhost/response-api-sederhana/`.

## Endpoints API

Berikut adalah daftar endpoint yang tersedia:

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
*  Bisa kita ilihat bahwa user baru yang ditambahkan melalui method POST akan masuk ke dalam database
 ![POSTMAN POST](https://github.com/user-attachments/assets/879aa177-9b13-433d-b2b5-3414f3fdaecb)


### 3. Mengubah Data Pengguna(Update)
* **Method:** `PUT`
* **Endpoint:** `/users`
* **Contoh URL:** `http://localhost/response-api-sederhana/index.php?path=users`
  ![Screenshot 2025-06-07 001116](https://github.com/user-attachments/assets/d6a8f5e3-5a77-4d17-9d6b-5b657b94e2af)
  Setelah Method PUT di request maka perubahan dapat dilihat pada database
  ![Screenshot 2025-06-07 001208](https://github.com/user-attachments/assets/4259a1a8-629a-4fda-ae33-d3c8e720a7f0)

### 4. Menghapus Data Pengguna
* **Method:** `DELETE`
* **Endpoint:** `/users`
* **Contoh URL:** `http://localhost/response-api-sederhana/index.php?path=users/7`
  ![Screenshot 2025-06-07 001428](https://github.com/user-attachments/assets/baa01407-1826-4071-bf65-484b455f0522)
   Setelah Method DELETE di request maka perubahan dapat dilihat pada database
  




  

  


