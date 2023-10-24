Laporan Tugas Pemrograman Web SRS 

             Disusun oleh:

                 1.Muhammad Avie Siena (22091397103)
                 2.Muhammad Faaizul Hakim  (22091397075)
                 3.Mochamad Satria Cahya Nugraha (22091397110)

        Program Studi D4 Menejemen Informatika 
       Fakultas Vokasi Universitas Negeri Surabaya 
                         2023


        1. Tujuan
        
  Tujuan website Thrifting Sepatu adalah untuk menjelaskan cakupan dari produk yang dijelaskan dalam dokumen SRS, fungsi utama, karakteristik pengguna, lingkungan operasional, kendala desain dan implementasi, dokumentasi pengguna. Dengan tujuan ini, pembaca dokumen akan memahami produk yang akan dikembangkan dan batasan serta kondisi yang harus dipertimbangkan dalam mengembangkan website tersebut.


        3. Lampiran

           a. Flowchart
              
![image](https://github.com/22091397103-MohammadAvieSienaMIC22/PEMWEB-07/assets/144098631/47ca8aba-2b84-4825-90e5-988dab373cb5)


![image](https://github.com/22091397103-MohammadAvieSienaMIC22/PEMWEB-07/assets/144098631/a82f80b2-5092-4d3e-91eb-8bd23a558df9)


           b.UseCase 

![image](https://github.com/22091397103-MohammadAvieSienaMIC22/PEMWEB-07/assets/144098631/b330d528-2e55-4fa6-a2ba-76f9dcc7749a)



       4. Penjelasan Code

          a. HTML
![Alt text](image.png)

1. <!DOCTYPE html>: Mendeklarasikan dokumen sebagai HTML5. Ini memberi tahu browser jenis dokumen yang dihadapi dan bagaimana menafsirkannya.

2. <html lang="id">: Tag pembuka untuk dokumen HTML. Atribut lang="id" menunjukkan bahwa konten di halaman ini dalam bahasa Indonesia.
  
3. <head>: Bagian kepala dari halaman web. Berisi meta-informasi tentang dokumen dan tautan ke stylesheet, skrip, dan sumber daya lainnya.
  
4. <meta name="viewport" content="width=device-width, initial-scale=1.0">: Menyediakan instruksi untuk browser tentang bagaimana mengontrol dimensi halaman dan penskalaan. Ini penting untuk responsivitas situs web di perangkat mobile.

5. cmeta charset="utf-8">: Sepertinya ada kesalahan pengetikan di sini. Seharusnya <meta charset="utf-8">, yang mendeklarasikan pengkodean karakter halaman sebagai UTF-8, standar untuk pengkodean multibahasa.

5. <title>#TEFNARF</title>: Judul halaman yang akan muncul di tab browser.

6. <link rel="stylesheet" href-"globals.css" />: Ada kesalahan sintaks. Atribut href harus menggunakan = bukan -. Ini adalah tautan ke file stylesheet eksternal yang bernama "globals.css".

7. <link rel="stylesheet" href="cart.css" />: Tautan ke file stylesheet lain yang bernama "cart.css".

8. </head>: Penutup tag kepala.

9. <body>: Tag pembuka untuk isi utama dari halaman web.
  10. <nav>: Tag pembuka untuk navigasi halaman.
  11. di class="logo"><a href="index.ht index.html" class="page-scroll">TRIE MARE</a></LI>: Ada beberapa kesalahan di sini. Sepertinya seharusnya <li class="logo"> dengan tautan ke "index.html". Ini adalah item daftar yang berfungsi sebagai logo dan tautan ke halaman utama.
  12. cl class-"menu">: Sepertinya seharusnya <ul class="menu">. Ini mengindikasikan awal dari daftar yang berfungsi sebagai menu navigasi.
  13.Anda memiliki item daftar (<li>) yang berisi tautan atau input.
  14. <11> dan </li>: Ada kesalahan sintaks dan tag yang tidak dikenali. Sepertinya ini seharusnya <li>.
  15. <li><button class="buttoncart" onclick="window.location.href='cart.html"></li>: Item daftar yang berisi tombol untuk mengarahkan pengguna ke halaman "cart.html".
  16. <li><button class="buttonlogin" onclick="window.location.href="login.html""></li>: Item daftar yang berisi tombol untuk mengarahkan pengguna ke halaman "login.html", tetapi ada kesalahan dalam atribut onclick.
  17. </ul>: Penutup tag untuk daftar menu.

<img width="290" alt="image" src="https://github.com/22091397103-MohammadAvieSienaMIC22/PEMWEB-07/assets/144098631/64554730-e026-4b1a-9542-5415f9d536f0">

19. </nav>: Penutup dari elemen navigasi, mengindikasikan akhir dari bagian navigasi halaman.
20. csection id="cart" class="yourcart">: Ini tampaknya kesalahan ketik. Seharusnya <section id="cart" class="yourcart">. Ini merupakan pembuka dari elemen section dengan ID "cart" dan class "yourcart".
21. <h1>Your cart</h1>: Judul bagian yang menunjukkan bahwa bagian ini berkaitan dengan keranjang belanja pengguna.
22. Setelahnya, ada beberapa <div> yang terstruktur dengan cara yang tidak benar dan beberapa kesalahan sintaks lainnya. Struktur dan tag <div> harus diperbaiki agar memiliki pembuka dan penutup yang sesuai.
23. Di dalam <div class="frane_order">, Anda memiliki rincian pesanan seperti Subtotal, Diskon, Biaya Pengiriman, dan Total. Ada beberapa kesalahan ketik dalam elemen (misalnya, <h1>Discount:</h harusnya <h1>Discount:</h1>).
23. Bagian input untuk kode promo (<input class="search promo" type="text" name "query" placeholder="Add promo code!">) memiliki kesalahan pada atribut name, seharusnya name="query".
24. <button: href="#">Apply</button>: Kesalahan ketik yang jelas. Seharusnya <button href="#">Apply</button> atau hanya <button>Apply</button> jika tidak ada tautan yang perlu diterapkan pada tombol.
25. Ada beberapa kesalahan dengan tag penutup </div>. Pastikan setiap pembuka <div> memiliki penutup yang sesuai.
26. csection class="contact">: Kesalahan ketik, seharusnya <section class="contact">.
27. Di dalam bagian "contact", ada formulir untuk mendaftar newsletter. Ada kesalahan dalam atribut <h1> (</N1>>
    harusnya </h1>) dan beberapa tag lainnya.
29. <footer> muncul dua kali, namun tidak ada konten di antaranya. Hanya satu elemen <footer> yang diperlukan.
30. </body> dan </html>: Penutup dari seluruh halaman web.

 ![image](https://github.com/22091397103-MohammadAvieSienaMIC22/PEMWEB-07/assets/144098631/864c36c3-e5cc-43b4-a3fa-08f81e4e45c6)

 31.	<section>: Ini memulai sebuah bagian baru di halaman. Di HTML5, <section> digunakan untuk mendefinisikan konten yang terkait dalam halaman.
32.	<div class="framelogin">: Sebuah div dengan class "framelogin" yang kemungkinan digunakan untuk styling atau JavaScript.
33.	<div class="textlogin">: div lain yang mungkin mendefinisikan area teks untuk login.
34.	(nI>Login</h1>: Ini salah. Seharusnya <h1>Login</h1> yang merupakan header dengan teks "Login".
35.	Kdivs crossorigin="anonymous"): Ini tidak masuk akal dalam konteks HTML dan sepertinya merupakan kesalahan ketik.
36.	<form class="form_login">: Ini memulai form login, tempat pengguna akan memasukkan detailnya untuk login.
37.	dIv cIass="Iabelemail dan sebagainya: Ini adalah kesalahan ketik dan seharusnya merupakan elemen <div> dengan class tertentu.
38.	crossorigin="anonymous": Atribut ini biasanya digunakan dengan elemen <script> untuk mengontrol request lintas asal. Di sini, penggunaannya keliru.
39.	name="password" Céauired n Laceho Ider=-basswort: Ini sepertinya merupakan kesalahan ketik dan mungkin seharusnya adalah atribut dari sebuah elemen input, seperti required dan placeholder.
40.	s/i/a hrat- x (1 class= Tab Ta-google icon"></i></ay: Ini lagi-lagi tampaknya adalah kesalahan ketik.
41.	</ul></div>: Penutup dari list yang sepertinya mengandung tautan ke media sosial. Namun, strukturnya keliru dan perlu diperbaiki.
42.	</section>: Penutup dari elemen <section>.
43.	</dius: Sepertinya kesalahan ketik dan mungkin seharusnya </div>.
44.	<footer>: Ini memulai footer halaman, tempat Anda bisa menempatkan informasi hak cipta, tautan tambahan, dan lainnya.
45.	<p>&copy; 2023 TRIEFWARE. All rights reserved.</p>: Paragraf yang mengandung informasi hak cipta untuk TRIEFWARE.
46.	</footer>, </body>, dan </html>: Penutup dari elemen footer, body, dan html.

![image](https://github.com/22091397103-MohammadAvieSienaMIC22/PEMWEB-07/assets/144098631/dd11716b-5f47-4f67-ae46-3b17f0efbf84)

47.	 <div class="filter_Image">: Ini memulai div dengan class "filter_Image", yang kemungkinan besar digunakan untuk mengelompokkan beberapa elemen yang berkaitan dengan filter gambar.
48.	ALY class="frame filter: Ini tampaknya kesalahan. Mungkin seharusnya dimulai dengan tag (misalnya <div>) dengan beberapa class yang ditentukan.
49.	dag src="./ing/Filter.png" alt="Sep" height="3: Sepertinya ini adalah bagian dari elemen gambar (<img>), tetapi terpotong dan memiliki kesalahan ketik.
50.	my class flexfilters1: Kesalahan lain. Ini mungkin harus menjadi tag pembuka dari suatu elemen (misalnya <div>) dengan class "flexfilters1".
51.	<h1>al</: Ini tampaknya awal dari elemen header (<h1>) yang terpotong.
52.	ing area"./img/pamahtiiter,.png" width="20px" height="20px" altants: Ini adalah upaya lain untuk menambahkan elemen gambar tetapi dengan banyak kesalahan ketik.
53.	sty class flexfilters", mg src="./img/pantilter.png" width="200" height=, iv clasflextilters": Semua baris ini tampaknya bagian dari elemen yang terpotong dan memiliki kesalahan ketik.
54.	"Flexfrancolor" dt class flexcolor2: Sepertinya ini adalah atribut dari elemen lain yang terputus.
55.	Potongan kode dengan ting, sing, dan xing: Semua potongan ini tampaknya bagian dari elemen gambar yang terputus.
56.	<div class="garisatas3"></div>: Ini div dengan class "garisatas3" mungkin digunakan untuk menambahkan garis atau pemisah.
57.	raiv class="flexsize": Kesalahan ketik lain. Mungkin seharusnya <div class="flexsize">`.
58.	Beberapa elemen dengan a class="buttons", <div class="buttons", dan lainnya: Potongan-potongan kode ini tampaknya bagian dari elemen-elemen yang digunakan untuk menampilkan tombol atau elemen interaktif lainnya, tetapi banyak dari mereka terputus atau memiliki kesalahan ketik.
59.	x clms buttonsze, el class="button", dan sejenisnya: Ini adalah potongan-potongan kode yang tampaknya rusak dan tidak lengkap. Mereka sepertinya adalah bagian dari elemen <div>, tetapi penulisan dan strukturnya salah.
60.	<button href="#">38-Large</button: Ini tampaknya sebuah tombol, tetapi tag <button> tidak menggunakan atribut href. Selain itu, tag penutupnya tidak lengkap.
61.	<div class="box">: Ini adalah div dengan class "box" yang mungkin digunakan untuk mengelompokkan elemen-elemen tertentu.
62.	<img src="./img/produk 1.1.png" alt="259px" height="27px" alt">: Ini adalah elemen gambar yang mengacu pada gambar "produk 1.1.png". Namun, ada beberapa masalah dengan elemen ini. Ada dua atribut alt dan salah satu dari mereka memiliki nilai "259px", yang seharusnya bukan nilai dari atribut alt.
63.	hreffebok Emergen LITE Mens/p: Ini sepertinya merupakan kesalahan ketik. Mungkin maksudnya adalah tag paragraf dengan teks "Emergen LITE Mens".
64.	cd class "box">: Kesalahan lain. Sepertinya seharusnya <div class="box">.
65.	<ine tres-/tmp/produx 1.4.png" width 259px" height="27px" * Jordan 1 lavata </: Ini tampaknya adalah bagian dari elemen gambar yang rusak dan tidak lengkap

![image](https://github.com/22091397103-MohammadAvieSienaMIC22/PEMWEB-07/assets/144098631/c765d171-44b3-4b44-9847-ceed7edd1534)

66.	</nav>: Penutup dari elemen navigasi yang mengindikasikan akhir dari bagian navigasi halaman.
67.	chouder id="home">: Kesalahan ketik. Ini sepertinya harus menjadi <header id="home">.
68.	div class judul: Kesalahan lagi. Seharusnya <div class="judul">.
69.	CHYTRE SERIES THAT <br> <MATCHES VISIE STYLE</</a>: Terdapat teks yang tampaknya harus diapit dengan tag (seperti <h1> atau <p>), dan tag penutup </a> yang tidak memiliki pasangan tag pembukanya.
70.	<div class="buttonshopnow">: Pembukaan div dengan class "buttonshopnow", kemungkinan untuk menampung tombol atau elemen interaktif lainnya.
71.	Elemen dengan hutan, king_oncu, prefike, dll.: Banyak dari elemen-elemen ini tampaknya kesalahan ketik untuk tag HTML yang sebenarnya, seperti <button>, <img src="...">, dan <a href="...">.
72.	<div class="fitur">, <div class="kotak">: Elemen-elemen pembungkus dengan class yang berbeda, mungkin untuk pengelompokan konten.
73.	Bagian dengan .png: Ini tampaknya adalah elemen gambar, tetapi banyak dari mereka yang memiliki kesalahan dalam atribut mereka.
74.	<section class="contact">: Ini memulai sebuah bagian baru di halaman dengan class "contact".
75.	<h1 class="contact text'>STAY UP TO DATE ABOUT OUR LATEST OFFERS</h1>: Ini adalah header yang memberitahu pengunjung untuk tetap up-to-date mengenai penawaran terbaru.
76.	<div <input class="search_contact" type="text" naver"query" (Jacanalder-"Enter your mail Address">: Elemen input ini memiliki banyak kesalahan sintaks.
77.	22 11 served.</p>: Ini tampaknya bagian dari teks hak cipta, tetapi terputus.
78.	</body> </html>: Penutup dari seluruh halaman web.




     b.CSS
![image](https://github.com/22091397103-MohammadAvieSienaMIC22/PEMWEB-07/assets/144098631/dc89dcb0-a996-4de8-81a6-3b5af45021ce)




 
