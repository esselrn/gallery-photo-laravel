# Galeri Foto (Laravel)

Versi pengembangan aplikasi galeri foto menggunakan framework Laravel, dibuat sebagai project kelas 12 semester 2.

## 🛠️ Teknologi
- Laravel
- Tailwind CSS
- PHP

## ✨ Fitur
- Login & autentikasi pengguna
- Upload foto
- Tampilan galeri foto
- Kategori & album foto
- Hapus foto
- CRUD lengkap

## 📁 Cara Menjalankan
1. Clone repo ini
```bash
   git clone https://github.com/esselrn/galeri-foto-laravel.git
```
2. Masuk ke folder project
```bash
   cd galeri-foto-laravel
```
3. Install dependencies
```bash
   composer install
   npm install
```
4. Salin file `.env.example` menjadi `.env`
```bash
   cp .env.example .env
```
5. Generate app key
```bash
   php artisan key:generate
```
6. Jalankan **XAMPP** atau **Laragon**, aktifkan Apache & MySQL
7. Sesuaikan konfigurasi database di file `.env`, lalu jalankan migrasi
```bash
   php artisan migrate
```
8. Jalankan server
```bash
   php artisan serve
```
9. Buka browser dan akses `http://localhost:8000`

## 📝 Catatan
Project ini dibuat untuk keperluan tugas sekolah dan tidak di-deploy secara publik.
