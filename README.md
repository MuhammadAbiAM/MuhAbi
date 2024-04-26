# TUTORIAL HTML, CSS, JAVASCRIPT - W3SCHOOL & PRAKTIKUM PEMROGRAMAN WEB1

# TUTORIAL HTML, CSS, JAVASCRIPT - W3SCHOOL

## Overview
README ini memberikan pengenalan tentang tutorial HTML, CSS, dan JavaScript yang ditawarkan oleh W3Schools. Tutorial ini membantu mempelajari dan menguasai HTML, CSS, dan JavaScript, bahasa markup standar untuk membuat halaman web.

[![N|Solid](https://w3schoolsua.github.io/images/img_w3slogo.gif)](https://www.w3schools.com/)

## Content
- Introduction
- Try It Your Self
- Example
- Exercise
- Quiz
- Reference

## Introduction
- HTML (Hypertext Markup Language) adalah bahasa markup standar yang digunakan untuk membuat halaman web. Dengan HTML, kita dapat membangun struktur dasar halaman web dan menentukan bagaimana konten akan ditampilkan di browser. Dengan HTML, kita dapat membuat elemen seperti teks, gambar, tautan, tabel, formulir, dan lain-lain. Contoh: `<h1>Ini adalah Judul</h1> <p>Ini adalah paragraf.</p>`

- CSS (Cascading Style Sheets) adalah bahasa yang digunakan untuk mengatur tampilan dan format halaman web. Dengan CSS, kita dapat mengontrol layout (tata letak), warna, font, garis, latar belakang, animasi, dan lain-lain. CSS memisahkan presentasi dari struktur HTML. Contoh: `h1 { color: blue; font-size: 24px; }`

- JavaScript adalah bahasa pemrograman yang digunakan untuk menambahkan interaktivitas dan fungsionalitas pada halaman web. Dengan JavaScript, kita dapat membuat efek animasi, validasi formulir, mengambil data dari server, dan lain-lain. JavaScript berfungsi bersama dengan HTML dan CSS untuk menciptakan pengalaman web yang lebih dinamis. Contoh: `document.getElementById("myButton").addEventListener("click", function() { alert("Tombol diklik!"); });`

## Try It Your Self

- HTML
  
Gunakan editor interaktif "Try It Your Self" untuk mempelajari lebih lanjut tentang HTML.
![html1](https://github.com/MuhammadAbiAM/praktikum-web1/assets/168069395/030aa091-fab3-4b47-a869-2c5c7b7e736e)

Ubah kode HTML untuk melihat perubahannya secara langsung. Contoh sederhananya sebagai berikut:
![html2](https://github.com/MuhammadAbiAM/praktikum-web1/assets/168069395/b84565e5-b7bb-4e46-8f09-d716ceda8102?raw=true)

- CSS
  
Gunakan editor interaktif "Try It Your Self" untuk mempelajari lebih lanjut tentang CSS.
![css1](https://github.com/MuhammadAbiAM/praktikum-web1/assets/168069395/7733889d-c166-4c2c-bd90-f76bdc4c5205)

Ubah kode CSS untuk melihat perubahannya secara langsung. Contoh sederhananya sebagai berikut:
![css2](https://github.com/MuhammadAbiAM/praktikum-web1/assets/168069395/700e2d5b-e047-4c0b-8583-b5350fdfb38c)

- JavaScript

Gunakan editor interaktif "Try It Your Self" untuk mempelajari lebih lanjut tentang JavaScript.
![js1](https://github.com/MuhammadAbiAM/praktikum-web1/assets/168069395/91f7aedc-cca0-4382-be83-f3ebeaa0ea46)

Ubah kode JavaScript untuk melihat perubahannya secara langsung. Contoh sederhananya sebagai berikut:
![js2](https://github.com/MuhammadAbiAM/praktikum-web1/assets/168069395/9958cfd3-32c4-43e5-9bc8-cb8876202597)

Apabila tombol di klik, outputnya menjadi seperti berikut:
![js3](https://github.com/MuhammadAbiAM/praktikum-web1/assets/168069395/b6f6d49b-278c-4435-aeac-da1f83158478)

# Example

Di dalam tutorial W3School akan menemukan lebih dari 200 contoh. Setiap contoh dilengkapi dengan editor interaktif, sehingga dapat mengedit dan menguji kode sendiri. Untuk mempelajari tutorial dan melihat banyak contoh, lihat di bagian [HTML](https://www.w3schools.com/html/default.asp), [CSS](https://www.w3schools.com/css/default.asp), dan [JavaScript](https://www.w3schools.com/js/default.asp).

#  Exercise

Uji kemampuan dan tingkatkan pemahaman dengan mengerjakan soal latihan yang ada di W3School. Ada hampir seratus soal latihan yang disediakan di W3Scool untuk melatih kemampuan HTML, CSS, JavaScript. Contoh latihannya adalah sebagai berikut:

![exercise](https://github.com/MuhammadAbiAM/praktikum-web1/assets/168069395/23404f7f-9418-46d2-b25d-5777caf5717a)

# Quiz

Untuk menguji pengetahuan HTML, ikuti [Kuis HTML](https://www.w3schools.com/quiztest/quiztest.asp?qtest=HTML), serta uji kemampuan pengetahuan CSS, ikuti [Kuis CSS](https://www.w3schools.com/quiztest/quiztest.asp?qtest=CSS), dan Uji kemampuan pengetahuan JavaScript, ikuti [Kuis JavaScript](https://www.w3schools.com/quiztest/quiztest.asp?qtest=JS).

![html](https://github.com/MuhammadAbiAM/praktikum-web1/assets/168069395/33145b36-05b3-4b77-90ad-cb2bf4b21958)

# Reference

Untuk referensi lengkap tentang elements, attributes, events, color names, entities, character sets, URL encoding, language codes, HTTP messages, browser support, dan lain-lain, kunjungi bagian [Referensi](https://www.w3schools.com/).

[![N|Solid](https://w3schoolsua.github.io/images/img_w3slogo.gif)](https://www.w3schools.com/)


# PRAKTIKUM PEMROGRAMAN WEB1

## Challenge JavaScript
Program ini merupakan aplikasi web sederhana yang menunjukkan operasi aritmatika dan pengubahan gambar dengan menggunakan :
- HTML
- CSS
- JavaScript

## Fitur
- Melakukan operasi aritmatika (penjumlahan dan pengurangan) pada tiga variabel (A, B, dan C) dan menampilkan hasil secara dinamis di halaman web.
- Pengguna dapat memasukkan nilai baru untuk variabel A, B, dan C dengan tombol Ubah Nilai.
- Setelah mengubah nilai dengan tombol "Ubah Nilai", program menghitung kembali hasilnya dan memicu perubahan pada gambar yang ditampilkan.

## HTML (index.html)
Di dalam tag dengan class container berisikan Heading, tabel, gambar dan tombol

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div class="container">
        <h1> JavaScript Arithmetic</h1>
        <table cellpadding="10">
            <tr>
                <th>Variabel</th>
                <th>Nilai</th>
                <th rowspan="5"><img id="gambar" 
                    src="https://www.techfor.id/wp-content/uploads/2019/12/html.png" alt=""></th>
            </tr>
            <tr>
                <td>a</td>
                <td id="satu">5</td>
            </tr>
            <tr>
                <td>b</td>
                <td id="dua">2</td>
            </tr>
            <tr>
                <td>c</td>
                <td id="tiga">1</td>
            </tr>
            <tr>
                <td >Hasil</td>
                <td id="hasil"></td>
            </tr>
        </table>
        <button id="tombol">Ubah nilai</button>
    </div>
</body>
</html>
```

Berikut tampilan output HTML jika belum ditambahkan CSS dan JavaScript:
![html](https://github.com/MuhammadAbiAM/praktikum-web1/assets/168069395/c1c886f8-f513-42e1-8939-8b022b11e4bb)

## CSS (Style.css)

Di dalam file style.css terdapat styling yang didefinisikan untuk membuat tampilan tabel dan elemen-elemen HTML lainnya. Bisa juga ditambahkan di dalam `<style></style>` di index.html.
```css
 table, tr, th, td {
            border: solid 1px grey;
            border-collapse: collapse;
        } 

        th, td { 
            padding: 10px;
        }

        .container {
            font-family: Arial, Helvetica, sans-serif;
            align-items: center;
            justify-content: center;
            display: flex;
            flex-direction: column;
        }

        tr:nth-child(even),
        tr:first-child {
            background-color: rgba(128, 128, 128, 0.329);
        }

        tr:hover {
            background-color: rgba(128, 128, 128, 0.8);
        }

        button {
            margin-top: 30px;        
        }

        img {
            width: 200px;
            height: 150px;
        }
```

Berikut tampilan Output setelah melakukan styling pada index.html di style.css:
![css](https://github.com/MuhammadAbiAM/praktikum-web1/assets/168069395/12372fcb-59fb-43b1-927f-ee433e1367f2)

## JavaScript (Script.js)
Terdapat onmouseover dan onmouseleave yang memanggil fungsi *tampilHasil()* dan *tampilKosong()* saat pengguna mengarahkan kursor ke baris hasil atau mengarahkan kursor keluar dari baris hasil.

```javascript
let hasil= document.getElementById('hasil');
hasil.addEventListener('mouseover', tampil);
hasil.addEventListener('mouseout', hilang);

let tombol = document.getElementById('tombol');
tombol.addEventListener('click', ubahNilai);
```

Fungsi ini memiliki parameter (a, b, c) yang akan mengembalikan hasil dari operasi aritmatika (a + b - c).

```javascript
function hitung (a, b, c) {
    return a + b - c;
}
```

Fungsi ini digunakan untuk menampilkan hasil perhitungan aritmatika pada tabel ketika pengguna mengarahkan kursor ke baris hasil.

```javascript
function tampil() {
    let a = parseInt(document.getElementById('satu').innerHTML);
    let b = parseInt(document.getElementById('dua').innerHTML);
    let c = parseInt(document.getElementById('tiga').innerHTML);
    document.getElementById('hasil').innerHTML = hitung(a, b, c);
}
```

Fungsi ini digunakan untuk menghapus hasil perhitungan dari tabel ketika pengguna mengarahkan kursor keluar dari baris hasil.

```javascript
function hilang() {
    document.getElementById('hasil').innerHTML = " ";
}
```

Fungsi ini dipanggil saat tombol "Ubah Nilai" ditekan yang kemudian menampilkan popup prompt untuk menambahkan nilai a, b, dan c, lalu memperbarui tabel dengan nilai-nilai yang dimasukkan. Setelah nilai terkahir dimasukan gambar yang ditampilkan akan berubah.

```javascript
function ubahNilai() {
    let perintah1 = prompt("Tambahkan nilai 'A'");
    document.getElementById('satu').innerHTML = perintah1;
    
    let perintah2 = prompt("Tambahkan nilai 'B'");
    document.getElementById('dua').innerHTML = perintah2;

    let perintah3 = prompt("Tambahkan nilai 'C'");
    document.getElementById('tiga').innerHTML = perintah3;

    document.getElementById('gambar').src = 
    "https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/1200px-Unofficial_JavaScript_logo_2.svg.png";
}
```

Berikut tampilan output setelah ditambahkan javascript:

![1](https://github.com/MuhammadAbiAM/praktikum-web1/assets/168069395/65966c77-dd3b-4bd7-a8b3-3b62162087a0)

![2](https://github.com/MuhammadAbiAM/praktikum-web1/assets/168069395/830209cb-2e89-41c8-b087-b00fea0fb4f6)

![3](https://github.com/MuhammadAbiAM/praktikum-web1/assets/168069395/0a038661-6324-4e35-a373-a15c6e42d200)
