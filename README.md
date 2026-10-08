# Portofolio Dhany Rolas

Landing page portofolio pribadi yang dibangun menggunakan HTML5 semantik dan CSS murni (tanpa framework/library external), sebagai pemenuhan **Tugas Rutin 2: CSS Layouting Portofolio** pada mata kuliah Pemrograman Web, Universitas Negeri Medan (UNIMED).

Proyek ini melanjutkan struktur HTML dari Tugas Rutin 1 (landing page pribadi) dengan menyusun ulang tata letak (*layout*) dan gaya (*styling*) menggunakan kombinasi **CSS Grid** dan **Flexbox**.

---

## 📁 Struktur Berkas

```text
.
├── index.html   # Struktur HTML5 semantik
├── style.css    # CSS Variables, reset, Grid, Flexbox, & Dark Mode
└── README.md    # Dokumentasi proyek
```

---

## ✅ Kesesuaian Kriteria Tugas

Berikut adalah pemetaan implementasi kode terhadap *requirement* tugas yang diberikan:

| No | Requirement | Detail Implementasi |
|---|---|---|
| 1 | **HTML5 Semantik** (`header`, `aside`, `main`, `nav`) | Digunakan langsung pada `index.html`: `<header class="header-container">`, `<nav class="nav-bar">`, `<main class="main-content">`, dan `<aside aria-label="Sedang dipelajari">`. |
| 2 | **Minimal 5 CSS Variables di `:root`** | 8 variabel didefinisikan pada `style.css`: `--bg`, `--surface`, `--ink`, `--ink-dim`, `--line`, `--primary`, `--secondary`, dan `--highlight`. |
| 3 | **`box-sizing: border-box` Global** | Diterapkan pada *universal reset* `*, *::before, *::after` di awal file `style.css`. |
| 4 | **CSS Grid untuk Struktur Utama** | Digunakan pada `.layout-container` untuk mengatur tata letak dua kolom antara area konten utama (`main`) dan bilah samping (`aside`). |
| 5 | **Flexbox untuk Minimal 2 Komponen** | Diterapkan pada nav-bar (`.nav-list`) dan kontainer konten utama (`.main-content`). |
| 6 | **Kode Rapi & *Kebab-case*** | Penamaan kelas konsisten menggunakan *kebab-case* (seperti `header-container`, `nav-list`, `card-box`, `project-item`). |
| **Bonus** | **Dark Mode via `@media (prefers-color-scheme: dark)`** | Diterapkan di bagian akhir `style.css` dengan menyesuaikan skema warna secara dinamis sesuai preferensi sistem pengguna. |

> **Catatan Tambahan:**
> Halaman ini tetap mempertahankan standar dari tugas sebelumnya, seperti validasi form interaktif (`required`, `minlength`, `type="email"`, `type="date"`), hirarki *heading* yang terstruktur (`h1` → `h2` → `h3`), serta elemen `figure` dan `figcaption` pada foto profil.

---

## 🚀 Cara Menjalankan Proyek

1. **Clone repository ini:**
   ```bash
   git clone https://github.com/dhanyrolas21/NAMA_REPOSITORY_ANDA.git
   ```
2. **Buka halaman di browser:**
   - Buka berkas `index.html` secara langsung di browser pilihan Anda.
   - Atau gunakan ekstensi **Live Server** di Visual Studio Code untuk mendapatkan *local server* otomatis.
3. *Tanpa ada instalasi dependensi tambahan (murni HTML5 & CSS3).*

---

## 📸 Pratinjau Tampilan

Tangkapan layar (*screenshot*) hasil tampilan layout CSS telah diunggah ke dalam berkas repositori GitHub ini.

---

**Dhany Rolas**  
*Mahasiswa Ilmu Komputer — Universitas Negeri Medan*
