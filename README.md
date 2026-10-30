[Bahasa Indonesia](./README.md) | [English](./README.en.md)

# Damta Noviyan Muhamad Faiz

Mahasiswa Sistem Informasi di UIN Syarif Hidayatullah Jakarta. Saya membangun sistem full-stack dari rancangan database sampai deployment, dengan fokus pada aplikasi bisnis, sistem informasi akuntansi, dan keamanan aplikasi web.

[Email](mailto:damtafaiz@gmail.com) | [LinkedIn](https://linkedin.com/in/damta-noviyan-muhamad-faiz-955493221/) | [Portofolio](https://damtaweb.com)

## Daftar isi

- [Tentang saya](#tentang-saya)
- [Sedang dikerjakan](#sedang-dikerjakan)
- [Ringkasan repository](#ringkasan-repository)
- [Proyek pilihan](#proyek-pilihan)
- [Proyek lainnya](#proyek-lainnya)
- [Tumpukan teknologi](#tumpukan-teknologi)
- [Distribusi bahasa](#distribusi-bahasa)
- [Cara saya bekerja](#cara-saya-bekerja)
- [Arah karier](#arah-karier)
- [Sedang dipelajari](#sedang-dipelajari)
- [Sistem lokal](#sistem-lokal)
- [Terhubung](#terhubung)

## Tentang saya

Saya memilih masalah nyata di sekitar sebagai sumber proyek: warung, kampus, komunitas gamer, usaha kecil, sampai kebutuhan pribadi. Prinsip kerja yang saya pegang:

- Membangun proyek end-to-end, dari desain database sampai deployment, bukan potongan fitur.
- Mencoba stack baru untuk memahami trade-off arsitekturnya, bukan sekadar mengikuti tren.
- Menulis dokumentasi dan menata repository supaya proyek lama tetap bisa dibaca ulang.
- Menjaga proyek yang menyangkut keamanan tetap privat sampai arsitekturnya matang.

## Sedang dikerjakan

**Sistem Informasi Akuntansi Otomotif** (repository privat). Aplikasi tugas kuliah Sistem Informasi Akuntansi yang mensimulasikan pembukuan perusahaan suku cadang. Empat siklus (pendapatan, pengeluaran, produksi, SDM dan penggajian) menjurnal otomatis ke buku besar, akses dibatasi per peran (Project Manager, ketua, anggota, pengunjung), dan ada alat untuk memantau progress mingguan tim. Rancangan basis datanya relasional dan dipecah per siklus, dengan tabel pilihan supaya isian terbatas tidak diketik bebas. Seluruh data perusahaan di dalamnya berlabel simulasi.
Stack: Next.js, TypeScript, Tailwind CSS, Firebase (Firestore dan Auth), dengan salinan MySQL untuk analisis.

**sentinel** (repository privat). Platform keamanan web terdistribusi dengan pemindaian DAST dan penambalan otomatis berbasis AST, disusun sebagai monorepo poliglot (Next.js, Hono, Python, Go) dengan hierarki peran SOC enam tingkat. Sengaja ditutup sampai arsitekturnya matang.

## Ringkasan repository

20 repository: 17 publik dan 3 privat (`sistem-SIA`, `sentinel`, `finance-person`).

| Repository | Deskripsi | Bahasa utama | Visibilitas |
|---|---|---|---|
| sistem-SIA | Sistem informasi akuntansi otomotif, 4 siklus, simulasi | TypeScript | Privat |
| sentinel | Platform keamanan web terdistribusi | TypeScript | Privat |
| finance-person | Pelacak keuangan pribadi dengan Google sign-in | TypeScript | Privat |
| [perpustakaan-digital](https://github.com/damta8827773/perpustakaan-digital) | Perpustakaan digital UIN Jakarta, antarmuka mahasiswa dan admin terpisah | TypeScript | Publik |
| [agent-stack-audit](https://github.com/damta8827773/agent-stack-audit) | CLI read-only untuk mengaudit skill, plugin, dan hook Claude Code | Go | Publik |
| [UMKM-Konsep-Sistem-Informasi](https://github.com/damta8827773/UMKM-Konsep-Sistem-Informasi) | Warung Analytics: etalase dan inventori admin | TypeScript | Publik |
| [geprek-supply](https://github.com/damta8827773/geprek-supply) | Pemetaan pemasok dan rute radius pintar | TypeScript | Publik |
| [premium](https://github.com/damta8827773/premium) | Etalase produk digital dengan contoh API client | PHP | Publik |
| [esports-management-system](https://github.com/damta8827773/esports-management-system) | Manajemen tim esports Mobile Legends | TypeScript | Publik |
| [sistem-otomasi-suara](https://github.com/damta8827773/sistem-otomasi-suara) | Kendali laptop lewat suara dengan Whisper | Python | Publik |
| [steam-cuci-motor](https://github.com/damta8827773/steam-cuci-motor) | Sistem kasir usaha cuci motor steam | TypeScript | Publik |
| [pendapatan](https://github.com/damta8827773/pendapatan) | Pencatat pemasukan full-stack | JavaScript | Publik |
| [finance-web](https://github.com/damta8827773/finance-web) | Pencatatan keuangan harian usaha crepes | TypeScript | Publik |
| [portoprivate](https://github.com/damta8827773/portoprivate) | Kode sumber situs portofolio | TypeScript | Publik |
| [catatan-belajar](https://github.com/damta8827773/catatan-belajar) | Catatan teknis dan diskusi belajar | - | Publik |
| [for-my-fav-person](https://github.com/damta8827773/for-my-fav-person) | Proyek pribadi lintas bahasa | TypeScript | Publik |
| [tugas-5](https://github.com/damta8827773/tugas-5), [pertemuan-1](https://github.com/damta8827773/pertemuan-1), [pertemuan-2](https://github.com/damta8827773/pertemuan-2), [pertemuan-6](https://github.com/damta8827773/pertemuan-6) | Latihan mingguan perkuliahan | HTML, CSS | Publik |

## Proyek pilihan

### premium: etalase produk digital

Etalase untuk penjualan produk digital, dengan contoh integrasi API client sebagai referensi teknis.

- Pembayaran lewat Midtrans
- Manajemen produk digital dan pengiriman otomatis setelah pembayaran berhasil
- Autentikasi dan akses berbasis Firebase
- Stack: PHP, JavaScript, CSS, Firebase. Lisensi MIT.

Catatan: versi lokal memakai lebih banyak bahasa (C, C++, C#, Go, Ruby, Rust, Scala) untuk contoh API client, sedangkan versi di GitHub baru berisi PHP, CSS, dan JavaScript.

### geprek-supply: pemetaan pemasok

Platform pemetaan dan smart routing yang menghubungkan warung ayam geprek dengan pemasok bahan baku terdekat. Juga menjadi deliverable mata kuliah Konsep Sistem Informasi.

- Filter radius dengan rumus Haversine
- Estimasi waktu tempuh berbasis rute nyata
- Peta dengan MapLibre (bukan Google Maps) untuk menekan biaya
- Estimasi ongkos kirim mengikuti pola tarif ojek online
- Admin ditentukan lewat environment variable, tanpa pendaftaran email dinamis
- Stack: React, TypeScript, Node.js, Express, Prisma

### sistem-otomasi-suara: kendali lewat suara

Terminal voice controller yang menjalankan perintah di laptop lewat suara, dalam bahasa apa pun, dengan Whisper yang berjalan offline.

- Membuka aplikasi dan situs web
- Mengatur volume dan mengunci layar
- Tanpa API eksternal
- Stack: Python. Lisensi MIT.

### esports-management-system: manajemen tim esports

Sistem informasi manajemen tim Mobile Legends dengan pendekatan dashboard modern.

- Manajemen roster tim dan jadwal pertandingan
- Komponen konsisten berbasis styled-components
- Stack: React, TypeScript, Next.js

### steam-cuci-motor: sistem kasir

Sistem kasir untuk usaha cuci motor steam, full-stack TypeScript.

- Pencatatan transaksi kasir
- Data pelanggan dan riwayat servis
- Stack: TypeScript, Express, React, Prisma

### pendapatan: pelacak pemasukan

Aplikasi pelacak pemasukan full-stack yang terhubung ke MySQL.

- Frontend React 19 dan Vite, styling Tailwind CSS
- Backend Express 5 dengan Prisma dan MySQL
- Lisensi MIT

## Proyek lainnya

- **perpustakaan-digital**: sistem perpustakaan digital UIN Jakarta dengan antarmuka mahasiswa dan admin terpisah.
- **UMKM-Konsep-Sistem-Informasi**: Warung Analytics, etalase dan sistem inventori admin dengan Next.js dan Firebase.
- **finance-web**: pencatatan keuangan harian usaha crepes dengan Express, Prisma, dan Next.js.
- **agent-stack-audit**: alat bantu baris perintah berbahasa Go untuk mengaudit konfigurasi Claude Code.
- **portoprivate**: kode sumber situs portofolio pribadi, dipublikasikan untuk dipelajari.

## Tumpukan teknologi

<img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,php,python,go,mysql,firebase,tailwind,docker,git,figma&theme=dark" />

**Frontend:** React, Next.js, TypeScript, Tailwind CSS, Vite, HTML dan CSS.
**Backend:** Node.js dengan Express dan Hono, Prisma, PHP, Python, Go.
**Data dan infrastruktur:** MySQL, Firebase (Firestore dan Auth), SQLite untuk prototipe, Docker, Git dan GitHub, Vercel.
**Alat:** VS Code, Postman, Figma, npm dan pip.

## Distribusi bahasa

Dihitung dari seluruh 20 repository (publik dan privat) lewat data bahasa GitHub, total sekitar 8,2 MB kode.

| Bahasa | Porsi |
|---|---|
| TypeScript | 74,0% |
| JavaScript | 13,8% |
| PHP | 5,0% |
| Go | 2,7% |
| CSS | 2,1% |
| Python | 1,2% |
| HTML | 0,6% |
| Lainnya (PowerShell, Dockerfile, Java, Batchfile, Shell) | 0,6% |

## Cara saya bekerja

1. Memahami masalah nyata dulu, biasanya dari kasus di sekitar.
2. Merancang skema data dan relasinya sejak awal, bukan belakangan.
3. Membangun logika inti dan API sebelum antarmuka, supaya kontrak data jelas.
4. Membuat antarmuka secara bertahap dengan komponen yang bisa dipakai ulang.
5. Merapikan struktur repository dan dokumentasi sebelum proyek dianggap selesai.

Prinsip tambahan: memilih stack berdasarkan kebutuhan, menghindari over-engineering di proyek kecil tetapi tetap menyiapkan struktur yang bisa berkembang, dan menulis ulang bagian berantakan begitu ditemukan.

## Arah karier

Target jangka panjang saya adalah peran kepemimpinan di bidang keamanan siber. Jalur sertifikasi yang saya rencanakan, semuanya belum diambil:

| Tahap | Sertifikasi | Fokus |
|---|---|---|
| 1 | eJPT | Dasar penetration testing |
| 2 | OSCP | Keamanan ofensif praktikal |
| 3 | CISM | Manajemen keamanan informasi |
| 4 | CISSP | Kepemimpinan keamanan tingkat enterprise |

Urutannya bergeser dari teknis ke manajerial: kemampuan praktis dibangun lebih dulu agar pemahaman soal cara sistem diserang berasal dari pengalaman langsung, lalu tata kelola. CISSP ditaruh terakhir karena umumnya mensyaratkan pengalaman kerja bertahun-tahun.

## Sedang dipelajari

| Area | Alasan |
|---|---|
| Keamanan aplikasi (DAST dan AST) | Diterapkan di proyek sentinel |
| Arsitektur monorepo poliglot | Dibutuhkan untuk sentinel yang menggabungkan Next.js, Hono, Python, dan Go |
| Penetration testing dasar | Persiapan menuju eJPT |
| Tata kelola keamanan informasi | Persiapan menuju CISM dan CISSP |

Prinsip yang saya latih lewat proyek keamanan: defense in depth, least privilege, fail securely, deteksi otomatis, dan mencatat temuan secara terstruktur.

## Sistem lokal

Beberapa sistem sudah dibangun tetapi belum diunggah ke GitHub, sehingga belum masuk hitungan di atas: versi lokal premium, parafrase (Sentinel AI Paraphrase), inovasi (Neuro-Nexus), marketplace, inventori (gagas), absensi dengan pengenalan wajah, dan toko Shopify (Lumera).

## Terhubung

[Email](mailto:damtafaiz@gmail.com) | [LinkedIn](https://linkedin.com/in/damta-noviyan-muhamad-faiz-955493221/) | [Portofolio](https://damtaweb.com)
