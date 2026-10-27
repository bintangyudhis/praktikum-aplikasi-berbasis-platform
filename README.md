# Praktikum Aplikasi Berbasis Platform

Repositori ini berisi kumpulan source code tugas praktikum mata kuliah Aplikasi Berbasis Platform. Setiap folder adalah tugas satu pertemuan, dengan teknologi yang berbeda mengikuti materi pertemuan tersebut, mulai dari halaman web statis sampai aplikasi Flutter dan Laravel.

## Isi Repositori

- `Pertemuan 1` dan `Pertemuan-1` berisi halaman HTML statis bertema Idul Fitri dengan Bootstrap, dilengkapi penghitung waktu berbuka puasa dan screenshot hasil.
- `Pertemuan-2-Aplikasi-CRUD` berisi aplikasi CRUD data siswa berbasis Node.js dan Express. Data disimpan di berkas `data.json`. Folder ini memiliki README dan penjelasan kode sendiri.
- `Pertemuan-3` berisi program PHP untuk menghitung nilai akhir mahasiswa dari nilai tugas, UTS, dan UAS, lengkap dengan grade dan status kelulusan.
- `Pertemuan-4` berisi latihan AJAX. Halaman `index.html` mengambil data profil berformat JSON dari `data.php` tanpa memuat ulang halaman.
- `Pertemuan-5-Laravel` berisi aplikasi Laravel dengan autentikasi bawaan Breeze dan CRUD produk.
- `Pertemuan-7` berisi aplikasi Flutter untuk latihan widget dasar, seperti Container, GridView, ListView, dan Stack.
- `Pertemuan-8` berisi aplikasi Flutter dengan fitur ambil foto dari kamera, pilih foto dari galeri, dan notifikasi lokal.
- `pertemuan_9_10` berisi aplikasi Flutter dengan Firebase Cloud Messaging untuk push notification, memakai Provider sebagai state management.
- `pertemuan_11` berisi aplikasi Flutter katalog produk dengan keranjang belanja, memakai state management Cubit.

## Teknologi

- HTML, CSS, dan Bootstrap
- PHP
- Node.js dan Express
- Laravel 13 dan PHP 8.3
- Flutter dan Dart
- Firebase Cloud Messaging

## Cara Instalasi

Clone repositori ini, lalu masuk ke folder pertemuan yang ingin dijalankan. Setiap subproyek berdiri sendiri dan memiliki dependensinya masing-masing.

Untuk aplikasi Node.js di Pertemuan 2:

```bash
cd Pertemuan-2-Aplikasi-CRUD
npm install
```

Untuk aplikasi Laravel di Pertemuan 5:

```bash
cd Pertemuan-5-Laravel
composer install
cp .env.example .env
php artisan key:generate
```

Untuk aplikasi Flutter, jalankan `flutter pub get` di folder pertemuannya.

## Cara Menjalankan

- Pertemuan 1: buka berkas `index.html` langsung di browser.
- Pertemuan 2: jalankan `npm start` di folder `Pertemuan-2-Aplikasi-CRUD`, lalu buka `http://localhost:3000`.
- Pertemuan 3 dan 4: letakkan folder di server PHP lokal, misalnya XAMPP, lalu buka melalui `http://localhost`. Pertemuan 4 membutuhkan server PHP karena data diambil dari `data.php`.
- Pertemuan 5: jalankan `php artisan serve` di folder `Pertemuan-5-Laravel`, lalu buka `http://localhost:8000`.
- Pertemuan 7, 8, 9-10, dan 11: buka foldernya sebagai proyek Flutter, lalu jalankan `flutter run`.

Detail setiap tugas ada di berkas dokumentasi di dalam folder masing-masing pertemuan.

## Lisensi

Proyek ini memakai lisensi MIT. Lihat berkas [LICENSE](LICENSE) untuk teks lengkapnya.
