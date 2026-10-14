# Boku no Sekai — Konversi CSS ke SCSS

## Struktur
Proyek menggunakan pola 7-1: `abstracts`, `base`, `components`, `layout`, `pages`, `themes`, `vendors`, dan file utama `scss/main.scss`.

## Cara menjalankan kompilasi
Pastikan Node.js sudah terpasang, lalu buka terminal di folder proyek:

```bash
npm install
npm run build:css
```

Untuk otomatis mengompilasi ulang ketika file SCSS disimpan:

```bash
npm run watch:css
```

Hasil kompilasi disimpan ke `style.css`, yang dipanggil oleh `index.html`.

## Catatan aset
Letakkan `background.mp4` dan `orangganteng.webp` di folder yang sama dengan `index.html` agar aset tersebut tampil. Kedua aset itu tidak termasuk file yang dikirim saat ini.
