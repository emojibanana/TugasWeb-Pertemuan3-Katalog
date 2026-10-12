# TugasWeb-Pertemuan3-Katalog

[![BETA](https://img.shields.io/badge/status-BETA-yellow)](https://github.com/emojibanana/TugasWeb-Pertemuan3-Katalog)

Katalog buku sederhana berbasis HTML dan CSS (Tailwind via CDN) — **tanpa JavaScript**. Berisi cover buku dengan harga, filter kategori murni CSS, detail buku expand-in-place, dan tombol Beli via WhatsApp.

## Cara Menjalankan

Buka `index.html` langsung di browser. Tidak perlu build maupun server.

## Isinya

- Satu halaman katalog responsif (2 kolom di HP, 3 di tablet, 4 di desktop)
- Navigasi pakai anchor: Beranda dan Buku
- Filter kategori berfungsi (Semua / Favorit / Novel / Ilmu / Horror) — murni radio + CSS, tanpa JS
- Tombol Detail per buku (expand di tempat pakai `<details>`)
- Tombol Beli per buku → chat WhatsApp ke 1234567890 dengan pesan otomatis berisi judul + harga
- Tailwind CSS (via CDN)

## Status Pengerjaan

- [x] Kategori bisa dipilih dan memfilter (CSS-only)
- [x] href navigasi terisi anchor yang benar
- [x] Detail buku proper (bukan placeholder)
- [x] Tombol Beli (via WhatsApp)
- [x] Ukuran kartu & cover disamakan (`object-fit: cover`, tinggi seragam)
- [x] Animasi hover dirapikan (lift + zoom halus, hormat `prefers-reduced-motion`)
- [x] Aksesibilitas (`lang="id"`, alt deskriptif, label, `aria-label`)
- [x] Optimasi (`loading="lazy"`, `decoding="async"`, meta description)
- [ ] Footer & formulir kontak dihapus sesuai keputusan (pemesanan lewat WhatsApp)

## Author

Ahmad Al Banna
- Email: ahmadbanna1709@gmail.com

---

*Repo ini cuma untuk Tugas Kuliah! Tapi mungkin bisa dikembangkan lagi.*
