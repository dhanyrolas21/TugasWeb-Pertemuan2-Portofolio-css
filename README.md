Portofolio Dhany Rolas

Landing page portofolio pribadi, dibangun dengan HTML5 semantik dan CSS murni (tanpa framework), sebagai bagian dari Tugas Rutin 2 — CSS Layouting Portofolio mata kuliah Pemrograman Web, Universitas Negeri Medan (UNIMED).

Proyek ini melanjutkan struktur HTML dari Tugas Rutin 1 (landing page pribadi), lalu ditata ulang layout dan stylingnya menggunakan kombinasi CSS Grid dan Flexbox.

Struktur File
├── index.html   # struktur HTML5 semantik
├── style.css    # styling, layout grid & flexbox, dark mode
└── README.md
Kesesuaian dengan Ketentuan Tugas

Berikut pemetaan hasil pengerjaan terhadap requirement yang diberikan:

No	Requirement	Implementasi
1	HTML5 semantik (header, aside, main, nav)	Digunakan langsung di index.html: <header class="header-container">, <nav class="nav-bar">, <main class="main-content">, <aside aria-label="Sedang dipelajari">
2	Minimal 5 CSS variables di :root	8 variabel didefinisikan: --bg, --surface, --ink, --ink-dim, --line, --primary, --secondary, --highlight
3	box-sizing: border-box global	Diterapkan pada reset *, *::before, *::after di awal style.css
4	CSS Grid untuk struktur utama	.layout-container menggunakan display: grid untuk menyusun area konten utama (main) dan sidebar (aside)
5	Flexbox untuk minimal 2 komponen	.nav-list dan .main-content menggunakan display: flex
6	Kode rapi (kebab-case)	Seluruh penamaan class konsisten kebab-case, misalnya header-container, nav-list, card-box, project-item
Bonus	Dark mode via @media (prefers-color-scheme: dark)	Diimplementasikan di bagian akhir style.css, mengubah seluruh palet warna (bukan sekadar invert) mengikuti preferensi sistem pengguna


Selain requirement wajib di atas, halaman juga mempertahankan kriteria dari tugas landing page sebelumnya: struktur semantik lengkap, formulir interaktif dengan validasi (required, minlength, type="email", type="date"), heading hierarkis (h1 → h2 → h3), serta figure + figcaption untuk foto profil.

Cara Menjalankan
Clone repository ini.
Buka index.html langsung di browser, atau jalankan lewat Live Server (mis. ekstensi VS Code) agar path lebih rapi.
Tidak ada dependency tambahan yang perlu diinstal — murni HTML & CSS

Untuk Screenshot preview css nya sudah saya tambahkan file screenshot nya di Github.

Dhany Rolas Mahasiswa Ilmu Komputer, Universitas Negeri Medan

