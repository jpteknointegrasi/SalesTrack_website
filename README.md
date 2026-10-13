# SalesTrack — Website Publik

Landing page SalesTrack by Nusa Tekno untuk **salestracker.biz.id**, dihosting dengan GitHub Pages.
Aplikasi SalesTrack ada di repo terpisah (`jpteknointegrasi/SalesTrack`) dan tetap dihosting di Vercel.

## Isi
- `index.html` — satu halaman statis (HTML, CSS, JS tanpa build).
- `assets/` — ilustrasi hero dan banner partner.
- `CNAME` — domain kustom untuk GitHub Pages.
- `.nojekyll` — file disajikan apa adanya.

## Pengaturan
Di bagian atas `<script>` dalam `index.html`:
- `APP_URL` — alamat aplikasi (tombol Masuk dan formulir order). Sekarang `https://salestrack-virid.vercel.app/app`.
- `ORDER_SLUG` — alamat formulir order umum; samakan dengan Pengaturan Kemitraan di aplikasi (sekarang `nusatekno`).

Link partner `?ref=KODE` dan `?order=alamat` yang dibuka di website diteruskan otomatis ke formulir order di aplikasi.

## Publikasi
1. Settings → Pages → Source: Deploy from a branch → `main` / `(root)`.
2. DNS di DomaiNesia: A `@` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153; CNAME `www` → `jpteknointegrasi.github.io`.
3. Setelah DNS aktif: centang **Enforce HTTPS**.
