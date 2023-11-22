---
author: AgungIchiruki
pubDatetime: 2023-11-20T23:28:29.311198+08:00
title: Struktur Dasar HTML
postSlug: struktur-dasar-html
tags:
  - html
  - membuat_file_html
  - menampilkan_file_html_di_web_browser
  - belajar
description: "Index belajar HTML (HyperText Markup Language)"
---


Sekarang kita akan mempelajari struktur dasar dari HTML. Buka kembali file "index.html" yang sudah kita buat di posts sebelumnya dengan kode editor VSCode. Pada file tersebut, kita sudah menuliskan struktur dasar atau struktur minimal sebuah HTML.

```html
<!DOCTYPE html>

<html>
  <head>
    <title>My First Website</title>
  </head>

  <body>
    <h1>Hello, This is my first website</h1>
  </body>
</html>
```

Kode HTML diatas terdiri dari beberapa tag, seperti tag `<html>`, `<head>`, `<body>`, dll. Kita akan bedah tag-tag ini beserta kegunaannya.

Pada baris pertama terdapat tag `<!DOCTYPE html>`. Tag ini berguna untuk memberi tahu browser bahwa halaman web yang kita buat menggunakan HTML versi terbaru yaitu HTML5.

Lalu terdapat tag `<html>`. Tag ini berguna untuk menandai awal dari kode HTML. Perhatikan pada baris terakhir, terdapat tag yang mirip dengan tag ini, tetapi ditambahkan dengan karakter "/" diawal yaitu tag `</html>`. Tag `</html>` ini adalah tag penutup dari tag `<html>` yang berfungsi untuk menandai akhir dari kode HTML. Semua elemen HTML yang ingin dibuat, harus dituliskan didalam tag `<html>` dan `</html>` ini.

Kemudian didalam tag `<html>...</html>`, yang pertama terdapat tag `<head>...</head>`. Tag ini berguna untuk memberikan informasi-informasi meta tentang halaman web yang kita buat, seperti tag `<title>...</title>` yang berguna untuk memberikan informasi judul dari halaman web.

![Judul Web](/assets/posts-images/belajar-html/web-title.png)

Tidak hanya informasi, tag `<head>...</head>` juga digunakan untuk menuliskan kode CSS dan Javascript internal, serta koneksi ke file CSS dan JavaScript external. Masih banyak lagi tag-tag yang berguna untuk memberikan informasi halaman web yang bisa dituliskan diantara tag `<head>...</head>` ini, Tetapi untuk struktur dasar, penggunaan tag `<title>...</title>` saja saya rasa sudah cukup.

Kemudian ada tag `<body>...</body>`. Tag ini berfungsi untuk menentukan konten utama dari sebuah halaman web. Semua elemen yang ingin kita tampilkan pada halaman web seperti teks, gambar, video/audio, tautan/link, dan elemen lainnya harus dituliskan diantara didalam tag ini. Contoh pada kode HTML diatas, terdapat tag `<h1>...</h1>` didalam tag `<body>...</body>` yang berfungsi untuk menampilkan teks judul utama atau heading 1. Maka saat kita melihat tampilan kode HTML kita sebagai halaman web pada web browser, akan tampil teks yang kita tuliskan diantara tag `<h1>...</h1>` dalam format judul utama atau heading 1.

![konten heading 1 (h1)](/assets/posts-images/belajar-html/web-h1.png)

Semua tag-tag yang kita bahas kecuali tag `<!DOCTYPE html>` dan `<h1>...</h1>`, adalah struktur dasar atau struktur minimal yang harus ada pada sebuah file HTML. Kita lihat bahwa tag-tag yang sudah kita pelajari masing-masing memiliki pasangan atau tag penutup,meskipun ada juga tag-tag HTML yang berdiri sendiri atau tag yang tidak memiliki tag penutup.