---
author: AgungIchiruki
pubDatetime: 2023-11-20T23:28:29.311198+08:00
title: Membuat dan Menampilkan File HTML di Web Browser
postSlug: membuat-dan-menampilkan-file-html-di-web-browser
tags:
  - html
  - membuat_file_html
  - menampilkan_file_html_di_web_browser
  - belajar
description: "Index belajar HTML (HyperText Markup Language)"
---

Pada bagian ini, kita akan belajar membuat halaman web dengan HTML dan menampilkannya pada web browser. Sebelum mulai, pastikan kalian sudah menginstall kode editor dan web browser di mesin kalian.

Kode editor yang saya sarankan adalah VSCode dan web browser-nya adalah Mozilla Firefox. Dengan menggunakan keduanya, kalian akan mudah mengikuti tulisan ini. Karena sepanjang tulisan ini, saya akan menggunakan keduanya.

### Membuat File HTML
Buat sebuah direktori sebagai tempat kita menyimpan file HTML yang akan kita buat. Pada contoh dibawah ini, saya membuat direktori "Belajar HTML". Kalian bebas menamai direktori ini, intinya mudah kalian kenali sebagai direktori tempat kalian menyimpan file HTML.

![buat folder html](/assets/posts-images/belajar-html/buat-folder.png)

Kemudian buka kode editor, lalu arahkan ke folder HTML yang sudah kita buat tadi.

![vscode klik file](/assets/posts-images/belajar-html/vscode-klik-file.png)
Klik menu file.

![vscode klik open folder](/assets/posts-images/belajar-html/vscode-klik-open-folder.png)
Klik open folder.

![vscode pilih folder](/assets/posts-images/belajar-html/vscode-pilih-folder.png)
Pilih folder HTML yang sudah kita buat.

![vscode buka folder](/assets/posts-images/belajar-html/vscode-klik-buka-folder.png)
Klik tombol open di sudut kanan atas.

Kemudian buat sebuah file baru dengan nama "index.html".

![vscode buat file baru](/assets/posts-images/belajar-html/vscode-new-file.png)
Klik tombol "New File" seperti gambar diatas.

![vscode beri nama file](/assets/posts-images/belajar-html/vscode-nama-file.png)
Beri nama "index.html" seperti gambar diatas.

Kalian bisa mengganti nama file "index" dengan nama lain-nya. Tetapi, yang harus diingat bahwa file HTML harus berakhiran ".html", kalian tidak bisa kreatif di bagian ini. Jika kalian mengganti-nya dengan yang lain misalnya ".xxxx", maka file yang kita buat tidak akan lagi dikenali sebagai file HTML. Inilah yang dinamakan dengan ekstensi file, dimana ekstensi file ini berguna sebagai identifikasi sebuah file, dan ekstensi file HTML ialah ".html".

Kemudian, tuliskan kode HTML dibawah ini ke file "index.html" yang tadi kita buat.

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

Lalu simpan perubahan file HTML kita dengan menekan "ctrl + s".

Jika kalian bingung dengan kode diatas itu wajar, karena kalian baru belajar. Abaikan saja karena kode diatas nanti akan kita bahas di tulisan selanjutnya. Tujuan kita ditulisan ini hanya belajar membuat dan menampilkan file HTML.

Sekarang, buka folder tempat kita menyimpan file HTML tadi. Kemudian klik kiri dua kali pada file HTML yang sudah kita buat untuk membukanya pada web browser. Sistem Operasi kita akan mengenali file HTML yang kita buat dan akan otomatis membukanya dengan web browser yang terinstall.

![buka file html](/assets/posts-images/belajar-html/buka-file-html.png)
Klik dua kali pada file HTML.

![tampilan file HTML di web browser](/assets/posts-images/belajar-html/tampilan-html-di-web-browser.png)
Tampilan file HTML pada web browser.

Sampai disini, web browser sudah menampilkan file HTML yang kita buat. Bisa dilihat bahwa kode-kode HTML yang kita ketikkan tadi akan ditampilkan oleh web browser sebagai sebuah halaman web.