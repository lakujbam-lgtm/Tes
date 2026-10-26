# BimbelKu — Struktur HTML Terpisah

## Cara menjalankan
Karena halaman dimuat menggunakan `fetch()`, jangan membuka `index.html` langsung dengan `file://`.
Jalankan melalui server lokal atau deploy ke Vercel.

## Struktur
- `index.html` — kerangka utama
- `components/menu.html` — navbar/menu
- `components/notifikasi.html`, `components/login.html`, `components/daftar.html` — modal terpisah
- `components/footer.html` — footer
- `pages/` — konten setiap menu/materi
- `css/style.css` — CSS tambahan
- `js/app.js` — fungsi JavaScript dan pemuat halaman

## File menu/materi
- `pages/beranda.html`
- `pages/fundamental.html`
- `pages/fundamental-bahasa.html`
- `pages/logika.html`
- `pages/matematika.html`
- `pages/subtes-utbk.html`
- `pages/pu.html`
- `pages/ppu.html`
- `pages/pbm.html`
- `pages/pk.html`
- `pages/pm.html`
- `pages/lbi.html`
- `pages/lbe.html`
- `pages/tryout.html`

## GitHub dan Vercel
Unggah seluruh isi folder proyek ini ke repository GitHub (bukan hanya `index.html`), lalu pastikan Vercel menggunakan repository tersebut. Untuk proyek HTML statis, biasanya Framework Preset dapat dipilih `Other` dan Build Command dikosongkan.
