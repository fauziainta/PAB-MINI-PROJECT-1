# PAB-MINI-PROJECT-1
## Fauzia Inanta Aurelia/2409114044/ Sistem Informasi (B)

## Deskripsi Aplikasi
Aplikasi Laundry Mobile adalah aplikasi berbasis Flutter untuk membantu pengelolaan data laundry secara terstuktur. Aplikasi ini membantu pengguna untuk mencatat data pelanggan, jenis layanan, berat cucian, dan total harga. Data ditampilkan dalam bentuk daftar sehingga mudah dipantau dan dikelola oleh pengguna.

## Struktur Project
lib/
 
  models/
   
    • laundry.dart
  
  pages/
    
    • home_page.dart
    
    • form_page.dart
    
 • main.dart

## Fitur Aplikasi
1. Tambah Data Laundry

   Pengguna dapat memasukkan nama pelanggan, berat cucian, jenis layanan, dan harga.

2. Tampilkan Daftar Data

   Semua data laundry ditampilkan dalam bentuk ListView.

3. Hapus Data

   Pengguna dapat menghapus data yang tidak diperlukan.

4. Edit Data

   Pengguna dapat memperbarui data laundry yang sudah ada.

5. Navigasi Antar Halaman

   Aplikasi menggunakan lebih dari satu halaman untuk memisahkan tampilan daftar dan form input.

## Widget yang Digunakan
1. MaterialApp

   Mengatur struktur dasar aplikasi.
   <img width="596" height="361" alt="image" src="https://github.com/user-attachments/assets/895685fb-c622-4600-975b-40d8f2dbc5b9" />

2. Scaffold

   Membuat layout utama setiap halaman.
   <img width="574" height="445" alt="image" src="https://github.com/user-attachments/assets/bbb550fe-46af-4af5-87b0-5175b2834886" />

4. AppBar

   Menampilkan judul halaman.
   <img width="497" height="543" alt="image" src="https://github.com/user-attachments/assets/da1c0d82-1e6b-4dca-999a-3ff801ef266c" />

5. ListView

   Menampilkan daftar data laundry.
   <img width="540" height="289" alt="image" src="https://github.com/user-attachments/assets/8a4c8ba5-c7d5-47ff-add3-873ecb5f609d" />

6. Card

   Membungkus setiap item data agar rapi.
   <img width="510" height="250" alt="image" src="https://github.com/user-attachments/assets/43c07613-e409-42da-8f1a-56276ee1de2c" />

7. Text

   Menampilkan informasi pelanggan dan detail laundry.
   <img width="544" height="136" alt="image" src="https://github.com/user-attachments/assets/f5dd8d99-bf41-464c-8dac-d584391cc93e" />

8. TextFormField

   Input nama, berat, jenis layanan, dan harga.
   <img width="580" height="311" alt="image" src="https://github.com/user-attachments/assets/e2ded321-8b78-4efd-97fe-2577c3a4749e" />

9. ElevatedButton

   Tombol untuk menyimpan data.
   <img width="505" height="250" alt="image" src="https://github.com/user-attachments/assets/5aab1f52-2e47-471e-9383-5a9ceb4edb11" />

10. Form dan GlobalKey
  
    Mengelola validasi input.
    <img width="581" height="38" alt="image" src="https://github.com/user-attachments/assets/f8bfc472-3b3b-4dc4-9144-10bab5a0d933" />

11. Navigator atau Get

    Mengatur perpindahan halaman
    <img width="518" height="35" alt="image" src="https://github.com/user-attachments/assets/c0f21914-ea21-45df-a4b4-df4f347be3fe" />

    kembali dan pengiriman data.
    <img width="592" height="24" alt="image" src="https://github.com/user-attachments/assets/e54c472d-131c-420b-95ba-b4ff37617ffe" />

## Penjelasan Nilai Tambah
1. Update Status Data

   Fitur ini digunakan pengguna untuk memperbarui status pesanan pelanggan. Saat tombol '✔' ditekan, status 'Diproses' pada form data pelanggan akan berubah. Setelah
   diperbarui, status pesanan pelanggan menjadi 'Selesai'.

   a. Menambahkan properti isSelesai pada model Laundry

   b. Menggunakan setState untuk memperbarui tampilan

   c. Mengubah tampilan warna dan teks status berdasarkan kondisi data

3. Multi Page Navigation

   Aplikasi menggunakan navigasi antar halaman untuk memisahkan tampilan daftar data dan form input.

    a. Menggunakan Get.to untuk membuka FormPage

    b. Menggunakan Get.back(result: data) untuk mengirim data kembali

    c. Data diterima di HomePage dan ditambahkan ke dalam List
