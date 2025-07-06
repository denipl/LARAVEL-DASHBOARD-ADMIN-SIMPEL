![Screenshot 2025-07-06 131359](https://github.com/user-attachments/assets/75d7029c-cf0c-41c1-8082-d1ebb5273411)# Laravel Dashboard Admin Simpel

Aplikasi dashboard admin sederhana berbasis Laravel. Studi kasus toko online dengan fitur manajemen user, kategori, produk, dan laporan.

## Fitur

![Screenshot 2025-07-06 131419](https://github.com/user-attachments/assets/d96b75fe-cb39-41f8-acfc-ed3d620ce20d)
![Screenshot 2025-07-06 131359](https://github.com/user-attachments/assets/cd9b3ab4-15b6-4610-a57b-1171af3e3d73)



- Manajemen User (CRUD)
- Manajemen Kategori Produk (CRUD)
- Manajemen Produk (CRUD, upload foto, thumbnail otomatis)
- Laporan User & Produk (filter tanggal, cetak)
- Autentikasi & Hak Akses (Admin & Super Admin)
- Upload gambar dengan resize otomatis
- Notifikasi SweetAlert
- Responsive Admin Template

## Instalasi

1. **Clone repository**
    ```sh
    git clone https://github.com/username/laravel-dashboard-admin-simpel.git
    cd laravel-dashboard-admin-simpel
    ```

2. **Install dependency**
    ```sh
    composer install
    npm install
    ```

3. **Copy file environment**
    ```sh
    cp .env.example .env
    ```

4. **Generate key**
    ```sh
    php artisan key:generate
    ```

5. **Atur koneksi database**  
    Edit file `.env` dan sesuaikan konfigurasi database Anda.

6. **Jalankan migrasi & seeder**
    ```sh
    php artisan migrate --seed
    ```
7. **Jalankan migrasi & seeder**
    ```sh
    php artisan storage:link
    ```
8. Buatkan folder di : 1.public\storage/img-produk
                       2.public\storage/img-user

10. **Jalankan server**
    ```sh
    php artisan serve
    ```

11. **Akses aplikasi**  
    Buka browser ke [http://localhost:8000](http://localhost:8000)

## Akun Default

- **Super Admin**
  - Email: `admin@admin.com`
  - Password: `Den12@`
- **Admin**
  - Email: `sopianaji@admin.com`
  - Password: `P@55word`

## Struktur Folder

- `app/` - Kode utama aplikasi (controller, model, helper)
- `resources/views/` - Blade template
- `routes/web.php` - Routing aplikasi
- `public/` - Asset publik (css, js, gambar)
- `database/seeders/` - Seeder data awal

## Lisensi

Proyek ini menggunakan lisensi [MIT](LICENSE).

