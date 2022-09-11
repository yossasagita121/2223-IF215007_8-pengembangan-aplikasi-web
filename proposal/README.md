## Aplikasi E-kost



 - Aplikasi pengelolaan data kost serta mencatat pendapatan kost

## Permasalahan

 - Masih banyak pemilik kost yang kesulitan untuk mengelola data kostnya
 - Pemilik kost kesulitan untuk mencatat pendapatan secara manual
 - Pemilik kost bisa saja memiliki lebih dari 1 atau bahkan banyak rumah kost di berbagai tempat

## Rancangan Solusi

 - Membuat aplikasi untuk mengelola data kost
 - Pemilik kost dapat melihat kamar kost yang kosong atau sedang ditempati hanya lewat aplikasi ini.
 - Pemilik kost dapat melihat waktu tempo pembayaran penghuni kostnya
 - Pemilik kost dapat melihat pendapatan kostnya

## Use Case

 - User admin dapat mengelola seluruh data pada aplikasi termasuk data user
 - User pemilik melakukan registrasi menggunakan email dan passoword
 - user pemilik melakukan login
 - User pemilik hanya dapat mengelola data kostnya sendiri
 - User pemilik dapat mencetak laporan pendapatan kostnya


## Struktur Data

User
| Atribut | Tipe Data | Contoh |
|--|--|--|
|id_user|Integer|1|
|nama|String|Yoss Sagita|
|email|String|sagitayoss121@gmail.com|
|password|String|admin123|
|telepon|String|08123456789|
|level|String|admin|

Kost
| Atribut | Tipe Data | Contoh |
|--|--|--|
| id_kost | Integer | 1213 |
|id_pemilik|Integer|1|
|nama|String|anugrah|
|alamat|String|Manisi|

Kamar
| Atribut | Tipe Data | Contoh |
|--|--|--|
| id_kamar | Integer | 1232 |
|id_kost|Integer|1213|
|no_kamar|String|1A|
|harga|Integer|450000|
|status|String|Berpenghuni|

Laporan
| Atribut | Tipe Data | Contoh |
|--|--|--|
| id_laporan | Integer | 1 |
|id_kost|Integer|1213|
|id_pemilik|Integer|1|
|id_kamar|Integer|1232|
|nama_penghuni|String|Zakki Mubarok|
|telepon|String|08382715468|
|check_in|Date|12-09-2022|
|check_out|Date|12-09-2023|


## UX Wireframe
<img width="1440" alt="proposal" src="https://user-images.githubusercontent.com/68968229/189554318-d9a07866-b7e3-4471-b16c-2e9cfe1e5309.png">
