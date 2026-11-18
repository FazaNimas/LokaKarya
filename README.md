# LokaKarya

Landing page LokaKarya untuk platform ekonomi sirkular yang memperkenalkan produk kerajinan hasil daur ulang UMKM lokal dan membantu pengguna menemukan bank sampah terdekat.

## Tentang Proyek

LokaKarya menggabungkan dua kebutuhan dalam satu pengalaman:

- **E-Commerce Showroom:** katalog produk daur ulang UMKM dengan informasi bahan, harga simulasi, dan tautan pembelian eksternal.
- **Direktori Bank Sampah:** preview lokasi penyetoran dengan pencarian, filter jenis sampah, alamat, jam operasional, marker peta, dan tautan Google Maps simulasi.

Proyek mendukung tema SDG 8 — Decent Work and Economic Growth dan SDG 12 — Responsible Consumption and Production.

Landing page ini merupakan implementasi Phase 1. Semua produk, harga, alamat, jam operasional, kontak, dan tautan adalah data simulasi untuk praktikum.

## Teknologi

- HTML5 semantic
- CSS3 dengan custom properties dan responsive layout
- Bootstrap 5 CDN untuk grid dan navbar
- Vanilla JavaScript untuk rendering data dan interaksi
- Figma-exported SVG/JPG assets

## Fitur

- Header floating responsive dengan anchor navigation.
- Hero ekonomi sirkular dengan ilustrasi tote bag, botol, dan tanaman.
- Benefit cards.
- Katalog 8 produk simulasi dengan filter kategori.
- Preview 4 bank sampah simulasi dengan pencarian, filter material, active card, marker, dan link Google Maps.
- Form setor sampah simulasi dengan validasi nama, WhatsApp, jenis sampah, tanggal, lokasi, dan metode setor.
- Success state form yang membedakan pengajuan simulasi dari konfirmasi jadwal.
- Footer kontak dan label data simulasi.

## Menjalankan Proyek

1. Clone repository:

   ```bash
   git clone https://github.com/miawmiawpaw/LokaKarya.git
   cd LokaKarya
   ```

2. Buka `index.html` dengan VS Code Live Server.

   Bootstrap dan Google Fonts dimuat melalui CDN, sehingga koneksi internet diperlukan untuk tampilan penuh.

## Struktur File

- `index.html` — markup landing page.
- `assets/css/style.css` — design tokens, layout, komponen, dan responsive rules.
- `assets/js/data.js` — data produk, manfaat, lokasi, dan konfigurasi kontak.
- `assets/js/main.js` — rendering dan interaksi Vanilla JavaScript.
- `assets/img/` — aset visual lokal hasil ekspor Figma.

## Batasan Phase 1

Belum tersedia backend, database, autentikasi, checkout, pembayaran, halaman katalog terpisah, halaman detail produk, atau direktori terpisah. Form setor sampah hanya simulasi frontend.

## Design Reference

- [Figma Mockup](https://www.figma.com/design/PoGctK8bkFvyKu710ViZau/Desain-Web?node-id=125-163)
- [Figma Wireframe](https://www.figma.com/design/PoGctK8bkFvyKu710ViZau/Desain-Web?node-id=125-164)
