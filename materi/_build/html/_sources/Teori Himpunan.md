---
title: Teori Himpunan

---

# Teori Himpunan
**Pendahuluan**
**Definisi:**
* Himpunan adalah kumpulan objek- objek yang berbeda.
* Objek didalam himpunan disebut **elemen**,**unsur**,atau **anggota**
* HMI adalah contoh sebuah himpunan, didalamnya berisi anggota berupa mahasiswa. Tiap mahasiswa berbeda satu sama lain.

**1.Notasi Himpunan**
Biasanya menggunakan huruf kapital seperti A,B,C,S, dan T untuk merepresentasikan himpunan, dan uruf kecil yang sesuai a,b,c,s, dan t, masing-masing. Untuk menunjukkan bahwa b adalah elemen himpunan B, kita mengadopsi notasi b∈B, yang berarti “b milik B” atau “b adalah elemen B.”
Contoh:
* $x \in A$: x merupakan anggota elemen A
* $x \notin A$: x bukan merupakan anggota elemen A

**2.Simbol-Simbol Baku:**
P =himpunan bulat positif=(1,2,3,4...)
N =himpunan bulat asli(natural)=(1,2...)
Z =himpunan bilangan bulat = (..,-2,-1,0,1,2..)
Q =himpunan bilangan bulat rasional=(1/2, 3/4,..)
R =himpunan bilangan rill(semua bilangan)=(R,P,N,Z...)
C =himpunan bilangan bulat kompleks(Bilangan imajiner)=(3 – 2i, 4 + 2i, 0)
Himpunan yang **Universal**: semesta, disimbolkan dengan U.
Contoh:
* Misalkan U=(1,2,3,4,5) dan A adalah himpunan bagian dari U. dengan A =(1,3,5)

**3.Notasi Pembentuk Himpunan**
Notasi:$\{ x \mid \text{ adalah syarat yang harus dipenuhi oleh x} \}$
Contoh:
* A adalah himpunan bulat positif kecil dari 5
A=$\{ x \mid \text{x adalah Bilangan bulat positif lebih kecil dari 5} \}$
atau atau $A = { x \mid x \in P, x < 5 }$
yang ekivalen dengan A = {1,2,3,4}

