# Lab2Web
Pertanyaan dan Jawaban
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini. 
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya! 
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
 4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!  ( <p id="paragraf-1" class="text-paragraf">)
 Jawaban :
 2. Elemen <h1> ini kita buat supaya tulisannya rata tengah, maka kita beri property text-align dengan value center. Property dan value CSS dipisahkan dengan tanda titik dua (:). Kita dapat memberikan lebih dari satu property style dengan memisahkan antar property dengan tanda titik koma (;).  property dan value disimpan di dalam kurung kurawal { dan }.
3. yang akan ditampilkan pada browser yaitu Inline CSS karena inline css Sangat membantu ketika Anda hanya ingin menguji dan melihat perubahan pada satu elemen yaitu seperti pada browser. Contohnya :
contoh penempatan kode dari Inline CSS:
<h2 style="color:blue; font-family: arial;">Niagahoster</h2>
4. yang akan ditampilkan pada browser yaitu Class
Class merupakan selector yang dapat kita digunakan oleh lebih dari satu tag html. Artinya beberapa tag html bisa menggunakan css dari class tersebut.Tag class dengan nama yang sama dapat dipakai berulang-ulang pada satu halaman.Satu elemen boleh memiliki lebih dari satu Class yang berbeda-beda.
  Laporan Praktikum :
 Langkah pertama yaitu membuat file baru dengan menamakan lab2_css_dasar.html, kemudian setelah itu membuat struktur dari dokumen html dan langsung mengodingnya seperti di bawah ini, dan lihat di browser, refresh di browser dan lihat hasilnya.
![WEB CSS 1](https://user-images.githubusercontent.com/56400200/114251669-1767f880-99cc-11eb-96e6-087ac795ff3d.PNG)
![WEB CSS (1)](https://user-images.githubusercontent.com/56400200/114251971-3fa42700-99cd-11eb-8511-34bf11bef65a.PNG)
Langkah ke dua tambahkan deklarasi css internal seperti di lihat di bawah ini. dan lihat di browser lagi refresh dan lihat hasilnya.
![WEB CSS 2](https://user-images.githubusercontent.com/56400200/114252177-1e900600-99ce-11eb-918f-f286e5b4436d.PNG)
![WEB CSS (2)](https://user-images.githubusercontent.com/56400200/114252410-269c7580-99cf-11eb-97dc-9d9c60cfc736.PNG)
Langkah selanjutnya,yang ke 3 yaitu,tambahkan deklarasi inline css pada tag <p> dan lihat pada browser refresh kembali lihat hasil dan perubahannya. Dan tulisannya pun berubah minjadi white.
![WEB CSS 3](https://user-images.githubusercontent.com/56400200/114252461-91e64780-99cf-11eb-91bf-4113a1c6f67b.PNG)
![WEB CSS (3)](https://user-images.githubusercontent.com/56400200/114252631-73cd1700-99d0-11eb-902e-bb0d0aef876e.PNG)
Selanjutnya yang ke 4 membuat file baru terlebih dahulu dengan menamakan style_eksternal.css dan langsung mengodingnya seperti di bawah ini
![WEB CSS 4](https://user-images.githubusercontent.com/56400200/114252719-e807ba80-99d0-11eb-895e-382e2c387f22.PNG)
kemudian tambahkan <link> untuk menunjuk file css yang sudah dibuat pada bagian <head> dan kodingan ini tetap di tempatkan pada lab2_css_dasar.html kemudian lihat lagi di browser dan lihat hasil dan perubahannya.
![WEB CSS 4  ke 2](https://user-images.githubusercontent.com/56400200/114252744-14233b80-99d1-11eb-9bf7-ccd65f1b7bd5.PNG)
 ![WEB CSS (4)](https://user-images.githubusercontent.com/56400200/114252784-3ae17200-99d1-11eb-8c17-d2536ba6789d.PNG)
 Langkah ke 5 selanjutnya yaitu menambahkan css selector menggunakan ID dan class selectore pada file style_eksternal.css yang tadi sudah di buat, kemudian simpan dan lihat di browse,r refresh dan lihat hasilnya.
![WEB CSS 5](https://user-images.githubusercontent.com/56400200/114252828-74b27880-99d1-11eb-9f34-7f6df275066e.PNG)
 ![WEB CSS (5)](https://user-images.githubusercontent.com/56400200/114252885-c0fdb880-99d1-11eb-9240-11b585a96912.PNG)

