---
title: Algoritma

---

# Algoritma
## Definisi Algoritma
Algoritma adalah suatu langkah atau metode yang telah direncanakan secara matang sehingga terurut dan terorganisir dengan baik dan biasanya digunakan untuk memecahkan suatu masalah dengan memberikan suatu instruksi sehingga menjadi suatu tindakan.
### Algoritma sequential Search
Sequential search adalah teknik pencarian data yang dilakukan dengan cara membandingkan setiap elemen data satu per satu, mulai dari elemen pertama hingga elemen yang dicari ditemukan. Proses ini terus berlanjut hingga data ditemukan atau seluruh elemen telah diperiksa.

Algoritma ini termasuk salah satu algoritma pencarian yang paling sederhana dan sering digunakan dalam situasi di mana data tidak memiliki struktur tertentu.
**Fungsi Sequential Search**
* Digunakan untuk mencari data dengan melakukan proses membandingkan setiap elemen larik secara beruntun satu persatu, mulai dari elemen pertama, sampai elemen yang dicari ditemukan, atau seluruh elemen sudah diperiksa .
* Dapat digunakan untuk pengelolaan data, seperti fungsi pencarian data barang pada master data barang .
* Dalam konteks pengujian kecepatan pencarian, Algoritma Sequential Search dapat digunakan dengan fungsi microtime untuk mengevaluasi kecepatan pencarian data.
**Cara Kerja Sequential Search***
Algoritma Sequential Search bekerja dengan melakukan perbandingan satu persatu secara beruntun dalam kumpulan data dengan data yang dicari sampai data tersebut ditemukan atau tidak ditemukan.

Proses pencarian ini hanya melakukan pengulangan data dari 1 sampai dengan jumlah data (N). Setiap pengulangan, dilakukan perbandingan data ke-i dengan data yang sedang dicari. Jika data sama dengan yang dicari, berarti data telah berhasil ditemukan. Sebaliknya, jika sampai akhir pengulangan tidak ada data yang sama dengan yang dicari, berarti data tidak ditemukan.
### Algoritma Binary search
Binary search adalah sebuah algoritma pencarian yang digunakan untuk mencari elemen tertentu dalam sebuah array atau daftar yang sudah diurutkan. Algoritma ini bekerja dengan membagi daftar menjadi dua bagian, kemudian memeriksa elemen tengahnya. Jika elemen yang dicari sama dengan elemen tengah ini, pencarian selesai. Jika tidak, algoritma akan menentukan apakah elemen yang dicari lebih besar atau lebih kecil dari elemen tengah, dan kemudian hanya memeriksa salah satu bagian dari daftar yang masih mungkin mengandung elemen yang dicari. Proses ini terus berlanjut hingga elemen yang dicari ditemukan atau daftar habis diperiksa.
**Cara Kerja Binary Search**
Cara kerja binary search sangat sederhana. Algoritma ini beroperasi pada daftar yang sudah diurutkan. Berikut adalah langkah-langkah utama dalam binary search:

* Tentukan Rentang Pencarian Awal: Di awal pencarian, kita memiliki seluruh daftar sebagai rentang pencarian. Rentang ini didefinisikan dengan dua indeks, yaitu awal dan akhir, yang mengacu pada elemen pertama dan terakhir dalam daftar.
* Hitung Elemen Tengah: Temukan indeks tengah di dalam rentang pencarian dengan rumus tengah = (awal + akhir) / 2.
* Periksa Elemen Tengah: Bandingkan elemen tengah dengan elemen yang ingin Anda cari. Jika elemen tengah sama dengan elemen yang dicari, maka pencarian selesai, dan Anda telah menemukan elemennya.
* Perkecil Rentang Pencarian: Jika elemen tengah lebih besar dari elemen yang dicari, maka Anda dapat memastikan bahwa elemen yang dicari hanya mungkin ada di sebelah kiri elemen tengah. Oleh karena itu, perkecil rentang pencarian menjadi antara awal dan tengah - 1. Jika elemen tengah lebih kecil, perkecil rentang menjadi antara tengah + 1 dan akhir.
* Ulangi Langkah 2–4: Ulangi proses ini sampai Anda menemukan elemen yang dicari atau rentang pencarian menjadi kosong.

Algoritma ini terus membagi rentang pencarian menjadi setengah hingga elemen yang dicari ditemukan atau rentang habis. Hal ini menghasilkan kompleksitas waktu O(log n), di mana n adalah jumlah elemen dalam daftar. Ini sangat efisien dibandingkan dengan pencarian linear yang memiliki kompleksitas waktu O(n).

## Pseudocoe adalah....
Pseudocode adalah cara penulisan kode dan algoritma menggunakan bahasa umum yang digunakan sehari-hari sehingga lebih mudah dipahami. Karena itu pseudocode juga disebut sebagai false code atau representation code.

