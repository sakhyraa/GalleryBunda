# Gallery Bunda — Link-in-Bio

Website statis HTML, CSS, dan JavaScript dengan tampilan editorial elegan, warna cream, ungu tua/terong, lavender, dan aksen butter yellow. Sudah responsif untuk HP dan laptop, dan dapat di-host gratis di GitHub Pages.

## File
- `index.html` — isi halaman dan semua tautan.
- `style.css` — desain dan responsive layout.
- `script.js` — JavaScript ringan (tidak perlu build).

## WAJIB cek tautan sebelum publikasi
Buka `index.html` dan ganti placeholder berikut:

1. **WhatsApp:** cari `628XXXXXXXXXX` (muncul pada tombol booking dan ikon footer), lalu ganti dengan nomor admin dalam format internasional tanpa tanda plus/spasi. Contoh format: `6281234567890`.
2. **TikTok:** cari `@USERNAME_TIKTOK` dan ganti dengan username TikTok Gallery Bunda.
3. **Google Maps:** ganti `https://maps.google.com/` dengan link lokasi toko yang tepat.
4. **How to Rent:** ganti `https://drive.google.com/` pada tombol How to Rent dengan link Google Drive panduan sewa yang sudah disetel agar bisa dibuka oleh calon penyewa.
5. **Katalog Sepatu:** untuk sementara mengarah ke Instagram `@galery_bunda81`. Ubah jika katalog memiliki tautan tersendiri.
6. **Instagram:** sudah diarahkan ke `https://www.instagram.com/galery_bunda81/`.

Jangan publikasikan sebelum semua placeholder diganti.

## Preview lokal
1. Ekstrak ZIP.
2. Buka folder di VS Code.
3. Buka `index.html` di browser atau gunakan Live Server.

## Publikasi di GitHub Pages
1. Buat repository baru di GitHub, misalnya `gallery-bunda`.
2. Untuk akun gratis, pilih repository **Public**.
3. Upload `index.html`, `style.css`, `script.js`, dan `README.md` langsung ke root repository (jangan diletakkan di subfolder lain).
4. Klik **Commit changes**.
5. Buka **Settings → Pages**.
6. Pada **Build and deployment**, pilih **Deploy from a branch**.
7. Pilih branch `main`, folder `/(root)`, lalu klik **Save**.
8. Tunggu proses deploy selesai. Alamat biasanya berbentuk `https://USERNAME.github.io/gallery-bunda/`.
9. Tes setiap tombol dari HP dan laptop.

## Catatan
- Tidak membutuhkan database, PHP, Node.js, atau proses build.
- Google Fonts memerlukan koneksi internet; font cadangan akan dipakai jika tidak tersedia.
- Jangan menyimpan kata sandi atau data pribadi pelanggan di repository publik.