**4.Diagram Ven**
Himpunan dapat direpresentasikan secara grafis menggunakan diagram Venn,
Dalam diagram Venn, himpunan universal U, yang memuat semua objek yang, direpresentasikan oleh persegi panjang. (Perhatikan bahwa himpunan universal tergantung pada objek yang dibahas.) Di dalam persegi panjang ini, lingkaran atau bentuk geometris lainnya digunakan untuk merepresentasikan himpunan. Terkadang titik digunakan untuk merepresentasikan elemen-elemen tertentu dari himpunan. Diagram Venn sering digunakan untuk menunjukkan hubungan antar himpunan.
![Cuplikan layar 2024-10-12 210052](https://hackmd.io/_uploads/rkqSZbOk1e.png)

**Kardinalitas**
Jumlah elemen didalam A disebut **kardinal** dari himpunan A.Notasi:n(A) atau |A|.
Contoh:
* B=$\{ x \mid \text{x x merupakan bilangan prima lebih kecil dari 20} \}$ atau B= {2,3,5,7,11,13,17,19} maka |B| = 8

**Himpunan Koong (null set)**
Himpunan dengan kardinal = 0 disebut himpunan kosong(null set) dengan notasi:$\varnothing atau \{ \}$
Contoh:
* E = $\{ x \mid x < x \}$, maka n(E)=0

**Himpunan Bagian(subset)**
* Himpunan A dikatakan himpunan bagian dari himpunan B jika dan hanya jika setiap elemen A merupakan elemen dari B.
* Dalam hal ini, B dikatan superset dari A.
* Notasi $A \subseteq B$
* Diagram Ven:
![Cuplikan layar 2024-10-13 083246](https://hackmd.io/_uploads/B10_mju1Je.png)
Contoh:
* {1,2,3} $\subseteq$ {1,2,3,4,5}

**5.Operasi Terhadap Himpunan**
**1. Irisan(intersection)**
* Notasi :
$A \cap B$ atau
$A \cap B= \{ x \mid x \in A \text{ dan } x \in B \}$
![Cuplikan layar 2024-10-13 084516](https://hackmd.io/_uploads/H1ZILjO1ye.png)
Contoh:
* Jika A = {2,4,6,8,10} dan B = {4,10,14,18}, maka $A \cap B$ = {4,10}

**2. Gabungan(Union)**
* Notasi : 
$A \cup B$ atau $A \cup B = \{ x \mid x \in A \text{ atau } x \in B \}$
![Cuplikan layar 2024-10-13 085651](https://hackmd.io/_uploads/ryKWtsdyJx.png)
Contoh:
* Jika A = {2,5,8} dan B = {7,5,22}, maka $A \cup B$ = {2,5,7,22}

**3. Komplemen(Complement)**
* Notasi : 
$\overline{A} = \{ x \mid x \in U, x \notin A \}$
![Cuplikan layar 2024-10-13 090544](https://hackmd.io/_uploads/S1MGsj_kJl.png)
Contoh:
* Misalkan U = {1,2,3,4,5,6,7,8,9}
* Jika A = {1,3,7,9}, Maka $\overline{A}$={2,4,5,6,8}

**4. Selisih(difference)**
$A - B = {x \mid x \in A \text{ dan } x \notin B} = A \cap \overline{B}$
![Cuplikan layar 2024-10-13 092439](https://hackmd.io/_uploads/HkKtJ2_yJe.png)
Contoh:
* Jika A = {1,2,3...,10} dan B = {2,4,6,8,10}, maka A-B = {1,3,5,7,9} dan B-A = $\varnothing$

**5. Perkalian(Kartesian)**
* Notasi: $A \times B = {(a, b) \mid a \in A \text{ dan } b \in B }$
Contoh:
Misalkan C={1,2,3}, dan D={a,b}, maka C x D = {(1,a),(1,b),(2,a),(2,b),(3,a),(3,b)}

**Hukum Hukum Himpunan**
![Picture1](https://hackmd.io/_uploads/H11tH3dJ1e.png)

<!--De Morgan Laws-->
**TUGAS** 
**1.Dee Morgan Laws**
$\begin{aligned} & \overline{A \cap B}=\bar{A} \cup \bar{B} \\ & \overline{A \cup B}=\bar{A} \cap \bar{B}\end{aligned}$
Contoh Soal :
* U={1,2,3,4,5,6,7,8,9,10}
A={2,3,6,7}
B={1,2,3}
C={2,6,7}
Jawaban
${A \cup B}=${1,2,3,6,7}
$\overline{A \cup B}=${4,5,8,9,10}
Pembuktian:
$\bar{A}$={1,4,5,8,9,10}
$\bar{B}$={4,5,6,7,8,9,10}
$\overline{A \cup B}=$ {4,5,8,9,10}

<!--Absortion Laws/Hukum Penyerapan-->
**2.Absortion Laws**
$\begin{aligned} & A \cup(A \cap B)=A \\ & A \cap(A \cup B)=A\end{aligned}$
Contoh soal:
U={1,2,3,4,5,6,7,8,9,10}
A={2,3,6,7}
B={1,2,3}
C={2,6,7}
Jawaban:
$\begin{aligned} & A \cup(A \cap B)=A \end{aligned}$
Berarti,karena ${A \cup B}=${1,2,3,6,7},maka $\begin{aligned} & A \cup(A \cap B)=\end{aligned}${2,3,6,7} sama dengan A,Karena A digabung dengan yang didalam kurung

<!--Hukum Komplemen-->
**3.Hukum Complement**
$\begin{aligned} & A \cup \bar{A}=U \\ & A \cap \bar{A}=\emptyset\end{aligned}$
Contoh Soal
A ∩ AC = ∅
Artinya, tidak ada anggota himpunan A yang menjadi bagian anggota komplemen himpunan A. Hal itu karena komplemen merupakan anggota semesta yang bukan anggota {A}. Perhatikan contoh berikut.
S = {a, b, d, i, n, u}
A = {d, i, a, n}
AC = {b, u}
Dari contoh di atas, terlihat bahwa tidak ada anggota himpunan A yang menjadi bagian komplemennya.
A={1,3,5,7}
B={2,4,6,8}
$A \cup \bar{A}=${1,2,3,4,5,6,7,8,}Semestanya(U).

**Referensi**
**Sang Tutor. (2020, Desember 10).  MATEMATIKA DISKRIT || HIMPUNAN (BAGIAN 1). YouTube.https://youtu.be/wA1ZltkqypM?si=pI9cABcG-L6X2IQj**

**Sang Tutor. (2020, Desember 17).  MATEMATIKA DISKRIT || HIMPUNAN (BAGIAN 2). YouTube.https://youtu.be/wA1ZltkqypM?si=pI9cABcG-L6X2IQj**