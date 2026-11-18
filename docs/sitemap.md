# Sitemap LokaKarya

## Status Proyek

LokaKarya saat ini merupakan project **frontend-only** untuk kebutuhan praktikum.

- Tidak menggunakan backend.
- Tidak menggunakan database.
- Tidak memproses checkout atau pembayaran.
- Tidak memiliki keranjang belanja atau sistem transaksi internal.
- Data produk, harga, lokasi, jam operasional, dan kontak bersifat simulasi.
- Form setor sampah hanya melakukan simulasi validasi dan konfirmasi frontend.

## Sitemap Phase 1

```text
LokaKarya
└── Landing Page (`index.html`)
    ├── Header & Navigation
    │   ├── Beranda → `#beranda`
    │   ├── Katalog Produk → `#katalog-produk`
    │   ├── Lokasi Bank Sampah → `#lokasi-bank-sampah`
    │   ├── Setor Sampah → `#form-setor`
    │   └── Kontak → `#kontak`
    │
    ├── Beranda (`#beranda`)
    │   ├── Hero
    │   ├── CTA Jelajahi Produk → `#katalog-produk`
    │   └── CTA Cari Bank Sampah → `#lokasi-bank-sampah`
    │
    ├── Manfaat LokaKarya (`#manfaat`)
    │   ├── Produk UMKM Penuh Cerita
    │   ├── Bank Sampah Lebih Dekat
    │   └── Dukung Usaha Lokal
    │
    ├── Katalog Produk (`#katalog-produk`)
    │   ├── Filter Semua
    │   ├── Filter Plastik
    │   ├── Filter Kertas/Kardus
    │   ├── Filter Tekstil/Kain
    │   ├── Kartu produk simulasi
    │   ├── Beli via WhatsApp → kanal eksternal simulasi
    │   └── Lihat di Marketplace → kanal eksternal simulasi
    │
    ├── Lokasi Bank Sampah (`#lokasi-bank-sampah`)
    │   ├── Pencarian nama atau alamat
    │   ├── Filter jenis sampah
    │   ├── Daftar lokasi simulasi
    │   ├── Peta ilustratif dan marker
    │   └── Buka Google Maps → pencarian eksternal simulasi
    │
    ├── Form Setor Sampah (`#form-setor`)
    │   ├── Nama lengkap
    │   ├── Nomor WhatsApp
    │   ├── Jenis sampah
    │   ├── Tanggal penyetoran
    │   ├── Lokasi tujuan
    │   ├── Catatan
    │   ├── Metode penyetoran
    │   └── Konfirmasi pengajuan simulasi
    │
    └── Kontak (`#kontak`)
        ├── Tentang LokaKarya
        ├── Jelajahi
        ├── Email simulasi
        ├── WhatsApp simulasi
        └── Media sosial simulasi
```

## Navigasi Eksternal

Landing page tidak memproses transaksi internal. Aksi berikut hanya membuka layanan eksternal atau simulasi:

| Aksi | Tujuan |
|---|---|
| Beli via WhatsApp | Kanal WhatsApp UMKM simulasi |
| Lihat di Marketplace | Hasil pencarian marketplace simulasi |
| Buka Google Maps | Hasil pencarian lokasi simulasi |

## Halaman yang Belum Dibuat

Halaman berikut belum termasuk Phase 1 dan tidak tersedia pada project saat ini:

- Halaman katalog produk terpisah.
- Halaman detail produk.
- Halaman direktori bank sampah terpisah.
- Halaman login dan registrasi.
- Dashboard UMKM.
- Dashboard admin.
- Checkout dan pembayaran.
- Keranjang belanja.
- Riwayat transaksi.
- Backend dan database.
- Sistem reward atau poin.
- Pelacakan penjemputan real-time.

Fitur tersebut dapat direncanakan pada fase berikutnya setelah kebutuhan backend dan aturan bisnis ditetapkan.
