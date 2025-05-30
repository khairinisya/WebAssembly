# Aplikasi Web Absensi Karyawan QR Code GPS

<div align="center">
  <img src="https://github.com/user-attachments/assets/598ee07c-9d6b-4437-9027-9c5a28552b60" alt="Logo 1" height="150">
  &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/f30eae02-e20b-4e65-9d95-5ac4161de224" alt="Logo 2" height="150">
</div>

***
```
NAMA        : Khairinisya Ani Atmaja
NIM         : 312310365
KELAS       : TI.23.A4
MATAKULIAH  : Pemrograman Web 2
```
***
![Aplikasi Web Absensi Karyawan QR Code GPS](./screenshots/hero.png)

Aplikasi web absensi karyawan menggunakan QR Code dan GPS.

## Teknologi yang Digunakan

* [Laravel 11](https://laravel.com/)
* [Laravel Jetstream](https://jetstream.laravel.com/)
* [Endroid QR Code](https://github.com/endroid/qr-code)
* [Leaflet.js](https://leafletjs.com/)
* [OpenStreetMap](https://www.openstreetmap.org/)
* MySQL/MariaDB

## Instalasi

### Prasyarat

* [Composer](https://getcomposer.org)
* [NPM & Node.js](https://nodejs.org)
* PHP 8.2 atau lebih tinggi
* MySQL/MariaDB

---

1. Clone/download repository ini
2. Jalankan perintah `composer run-script post-root-package-install` untuk membuat file `.env`
3. Jalankan perintah `composer install` untuk menginstalasi dependency
4. Jalankan perintah `npm install` untuk menginstalasi dependency Javascript
5. Jalankan perintah `php artisan key:generate --ansi --force` untuk membuat key aplikasi
6. Jalankan perintah `php artisan migrate` untuk membuat tabel databasex
7. Jalankan perintah `npm run build` untuk membuat file css dan javascript yang diperlukan
8. Jalankan perintah `php artisan serve` untuk menjalankan aplikasi

### Seeder

Pilih salah satu opsi berikut:

* Jalankan perintah `php artisan db:seed DatabaseSeeder` untuk menyiapkan data awal
* Jalankan perintah `php artisan db:seed FakeDataSeeder` untuk menyiapkan data awal beserta data dummy (absensi & karyawan)

## Fitur & Pratinjau

### User/Karyawan

| Scan Page | Scan Page (Mobile) |
|---|---|
|![Scan](./screenshots/presensi-scan.png)|![Scan mobile](./screenshots/presensi-scan-mobile.png)|

| Pengajuan Absensi | Riwayat Absensi Karyawan |
|---|---|
|![Pengajuan Absensi](./screenshots/pengajuan-izin.jpeg)|![Riwayat Absensi](./screenshots/presensi-user.jpeg)|

### Admin & Superadmin

| Dashboard Admin | Dashboard Admin Dark |
|---|---|
|![Dashboard](./screenshots/dashboard-light.jpeg)|![Dashboard Dark](./screenshots/dashboard-dark.jpeg)|

| Barcode | Create/Edit Barcode |
|---|---|
|![Barcode](./screenshots/barcode.jpeg)|![Create Edit Barcode](./screenshots/create-edit-barcode.jpeg)|

| Absensi Karyawan | | |
|---|---|---|
| Absensi per hari | Absensi per minggu | Absensi per bulan |
|![Absensi per hari](./screenshots/absensi-hari.png)|![Absensi per minggu](./screenshots/absensi-minggu.png)|![Absensi per bulan](./screenshots/absensi-bulan.png)|

| Data Karyawan | Create/Edit Data Karyawan |
|---|---|
|![Data Karyawan](./screenshots/karyawan.jpeg)|![Create Edit Data Karyawan](./screenshots/create-edit-karyawan.png)|

|Export/Import from/to XLSX| |
|---|---|
| Export/Import Data Karyawan & User | Export/Import Data Karyawan & User + Preview Data |
|![Export/Import Data Karyawan](./screenshots/export-user.jpeg)|![Export/Import Data Karyawan + Preview](./screenshots/export-user-preview.jpeg)|
| Export/Import Data Absensi & User | Export/Import Data Absensi & User + Preview Data |
|![Export/Import Data Absensi](./screenshots/export-absensi.jpeg)|![Export/Import Data Absensi + Preview](./screenshots/export-absensi-preview.png)|

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

© 2025 Khairinisya Ani Atmaja. All rights reserved.
