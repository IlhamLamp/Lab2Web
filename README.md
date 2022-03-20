# LAB2 Web

<table border="2" cellpading="10">
  <tr>
    <td><b>Nama</b></td>
    <td>Ilham Nur Utomo</td>
  </tr>
  <tr>
    <td><b>NIM</b></td>
    <td>312010129</td>
  </tr>
  <tr>
    <td><b>Kelas</b></td>
    <td>TI.20.A1</td>
  </tr>
  <tr>
    <td><b>MataKuliah</b></td>
    <td>Pemrograman Web</td>
  </tr>
</table>

# <b>Praktikum</b>

## <b>1. File HTML awal</b>
![img1](image/0_1-filehtml.PNG)

## <b>2. Deklarasi CSS internal</b>
![img2](image/0_2-style-pada-head.PNG)

## <b>3. Inline CSS</b>
![img3](image/0_3-style-inline.PNG)

## <b>4. External CSS</b>
![img4](image/0_4-eksternal-css.PNG)

## <b>5. Selector CSS</b>
![img6](image/0_5-selector-css.PNG)

## <b>Validasi dokumen CSS
![img7](image/0_6-css-validator.PNG)


# Latihan
<b>1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.</b><br>
  - Jawaban = 
  - Membuat file baru, ``mencoba.html`` dengan eksternal css ``mencoba_css``.

  - Kode awal,
![img8](image/1_1-file-baru.PNG)<br>  
  
  - Setelah perubahan,
![img9](image/1_2-setelah-perubahan.PNG)<br>

  - Mengubah warna ``nav`` menjadi merah pada file ``mencoba_css.css``, dengan mengganti nilai dari properti ``background``.
  - Menambahkan font khusus untuk <i>hyperlink</i> yang ada di ``nav a``, menjadi <b>IMPACT</b>, tidak berpengaruh pada tag lain.<br><br>

<b>2. Apa perbedaan pendeklarasian CSS elemen ``h1 {...}`` dengan ``#intro h1 {...}``? berikan penjelasannya!</b>
  - Jawaban =

  - Dengan ``#intro h1``,
![img10](image/2_1-intro-h1.PNG)<br>
  
  - Tanpa ``#intro h1``, hanya ``h1``,
![img11](image/2_2-h1.PNG)<br>

  - ``h1`` merupakan <i>element selector</i> yang umum pada tag html, namun karena selektor tersebut dibawah pengaruh ``id=intro``, 
![img12](image/2_3-h1.PNG) maka css eksternal kebingungan mencari ``h1`` yang dimaksud. Tampilah ``h1`` yang ada di internal css ``mencoba.html``. ![img13](image/2_4-h1.PNG)

  - ``#intro h1`` merupakan <i>id selector</i>, sehingga pemformatan ``h1`` akan mengikuti ``#intro``.<br><br>

<b>3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!</b>
  - Jawaban = Deklarasi terakhir,

  - Kode sebelum,
![img14](image/3_1-kode-sebelum.PNG)<br>

  - Kode sesudah,
![img15](image/3_2-kode-sesudah.PNG)<br>

  - <b>Internal CSS</b> membuat tag ``<p>`` berwarna hitam, ukuran huruf besar, serta teks rata kanan. Namun tidak tereksekusi, karena masih ada kode selanjutnya (yang mirip).
  - <b>Eksternal CSS</b> membuat tag ``<p>`` berwarna oranye, ukuran huruf sangat kecil, serta teks rata kanan-kiri. Namun tidak tereksekusi seluruhnya, hanya ukuran huruf.
  - <b>Inline CSS</b> membuat tag ``<p>`` berwarna biru pudar, ukuran huruf masih dari <b>eksternal css</b>, aserta teks rata tengah. Maka kode yang tampil adalah: Teks rata tengah, warna biru pudar, ukuran sangat kecil.
  - CSS mengambil kode program yang terakhir.
  - Internal kemudian > Eksternal kemudian > Inline CSS<br><br>


<b>4. Pada sebuah elemen HTML terdapat ID dan Class, apabila    asing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! (<p id="paragraf-1" class="text-paragraf">)</b>
  - Jawaban = ID
   
  - Kode sebelum,
![img16](image/4_1-kode-sebelum.PNG)<br>

  - Kode sesudah,
![img17](image/4_2-kode-sesudah.PNG)<br>
![img18](image/4_2_1-kode-sesudah.PNG)<br>

  - ``id`` unik, digunakan pada tempat tertentu.
  - ``class`` lebih umum, sering digunakan untuk beberapa elemen.
  - ``id`` akan lebih ditampilkan.