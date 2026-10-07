# Junior Backend Developer Portfolio (Neobrutalism Style)

Repositori ini berisi kode sumber website portofolio digital profesional untuk **Junior Backend Developer** dengan spesialisasi pada ekosistem **PHP, Laravel, MySQL, dan PostgreSQL**.

Website dirancang menggunakan pendekatan visual **Neobrutalism** (kontur border tebal, drop shadow tegas tanpa blur, warna kontras tinggi, dan tipografi modern) serta struktur konten yang jujur, terukur, dan fokus pada rekayasa backend.

---

## 🚀 Fitur & Struktur Halaman

Website ini terdiri dari 7 section utama yang dirancang untuk mempermudah recruiter dan tim teknis menilai keahlian kandidat:

1. **Top Marquee & Navigation:** Status ketersediaan kerja (*Available for Hire*) dan navigasi responsif dengan dukungan menu mobile.
2. **Hero Section:**
   * Headline: *Junior Backend Developer | PHP, Laravel & Relational Database*
   * Tagline: *"Building reliable backend systems, structured databases, and practical web applications."*
   * Preview interaktif jendela kode PHP backend (*OOP & Clean Code representation*).
   * Tombol CTA langsung ke proyek, kontak, dan unduh CV.
3. **About Me:** Latar belakang D4 Teknik Informatika, orientasi kerja pada integritas data, pemodelan proses bisnis, dan modularitas backend.
4. **Skills Matrix:** Pengelompokan teknologi yang jujur tanpa klaim fiktif:
   * **Programming Languages:** PHP, C
   * **Backend Framework:** Laravel (MVC Architecture, Eloquent ORM, Migrations, Routing, Controllers)
   * **Database Management:** MySQL, PostgreSQL
   * **Tools & Version Control:** Git, GitHub
5. **Projects Portfolio:**
   * Proyek Utama: **Sistem Aplikasi Perpustakaan Digital** (Laravel & MySQL).
   * Dokumentasi lengkap: *Overview, Problem, Solution, Fitur Utama, Teknologi, Proses Pengembangan, Hasil/Metrik, dan Link Repository/Demo*.
   * *Next in Pipeline Card* untuk riset backend berikutnya.
6. **Experience & Education:**
   * Riwayat pengerjaan proyek akademik & personal.
   * Riwayat pendidikan formal D4 Teknik Informatika dan fokus mata kuliah relevan.
7. **Contact & Quick Message:**
   * Akses cepat ke Email, GitHub, LinkedIn, dan Resume.
   * Form pesan interaktif siap hubung ke backend/layanan form submission.

---

## 📂 Struktur File

```text
├── index.html        # Struktur markup HTML5 semantik dan konten portofolio
├── style.css         # Styling kustom bertema Neobrutalism & responsif
└── README.md         # Dokumentasi proyek
```

---

## 🎨 Karakteristik Desain (Neobrutalism)

* **Border:** Garis pembatas tebal (`3px` – `4px solid #121212`).
* **Shadow:** Hard drop shadow tanpa blur (`3px 3px` hingga `8px 8px`).
* **Warna Aksen:** Kuning (`#ffe600`), Cyan (`#00f0ff`), Hijau (`#23e277`), Pink (`#ff6b8b`), dan Jingga (`#ff5e36`).
* **Tipografi:** Google Fonts *Space Grotesk* (Heading/Teks Utama) & *JetBrains Mono* (Code, Badge, dan Metadata).

---

## 🛠️ Cara Menjalankan Secara Lokal

Website ini dibangun menggunakan **Vanilla HTML5 & CSS3** murni tanpa ketergantungan build tool kompleks, sehingga sangat ringan dan cepat.

### Opsi 1: Langsung Buka di Browser
Cukup klik ganda file `index.html` atau buka melalui browser pilihan Anda:
```bash
# Melalui PowerShell (Windows)
Start-Process index.html
```

### Opsi 2: Menggunakan Local Server (Opsional)
Jika Anda menggunakan ekstensi seperti **Live Server (VS Code)** atau Python HTTP server:
```bash
# Python 3
python -m http.server 8000
```
Lalu buka `http://localhost:8000` pada peramban web.

---

## 📝 Panduan Melengkapi Informasi (`***`)

Beberapa bagian pada [index.html](index.html) sengaja ditandai dengan placeholder `***` agar Anda dapat melengkapinya dengan data pribadi sebelum dipublikasikan:

| Placeholder | Keterangan yang Perlu Diisi | Lokasi di `index.html` |
|---|---|---|
| `[***]` pada Unduh CV | Tautan Google Drive / file PDF CV Anda | Hero & Contact Section |
| `[***]` pada Institusi | Nama Kampus / Politeknik Anda | About, Experience & Education |
| `[***]` pada Periode | Tahun masuk dan perkiraan kelulusan | Experience & Education |
| `[***]` pada GitHub Repo & Demo | Link repositori GitHub & link demo aplikasi perpustakaan | Project Section |
| `[***]` pada Kontak | Alamat email asli, URL profil GitHub, dan URL LinkedIn | Contact Section |

---

## 🌐 Rencana Deployment

Website ini siap di-deploy secara gratis melalui platform seperti:
* **GitHub Pages** (cukup push repositori dan aktifkan GitHub Pages dari branch `main`)
* **Vercel**
* **Netlify**
