# LokaKarya

LokaKarya merupakan platform berbasis website yang memperkenalkan produk kerajinan hasil daur ulang dari UMKM lokal serta membantu masyarakat menemukan informasi mengenai bank sampah. Website ini dirancang untuk meningkatkan kesadaran masyarakat terhadap pengelolaan sampah sekaligus mendukung perkembangan UMKM melalui pemanfaatan bahan daur ulang.

## Tentang Proyek

LokaKarya menggabungkan dua layanan utama dalam satu platform:

- **E-Commerce Showroom:** Menampilkan katalog produk kerajinan hasil daur ulang dari UMKM lokal, dilengkapi informasi bahan, harga simulasi, dan tautan pembelian eksternal.
- **Direktori Bank Sampah:** Menyediakan informasi lokasi bank sampah melalui fitur pencarian, filter jenis sampah, alamat, jam operasional, marker peta, dan tautan Google Maps simulasi.

Proyek ini mendukung tujuan Sustainable Development Goals (SDGs), yaitu:

- **SDG 8 – Decent Work and Economic Growth:** Mendukung perkembangan UMKM lokal melalui pengenalan dan promosi produk kerajinan daur ulang.
- **SDG 12 – Responsible Consumption and Production:** Mendorong konsumsi dan produksi yang bertanggung jawab melalui pemanfaatan kembali bahan bekas.

LokaKarya merupakan implementasi Phase 1. Seluruh data produk, harga, alamat, jam operasional, kontak, dan tautan yang ditampilkan masih berupa data simulasi untuk keperluan praktikum.

## Tujuan Proyek

1. Memperkenalkan produk kerajinan berbahan daur ulang dari UMKM lokal kepada masyarakat.
2. Membantu pengguna memperoleh informasi mengenai bank sampah dan lokasi penyetoran sampah.
3. Meningkatkan kesadaran masyarakat mengenai pentingnya pengelolaan dan pemanfaatan kembali sampah.
4. Mendukung ekonomi sirkular dengan menghubungkan kegiatan daur ulang dan peluang ekonomi UMKM lokal.

## Kelebihan Website

Beberapa kelebihan yang ditawarkan oleh LokaKarya antara lain:

1. **Menggabungkan Dua Layanan dalam Satu Platform**

   Pengguna dapat mengenal produk kerajinan hasil daur ulang sekaligus mencari informasi bank sampah tanpa harus mengakses website yang berbeda.

2. **Mempermudah Pencarian Bank Sampah**

   Fitur pencarian dan filter membantu pengguna menemukan informasi lokasi bank sampah berdasarkan jenis material yang ingin disetorkan.

3. **Mendukung Promosi UMKM Lokal**

   Katalog produk memberikan ruang bagi UMKM untuk memperkenalkan hasil kerajinan daur ulang kepada calon konsumen.

4. **Tampilan Responsif dan Mudah Digunakan**

   Website dirancang dengan tata letak responsif agar dapat diakses melalui berbagai ukuran layar, baik desktop maupun perangkat mobile.

5. **Meningkatkan Kesadaran Lingkungan**

   Website memberikan informasi dan alternatif bagi masyarakat untuk menerapkan kebiasaan konsumsi yang lebih bertanggung jawab serta mengurangi limbah.

6. **Informasi yang Terorganisasi**

   Informasi produk, lokasi bank sampah, dan formulir penyetoran disajikan dalam satu landing page dengan navigasi yang terstruktur.
   
## Analisis 5W1H

- **What:** Website yang menggabungkan katalog produk kerajinan daur ulang UMKM lokal dan direktori bank sampah.
- **Who:** Masyarakat, konsumen produk ramah lingkungan, dan UMKM lokal.
- **When:** Digunakan saat pengguna ingin mencari produk daur ulang atau informasi penyetoran sampah.
- **Where:** Dapat diakses melalui browser pada perangkat desktop maupun mobile.
- **Why:** Untuk mendukung promosi UMKM lokal dan meningkatkan kesadaran masyarakat terhadap pengelolaan sampah.
- **How:** Melalui katalog produk, pencarian bank sampah, informasi lokasi, dan formulir penyetoran sampah berbasis website.
## Teknologi yang Digunakan

- **HTML5 Semantic:** Digunakan untuk menyusun struktur halaman website.
- **CSS3:** Digunakan untuk mengatur tampilan, custom properties, dan responsive layout.
- **Bootstrap 5:** Digunakan melalui CDN untuk membantu pembuatan grid dan navbar.
- **Vanilla JavaScript:** Digunakan untuk mengatur rendering data dan interaksi website.
- **Figma-exported SVG/JPG Assets:** Digunakan sebagai aset visual hasil ekspor dari Figma.

## Fitur Website

- Header floating responsif dengan anchor navigation.
- Hero section bertema ekonomi sirkular dengan ilustrasi tote bag, botol, dan tanaman.
- Benefit cards yang menampilkan manfaat platform.
- Katalog delapan produk simulasi dengan filter kategori.
- Preview empat bank sampah simulasi dengan fitur pencarian, filter material, active card, marker peta, dan tautan Google Maps.
- Formulir setor sampah simulasi dengan validasi nama, WhatsApp, jenis sampah, tanggal, lokasi, dan metode setor.
- Success state pada formulir yang membedakan pengajuan simulasi dari konfirmasi jadwal.
- Footer yang berisi informasi kontak dan keterangan data simulasi.

## Sitemap

URL Sitemap: [Tambahkan URL Sitemap Project di sini]

## Design Reference

- [Figma Mockup](https://www.figma.com/design/PoGctK8bkFvyKu710ViZau/Desain-Web?node-id=125-163)
- [Figma Wireframe](https://www.figma.com/design/PoGctK8bkFvyKu710ViZau/Desain-Web?node-id=125-164)

## Menjalankan Proyek

1. Clone repository:

   ```bash
   git clone https://github.com/miawmiawpaw/LokaKarya.git
   cd LokaKarya
   ```

2. Buka folder project menggunakan Visual Studio Code.
3. Jalankan file `index.html` menggunakan ekstensi Live Server.

**Catatan:** Bootstrap dan Google Fonts dimuat melalui CDN sehingga koneksi internet diperlukan untuk menampilkan website secara optimal.

## Struktur File

```text
LokaKarya/
├── index.html
└── assets/
    ├── css/
    │   └── style.css
    ├── js/
    │   ├── data.js
    │   └── main.js
    └── img/
```

Keterangan:

- `index.html` — Berisi markup dan struktur landing page.
- `assets/css/style.css` — Berisi design tokens, layout, styling komponen, dan aturan responsif.
- `assets/js/data.js` — Berisi data produk, manfaat, lokasi, dan konfigurasi kontak.
- `assets/js/main.js` — Berisi fungsi rendering dan interaksi menggunakan Vanilla JavaScript.
- `assets/img/` — Berisi aset visual lokal hasil ekspor Figma.

## Batasan Phase 1

Pada tahap Phase 1, website masih berupa implementasi frontend dan belum memiliki fitur backend maupun database. Beberapa batasan yang terdapat pada tahap ini meliputi:

- Belum tersedia sistem autentikasi pengguna.
- Belum tersedia fitur checkout dan pembayaran.
- Belum tersedia halaman katalog dan detail produk secara terpisah.
- Belum tersedia direktori bank sampah secara terpisah.
- Formulir setor sampah hanya berfungsi sebagai simulasi frontend.
- Informasi produk, harga, lokasi, jam operasional, kontak, dan tautan masih menggunakan data simulasi.
