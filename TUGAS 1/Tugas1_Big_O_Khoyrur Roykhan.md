<h2 align="center" ><b>TUGAS 1 Disain dan Analisis Algoritma</b></h2>
<br>

### __Nama : Khoyrur Roykhan__
### __NIM  : 2110131210002__

<br>

<h3 align="center" ><b>Penjelasan Sederhana Tentang Time Complexity dan Big-O Notation</b></h3>

<p align="justify">&ensp;&ensp;&ensp;&ensp;Setiap programmer yang baik akan menggunakan cara yang paling efektif dan efisien dalam menyelesaikan suatu permasalahan. Dan untuk bisa melakukan hal tersebut, <b>kita harus bisa meminimalisir kompleksitas dari algoritma yang kita gunakan.</b></p>

Kompleksitas suatu algoritma dibagi menjadi 2, yaitu <i>Time Complexity</i> dan <i>Space Complexity.</i>

<p align="justify">&ensp;&ensp;&ensp;&ensp;<b>Time Complexity</b> adalah seberapa lama waktu yang diperlukan untuk menjalankan suatu algoritma. Sedangkan <b>Space Complexity</b> adalah seberapa besar memori yang kita gunakan untuk menjalankan suatu algoritma. Dan disini kita hanya akan membahas tentang <b>Time Complexity</b>.</p>

<br>

### __Algoritma__

<p align="justify">&ensp;&ensp;&ensp;&ensp;Sederhananya, algoritma adalah serangkaian proses yang dilakukan secara berurutan untuk menyelesaikan sebuah permasalahan. Algoritma bisa bermacam-macam tergantung kepada siapa yang membuat algoritma tersebut. Namun permasalahannya adalah <i>algoritma mana yang lebih efektif dan efisien?</i></p>

<p align="justify">&ensp;&ensp;&ensp;&ensp;Seperti halnya yang sering kita hadapi dalam permasalahan sehari-hari, ketika kita akan berpergian ke suatu tempat. Kita tahu ada banyak jalan yang bisa dilalui untuk bisa sampai di tempat tujuan, namun permasalahannya adalah <b><i>rute mana yang paling cepat yang bisa kita ambil untuk sampai di tempat tujuan?</i></b></p>

<p align="justify">&ensp;&ensp;&ensp;&ensp;<b>Time Complexity Analysis</b> adalah suatu cara sederhana untuk mengetahui berapa lama waktu yang dibutuhkan untuk menjalankan suatu algoritma dengan input tertentu (n). Biasanya lebih dikenal dengan sebutan <b>Big-O Notation.</b></p>

<p align="justify">&ensp;&ensp;&ensp;&ensp;<b>Big-O Notation</b> adalah cara untuk mengkonversi keseluruhan langkah-langkah suatu algoritma kedalam bentuk Aljabar, yaitu dengan menghiraukan konstanta yang lebih kecil dan koefisien yang tidak berdampak besar terhadap keseluruhan kompleksitas permasalahan yang diselesaikan oleh algoritma tersebut.</p>

Liat contoh dibawah ini:

<p align="center"><img width="650" src="Gambar/gambar1.png"></p>

<p align="justify">&ensp;&ensp;&ensp;&ensp;Sederhananya, semua contoh yang ada diatas mengatakan bahwa <b><i>“kita hanya akan melihat faktor yang memiliki dampak paling besar terhadap nilai yang dihasilkan oleh algoritma tersebut”.</i></b></p>

Terdapat beberapa macam time complexity, diantaranya:

- __O(1) - Constant Time__

    <p align="justify"><b>Constant Time</b> artinya banyaknya input yang diberikan kepada sebuah algoritma, tidak akan mempengaruhi waktu proses (runtime) dari algoritma tersebut.</p>

    <p align="center"><img width="650" src="Gambar/gambar2.png"></p>

    <p align="justify">Contoh diatas, terdapat sebuah fungsi untuk mengambil elemen pertama dari sebuah input array. Kita bisa melihat bahwa berapapun jumlah array yang diberikan kepada fungsi tersebut, dia akan selalu melakukan 1 hal, yaitu mengambil elemen pertama. Itu artinya <b>jumlah input yang diberikan tidak mempengaruhi waktu proses (<i>runtime</i>) dari algoritma tersebut.</b></p>

    <p align="center"><img width="650" src="Gambar/gambar3.png"></p>

<br>

- __O(log n) - Logarithmic Time__

    <p align="justify"><b>Logarithmic Time</b> artinya ketika kita memberikan input sebesar n terhadap sebuah fungsi, jumlah tahapan yang dilakukan oleh fungsi tersebut berkurang berdasarkan suatu faktor. Salah satu contohnya adalah algoritma <b>Binary Search.</b></p>

    <p align="justify"><b>Binary Search</b> adalah algoritma yang kita gunakan dalam mencari posisi nilai dari suatu array dengan cara ‘mengeliminasi’ setengah dari array input untuk mempercepat proses pencarian.</p>

    <p align="center"><img width="650" src="Gambar/gambar4.png"></p>
<br>

- __O(n) - Linear Time__

    <p align="justify"><b>Linear Time</b> adalah ketika runtime dari fungsi kita berbanding lurus dengan jumlah input yang diberikan.</p>

    <p align="center"><img width="650" src="Gambar/gambar5.png"></p>

    <p align="justify">Kita bisa melihat bahwa <b>semakin banyak jumlah input yang diberikan, maka waktu proses/<i>runtime</i> dari fungsi tersebut akan semakin besar.</b></p>

    <p align="center"><img width="650" src="Gambar/gambar6.png"></p>
<br>

- __O(n²) — Quadratic Time__

    <p align="justify">b>Quadratic Time</b> adalah ketika runtime dari fungsi kita adalah sebesar n^2, dimana n adalah jumlah input dari fungsi tersebut. Hal tersebut bisa terjadi karena kita menjalankan <b>fungsi linear didalam fungsi linear</b> (n*n).</p>

    <p align="center"><img width="650" src="Gambar/gambar7.png"></p>

    <p align="center"><img width="650" src="Gambar/gambar8.png"></p>
<br>

- __O(2^n) — Exponential Time__

    <p align="justify"><b>Exponential Time</b> biasanya digunakan dalam situasi dimana kita tidak terlalu tahu terhadap permasalahan yang dihadapi, sehingga mengharuskan kita mencoba setiap <b>kombinasi</b> dan <b>permutasi</b> dari semua kemungkinan.</p>

    <p align="center"><img width="650" src="Gambar/gambar9.png"></p>
<br>

### __Kesimpulan__

<p align="justify">&ensp;&ensp;&ensp;&ensp;Sebagai programmer, kita sering kali dihadapkan dengan adanya beberapa solusi untuk sebuah permasalahan dan kita dibingungkan dengan pertanyaan <b><i>“mana solusi yang lebih efisien?”.</i></b></p>

<p align="justify">&ensp;&ensp;&ensp;&ensp;Dengan memahami <b>Big-O Notation</b>, kita akan lebih mudah dalam melihat mana algoritma yang lebih efisien yang bisa kita gunakan untuk menyelesaikan permasalahan yang sedang dihadapi.</p>

