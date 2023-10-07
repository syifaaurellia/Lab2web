  # Lab2web
Nama : Syifa Aurellia Rahma

NIM  : 312210009

Kelas : TI.22.A1

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Instruksi Praktikum|[Click Here](#instruksipraktikum)|
|2|Praktikum|[Click Here](#praktikum)|
|3|Pertanyaan dan Tugas|[Click Here](#pertanyaandantugas)|

## Instruksi Praktikum :
> 1. Persiapkan text editor misalnya VSCode.
> 2. Buat file baru dengan nama `lab2_css_dasar.html`
> 3. Buat struktur dasar dari dokumen HTML.
> 4. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
> 5. Lakukan validasi dokumen css dengan mengakses https://jigsaw.w3.org/css-validator/


## Praktikum :
### 1. Membuat dokumen HTML
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS Dasar</title>
  </head>
  <body>
    <header>
      <h1>CSS Internal dan <i>Inline CSS</i></h1>
    </header>
    <nav>
      <a href="lab2_css_dasar.html">CSS Dasar</a>
      <a href="lab2_css_eksternal.html">CSS Eksternal</a>
      <a href="lab1_tag_dasar.html">HTML Dasar</a>
    </nav>
    <!-- CSS ID Selector -->
    <div id="intro">
      <h1>Hello World</h1>
      <p>
        Kami sedang belajar HTML dan CSS dasar, pada mata kuliah
        <b>Pemrograman Web</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran
        pertama yang kami dapat adalah membuat tampilan web sederhana dalam
        rangka mengenal tag-tag dasar HTML dan CSS.
      </p>
      <!-- CSS Class Selector -->
      <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
    </div>
  </body>
</html>
```
> - Maka hasilnya akan seperti berikut : 

![Screenshot (12)](https://github.com/syifaaurellia/Lab2web/assets/115867244/a4b9ea90-d52f-43f2-8d78-870c6bb28540)


### 2. Mendeklerasikan CSS Internal
```
<head>
<title>CSS Dasar</title>
<style>
body {
font-family:'Open Sans', sans-serif;
}
header {
min-height: 80px;
border-bottom:1px solid #77CCEF;
}
h1 {
font-size: 24px;
color: #0F189F;
text-align: center;
padding: 20px 10px;
}
h1 i {
color:#6d6a6b;
}
</style>
</head>
```
> - Maka hasilnya akan seperti berikut :

  ![Screenshot (13)](https://github.com/syifaaurellia/Lab2web/assets/115867244/01be2aa6-a4db-45ad-b058-26f651cbc5c8)

> - CSS internal adalah css yang filenya di letakan dalam html dengan pendeklarasian style.


### 3. Menambahkan Inline CSS
> - Menambahkan Inline CSS, kemudian tambahkan deklarasi inline CSS pada tag `<p>`
```
<p style="text-align: center; color: #ccd8e4;">
```
> - Maka hasilnya akan seperti berikut :

![Screenshot (16)](https://github.com/syifaaurellia/Lab2web/assets/115867244/dc2966a3-55bf-44ba-b5ff-0c3d0e2c5e9f)


### 4. Membuat CSS Eksternal
> - Membuat CSS Eksternal dengan membuat file baru dengan nama **style_eksternal.css** kemudian buat deklarasi css seperti berikut ini.
```
nav {
background: #20A759;
color:#fff;
padding: 10px;
}
nav a {
color: #fff;
text-decoration: none;
padding:10px 20px;
}
nav .active,
nav a:hover {
background: #0B6B3A;
}
```
> - Kemudian tambahkan <link untuk merujuk File CSS yang telah dibuat pada bagian `<head>`
```
<head>
<!-- menyisipkan css eksternal -->
<link rel="stylesheet" href="style_eksternal.css" type="text/css">
</head>
```

> - Maka hasilnya akan seperti berikut :

![Screenshot (17)](https://github.com/syifaaurellia/Lab2web/assets/115867244/5f78a0cf-48c6-4342-b203-07c23198b1fc)

> - CSS ekternal adalah CSS yang file di tempatkan di luar file HTML dengan menambahkan link dalam HTML agar tertaut dengan file CSS

### 5. Menambahkan CSS Selector
> - Selanjutnya menambahkan CSS Selector menggunkan ID dan class Selector pada file **style_eksternal.css** dan menambahkan kode seperti berikut :
```
/* ID Selector */
#intro {
background: #418fb1;
border: 1px solid #099249;
min-height: 100px;
padding: 10px;
}
#intro h1 {
text-align: left;
border: 0;
color: #fff;
}
/* Class Selector */
.button {
padding: 15px 20px;
background: #bebcbd;
color: #fff;
display: inline-block;
margin: 10px;
text-decoration: none;
}
.btn-primary {
background: #E42A42;
}
```
> - Maka hasilnya akan seperti berikut :

![Screenshot (19)](https://github.com/syifaaurellia/Lab2web/assets/115867244/4f52e1e5-db63-446e-a492-8629d712e52a)

> - CSS Selector terdiri atas selector ID, Selector Class, Dan Selector elemen Selector ID pendeklarasiannya yaitu dengan (#), Sedangkan Class pendeklarasiannya yaitu dengan (.), Dan Selector elemen pendeklarasiannya dengan elemen HTML sebagai contoh (p) yang akan di beri gaya pada CSS.

### 6. MeLakukan validasi dokumen css dengan mengakses https://jigsaw.w3.org/css-validator/

![Screenshot (24)](https://github.com/syifaaurellia/Lab2web/assets/115867244/b83d42a1-b3fd-4f97-bf22-e394ae012158)


![Screenshot (25)](https://github.com/syifaaurellia/Lab2web/assets/115867244/f878a92d-b2f3-40cb-81d9-bb682245c62b)

## Pertanyaan dan Tugas :

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
> Jawaban :

![Screenshot (27)](https://github.com/syifaaurellia/Lab2web/assets/115867244/486792ca-4b5d-4e17-87a3-5849bd9b9c37)

![Screenshot (28)](https://github.com/syifaaurellia/Lab2web/assets/115867244/46d0c284-b14d-4a57-9e60-3487102335e7)


> - Pada contoh ini, terdapat elemen `<h1> dengan class "title"` dan `elemen <p> dengan class "text"`. Class tersebut akan digunakan sebagai selector dalam CSS untuk mengubah properti dan nilai. Dalam file CSS (style.css), terdapat aturan CSS yang dideklarasikan untuk `class "title" dan "text"`. Aturan tersebut mengubah properti `"color"` pada elemen dengan class tersebut. Anda dapat mengubah nilai properti `"color"` pada file CSS sesuai keinginan Anda untuk melihat perubahan yang terjadi pada `judul (h1)` dan `paragraf (p)` dalam hal warna teks.


2. Apa perbedaan pendeklarasian CSS elemen `h1 {...}` dengan `#intro h1 {...}?` berikan penjelasannya!
> Jawaban :

- `h1 {...}` : Deklarasi ini akan merubah semua elemen "h1".

- `#intro h1 {...}` : Deklarasi ini lebih spesifik, maksud nya adalah pendeklarasian yang mengacu kepada pemberian atribut pada elemen "h1" dengan menambahkan id "intro".
