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
•main.dart

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
2. Scaffold
Membuat layout utama setiap halaman.
3. AppBar
Menampilkan judul halaman.
4. ListView
Menampilkan daftar data laundry.
5. Card
Membungkus setiap item data agar rapi.
6. Text
Menampilkan informasi pelanggan dan detail laundry.
7. TextFormField
Input nama, berat, jenis layanan, dan harga.
8. ElevatedButton
Tombol untuk menyimpan data.
9. Form dan GlobalKey
Mengelola validasi input.
10. Navigator atau Get
Mengatur perpindahan halaman dan pengiriman data.

## Penjelasan Nilai Tambah
1. Update Status Data
Fitur ini digunakan pengguna untuk memperbarui status pesanan pelanggan. Saat tombol '✔' ditekan, status 'Diproses' pada form data pelanggan akan berubah. Setelah diperbarui, status pesanan pelanggan menjadi 'Selesai'.
  a. Menambahkan properti isSelesai pada model Laundry
  b. Menggunakan setState untuk memperbarui tampilan
  c. Mengubah tampilan warna dan teks status berdasarkan kondisi data
4. Multi Page Navigation
Aplikasi menggunakan navigasi antar halaman untuk memisahkan tampilan daftar data dan form input.
  a. Menggunakan Get.to untuk membuka FormPage
  b. Menggunakan Get.back(result: data) untuk mengirim data kembali
  c. Data diterima di HomePage dan ditambahkan ke dalam List
