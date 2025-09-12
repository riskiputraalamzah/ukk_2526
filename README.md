# 🛠️ Aplikasi Bengkel Mobil – UKK 2526

> **Progress Terakhir:** Setup awal

<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

<p align="center">
<img src="https://img.shields.io/badge/Laravel-12.x-red" alt="Laravel Version">
<img src="https://img.shields.io/badge/Status-Development-orange" alt="Status">
</p>

---

## 📌 Tentang Proyek

Aplikasi **Bengkel Mobil** adalah sistem berbasis web yang membantu mengelola seluruh operasional bengkel secara digital, mulai dari booking servis, manajemen sparepart, hingga laporan keuangan.

### 🎯 Tujuan Utama

-   **Efisiensi Operasional:** Mengurangi pencatatan manual dan mempercepat alur kerja.
-   **Meningkatkan Layanan Pelanggan:** Booking online & reminder servis mengurangi antrian.
-   **Mengurangi Human Error:** Stok sparepart & transaksi lebih akurat.
-   **Transparansi & Kontrol:** Pemilik bisa memantau laporan dari mana saja.
-   **Keunggulan Kompetitif:** Bengkel terlihat lebih profesional dengan sistem digital.

### 👥 Pengguna Utama

-   **Pemilik Bengkel(owner):** Memantau laporan, stok, dan keuntungan.
-   **Mekanik/Staff:** Mencatat layanan, memperbarui status kendaraan.
-   **Kasir/Administrasi:** Mencatat pembayaran & data pelanggan.
-   **Pelanggan:** Booking servis, cek status, menerima notifikasi.
-   **Supplier Sparepart (Opsional):** Update stok barang secara otomatis.

### 🕒 Waktu Penggunaan

-   **Operasional Harian:** Pencatatan layanan & transaksi.
-   **Sebelum Servis:** Booking online & reminder.
-   **Sesudah Servis:** Riwayat servis & notifikasi ke pelanggan.
-   **Akhir Periode:** Laporan keuangan & performa bengkel.

### 🔑 Fitur Utama

-   📅 **Booking Online** untuk reservasi jadwal servis.
-   📦 **Manajemen Sparepart** (stok keluar/masuk otomatis tercatat).
-   📝 **Riwayat Servis Kendaraan** tersimpan rapi per pelanggan.
-   🔔 **Notifikasi & Reminder** servis berkala.
-   📊 **Laporan & Analitik** omzet, pengeluaran, sparepart terlaris.
-   👥 **Multi-user** (pemilik, mekanik, kasir dengan akses berbeda).

---

## 🔄 Cara Clone Branch Ini

Gunakan perintah berikut untuk clone hanya branch ini saja:

```bash
git clone --branch aplikasi_bengkel_mobil --single-branch https://github.com/riskiputraalamzah/ukk2526.git aplikasi_bengkel_mobil
```

Lalu masuk ke folder project:

```bash
cd aplikasi_bengkel_mobil
```

---

## 🚀 Cara Menjalankan Aplikasi

Pastikan environment Laravel sudah siap (PHP, Composer, dan database server). Lalu jalankan:

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
```

Aplikasi akan berjalan di: `http://127.0.0.1:8000`

---

## 💬 Penutup

Semangat untuk teman-teman kelas 12 RPL yang sedang mengerjakan **UKK 2526**! 💪
Kerjakan dengan teliti, update bagian _Progress Terakhir_ di README ini setiap ada fitur baru, dan jaga kerapihan kode agar mudah dipresentasikan dan dinilai dengan baik. 🚀
