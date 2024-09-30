---
title: Logika dan Pembuktian

---

# Logika Matematika

## Negasi
Ingkaran atau negasi merupakan kebalikan/lawan dari suatu pernyataan P, maka negasinya adalah $\neg p$ atau dibacanya tidak p



| p     | -p    |
| ----- | ----- |
| benar | salah |
| salah | benar |

contoh soal:
p:semua unggas adalah burung
-p:ada unggas yang bukan burung


## Konjungsi
Konjungsi(dan) adalah pernyataan majemuk dengan kata hubung "dan" dengan notasi penulisan $p \wedge q$. Berikut adalah tabel nilai kebenarannya:<br>


| p   | q   | $p \wedge q$ |
| --- | --- | ----- |
| T   | T   | T     |
| T   | S   | S     |
| S   | B   | S     |
| S   | S   | S     |

Contoh soal
p: 3 adalah bilangan prima(pernyataan benar)
q: 3 adalah bilangan ganjil(pernyataan benar)
$p \wedge q$ : benar


## Disjungsi
Disjungsi adalah pernyataan majemuk yang menggunakan kata hubung "atau" disajikan dengan lambang v. Disjungsi bernilai benar bila sekurang-kurangnya salah satu pernyataan tunggalnya benar. berikut tabel kebenarannya:


| P   | q   | p v q |
| --- | --- | ----- |
| T   | T   | T     |
| T   | F   | T     |
| F   | T   | T     |
| F   | F   | F     |

Contoh soal:
p: paus adalah mamalia(pernyataan benar)
q: paus adalah herbivora(pernyataan salah)
 p v q: Paus adalah mamalia atau herbivora(pernyataan benar)

# Implikasi
Impikasi adalah pernyataan majemuk yang menggunakan kata hubung "jika....maka...". Kata hubung "jika...maka..." disajikan dengan lambang. Jika p maka akan terjadi q. Berikut tabel kebenarannya:

| p   | q   |  $p \rightarrow q$ |
| --- | --- | ----- |
| T   | T   | T     |
| T   | F   | F     |
| F   | T   | T     |
| F   | F   | T     |

Maksud tabel diatas:
1.Jika dia melakukan sesuatu benar kemudian dinyatakan benar maka, disimpulkan benar.
2.jika dia melakukan kebenaran tetapi dinyatakan salah, maka kesimpulannya salah.
3.Dia melakukan kesalahan tetapi dinyatakan benar, maka kesimpulannya benar.
4.Ketika dia melakukan kesalahan dan dinyatakan bersalah, maka tindakan benar.

Contoh soal:
p:Andi belajar secara online(pernyataan bernilai benar)
q:Andi dapat belajar diamana saja (Pernyataan bernilai benar)
$p \rightarrow q$:Jika Andi belajar secara online, maka Andi dapat belajar di mana saja(Pernyataan bernilai benar)


# Biimplikasi
Pernyataan majemuk yang menggunakan kata hubung "jika dan hanya jika" disebut biimplikasi kata hubung tersebut disajikan dengan lambang $p \leftrightarrow q$. 
Definisi: Biimplikasi bernilai benar bila kedua pernyataan tunggalnya mempunyai nilai kebenaran yang sama.Berikut tabel kebenarannya:


| p   | q   | $p \leftrightarrow q$ |
| --- | --- | --- |
| T   | T   | T   |
| T   | F   | F   |
| S   | B   | S   |
| S   | S   | B   |

Referensi: Catatan Sendiri

# Tugas
Buatlah tabel kebenaran untuk~pernyataan berikut $$P\lor(R\to\ Q)$$

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{T}&\text{T}&\text{T}\\\text{Т}&\text{Т}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{T}&\text{F}&\text{T}&\text{F}&\text{F}&\text{T}\\\text{T}&\text{F}&\text{F}&\text{F}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{T}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{T}&\text{F}&\text{F}&\text{F}\\\text{F}&\text{F}&\text{F}&\text{F}&\text{T}&\text{T}&\text{-}\end{array}$$


