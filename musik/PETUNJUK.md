# Musik latar

Tambahkan file lagu pilihanmu di folder ini dengan nama `lagu.mp3`.

Jika nama atau ekstensi berbeda, ubah konfigurasi di index.html:

```js
const MUSIK = 'musik/lagu.mp3';
```

Nama file dan huruf besar/kecil harus sesuai. Gunakan file audio langsung, bukan link halaman YouTube atau Spotify.

Musik mulai setelah pengunjung mengeklik “Buka kejutannya” atau “Putar musik”, berulang otomatis, dan tetap berjalan saat berpindah langkah. Tombol “Jeda musik” menghentikan sementara pemutaran.

Volume awal 45%, dapat diubah melalui `audio.volume = 0.45` di index.html (rentang 0 sampai 1).

File lagu belum disertakan. Setelah menambahkannya, buka website dan periksa pemutaran di browser.
