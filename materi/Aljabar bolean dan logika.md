---
title: Aljabar bolean dan logika

---

# *Aljabar Boolean & Gerbang Logika*
Aljabar Boolean dicetus oleh seorang filsuf dan matematikawan asal Inggris yang bernama George Boole. Penemuannya berupa aljabar memiliki kontribusi banyak dalam ilmu komputer. Bahkan, hampir sebuah bahasa pemrograman mengenal tipe daat Boolean.
Karekteristik aljabar Boolean yang hanya mengenal dua nilai, yaitu 0 dan 1 digunakan dalam perancangan rangkaian listrik dan elektronik hingga saat ini. Aljabar Boolean merupakan aljabar yang berhubungan dengan variabel-variabel biner dan operasi logik. Variabel-variabel diperhatikan dengan huruf alfabet dan tiga operasi dasar AND, OR, dan NOT.
Fungsi Boolean terdiri dari variabel biner yang menunjukkan fungsi suatu tanda sama dengan dan suatu ekspresi aljabar dibentuk dengan menggunakan variabel-variabel biner, konstanta 0 dan 1, serta simbol operasi logika dan tanda kurung.Aljabar Boolean sering digunakan dalam pemrograman untuk mengevaluasi ekspresi logika.
Contoh dalam bahasa python:
![Picture1](https://hackmd.io/_uploads/rk9IZfZkJg.png)
**1.OPERATOR**
**Operator Biner:**
Aljabar Boolean memiliki dua operator biner:
Penjumlahan (+): Digunakan untuk operasi disjungsi (OR).
Perkalian (⋅): Digunakan untuk operasi konjungsi (AND).

**Operator Uner:**
Komplemen (’): Digunakan untuk menghasilkan nilai yang berlawanan dari suatu elemen. Misalnya, jika a = 1, maka a’ = 0, dan sebaliknya.

**2.Aksioma-Aksioma:**
Untuk setiap a, b, c ∈ B, berlaku aksioma-aksioma berikut:
**Closure:** a + b ∈ B dan a ⋅ b ∈ B.
**Identitas:** a + 0 = a dan a ⋅ 1 = a.
**Komutatif:** a + b = b + a dan a ⋅ b = b ⋅ a.
**Distributif:** a ⋅ (b + c) = (a ⋅ b) + (a ⋅ c) dan a + (b ⋅ c) = (a + b) ⋅ (a + c).
**Komplemen:** Untuk setiap a ∈ B, terdapat elemen unik a’ ∈ B sehingga a + a’ = 1 dan a ⋅ a’ = 0

Aljabar Boolean adalah sistem matematika untuk manipulasi variabel yang dapat memiliki salah satu dari dua nilai. 
Dalam logika formal, nilai-nilai ini adalah "benar" dan "salah." 
Dalam sistem digital, nilai-nilai ini adalah "nyala" dan "mati," 1 dan 0, atau "tinggi" dan "rendah." 
Ekspresi Boolean dibuat dengan melakukan operasi pada variabel Boolean. 
Operator Boolean yang umum termasuk AND (AND), (OR), dan (NOT).

**3.Aljabar Boolean**
* Sebuah operator Boolean dapat dijelaskan sepenuhnya menggunakan tabel kebenaran.
* Tabel kebenaran untuk operator Boolean D (AND) dan (OR) ditunjukkan di sebelah bawah. 
* Operator AND  juga dikenal sebagai produk Boolean. Operator OR adalah jumlah Boolean.
![Picture2](https://hackmd.io/_uploads/H1_Xk6_yJx.png)

**Boolean Algebra**
* Tabel kebenaran untuk operator Boolean (NOT) ditunjukkan di sebelah bawah.
* Operasi NOT paling sering dilambangkan dengan garis atas.
![Picture3](https://hackmd.io/_uploads/SJodJaO1kl.png)
* Sebuah fungsi Boolean memiliki: 
Setidaknya satu variabel Boolean, 
Setidaknya satu operator Boolean, dan 
Setidaknya satu input dari himpunan {0,1}.
* Fungsi ini menghasilkan output yang juga merupakan anggota dari himpunan {0,1}.
* Tabel kebenaran untuk fungsi Boolean. : 
![Picture4](https://hackmd.io/_uploads/HJ-MgTd1Jl.png)
ditunjukkan sebelah bawah.
![Picture5](https://hackmd.io/_uploads/HyNNxp_1kx.png)
* Untuk mempermudah evaluasi fungsi Boolean, tabel kebenaran berisi kolom tambahan (diarsir) untuk menyimpan evaluasi dari bagian-bagian subfungsi.
![Picture6](https://hackmd.io/_uploads/B1TvgTd1Jx.png)
* Sebagian besar identitas Boolean memiliki bentuk AND (perkallian) serta bentuk OR (jumlah). Kami menyajikan identitas kami menggunakan kedua bentuk tersebut. 
![Picture7](https://hackmd.io/_uploads/ryFcxa_kkg.png)
* Kelompok kedua
![Picture8](https://hackmd.io/_uploads/Bkp2xT_11l.png)
* Kelompok 3
![Picture9](https://hackmd.io/_uploads/Hk0--a_kkg.png)
* Terkadang, lebih ekonomis membangun sirkuit dengan menggunakan komplemen fungsi dan mengkomplementasi hasilnya dibandingkan mengimplementasikan fungsi secara langsung. Hukum DeMorgan memudahkan penemuan komplemen dari fungsi Boolean, yang menyatakan: :
![Picture10](https://hackmd.io/_uploads/rJEE-6_1ye.png)

**4.Logic Gates**
* Fungsi Boolean diimplementasikan dalam sirkuit komputer digital yang disebut gerbang (gates). 
* Gerbang adalah perangkat elektronik yang menghasilkan hasil berdasarkan dua atau lebih nilai input. 
* Dalam kenyataannya, gerbang terdiri dari satu hingga enam transistor, tetapi desainer digital menganggapnya sebagai satu kesatuan. 
* Sirkuit terintegrasi mengandung kumpulan gerbang yang sesuai untuk tujuan tertentu.
* **Tiga gerbang AND, OR, dan  NOT.**
![Picture11](https://hackmd.io/_uploads/Hk2aba_Jke.png)
* Gerbang yang sangat berguna lainnya adalah gerbang eksklusif OR (XOR). 
* Output dari operasi XOR adalah benar hanya ketika nilai-nilai input berbeda.
* ![Picture13](https://hackmd.io/_uploads/SkTIGpOy1e.png)
* NAND dan NOR dua gerbang yang sangat penting. Simbol dan tabel kebenarannya ditunjukkan di sebelah bawah.
![Picture14](https://hackmd.io/_uploads/r1oKzaOy1g.png)
* NAND dan NOR dikenal dengan gerbang universal  karena mereka murah untuk diproduksi dan setiap fungsi Boolean dapat dibangun menggunakan gerbang ini. NAND atau hanya gerbang NOR .  
![Picture15](https://hackmd.io/_uploads/S1b3zTdJkx.png)
* Gerbang dapat memiliki beberapa  inputs dan dan lebih dari satu output.
![Picture16](https://hackmd.io/_uploads/rJj0Ga_11g.png)

**5.Komponen Digital**
* Hal utama yang perlu diingat adalah bahwa kombinasi gerbang menerapkan fungsi Boolean.
* Rangkaian di bawah ini mengimplementasikan fungsi Boolean :
![Picture17](https://hackmd.io/_uploads/HyWc76d1ye.png)
![Picture18](https://hackmd.io/_uploads/HkKcmTuk1e.png)

**6.Combinational Circuits**
* Sirkuit logika kombinasi memberi kita banyak perangkat yang berguna.
Salah satu yang paling sederhana adalah setengah penambah, yang menemukan jumlah dua bit.
* Kita dapat memperoleh beberapa wawasan tentang konstruksi setengah penambah dengan melihat tabel kebenarannya, ditunjukkan di sebelah kanan.
* ![Picture19](https://hackmd.io/_uploads/rJm446OJJg.png)
* Seperti kita lihat, jumlahnya dapat ditemukan menggunakan operasi XOR dan sisanya menggunakan operasi AND.
![Picture21](https://hackmd.io/_uploads/BkTuNad1yg.png)![Picture20](https://hackmd.io/_uploads/BJxoE6u11x.png)

**Refersensi:**
Hendrik, Nuryanto. (2021, 15 Maret). Gerbang Logika: Pengertian, Jenis, Fungsi, dan Simbol. https://www.gramedia.com/literasi/gerbang-logika/

The Organic Chemistry Tutor. (2021, Januari 23). Logic Gates, Truth Tables, Boolean Algebra AND, OR, NOT, NAND & NOR.https://youtu.be/JQBRzsPhw2w?si=sTzRF_N78Q2o283-

MathemaNesos. (2021, Desember 13).Aljabar Boolean - Gerbang Logika - MathemaNesos.https://youtu.be/jtMX7ExAsZ0?si=F6O0F6GAL2Lc9VaU




