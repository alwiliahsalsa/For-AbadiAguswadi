# Birthday Website — Soft Pink & Milky White

## Cara menjalankan di VSCode

1. Extract folder project.
2. Buka folder `birthday_website_boyfriend` di VSCode.
3. Buka `index.html`.
4. Klik kanan `index.html` → **Open with Live Server** jika extension Live Server sudah terpasang.
   Jika belum, install extension **Live Server** dari Extensions di VSCode.
5. Website akan terbuka di browser.

## Cara memasukkan video YouTube

Buka `index.html`, lalu cari:

```html
src="https://www.youtube.com/embed/VIDEO_ID?controls=1"
```

Ganti `VIDEO_ID` dengan ID video YouTube.

Contoh:
Link YouTube:
`https://www.youtube.com/watch?v=dQw4w9WgXcQ`

ID videonya:
`dQw4w9WgXcQ`

Sehingga menjadi:

```html
src="https://www.youtube.com/embed/dQw4w9WgXcQ?controls=1"
```

Audiens website tetap bisa menekan **Play/Pause, volume, dan fullscreen** melalui kontrol YouTube.

## Membuat website menjadi publik

Cara mudah:
1. Buat akun GitHub.
2. Buat repository baru, misalnya `birthday-website`.
3. Upload `index.html`, `style.css`, dan folder `assets`.
4. Masuk ke **Settings → Pages**.
5. Pada Source pilih **Deploy from a branch**.
6. Pilih branch `main` dan folder `/root`.
7. Save.
8. GitHub akan memberikan alamat website publik.

Pastikan file gambar tetap berada di:
`assets/birthday-cat.jpg`
