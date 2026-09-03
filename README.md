# 📚 Sistem Informasi Perpustakaan SMKN 8 Yogyakarta

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)](#)

Aplikasi Web Manajemen Perpustakaan SMKN 8 Yogyakarta yang dirancang untuk mempermudah pengelolaan data buku, transaksi peminjaman & pengembalian, anggota/siswa, serta penyajian laporan perpustakaan secara efisien dan terintegrasi.
ird https://raw.githubusercontent.com/lutpiananurmasari/perpustakaansmkn8jogja/refs/heads/main/WhatsApp%20Image%202026-09-03%20at%203.54.35%20PM.jpeg

---

## 📑 Daftar Isi
- [Fitur Utama](#-fitur-utama)
- [Teknologi yang Digunakan](#-teknologi-yang-digunakan)
- [Prasyarat](#-prasyarat)
- [Panduan Instalasi](#-panduan-instalasi)
- [Konfigurasi Database](#-konfigurasi-database)
- [Penggunaan](#-penggunaan)
- [Struktur Direktori](#-struktur-direktori)
- [Kontribusi](#-kontribusi)
- [Lisensi](#-lisensi)

---

## ✨ Fitur Utama

### 👨‍💼 Panel Admin / Pustakawan
* **Dashboard Analitik**: Ringkasan total buku, transaksi aktif, jumlah anggota, dan grafik aktivitas.
* **Manajemen Data Buku**: Tambah, edit, hapus, ketersediaan, kategori, dan pencarian katalog buku.
* **Manajemen Anggota**: Pengelolaan data siswa, guru, dan staf perpustakaan.
* **Transaksi Peminjaman & Pengembalian**:
  * Pencatatan peminjaman buku dengan batasan tanggal.
  * Proses pengembalian otomatis menghitung keterlambatan.
  * Perhitungan denda keterlambatan (opsional).
* **Laporan & Export**: Cetak laporan transaksi dan stok buku (PDF / Excel).

### 👩‍🎓 Akses Siswa / Anggota (Katalog Online)
* **Katalog Digital (OPAC)**: Pencarian koleksi buku berdasarkan judul, pengarang, atau kategori.
* **Status Ketersediaan**: Cek apakah stok buku sedang dipinjam atau tersedia.
* **Riwayat Peminjaman**: Melihat daftar buku yang sedang/pernah dipinjam.

---

## 🛠 Teknologi yang Digunakan

| Komponen | Teknologi / Library |
| :--- | :--- |
| **Backend** | PHP / Laravel (atau Framework/Native terkait) |
| **Frontend** | HTML5, CSS3, JavaScript, Bootstrap / Tailwind CSS |
| **Database** | MySQL / MariaDB |
| **Web Server** | Apache / Nginx / XAMPP / Laragon |

---

## 📋 Prasyarat

Sebelum memulai, pastikan perangkat Anda telah terinstal:
* **PHP** (Versi `>= 8.0`)
* **Composer** (Jika menggunakan Laravel)
* **MySQL / MariaDB** (via XAMPP, Laragon, atau MySQL Standalone)
* **Git**

---

## 🚀 Panduan Instalasi

### 1. Clone Repositori
```bash
git clone [https://github.com/lutpiananurmasari/perpustakaansmkn8jogja.git](https://github.com/lutpiananurmasari/perpustakaansmkn8jogja.git)
cd perpustakaansmkn8jogja
