# Refactoring Personal Portfolio & Service Portal (Bootstrap 5)

**Nama:** Immanuel Alexander Tambunan  
**NIM:** 12S24034  
**Program Studi:** S1 Sistem Informasi  
**Mata Kuliah:** Pemrograman dan Pengujian Web (12S3101)  

---

## 🚀 Ringkasan Pembaruan Minggu 3
Proyek ini merupakan refactoring dari tugas portofolio Minggu 2 menggunakan framework **Bootstrap 5.3.3** dan **Bootstrap Icons** yang dipadukan dengan Custom CSS Variables (`:root`).

---

## 📊 Tabel Komparasi: Sebelum vs Sesudah Integrasi Framework

| Komponen / Area | Sebelum (Minggu 2 - Pure CSS) | Sesudah (Minggu 3 - Bootstrap 5 & Custom CSS) |
| :--- | :--- | :--- |
| **Tata Letak (Layout)** | Flexbox CSS Murni manual | System Grid 12-Kolom Responsif (`row`, `col-lg-4`, `col-lg-8`) |
| **Navigasi Mobile** | Menu statis | Responsive Sticky Navbar dengan Toggle Hamburger Collapse (`.navbar-toggler`) |
| **Penyajian Proyek** | Tabel tunggal murni | Kombinasi Grid Cards interaktif + Modal Dialog (`.modal`) detail proyek |
| **Formulir Layanan** | Form HTML standar | Modern Floating Labels (`.form-floating`), Input Groups berikon, & Visual Validation |
| **Arsitektur CSS** | CSS Manual per elemen | 7 Variabel CSS (`:root`), Bootstrap Utilities, & Overrides terstruktur |

---

## 🛠️ Spesifikasi Teknis
- **CSS Framework:** Bootstrap 5.3.3 via CDN
- **Icon Library:** Bootstrap Icons v1.11.3
- **Aksesibilitas:** WCAG 2.2 Level AA Focus Ring & Native HTML Validation
- **Deployment:** Live di GitHub Pages