Biasanya bahasa yang digunakan dalam pseudocode adalah bahasa Inggris sederhana, tapi bisa juga dengan bahasa Indonesia atau bahasa lain. Tujuannya agar siapapun yang tidak memiliki latar belakang programming bisa memahami sebuah program dan menjalankannya dengan benar.

## Big O algoritma
Notasi Big-O adalah cara untuk mengekspresikan kompleksitas waktu (atau ruang) suatu algoritma. Notasi ini memberikan perkiraan kasar tentang berapa lama waktu yang dibutuhkan suatu algoritma untuk berjalan (atau berapa banyak memori yang digunakannya), berdasarkan ukuran input. Misalnya, suatu algoritma dengan kompleksitas waktuberarti waktu berjalan meningkat secara linear seiring dengan ukuran input.

## Hitung Big O dari Algoritma Sequential Search
 **Waktu kompleksitas (time complexity)**
Kompleksitas waktu adalah seberapa lama waktu yang dibutuhkan untuk menjalankan suatu algoritma, **Time Complexity Analysis** adalah suatu cara yang sederhana untuk menemukan seberapa lama waktu yang dibutuhkan untuk menjalankan suatu algoritma dengan input tertentu (n). Dan ini disebut dengan Big-O Notation.**Analisis Waktu Kompleksitas:**
* **Kasus Terbaik**: Jika elemen yang dicari berada di posisi pertama dalam daftar, maka hanya satu perbandingan yang diperlukan. Waktu kompleksitasnya adalah O(1).
* **Kasus Terburuk**: Jika elemen yang dicari tidak ada dalam daftar atau berada di posisi terakhir, algoritma harus memeriksa semua elemen. Jika ada 
𝑛 n elemen dalam daftar, maka waktu yang diperlukan adalah O(n).
* **Kasus Rata-rata:** Dalam kasus rata-rata, kita dapat mengasumsikan bahwa elemen yang dicari memiliki peluang yang sama untuk berada di mana saja dalam daftar. Maka, waktu rata-rata yang diperlukan juga O(n).
**Calculating Time Complexity**
T(n) = $2n^2$ + 3n + 1
     = $2n^2$
     = O $(n^2)$

**Ruang kompleksitas (space komplexity)**
Algoritma Sequential Search melakukan pencarian elemen dengan cara memeriksa setiap elemen dalam daftar satu per satu. Berikut adalah langkah-langkahnya:
1.Mulai dari elemen pertama.
2.Bandingkan elemen saat ini dengan elemen yang dicari.
3.Jika elemen saat ini cocok, algoritma selesai.
4.Jika tidak, lanjutkan ke elemen berikutnya hingga elemen ditemukan atau semua elemen telah diperiksa.

**Analisis Ruang Kompleksitas**
1.**Ruang untuk Input**: Algoritma ini memerlukan ruang untuk menyimpan input, yaitu daftar (array) yang akan dicari. Namun, ruang ini tidak dihitung dalam analisis ruang kompleksitas karena dianggap sebagai bagian dari input.
2.**Variabel Tambahan:**
* Algoritma Sequential Search hanya menggunakan sejumlah kecil variabel tambahan (seperti indeks untuk iterasi dan variabel untuk menyimpan nilai yang dicari).
* Ini berarti bahwa ruang tambahan yang diperlukan adalah konstan, terlepas dari ukuran input.
Dengan demikian, kompleksitas ruang dari algoritma Sequential Search adalah:
**Ruang Kompleksitas:O(1)**
Ini berarti bahwa algoritma Sequential Search memiliki kompleksitas ruang konstan, karena tidak tergantung pada ukuran input. Hanya memerlukan ruang yang tetap untuk variabel yang digunakan dalam proses pencarian, tanpa memperhitungkan ruang untuk input itu sendiri.



**Referensi**
K, Amira. (2023, Maret 5). Algoritma: Pengertian, Sejarah, Jenis, Fungsi, dan Contohnya. Gramedia Blog. https://www.techinsights.com/understanding-ai
diakses: 30/09/2024
Annisa. (2023, Desember 12). Algoritma Sequential Search: Pengertian, Fungsi dan Cara Kerjanya. UMSU. https://www.techinsights.com/understanding-ai
diakses: 30/09/2024
Palsu, Engineer. (2023, November 10). Mengenal Algoritma Binary Search. Medium. https://engineerpalsu.medium.com/mengenal-algoritma-binary-search-40a9047dab62
diakses: 30/09/2024
Apa itu Pseudocode?. (2024, Maret 5). Revou. https://revou.co/kosakata/pseudocode
diakses: 30/09/2024
Ahmad, Arslan. (2023, May 18). Demystifying Big-O Notation: The Ultimate Guide to Understanding Algorithm Complexity.https://www.designgurus.io/blog/big-o-algorithm-complexity
diakses: 30/09/2024





