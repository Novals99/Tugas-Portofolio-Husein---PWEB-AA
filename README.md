# Portofolio Pribadi — Nama Mahasiswa

Website portofolio pribadi statis yang dibuat untuk memenuhi Tugas P5 Pemrograman Web (PWEB).

## Teknologi yang Digunakan

- **HTML5** — Struktur halaman dan konten semantik
- **CSS3** — Gaya kustom (lihat `css/style.css`)
- **Bootstrap 5.3.8** — Layout responsif dan komponen UI (digunakan secara lokal)

> **Catatan:** Tidak ada CDN, backend, database, atau framework JavaScript yang digunakan.  
> Website berjalan sepenuhnya dengan membuka `index.html` di browser.

## Struktur Proyek

```
bootstrap-5.3.8-dist/
├── index.html              ← Halaman utama portofolio
├── css/
│   ├── bootstrap.min.css   ← Bootstrap 5.3.8 (lokal)
│   └── style.css           ← Gaya kustom portofolio
├── js/
│   └── bootstrap.bundle.min.js  ← Bootstrap JS + Popper (lokal)
├── images/
│   ├── profile/            ← Foto profil (isi dengan foto asli)
│   ├── projects/           ← Screenshot proyek
│   └── certificates/       ← Gambar sertifikat
└── reference/              ← Referensi desain UI
```

## Cara Membuka

1. Buka folder proyek
2. Klik dua kali pada `index.html`
3. Website akan terbuka langsung di browser

## Konten yang Perlu Diganti

Seluruh konten portofolio menggunakan **data dummy** yang mudah diidentifikasi dan diganti:

| Placeholder          | Ganti dengan           |
|----------------------|------------------------|
| `Nama Mahasiswa`     | Nama lengkap Anda      |
| `Nama Universitas`   | Nama universitas Anda  |
| `Nama Kota`          | Kota domisili Anda     |
| `nama@example.com`   | Alamat email Anda      |
| `github.com/username`| Username GitHub Anda   |
| `linkedin.com/in/username` | Profil LinkedIn Anda |
| `@username`          | Username Instagram Anda|

## Bagian Website

1. **Beranda (Hero)** — Perkenalan singkat dengan badge status, avatar, dan tombol CTA
2. **Tentang Saya** — Biografi, informasi pribadi, dan statistik ringkas
3. **Pendidikan** — Riwayat pendidikan dalam format timeline
4. **Pengalaman** — Pengalaman kerja, magang, dan organisasi
5. **Keahlian** — Daftar kemampuan teknis dan non-teknis dalam kategori
6. **Proyek** — Galeri proyek dengan deskripsi dan tautan
7. **Sertifikat & Prestasi** — Daftar sertifikat dan penghargaan
8. **Kontak** — Tautan kontak yang dapat diklik

## Fitur

- ✅ Desain minimalis putih dengan dot-grid background (sesuai referensi)
- ✅ Navbar mengambang berbentuk pill (sesuai referensi)
- ✅ Responsif penuh: desktop, tablet, smartphone
- ✅ Animasi fade-in halus menggunakan IntersectionObserver
- ✅ Tombol scroll-to-top
- ✅ Highlight navigasi aktif saat scroll
- ✅ Semua teks konten dalam Bahasa Indonesia
- ✅ Aksesibel: semantic HTML, alt text, ARIA labels
- ✅ Tidak membutuhkan internet setelah font/icon dimuat

---

*Dibuat sebagai bagian dari Tugas P5 Pemrograman Web — M. Husain Humaidi (2512501335)*
