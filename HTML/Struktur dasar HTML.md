# Perkenalan HTML

## Teks program


```html
<!DOCTYPE html>

<html>

    <head>

        <title>ini adalah judul</title>

    </head>

    <body>

        <p>ini adalah paragraf yang akan di tampilkan</p>

        <p>pilihannya hanya 2 tempe dan tahu</p>

        <p>kesuksesan itu seperti banyak tempe</p>

        <p>tidak ada yang tahu</p>

    </body>

</html>
```

![alt text](https://github.com/FrlcSven/HTML-OBSIDIAN/blob/main/ASET%20HTML/p%20perkenalan.png?raw=true)
### Hasil
![alt text](https://github.com/FrlcSven/HTML-OBSIDIAN/blob/main/ASET%20HTML/h%20perkenalan.png?raw=true)

#### Penjelasan program
- tag <!DOCTYPE html> memberitahukan web browser bahwa dokumen HTML adalah versi 5
- tag pembuka `<html>`menandai awal sebuah dokumen HTML sampai dengan tag penutup `</html>`
- tag pembuka `<head>` berisi informasi tentang halaman html biasanya dalam tag penutup `</head>` , biasanya dalam tag head terdapat tag `<title>` untuk memberikan informasi judul halaman html
- apapun tag yang berada di antara tag pembuka `<body`> sampai dengan tag penutup `</body>` akan tampil di web browser


## program link instagram

```html
<!DOCTYPE html>

<html>

  <head>

    <title>ini adalah judul</title>

  </head>

  <body>

    <p>untuk login ke instagram klik link dibawah</p>

<a href="https://www.instagram.com"> klik instagram </a>

  </body>

</html>
```
![alt text](https://github.com/FrlcSven/HTML-OBSIDIAN/blob/main/ASET%20HTML/p%20insta.png?raw=true)

### Hasil
![alt text](https://github.com/FrlcSven/HTML-OBSIDIAN/blob/main/ASET%20HTML/h%20insta.png?raw=true)

# Anatomy elemen
Anatomi elemen HTML merujuk pada struktur dasar atau komponen-komponen yang membentuk suatu elemen dalam HTML. Anatomi ini mencakup beberapa elemen utama seperti tag pembuka, tag penutup, atribut tag, isi/konten tag, dan tag dasar.

Elemen adalah suatu kesatuan dari sebuah tag yang dimulai dari tag pembuka hingga ke tag penutup Elemen HTML secara garis besar terdiri atas tiga bagian yaitu tag pembuka konten/isi.

![alt text](https://github.com/FrlcSven/HTML-OBSIDIAN/blob/main/ASET%20HTML/p%20insta.png?raw=true)

![alt text](https://github.com/FrlcSven/HTML-OBSIDIAN/blob/main/ASET%20HTML/h%20insta.png?raw=true)



- tag `<a>` adalah elemen dasar untuk membuat link di HTML dan termasuk di tag pembuka
- `herf`= adalah nama atribut yang menghubungkan antara halaman web.
- `https://www.instagram.com` atribut yang digunakan untuk mengakses subuah link. Isi konten itu untuk masuk ke URL/link yang sudah kiita buat di atrbut href yaitu klik link.
Dalam HTML, tag pembuka dan penutup digunakan untuk menandai awal dan akhir dari suatu elemen dalam dokumen. Ini membantu browser memahami struktur dan tata letak konten. Berikut adalah penjelasan singkat:

- Tag Pembuka (`<tag>`)
Membuka elemen HTML dan menunjukkan awal dari suatu bagian dalam dokumen.
Contoh: `<p>` menandakan awal dari paragraf.

- Tag Penutup (`</tag>`)
Menandakan akhir dari suatu elemen HTML yang telah dibuka dengan tag pembuka.
Contoh: `</p>` menandakan akhir dari paragraf yang telah dibuka dengan `<p>`.

- Atribut Tag

Elemen dalam HTML dapat memiliki atribut atribut memberikan informasi tambahan tentang suatu elemen informasi ini bisa berupa instruksi untuk memberi warna dan teks, menggatur besar huruf dan teks. setiap atribut memiliki pasangan nama dan nilai (value), dan ditulis dengan nama"nilai", Value/nilai diapit dengan tanda kutip, boleh menggunakan tanda kutip satu ( ' ) atau dua ( " ).

Setiap tag memiliki atribut tertentu dan tidak sembarangan.sehingga kita perlu mempelajari tag beserta atribut yang tepat untuk digunakan pada tag tersebut.sebagai contoh, atribut href dapat digunakan pada tag `<a>` dan memiliki nilai aribut yang khusus yaitu berupa link halaman web yang diarahkan.

contoh atribut lain seperti width untuk mengatur lebar dan height untuk mengatur tinggi dari sebuah gambar yang digunakan paa tag `<img>`

- Konten/isi Tag

Objek yang dikenai perintah oleh tag, letaknya berada di antara tag pembuka dan tag penutup biasanya apa yang dituliskan diantara tag pembuka dan tag penutup akan ditampilkan pada halaman website dan mempresentasikan hasil dari penggunaan tag beserta atributnya.

Sebagai contoh, tag yang ada digambar akan menampilkan tulisan Klik Google yang dimana teks tersebut jika di klik akan mengarahkan kita ke nilai atribut href yaitu url google` (https://www.intagram.com)`. Perlu diketahui fungsi tag `<a>` atau "anchor" akan mengarahkan pengguna web menuju lik halaman web tertentu.

# Tag dasar
## tag 
Tag dasar dalam pemrograman web biasanya merujuk pada elemen-elemen HTML (Hypertext Markup Language) yang digunakan untuk membangun struktur dasar halaman web. Berikut adalah beberapa tag dasar beserta contohnya:

1. `<!DOCTYPE html>`
- Menentukan versi HTML yang digunakan dalam dokumen.
2. `<head>`
- Berisi informasi-informasi meta dan pengaturan dokumen, seperti judul (`<title>`), stylesheet, atau skrip.
3. `<title>`
- Menentukan judul dari halaman web yang akan ditampilkan pada tab browser
4. `<body>` dan Heading `<h1>, <h2>, ..., <h6>`
- Mengandung semua konten yang akan ditampilkan pada halaman web, seperti teks, gambar, tautan, dan elemen-elemen lainnya.
- Menandakan heading (judul) dengan tingkat kepentingan yang berbeda.
5. `<p>`
- Membuat paragraf teks
6. `<a>`
- Membuat tautan (link) ke halaman web atau sumber daya lainnya.





- Tag Pembuka (`<tag>`)  
    Membuka elemen HTML dan menunjukkan awal dari suatu bagian dalam dokumen.  
    Contoh: `<p>` menandakan awal dari paragraf.  
- Tag Penutup (`</tag>`)  
    Menandakan akhir dari suatu elemen HTML yang telah dibuka dengan tag pembuka.  
    Contoh: `</p>` menandakan akhir dari paragraf yang telah dibuka dengan `<p>`.

## Heading 
heading atau judul dalam HTML digunakan untuk menandai tingkatan kepentingan dari teks judul pada halaman web. HTML menyediakan enam tingkat heading, mulai dari `<h1>` (heading level 1) sebagai tingkat judul paling tinggi hingga `<h6>` sebagai tingkat judul paling rendah.

Contoh penggunaan heading dalam HTML:
1. `<h1>` Heading Level 1

- Digunakan untuk judul utama atau judul halaman

2. `<h2>` Heading Level 2

- Digunakan untuk judul subseksi atau subbagian.

3. `<h3>` heading Level 3

- Digunakan untuk judul subbagian yang lebih dalam

4. `<h4>` Heading Level 4
- Digunakan untuk judul yang lebih spesifik atau terkait dengan subbagian.

5. `<h5>` Heading Level 5
- Digunakan untuk judul yang lebih rinci atau terkait dengan judul tingkat kepentingan lebih tinggi.

6. `<h6>` Heading Level 6
- Digunakan untuk judul tingkat kepentingan terendah dalam sebuah dokumen.
```html
<!DOCTYPE html>

<html>

<head>

    <title> heading</title>

</head>

<body>

 <h1>Judul utama</h1>

 <h2>sub judul</h2>

 <h3>contoh 3</h3>

 <h4>contoh 4</h4>

 <h5>contoh 5</h5>

 <h6>contoh 6</h6>

 </body>

</html>
```




## Paragraf

1. `<p>` Paragraph:
- Digunakan untuk membuat paragraf teks.

2. `<b>` Bold:
- Menggunakan teks tebal.

3. `<u>` Underline:
- Menggunakan garis bawah pada teks.

4. `<i>` Italic:
- Menggunakan teks miring.

5. `<br>` Line Break:
- Digunakan untuk memasukkan pemisah baris (line break).

6. `<hr>` horizontal rule:
- Membuat garis horizontal untuk konten.
- Dengan menggunakan tag tersebut, Anda dapat mengatur tampilan dan struktur teks pada halaman web dengan berbagai gaya dan pemisahan visual.

```html
<!DOCTYPE html>

<html>

<head>

    <title> heading dan paragraf</title>

</head>

<body>

 <h1>Judul utama</h1>

 <h2>sub judul</h2>

 <h3>contoh 3</h3>

 <h4>contoh 4</h4>

 <h5>contoh 5</h5>

 <h6>contoh 6</h6>

  

 <a href="htpps://instagram.com"> klik go</a>

 <p> paragraf:digunakan untuk membuat paragraf</p>

 <b> bold: menggunakan teks tebal</b>

 <u>- unduerline: menggunakan garis bawah pada teks</u>

 <i>-italic: menggunakan teks miring</i>

 <br>- line break: digunakan untuk memasukkan pemisah baris (line break).</br>

 <hr>- horizontal rule: membuat garis horizontal untuk memisahkan konten</hr>

  
  

</body>

</html>
```

![alt text](https://github.com/FrlcSven/HTML-OBSIDIAN/blob/main/ASET%20HTML/program%20hlp.png?raw=true)

![alt text](https://github.com/FrlcSven/HTML-OBSIDIAN/blob/main/ASET%20HTML/hasil%20heading%20%2Clink%20dan%20paragraf.png?raw=true)


## atibut align
Atribut align digunakan untuk mengatur perataan teks pada balaman HTML Elemen `<p>` dapat menggunakan nilai atribut `align="left">`, akan menghasilkan paragraf dengan perataan teks di sebelah kiri Nilai atribut `align="right">` akan menghasilkan paragraf dengan perataan teks di sebelah kanan. Nilai atribut `align="center">`, akan menghasilkan paragraf dengan perataan teks di tengah. Dan nilai atribut `align="justify">`, akan menghasilkan paragraf dengan perataan teks pada sisi kiri dan sisi kanan


```html
<!DOCTYPE html>

<html>

    <head>

        <title> align </title>

    </head>

    <body>

        <h3>Belajar menggunakan elemen tag html p</h3>

  

<p align="left">

Remake adalah proses pembuatan ulang sebuah produk yang sudah ada dalam edisi sebelumnya, dengan tujuan membuatnya lebih baru dan sesuai dengan standar masa kini. Hal ini juga berlaku dalam dunia anime, di mana banyak anime yang telah tayang di masa lalu dan sangat populer pada zamannya.

</p>

  

<p align="right">

Remake anime bertujuan untuk meningkatkan kualitas, baik dari segi gambar, animasi, suara, maupun untuk menarik basis penggemar baru. Beberapa contoh remake yang cukup populer termasuk "Hunter x Hunter" pada tahun 2011 dan "Rurouni Kenshin" pada tahun 2023

</p>

  

<p align="center">

menjadi Hunter, kelas elit dengan izin untuk pergi kemanapun yang dia mau atau melakukan semua hal. Kini Gon berusia 12 tahun, dan dia ingin mengikuti jejak dari ayahnya menjadi seorang Hunter yang hebat. Saat Gon menghadapi tantangan yang tak terduga yang diberikan Ujian Hunter keapdanya, dia berteman dengan tiga kadindat lainnya yaitu Kurapika, Leorio, dan Killua.

</p>

  

<p align="justify">

Selanjutnya ada Hunter x Hunter yang dimana anime ini pertama kali tayang pada Oktober 1999, dan kemudian mendapatkan remake-nya oleh Madhouse yang tayang pertama kali pada Oktober 2011.

Konten ini telah tayang di Kompasiana.com dengan judul "4 Anime Remake Terbaik yang Wajib Ditonton, Ada Hunter x Hunter dan Rurouni Kenshin", Klik untuk baca:

Kompasiana adalah platform blog. Konten ini menjadi tanggung jawab bloger dan tidak mewakili pandangan redaksi Kompas.

Tulis opini Anda seputar isu terkini di Kompasiana.com

</p>

    </body>

</html>
```

### Hasil
![alt text](https://github.com/FrlcSven/HTML-OBSIDIAN/blob/main/ASET%20HTML/h%20align1.png?raw=true)

## Komentar
Html juga mempunyai tag khusus untuk komentar. Untuk membuat komentar di Html
Kita menggunakan awalan `"<!-- "` dan penutup `-->` .

<!-- ini komenta,tidak akantamlil di browser -->
Contoh Kode :
html
    <!-- Ini komentar, tidak akan tampil di browser -->
    
    <p>Ini bukan komentar, dan akan tampil di browser</p>

```html
<!DOCTYPE html>

<html>

    <head>

        <title> contoh komentar</title>

    </head>

    <body>

        <!-- ini komenta,tidak akantamlil di browser -->

    <!-- Ini komentar, tidak akan tampil di browser -->

    <p>Ini bukan komentar, dan akan tampil di browser</p>

    </body>

</html>
```

### Hasil
![alt text](https://github.com/FrlcSven/HTML-OBSIDIAN/blob/main/ASET%20HTML/h%20komentar.png?raw=true)


## List
List adalah fungsi dalam Html yang digunakan untuk menampilkan daftar dari sesuatu. Dalam HTML yang digunakan untuk menampilkan daftar dari sesuatu. Dalam Html tag list terdiri dari dua jenis ol ordered list (berurutan) dan ul unordered list (tidak berurutan) . Ordered list akan di tampilkan dengan angka atau huruf sedangkan unordered list dengan bulatan atau kotak ataupun simbol lainnya

>[!faq]- LIST
>untuk menampilkan list dalam HTML dapat menggunakan tag `<li>`.... `</li>` namun perlu penyesuaian dengan menyisipkan elemen `<ol>`... `</ol>` atau `<ul>`... `</ul>` ke dalam elemen `<li>` tersebut untuk membuat daftar isi

```html
<!DOCTYPE html>

<html>

    <head>

        <title>list</title>

    </head>

    <body>

        <h1>cara membuat kopi</h1>

        <p>Bahan bahan</p>

        <ul>

            <li>2sdt kop bubuk</li>

            <li>2sdt gula pasir</li>

            <li>air panas secukupnya</li>

        </ul>

        <p>langkah langkah</p>

        <ol>

            <li>masukkan kopi bubuk dan gula kedalam cangkir</li>

            <li>seduh dengan air panas mendidih</li>

            <li>asuk dan siap dihidangkan</li>

        </ol>

    </body>

</html>
```

![[p list.png]]

![[h list.png]]



## Link
Ling dapat ditemukan di hampir semua halaman web .Link/tautan memungkinkan sebuah teks yang ketika di-klik akan pindah ke halaman lainnya. HTML menggunakan tag `<a>` untuk keperluan ini.Link ini ditulis dengan `<a>` yang merupakan singakatan dari anchor (jangkar).

> [!Faq]- LINK
> Setiap tag `<a>` setidaknya memiliki sebuah atribut `<href>`.Dimana `<href>`berisi alamat yang dituju .`<href>` adalah singkatan dari hypertext reference

Atribut penting lainnya dari tag `<a>` adalah `target` . Atribut target menentukan tempat untuk membuka dokumen yang di tautkan Atribut `target` memiliki beberapa nilai salah satunya `_blank` yang berfungsi untuk membuka tautan di tab baru.

```html
<!DOCTYPE html>

<html>

    <head>

        <title>Link</title>

    </head>

    <body>

        <h3>Menggunakan tag anchor</h3>

        <p>ini adalah link menuju instagram</p>

        <a href="htpps://instagram.com"target="_blank"> klik disini untuk menuju instagam</a><br>

        <a href="file:///folder obsidian/ASET HTML/">klik disini untuk ke halaman lain yang saya buat </a>

    </body>

</html>
```

![[p anhor.png]]

![[h anchor.png]]



## Multimedia
### Gambar
Dalam html gambar didefinisikan dengan tag `<img>`adalah tag kosong hanya berisi atribut saja dan tidak memiliki penutup.

>[!Faq]- GAMBAR
>Atribut `<src>` setidaknya ada dalam tag ini untuk menentukan url (Alamat web) dari gambar yang ingin ditampilkan

Atribut alt menyediakan teks alternatif untuk gambar jika pengguna karena beberapa alasan tidak dapat melihat nya (karena koneksi lambat kesalahan pada atribut src, jika web browser telah di setting untuk di tampilkan gambar

Dalam tag`<img>` terdapat juga atribut width dan height untuk mengatur ukuran gambar pada versi HTML5 standar satuan ukuran gambar adalah `alt`

- misalnya dalam folder root terdapat file gambar bernama logo.png untuk menampilkan gambar tersebut kita hanya perlu mengisi nama gambar beserta jenis ekstensi file gambar ke dalam atribut `src` contoh` src="logo.png"`
- untuk menampilkan gambar dari internet carilah link gambar yang akan di tampilkan lalu memasukkan dalam atribut `src` contohnya https://namasitus.com/gambar.jpg

```html
<!DOCTYPE html>

<html>

    <head>

        <title>gambar web</title>

    </head>

    <body>

        <img src="rtrboys.jpg" width="300" height="300">

    </body>

</html>
```

![[p gambar.png]]

![[h gambar.png]]

Berikut adalah letak gambar yang dimuat website diatas :

![[web gambar.png]]
### Video
dalam HTML, video didefinisikan dengan tag `<video>`, tag `<video>` adalah tag yang digunakan untuk memasukkan video kedalam web, di tag `<video>` terdapat tag khusus yang dimana tag ini tidak memiliki tag penutup yaitu `<source>` yang Digunakan untuk menyediakan beberapa sumber video dan memberi browser pilihan format yang sesuai.

Dalam tag `<video>` terdapat juga atribut   `controls` yang digunakan untuk Menambahkan kontrol pemutaran standar seperti play, pause, dan volume, dan juga di tag `<video>` ada atribut `width` dan `height` yang digunakan untuk mengatur ukuran video, pada versi HTML 5 standar satuan ukuran video adalah pixel, dan juga di dalam nya juga terdapat atribut `type` yang di gunakan untuk menentukan tipe MIME (Multipurpose Internet Mail Extensions) dari file video yang disematkan.

misalnya dalam folder root terdapat file video bernama video.mp4. untuk menampilkan video tersebut kita hanya perlu mengisi nama video beserta jenis ekstensi file video didalam tag `<source>`dan didalamnya atribut `src` terus juga didalam tag `<source>` kita beri juga didalamnya atribut `type` untuk menetukan tipe MIME(Multipurpose Internet Mail Extensions) di file video yang di sematkan.

```html
<!DOCTYPE html>

<html>

    <head>

        <title>video</title>

    </head>

    <video src="ML.mp4" width="300" height="400 "controls></video>

</html>
```

![[p video.png]]


![[h video.png]]

Berikut adalah letak gambar yang dimuat website diatas :

![[web video.png]]

### Audio
Di HTML, tag `<audio>` digunakan untuk menyematkan dan memainkan file audio di halaman web. Tag ini memungkinkan pengembang web menyertakan file audio langsung di dalam dokumen HTML, memungkinkan pemutaran langsung di halaman tanpa perlu mengarahkan pengguna ke halaman terpisah atau menggunakan pemutar audio eksternal. di dalam tag `<audio>` juga memiliki atribut yaitu `src` ,  `controls` , `type` yang memiliki fungsi masing masing.

Seperti yang telah dibahas sebelumnya bahwasanya tag `<audio>` merupakan bagian fitur HTML5 untuk menampilkan audio asli di halaman web tanpa memerlukan Flash sebagaimana pada HTML versi 4. Yang penting untuk diatur pada tag ini adalah atribut src yang berfungsi untuk mengidentifikasi sumber media. Selain itu, terdapat pula atribut controls agar pengguna dapat memutar dan menjeda media.

```html
<!DOCTYPE html>

<html>

    <head>

        <title>audio</title>

    </head>

    <audio src="oke gas2.mp3" controls></audio>

</html>
```

![[p audio.png]]

![[h audio.png]]

Berikut adalah letak gambar yang dimuat website diatas :
![[web audio.png]]




### Iframe
Elemen `<iframe>` dapat digunaka untuk menampilkan halaman website lain dalam suatu website. akan menampilkan dokumen HTML lain dalam subuah website. mudahnya. bisa dibilang website dalam website.

>[!Faq]- IFRAME
>CONTOH penggunaannya seperti ini. jika kita mempunyai website sekolah, lalu di website tersebut ingin menampilkan alamat dalam google maps sekolah, agar memudahkan pengunjung website, kita bisa langsung tampilkan saja halaman sekolah yang ada di google maps.

Dalam tag `<frame>` ada beberapa Atribut yang penting seperti :

- `<src>`, untuk mencari sumber halaman HTML atau web yang akan ditampilkan di dalam frame
- `<width>` dan `<height>` untuk mengatur ukuran panjang dan lebar dari frame.

```html
<!DOCTYPE html>

<html>

    <head>

        <title>Iframe</title>

    </head>

    <body>

        <iframe src="https://an1.com/games/" style width="300" height="900"></iframe>

    </body>

</html>
```

![[p iframe.png]]

![[h iframe.png]]




## Tabel
Tabel dalam HTML didefinisikan dengan tag `<table>`.
- Setiap baris tabel ddidefinisikan dengan tag `<tr>`
- Header (judul) tabel didefinisikan dengan tag `<th>`.Secara default, header tabel memiliki teks tebal dan berada di tengah.
- Data tabel/sel didefinisikan dengan tag `<td>` .Karena sel merupakan bagian terkecil dari tabel maka dari itu tag ini selalu berada di dalam tag `<tr>` 

Contoh:

```html
<!DOCTYPE html>

<html>

<head>

    <title>Tabel</title>

</head>

<body>

    <table border="1">

        <tr>

            <th>Nama</th>

            <th>Hasil institusi</th>

        </tr>

        <tr>

            <td>Ibrahim mallombasang</td>

            <td>Universitas Negeri Makassar</td>

        </tr>

        <tr>

            <td>conrado alain sharon</td>

            <td>SMKN 7 Makassar</td>

        </tr>

    </table>

  

</body>

</html>
```

![[p tabel.png]]

![[h tabel .png]]

>[!Faq]- TABEL
> Perhatikan bahwa pada tag `<table>` terdapat sebuah atribut `border`. Atribut `border` digunakan untuk memberikan nilai garis tepi dari tabel. Nilai ini dalam ukuran pixel. `border="1"`, berarti kita mengistruksikan kepada web browser bahwa tabel tersebut akan memiliki garis tepi sebesar 1 pixel. Jika tidak ditambahkan, secara default tabel tidak memiliki garis tepi.

Selain itu, terdapat pula beberapa atribut tabel yang penting untuk diketahui yaitu:

- `rowspan` merupakan atribut HTML yang berfungsi untuk menggabungkan beberapa baris (ke bawah).

- `colspan` atau column span merupakan atribut HTML yang berfungsi untuk menggabungkan beberapa kolom (ke samping).

- `width` berfungsi untuk mengatur lebar tabel yang nilainya didefinisikan dalam satuan pixel secara default.

- `height` berfungsi untuk mengatur tinggi tabel yang nilainya didefinisikan dalam satuan pixel secara default.

- `align` berfungsi untuk mengatur perataan teks pada tabel. Nilai atribut yang dapat diberikan yaitu `left` untuk perataan teks ke kiri, `right` untuk perataan teks ke kanan, dan center untuk perataan teks ke tengah.

Contoh:

```html
<!DOCTYPE html>

<html>

    <head>

        <title>TABEL 1</title>

    </head>

    <body>

        <table border="1">

            <tr>

                 <th rowspan="2">Nama</th>

                 <th colspan="2">Asal Institusi</th>

            </tr>

            <tr>

                 <th width="100">Sekolah</th>

                 <th width="100">Kampus</th>

            </tr>

            <tr>

                 <td>Ibrahim Mallombasang</td>

                 <td>SMAN 14 Makassar</td>

                 <td>Universitas Negeri Makassar</td>

            </tr>

            <tr>

                 <td>Condrado Alain Sharon</td>

                 <td rowspan="2">SMKN 7 Makassar</td>

                 <td align="center" rowspan="2">-</td>

            </tr>

            <tr>

            <td>Rezky Awalya</td>

            </tr>

            <tr>

                 <td>Muzhawir Amri</td>

                 <td>SMAN 1 Palu</td>

                 <td>STMIK Dinanegara</td>

            </tr>

  

    </body>

</html>
```

![[p tabel1.png]]

![[h tabel1.png]]


>[!Faq]- TABEL
>Perhatikan pada konten elemen `<td>` yang berisi `<reskyawalya` hanya terdapat satu elemen `<td>` disana. Hal ini dikarenakan konten elemen `<td>` sebelumnya yaitu `SMKN7 Makassar` dan `-` pada data `Condrado alain sharon` mengandung atribut `rowspawn` dengan nilai `2` yang secara otomatis mengisi data dibawahnya yakni data `Resky Awalya`. Nilai `2` menunjukkan bahwa ada dua baris yang digabungkan menjadi satu.Konsep ini juga sama dengan apa yang terjadi pada `<th rospawn="2">Nama</th>` dan `<th colspan="2">Asal Institusi</th>`.

### Tabel Hari dan Bulan
#### Struktur
```
<!DOCTYPE html>

<html>

    <head>

        <title>tes 2</title>

    </head>

    <body>

        <p>Buatlah kode program untuk tabel dibawah ini</p>

        <table border="1">

            <tr>

                <td colspan="2" bgcolor="yellow"> Nama Hari</td>

                <td colspan="2" bgcolor="yellow">Nama Bulan</td>

            </tr>

            <tr>

                <td>senin</td>

                <td>selasa</td>

                <td>april</td>

                <td rowspan="2"> juni</td>

            </tr>

            <tr>

                <td>rabu</td>

                <td>kamis</td>

                <td>mei</td>

            </tr>

  

        </table>

    </body>

  

</html>
```

**Penjelasan Strukturnya:**

1. `<table border="1">`: Mendefinisikan sebuah tabel dengan atribut batas sebesar 1 (menggunakan garis tepi).
2.  `<tr>`: Membuat baris pertama dalam tabel.

   -  `<td colspan="2" bgcolor="yellow"> Nama Hari</td>`: Sel ini mencakup dua kolom, memiliki latar belakang kuning, dan berisi teks "Nama Hari".

   -  `<td colspan="2" bgcolor="yellow">Nama Bulan</td>`: Sel ini juga mencakup dua kolom, memiliki latar belakang kuning, dan berisi teks "Nama Bulan".

3. `<tr>`: Membuat baris kedua dalam tabel.

   - `<td>senin</td>`: Sel ini berisi teks "senin".

   - `<td>selasa</td>`: Sel ini berisi teks "selasa".

   - `<td>april</td>`: Sel ini berisi teks "april".

   - `<td rowspan="2"> juni</td>`: Sel ini berisi teks "juni" dan mencakup dua baris.

4. `<tr>`: Membuat baris ketiga dalam tabel.

   - `<td>rabu</td>`: Sel ini berisi teks "rabu".

   - `<td>kamis</td>`: Sel ini berisi teks "kamis".

   - `<td>mei</td>`: Sel ini berisi teks "mei".
#### Analisis 

Program di atas adalah representasi tabel menggunakan HTML. Berikut adalah analisis struktur HTML tersebut:

1. `<table border="1">`: Membuat elemen tabel dengan atribut border yang diberi nilai 1, menandakan adanya garis batas tabel.

2. `<tr>`: Membuat baris dalam tabel.

3. `<td colspan="2" bgcolor="yellow"> Nama Hari</td>`: Membuat sel dalam baris pertama dengan menggabungkan dua kolom (colspan="2") dan memberikan latar belakang warna kuning (bgcolor="yellow"). Isi sel adalah "Nama Hari".

4. `<td colspan="2" bgcolor="yellow">Nama Bulan</td>`: Membuat sel dalam baris pertama untuk Nama Bulan dengan properti yang serupa.

5. `<tr>`: Membuat baris kedua dalam tabel.

6. `<td>senin</td>`: Membuat sel untuk hari Senin dalam baris kedua.

7. `<td>selasa</td>`: Membuat sel untuk hari Selasa dalam baris kedua.

8. `<td>april</td>`: Membuat sel untuk bulan April dalam baris kedua.

9. `<td rowspan="2"> juni</td>`: Membuat sel untuk bulan Juni dalam baris kedua dan menggabungkan dua baris (rowspan="2").

10. Baris ketiga dan keempat mengandung sel untuk Rabu, Kamis, dan Mei.


#### Contoh
![[p tabel hari.png]]

#### Hasil
![[h tabel hari.png]]

#### Kesimpulan
1. Tabel terdiri dari dua baris (`<tr>`).
2.  Baris pertama berisi dua sel yang menggabungkan dua kolom masing-masing, dengan latar belakang warna kuning. Sel pertama berisi teks "Nama Hari", dan sel kedua berisi teks "Nama Bulan".
3. Baris kedua memiliki tiga sel untuk hari Senin, Selasa, dan April. Sel keempat di baris kedua menggabungkan dua baris di kolom tersebut dan berisi teks "Juni".
4. Baris ketiga memiliki sel untuk Rabu, Kamis, dan Mei.

Dengan menggunakan atribut `colspan` dan `rowspan`, program ini menciptakan tata letak tabel yang kompleks dan menarik dengan beberapa sel yang digabungkan.

### Tabel Nama
#### Struktur
```
<!DOCTYPE html>

<html>

    <head>

        <title> tes </title>

    </head>

    <body>

        <table border="1">

            <tr>

                <td height="10px">ibrahim mallombasang</td>

                <td>SMAN 14 MAKASSAR</td>

                <td>UNIVERSITAS NEGERI MAKASSAR</td>

            </tr>

            <tr>

                <td bgcolor="red"> conrado</td>

                <td rowspan="2" width="100PX"> SMKN7 MAKASSAR</td>

                <td rowspan="2" align="center">-</td>

            </tr>

            <tr>

                <td align="center">Reaky awalya</td>

            </tr>

        </table>

    </body>

</html>
```


**Penjelasan Strukturnya:**

1. `<table border="1">`: Mendefinisikan sebuah tabel dengan atribut batas sebesar 1 (menggunakan garis tepi).

2. `<tr>`: Membuat baris pertama dalam tabel.

   - `<td height="10px">ibrahim mallombasang</td>`: Sel ini memiliki tinggi sebesar 10 piksel dan berisi teks "ibrahim mallombasang".

   - `<td>SMAN 14 MAKASSAR</td>`: Sel ini berisi teks "SMAN 14 MAKASSAR".

   - `<td>UNIVERSITAS NEGERI MAKASSAR</td>`: Sel ini berisi teks "UNIVERSITAS NEGERI MAKASSAR".

3. `<tr>`: Membuat baris kedua dalam tabel.

   - `<td bgcolor="red"> conrado</td>`: Sel ini memiliki latar belakang merah dan berisi teks "conrado".

   - `<td rowspan="2" width="100PX"> SMKN7 MAKASSAR</td>`: Sel ini mencakup dua baris dan lebar sebesar 100 piksel, berisi teks "SMKN7 MAKASSAR".

   - `<td rowspan="2" align="center">-</td>`: Sel ini mencakup dua baris, berisi tanda minus ("-"), dan diatur rata tengah.

4. `<tr>`: Membuat baris ketiga dalam tabel (bagian kedua dari rowspan).

   - `<td align="center">Reaky awalya</td>`: Sel ini diatur rata tengah dan berisi teks "Reaky awalya".
#### Analisis
1. `<table border="1">`: Membuat elemen tabel dengan atribut border yang diberi nilai 1, menandakan adanya garis batas tabel.

2. `<tr>`: Membuat baris pertama dalam tabel.

3. `<td height="10px">ibrahim mallombasang</td>`: Membuat sel dalam baris pertama dengan tinggi 10 piksel (height="10px"), berisi teks "ibrahim mallombasang".

4. `<td>SMAN 14 MAKASSAR</td>`: Membuat sel kedua dalam baris pertama, berisi teks "SMAN 14 MAKASSAR".

5. `<td>UNIVERSITAS NEGERI MAKASSAR</td>`: Membuat sel ketiga dalam baris pertama, berisi teks "UNIVERSITAS NEGERI MAKASSAR".

6. `<tr>`: Membuat baris kedua dalam tabel.

7. `<td bgcolor="red"> conrado</td>`: Membuat sel pertama dalam baris kedua dengan latar belakang warna merah (bgcolor="red"), berisi teks "conrado".

8. `<td rowspan="2" width="100PX"> SMKN7 MAKASSAR</td>`: Membuat sel kedua dalam baris kedua yang menggabungkan dua baris (rowspan="2") dan memiliki lebar 100 piksel (width="100PX"), berisi teks "SMKN7 MAKASSAR".

9. `<td rowspan="2" align="center">-</td>`: Membuat sel ketiga dalam baris kedua yang juga menggabungkan dua baris (rowspan="2") dan memiliki teks "-" yang diatur di tengah (align="center").

10. `<td align="center">Reaky awalya</td>`: Membuat sel keempat dalam baris kedua dengan teks "Reaky awalya" yang diatur di tengah (align="center").

Program ini menciptakan tabel dengan dua baris dan tiga kolom, menggunakan atribut khusus untuk mengatur tata letak, warna, lebar, dan tinggi dari sel-sel dalam tabel.
#### Contoh
![[p nama,sklh.png]]

#### Hasil
![[h nama,sklh.png]]

#### Kesimpulan
1. Tabel terdiri dari dua baris (`<tr>`).
2. Baris pertama memiliki tiga sel, masing-masing dengan tinggi 10 piksel (`height="10px"`). Sel pertama berisi teks "ibrahim mallombasang", sel kedua berisi "SMAN 14 MAKASSAR", dan sel ketiga berisi "UNIVERSITAS NEGERI MAKASSAR".
3. Baris kedua memiliki empat sel. Sel pertama memiliki latar belakang warna merah (`bgcolor="red"`) dan berisi teks "conrado". Sel kedua menggabungkan dua baris (`rowspan="2"`) dengan lebar 100 piksel (`width="100PX"`) dan berisi "SMKN7 MAKASSAR". Sel ketiga juga menggabungkan dua baris dan berisi tanda strip ("-") yang diatur di tengah (`align="center"`). Sel keempat mengandung teks "Reaky awalya" yang diatur di tengah.
4. Program ini menciptakan tata letak tabel yang beragam dengan menggunakan beberapa atribut khusus untuk menyesuaikan penampilan sel-sel dalam tabel.

Keseluruhan, program tersebut menyajikan informasi dalam tabel dengan penataan visual yang menarik menggunakan fitur-fitur HTML tertentu.




## Form
elemen `<form> ` Html digunakan untuk mendefinisikan form yang digunakan untuk mengumpulkan imputan dari oengguna website. Tag ini digunakan untuk mengkoleksi inputan dari user ,konsep ini sama seperti formulir didunia nyata

 >[!Faq]- FORM
 > Dengan kata lain tag`<form>` mempresentasikan sebuah **"formulir"**  dimana satu formulir bisa memiliki banyak kolom isian

Form HTML berisikan elemen-elemen `<form>` lainnya. Elemen `<form>` digunakan untuk menampung macam macam elemen yang berkaitan dengan sebuah `<form>` , seperti `textfields`,`checkbox`,`radio button`,tombol `submit` ,dan banyak lagi yang dapat di edit kemudian ditulis untuk dikirim pada sebuah server untuk selanjutnya diproses guna mendapatkan informasi tertentu dari atau untuk user

Umumnya,sebuah website selalu memiliki fitur form,contoh paling umum yang sering kita temui adalah seperti form login,fprm sign up,form komentar di suatu blog/media

1. **Input**
Elemen `<input>` adalah elemen `form` yang paling penting. Elemen `<input>` dapat ditampilkan dalam beberapa cara, tergantung pada nilai atribut `type` yang digunakan. Berikut adalah beberapa contoh nilai dari atribut `type`:

- `text` digunakan untuk mengambil isian berupa **teks**. Contohnya seperti nama.

- `password` digunakan untuk mengambil isian berupa **kata sandi** atau sesuatu yang bersifat rahasia. Tipe ini akan mengubah semua karakter yang diketikkan ke dalam karakter bulat.

- `radio` digunakan sebagai kolom isian bertipe **pilihan** yang menawarkan beberapa opsi kepada user namun tetapi **hanya satu opsi** saja yang boleh dipilih. Contohnya seperti jenis kelamin atau agama.

>[!Faq]- FORM
> Perlu diperhatikan bahwa untuk penggunaan tipe`radio` yang berkategori set pilihan yang sama mengharuskan nilai`name` -nya juga sama.

Opsi default dapat dilakukan dengan menambahkan atribut `checked` pada elemen opsi yang dijadikan sebagai opsi default.
- `checkbox` digunakan untuk memberikan **daftar pilihan dalam satu set opsi**. User dapat memilih satu atau bahkan **lebih dari satu pilihan** pada tipe ini. Hal ini berbeda dengan tipe sebelumnya yaitu `radio` yang hanya memungkinkan user untuk memilih satu pilhan saja. Contoh penggunaan `checkbox` seperti daftar makanan kesukaan, daftar olahraga yang tidak disukai, dan yang semisalnya.

>[!Faq]- FORM
> Perlu diperhatikan bahwa untuk penggunaan tipe `checkbox` yang berkategori set pilihan yang sama mengharuskan nilai `name` -nya juga sama.

- `number` digunakan untuk membatasi isian user hanya pada karakter **numerik** saja. Browser akan menambahkan dua buah tombol atas dan bawah untuk mengubah angka isian.

Beberapa atribut untuk tipe `number`:

- `min` - menentukan angka minimal

- `max` - menentukan angka maksimal

- `step` - menentukan kelipatan (nilai yang tidak sesuai kelipatan tidak bisa di-input, dan default dari atribut ini adalah `1`)
- `date` digunakan untuk memberikan isian berupa **tanggal**. Atribut `min` dan `max` dapat pula difungsikan pada tipe ini untuk mengatur **tanggal** minimal dan tanggal maksimal yang diinginkan. Nilai `min` dan `max` tersebut ditulis dengan format: `YYYY-MM-dd`.

- `file` digunakan untuk memungkinkan pengguna memuat **file**. Atribut `accept` juga dapat disisipkan pada tipe ini dengan maksud untuk mengatur file apa saja yang boleh di-upload. Beberapa contoh value dari atribut `accept` yaitu:

- `accept="image/png,image/jpg, image/jpeg"` - untuk file gambar seperti `png`,`jpg`, atau `jpeg`.
- `accept-".pdf"` - untuk file pdf
- `accept=".doc, .docx"` untuk file `doc` atau `docx`
- `accept=".ppt, .pptx"` - untuk file `ppt` atau `pptx`

- `submit` ditampilkan dalam bentuk **tombol untuk mengirim data** pada `<form>` yang menjadi pembungkusnya. Atribut `value` digunakan untuk mengisi teks yang ingin ditampilkan pada tombol.

- `reset` berguna untuk **mengembalikan state (keadaan) atau data dari suatu form ke nilai awalnya**. Jika nilai awal sebuah input adalah kosong, maka ketika direset ia akan kembali kosong. Tapi jika nilai awalnya sudah terisi sesuatu, maka ketika direset datanya akan kembali seperti yang sudah diset sebelumnya.

- `button` berguna untuk membuat **inputan berupa sebuah tombol**. Tombol ini nantinya bisa difungsikan sesuai dengan keinginan dari pengembang web.

Untuk bacaan tentang materi ini yang dirasa cukup lengkap dan mudah dipahami, silahkan mengunjungi halaman berikut:

[[https://jagongoding.com/web/php/web-dinamis/membuat-dan-menangani-form/https://jagongoding.com/web/php/web-dinamis/membuat-dan-menangani-form/]]

2. **Label**
Elemen `<label>` memiliki fungsi khusus untuk **melabeli sebuah kolom inputan**. ketika screen reader membaca konten halaman HTML, Lalu menemukan sebuah inputan , ia akan membaca label tang bersangkutan.

Fungsi lain dari tag `<label>` adalah ketika kita mengklik label,maka browser akan meletakkan fokus pada kolom isian yang terhubung dengannya.Syarat yang perlu diperhatikan yaitu dengan menghubungkan sebuah `<label` dan `<input` dengan atribut `for` untuk `label` , dan atribut `id` pada `<input>` dengan nilai kedua atribut tersebut mesti sama persis.

3.  **Select**
Elemen `<select>` **berguna dalam mendefinisikan** sebuah tombol **dropdown** yang dimana user dapat memilih salah satu dari banyak pilihan.

>[!Faq]- FORM
>Elemen `<select>` nantinya berperan sebagai kontainer atau pembungkus dari elemen `<option>` yang berperan sebagai daftar pilihan atau opsi.


Elemen `<select>` hampir mirip fungsinya dengan `<input type="radio">` akan tetapi baiknya elemen `<select>` digunakan untuk memilih satu pilihan yang terdapat banyak opsi di dalamnya , sedangkan `<input type="radio">` lebih baiknya untuk digunakan jika user diarahkan memilih hanya satu pilihan yang opsi pilihannya tidak terlalu banyak.Contoh penggunaan elemen ini seperti memasukkan pilihan berupa asal daerah atau yang semisalnya.   

Penting untuk diketahui bahwasanya opsi yang aktif secara default adalah adalah opsi yang pertama. Akan tetapi, kita bisa mengatur opsi mana yang aktif secara default dengan menambahkan atribut `selected` pada suatu `<option>` yang ingin dijadikan sebagai opsi default.

4. Text Area
Elemen `<textarea>` berguna untuk mengambil inputan user berupa teks yang dapat memuat lebih dari satu baris. Jika dibandingkan dengan elemen `<input>` teks biasa, elemen `<textarea>` memiliki ukuran tinggi yang lebih besar. Element `textarea` bisa diisi lebih dari satu baris dengan menekan enter.

Atribut yang dapat digunakan untuk mengatur ukuran dari `textarea` yaitu `rows` untuk jumlah baris, sedangkan atribut `cols` untuk lebarnya.

5. Button
Elemen `<button>` yang berada di dalam sebuah `form` akan otomatis dianggap sama fungsinya seperti `<input type="submit">`. Jika ingin membuat tombol biasa yang tidak men-submit `<form>` dapat dilakukan dengan menambahkan atribut `type="button"`.

Contoh :

```html
<!DOCTYPE html>

<html>

    <head>

        <title>formulir</title>

    </head>

    <body>

        <h1>Formulir Pendaftaran</h1>

        <form action="">

            <div>

                <label for="nama-lengkap"><b>Nama Lengkap:</b></label><br>

                <input type="text" id="nama-lengkap" name="nama_lengkap" placeholder="Masukkan password">

  

            </div>

            <div>

                <label for="password"><b>Password:</b></label><br>

                <input type="password" id="password" name="password" placeholder="Masukkan passssword">

            </div>

            <div>

                <b>Jenis Kelamin: </b><br>

                <input id="lk" type="radio" name="jenis_kelamin" checked>

                <label for="lk">Laki-Laki</label>

                <input id="pr" type="radio" name="jenis_kelamin">

                <label for="pr">Perempuan</label>

            </div>

            <div>

                <label for="isian-usia"><b>Usia:</b></label><br>

                <input type="number" id="isian-usia" name="usia" min="17" max="25" value="19">

            </div>

            <div>

                <label for="tgl-ijazah:"><b>Tanggal ijazah:</b></label><br>

                <input type="date" id="tgl-ijazah" name="tgl-ijazah" min="2021-01-0\1" value="2">

            </div>

            <div>

                <label for="opsi-agama"><b>Agama:</b></label><br>

                <select id="opsi-agama" name="agama" required>

                <option disabled>---Pilih Agama----</option>

                <option value="islam">Islam</option>

                <option value="kristen">Kristen</option>

                <option value="katolik">Katolik</option>

                <option value="hindu">Hindu</option>

                <option value="buddha">Buddha</option>

                <option value="atheis" disabled>Atheis</option>

                </select>

            </div>

            <div>

  

                <label for="alamat"><b>Alamat:</b></label> <br>

                <textarea id="alamat" name="alamat" cols="25" rows="5" placeholder="Harap masukan alamat"></textarea>

            </div>

            <div>

                <b>Kemampuan Berbahasa Asing:*</b><br>

                <input type="checkbox" id="inggris" name="bahasa_asing">

                <label for="inggris">Inggris</label>

                <input type="checkbox" id="arab" name="bahasa_asing">

                <label for="arab">,Arab</label>

  

                <input type="checkbox" id="jepang" name="bahasa_asing">

                <label for="Jepang">Jepang</label>

            </div>

            <br>

            <input type="submit" value="Kirim">

            <input type="reset" value="Batal">

            <i>*opsional (tidak wajib diisi)</i>

        </form>

    </body>

</html>
```
![[p form 1.png]]

![[p form 2.png]]

![[p form 3.png]]

![[p form 4.png]]

![[h formulir.png]]


Beberapa atribut yang digunakan pada contoh di atas yang perlu untuk diperjelas yaitu sebagai berikut:

- `name`- digunakan sebagai nama variabel yang akan diproses oleh web server (contoh menggunakan PHP)

- `required` - digunakan untuk memastikan bahwa pengguna harus memasukkan nilai pada input tersebut sebelum dapat melakukan proses submit formulir

- `placeholder` - menuliskan teks pada elemen input. Placeholder sangat bermanfaat untuk memberikan teks bantuan kepada user untuk inputan form yang kompleks

- `value` - menentukan nilai awal dari sebuah elemen input

- `disabled` - digunakan untuk menonaktifkan inputan pada elemen yang diberi atribut ini

Bagaimana Cara Memproses Form?

Ketika sebuah `<form>` disubmit, baik menggunakan elemen `<button>` mau pun `<input type="submit"`, browser akan mengirimkan data tersebut kepada URL yang didefinisikan pada atribut `action` di dalam tag `form`.

Ada pun jika atribut `action` tidak didefinisikan, maka browser akan menggunakan URL sekarang sebagai tujuan pengiriman data.

Contoh :

**<form** action**=** "/proses-pendaftaran"**>**
  ...
`</form>`


Pada contoh di atas, ketika form di-*submit*, **browser** akan mengirimkan data yang ada  menuju URL /proses-pendaftaran.

*Apa yang terjadi pada URL /`proses-pendaftaran?`*

Pada URL tersebut terdapat sebuah aplikasi/program yang berjalan di server (bukan di **browser**). Tugas dari program tersebut adalah mengelola data yang dikirim seperti misalnya menyimpan data tersebut ke dalam sebuah database.

Bahasa yang umum digunakan di dalam server adalah python, nodejs, PHP, dan lain sebagainya.

Untuk mendapatkan gambaran lebih jelas, sebenarnya akan dijelaskan pada modul selanjutnya yang berkaitan dengan materi PHP atau juga bisa dengan membaca tutorial berikut:

https://jagongoding.com/web/php/web-dinamis/membuat-dan-menangani-form/https://jagongoding.com/web/php/web-dinamis/membuat-dan-menangani-form/

## DIV & SPAN
### DIV
- `<div>` (division) adalah sebuah blok pembungkus yang digunakan untuk mengelompokkan elemen-elemen HTML menjadi satu unit. Biasanya digunakan untuk membuat bagian-bagian dari halaman web yang bisa diatur tata letaknya, seperti header, footer, sidebar, dan sebagainya. `<div>` memiliki sifat blok, yang berarti akan menempati seluruh lebar yang tersedia secara default.

Contoh

```html
  <div>
    <p>Ini adalah sebuah div.</p>
    <p>Ini adalah bagian dalam dari div.</p>
  </div>
```
  

### SPAN
`<span>` adalah elemen yang digunakan untuk menerapkan gaya atau menentukan bagian teks tertentu tanpa mempengaruhi tata letak secara keseluruhan. Biasanya digunakan untuk menyorot atau menerapkan gaya pada teks atau elemen kecil lainnya di dalam sebuah kalimat.

Contoh

```html
<p>Ini adalah <span style="color: red;">teks yang diberi warna merah</span> menggunakan elemen span.</p>
```
