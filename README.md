# ACL Directory

Alternatif iterasi AI Creator Labs Public Directory yang fokus pada direktori: layar pertama langsung katalog.

- Satu katalog untuk Skills, Video, dan Artikel dengan filter tipe, topik, level, dan urutan.
- Search palette (Ctrl/Cmd + K atau `/`) dengan hasil dikelompokkan dan navigasi keyboard.
- Panel detail di sisi kanan, tanpa pindah halaman.
- Font: Plus Jakarta Sans, dengan Cormorant Garamond Italic sebagai aksen serif (Google Fonts, lisensi OFL).
- Ikon pixel, logo, dan palet violet ACL; cursor trail yang sama dengan versi sebelumnya.

## Menjalankan

`index.html` (CSS dan JS inline) plus folder `images/`. Buka `index.html` di browser atau deploy folder ini ke hosting statis (Vercel, Netlify, GitHub Pages). Jaga `index.html` dan `images/` tetap sejajar.

## Catatan

- Routing memakai hash: `#/skills`, `#/video`, `#/artikel`, dengan parameter `c` (topik), `l` (level), `s` (urutan), `q` (kata kunci), dan `i` (item yang terbuka).
- Data masih contoh: link video (satu URL YouTube), daftar skill, artikel, dan angka popularitas untuk pengurutan.
