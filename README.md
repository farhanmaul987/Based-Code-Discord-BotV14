# PiggyBank

Sistem manajemen keuangan pribadi yang simpel, fleksibel, dan bisa diakses kapan pun dari mana pun. Cocok untuk melacak pemasukan, pengeluaran, dan melihat gambaran kesehatan finansial tanpa ribet.

## Fitur utama
- Catat pemasukan dan pengeluaran dengan cepat
- Kategori dan tag untuk pengelompokan transaksi
- Ringkasan harian, mingguan, dan bulanan
- Filter dan cari transaksi dengan mudah
- Ekspor data (CSV) untuk backup atau analisis
- Sinkronisasi/backup ke cloud (opsional)
- Mode aman: enkripsi data sensitif lokal

## Kenapa pakai PiggyBank?
- Antarmuka minimal — fokus pada apa yang penting: uang Anda.
- Ringan dan bisa dikembangkan sesuai kebutuhan pribadi.
- Privasi diutamakan — Anda pegang kontrol data.

## Quick start
1. Clone repo:
    ```
    git clone <repo-url>
    cd PiggyBank
    ```
2. Instal dependensi:
    ```
    # contoh untuk Node-based project
    npm install
    ```
3. Konfigurasi environment:
    - Buat file `.env` berdasarkan `.env.example`
    - Isi kredensial DB / penyimpanan cloud bila perlu
4. Jalankan aplikasi:
    ```
    npm run dev
    ```
5. (Opsional) Jalankan migrasi database dan seed:
    ```
    npm run migrate
    npm run seed
    ```

## Contoh alur penggunaan
- Tambah akun (cash / bank / e-wallet)
- Catat pemasukan saat gaji masuk
- Catat pengeluaran saat belanja atau tagihan
- Lihat ringkasan untuk mengetahui kebiasaan pengeluaran
- Ekspor laporan bulanan saat perlu laporan

## Arsitektur & teknologi (saran)
- Frontend: React / Vue / React Native (mobile)
- Backend: Node.js + Express / Python + FastAPI
- Database: SQLite untuk lokal, PostgreSQL untuk produksi
- Opsional: Docker untuk lingkungan konsisten

## Kontribusi
- Buka issue bila ada fitur/bug
- Fork → branch fitur → PR dengan deskripsi singkat
- Ikuti gaya kode dan tambahkan test jika memungkinkan

## Lisensi
Direkomendasikan: MIT — sesuaikan menurut preferensi.

## Catatan privasi singkat
Simpan data sensitif secara terenkripsi. Jika menyediakan sinkronisasi cloud, beri opsi untuk mematikan dan/atau memilih penyedia.

Selamat membangun kebiasaan finansial yang lebih baik dengan PiggyBank!