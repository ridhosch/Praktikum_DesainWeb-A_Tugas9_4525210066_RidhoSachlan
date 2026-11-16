# Laporan Tugas: One Page Website UMKM Selaras Coffee

| Informasi Praktikan | Keterangan |
| :--- | :--- |
| **Nama** | Ridho Sachlan |
| **NPM** | 4525210066 |
| **Kelas** | A |
| **Mata Kuliah** | Praktikum Desain Web |

Tugas pembuatan website profil UMKM satu halaman (*One Page Website*) menggunakan kerangka kerja Bootstrap 5 dan CSS

---

## Ringkasan Pengerjaan

Website UMKM *Selaras Coffee* dirancang dalam bentuk *One Page Website* menggunakan Bootstrap 5 dengan identitas visual bertema kopi. Komponen yang diimplementasikan meliputi navbar responsif dengan *hamburger toggle*, hero section informatif, notifikasi promo berbasis alert, tiga kartu produk unggulan, modal interaktif untuk informasi pemesanan, formulir kontak terstruktur, serta footer penutup. Styling eksternal dipisahkan ke dalam file `style.css` untuk memperkuat branding melalui palet warna hangat, efek interaksi kartu (*hover effect*), dan transisi yang serasi.

Selama proses perancangan, kendala yang dihadapi adalah bagaimana membuat komponen bawaan Bootstrap (seperti Card dan Navbar) agar tidak terlihat kaku dan menyerupai *template* standar pada umumnya. Selain itu, penyesuaian jarak antar elemen (*spacing*) pada *viewport* mobile sempat membuat tata letak formulir kontak dan bagian hero terasa terlalu padat, yang kemudian diatasi melalui pengaturan *padding* dan *margin* pada kustom CSS.

---

## Checklist Kelengkapan Komponen

| No | Komponen Wajib | Implementasi pada Kode | Keterangan |
| :--- | :--- | :--- | :--- |
| 1 | Navbar Responsif | `<nav class="navbar navbar-expand-lg ...">` | Collapse ke hamburger menu otomatis di perangkat mobile |
| 2 | Hero Section | `<header id="beranda" class="hero-section ...">` | Headline utama + tombol *call-to-action* dan ilustrasi |
| 3 | Minimal 3 Card | 3 kartu menu produk (`.card`, `.col-md-4`) | Menampilkan varian menu andalan, deskripsi & harga |
| 4 | Minimal 1 Alert | Alert promo (`.alert .alert-warning .alert-dismissible`) | Notifikasi diskon/kode promo yang bisa ditutup |
| 5 | Minimal 1 Modal | Modal popup (`#infoModal`) | Jendela dialog informasi pemesanan & kontak admin |
| 6 | Form Kontak | Form input nama, kontak, dan textarea pesan | Formulir interaktif *inquiries* & pertanyaan pelanggan |
| 7 | Footer | `<footer class="text-center py-3">` | Penutup halaman dengan informasi hak cipta tugas |
| 8 | Custom CSS | `style.css` (Terpisah) | Branding warna kopi (`:root`), variabel, & *hover effect* |

---

## Struktur Folder Project

## Struktur Folder Project

```text
Praktikum_DesainWeb-A_Tugas9_4525210066_RidhoSachlan/
├── css/
│   └── style.css
├── img/
├── index.html
└── README.md
