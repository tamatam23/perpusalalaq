# 📚 Sistem Manajemen Perpustakaan Modern (LibraryApp)

Sistem informasi perpustakaan berbasis web yang responsif, dirancang untuk memudahkan manajemen buku, anggota, transaksi peminjaman, serta buku tamu secara real-time. Dibangun menggunakan **Google Apps Script** sebagai backend dan **Google Sheets** sebagai database.

![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-purple?style=flat-square&logo=bootstrap)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=flat-square&logo=javascript)
![GoogleAppsScript](https://img.shields.io/badge/Google%20Apps%20Script-CAS-blue?style=flat-square&logo=google-apps-script)

---

## ✨ Fitur Utama

-   **Dashboard Interaktif**: Statistik jumlah buku, anggota, peminjaman aktif, dan grafik Top 5 Buku Populer menggunakan *Chart.js*.
-   **Katalog Buku & Barcode**: Manajemen data buku lengkap dengan fitur cetak label barcode (tunggal atau massal).
-   **Smart Autocomplete**: Pencarian anggota dan buku secara instan saat transaksi (Mendukung penggunaan **Barcode Scanner**).
-   **Sistem Peminjaman**: Pencatatan tanggal pinjam, tenggat waktu, dan status otomatis (Dipinjam/Kembali/Terlambat).
-   **Buku Tamu Digital**: Fitur bagi pengunjung untuk mengisi kehadiran dengan cepat.
-   **Import via Excel**: Mempercepat input data massal melalui fitur unggah file `.xlsx`.
-   **Keamanan Login**: Sistem otentikasi admin untuk melindungi integritas data.

---

## 🛠️ Teknologi yang Digunakan

-   **Frontend**: HTML5, CSS3 (Google Fonts - Inter), Bootstrap 5.
-   **Backend**: Google Apps Script (GAS).
-   **Database**: Google Sheets.
-   **Library Pihak Ketiga**:
    -   [Chart.js](https://www.chartjs.org/) (Visualisasi data).
    -   [SweetAlert2](https://sweetalert2.github.io/) (Pop-up notifikasi cantik).
    -   [SheetJS (XLSX)](https://sheetjs.com/) (Proses file Excel).
    -   [FontAwesome 6](https://fontawesome.com/) (Ikonografi).
    -   [TEC-IT Barcode API](https://barcode.tec-it.com/) (Generator barcode).

---

## 🚀 Cara Instalasi

1.  **Siapkan Database**:
    -   Buat Google Sheets baru.
    -   Buat 5 sheet dengan nama: `Users`, `Books`, `Members`, `Transactions`, dan `Visitors`.
2.  **Buka Script Editor**:
    -   Klik menu `Extensions` > `Apps Script`.
3.  **Salin Kode**:
    -   Salin isi file `Code.gs` ke editor Apps Script.
    -   Buat file HTML baru bernama `Index.html` dan tempelkan kode antarmuka.
4.  **Deploy**:
    -   Klik tombol `Deploy` > `New Deployment`.
    -   Pilih type `Web App`.
    -   Set `Execute as: Me` dan `Who has access: Anyone` (atau sesuaikan).
    -   Salin URL yang diberikan.

---

## 📸 Tampilan Aplikasi

| Dashboard | Manajemen Buku | Transaksi |
| :--- | :--- | :--- |
| ![Dashboard](https://via.placeholder.com/300x150?text=Dashboard+Library) | ![Buku](https://via.placeholder.com/300x150?text=Katalog+Buku) | ![Transaksi](https://via.placeholder.com/300x150?text=Sistem+Peminjaman) |

---

## 💡 Catatan Fitur Autocomplete
Aplikasi ini dilengkapi dengan fitur **Smart Search** pada menu Peminjaman:
-   Ketik minimal **2 karakter** untuk mencari nama atau judul buku.
-   Mendukung **Barcode Scanner**: Cukup arahkan scanner ke label buku saat kursor berada di kolom input, maka data akan terpilih otomatis.

---

## 📄 Lisensi
Proyek ini didistribusikan di bawah lisensi MIT. Silakan gunakan dan kembangkan lebih lanjut!

---

**Dibuat dengan ❤️ untuk kemajuan literasi.**
