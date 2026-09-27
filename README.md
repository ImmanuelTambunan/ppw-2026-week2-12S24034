# Laporan Praktikum Minggu 03: Modernisasi & Refactoring Personal Portfolio Berbasis Bootstrap 5.3

## 👤 Identitas Pengembang
* **Nama** : Immanuel Alexander Tambunan
* **NIM** : 12S24034
* **Kelas** : 12S3101 - Pemrograman dan Pengujian Web
* **Program Studi**: S1 Sistem Informasi
* **Institusi** : Institut Teknologi Del

---

## 🌐 Tautan Publikasi (Live Demo)
* **GitHub Pages Live Demo**: [https://immanueltambunan.github.io/ppw-2026-week2-12S24034/tugas/](https://immanueltambunan.github.io/ppw-2026-week2-12S24034/tugas/)[cite: 20]
* **Branch Pengerjaan**: `week3-bootstrap`[cite: 20]

---

## 📝 Ringkasan Pembaruan (Refactoring Summary)
Pada praktikum Minggu 03 ini, halaman portofolio personal dari Minggu 02 telah direfaktor sepenuhnya menggunakan ekosistem **Bootstrap 5.3.3** dan **Custom CSS Overrides**:
1. **Integrasi Bootstrap 5.3 CDN & Bootstrap Icons**: Menghubungkan CSS/JS bundle resmi dan ikon interaktif[cite: 20].
2. **Responsive Grid System 12-Kolom**: Menyusun ulang tata letak halaman agar responsif penuh di berbagai breakpoint perangkat (`col-lg-4`, `col-lg-8`, `row-cols-md-3`, dll)[cite: 20].
3. **Responsive Navbar with Hamburger Toggle**: Navigasi sticky-top dengan tombol *collapse* aktif untuk tampilan mobile[cite: 20].
4. **Komponen Interaktif Modal Dialog**: Menambahkan pop-up modal detail proyek serta pratinjau sertifikat PDF interaktif[cite: 20].
5. **Modernisasi Formulir Layanan**: Implementasi *Floating Labels* (`.form-floating`), *Input Groups* berikon, serta *validasi visual visual feedback* (`needs-validation`)[cite: 20].
6. **Custom Overrides & Theming (`style.css`)**: Mendefinisikan 7 CSS Custom Properties (`:root`), mikro-interaksi transisi hover, dan advanced selectors tanpa menggunakan `!important`[cite: 20].

---

## 📊 Tabel Komparasi: Sebelum vs Sesudah Integrasi Framework

| Area Komponen | Minggu 2 (CSS Murni) | Minggu 3 (Bootstrap 5 + Custom CSS) |
| :--- | :--- | :--- |
| **Tata Letak & Grid** | CSS Flexbox & Float manual[cite: 20] | Grid System 12-Kolom Bootstrap (`container`, `row`, `col-md-*`)[cite: 20] |
| **Navigasi** | Static Navbar biasa | Responsive Sticky Navbar dengan Collapse Toggle Hamburger[cite: 20] |
| **Penyampaian Detail** | Teks statis di halaman | Pop-up **Bootstrap Modal Dialog** interaktif & PDF Viewer[cite: 20] |
| **Formulir Layanan** | Form HTML standar tanpa feedback | Floating Labels (`.form-floating`), Input Group berikon, & State Validasi Visual[cite: 20] |
| **Arsitektur CSS** | CSS murni terpisah | Integrasi Framework + 7 CSS Variables pada `:root` untuk Kustomisasi Tema[cite: 20] |
| **Responsivitas** | Terbatas pada media query manual | Responsif otomatis di Smartphone, Tablet, hingga Wide Monitor[cite: 20] |

---

## 📸 Tangkapan Layar Tampilan Antarmuka (Screenshots)

> *Catatan: Ambil screenshot tampilan web kamu di browser, simpan di folder `asset/`, lalu sesuaikan nama filenya di bawah ini.*

### 1. Tampilan Tampilan Desktop (Hero & Portfolio)
![Tampilan Desktop Hero](../asset/desktop-preview.png)

### 2. Tampilan Modal Pratinjau Sertifikat PDF
![Tampilan Modal Sertifikat](../asset/modal-pdf-preview.png)

### 3. Tampilan Formulir Layanan & Validasi
![Tampilan Form Validasi](../asset/form-validation-preview.png)

### 4. Tampilan Responsive Mobile
![Tampilan Mobile Preview](../asset/mobile-preview.png)

---
© 2026 Immanuel Alexander Tambunan - Institut Teknologi Del[cite: 20]