# RZD Digital Bank — Demo Website

Website demo pencatatan keuangan dengan tema 3D-inspired, navy/electric blue, logo SVG, dashboard, transaksi, grafik, laporan CSV, dan profil.

## Jalankan lokal
1. Ekstrak ZIP.
2. Buka folder `RZD_Digital_Bank` di VS Code.
3. Jalankan `index.html` menggunakan ekstensi Live Server, atau gunakan server lokal sederhana.
4. Data demo disimpan pada `localStorage` browser.

## Deploy ke GitHub Pages
1. Buat repository baru di GitHub.
2. Upload seluruh isi folder ini (pastikan `index.html` ada di root repository).
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu Save.
6. Tunggu proses deployment selesai dan buka URL Pages yang diberikan GitHub.

## Deploy ke Cloudflare Pages
1. Push project ke repository GitHub.
2. Masuk ke dashboard Cloudflare → **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
3. Pilih repository RZD.
4. Framework preset: **None**.
5. Build command: kosongkan.
6. Build output directory: `/` (root).
7. Klik **Save and Deploy**.

## Catatan penting
Ini prototipe edukasi, bukan bank sungguhan. Login hanya simulasi tampilan; nama dan transaksi tersimpan di browser yang sama. Tidak ada backend, database bersama, transfer uang, rekening, atau autentikasi aman. Jangan masukkan password atau data keuangan asli. Untuk akun sungguhan dan akses admin diperlukan backend, database, autentikasi server-side, HTTPS, dan audit keamanan.
