---
title: Sistem Persamaan Linier

---

# Sistem persamaan linier
Sistem persamaan linear sendiri merupakan suatu persamaan aljabar. Aljabar adalah cabang matematika yang menggunakan simbol dan huruf tertentu untuk mewakili nilai dari suatu materi.

## Definisi Sistem Persamaan Linier
Dikutip dari buku Linear Programming dengan R: Aplikasi untuk Teknik Industri karya Ilyas Masudin, Muhammad Faisal Ibrahim, Gilang Yandeza, persamaan linear adalah sistem persamaan aljabar yang pada setiap sukunya mengandung konstanta, atau perkalian konstanta dengan variabel tunggal. 
Persamaan tersebut dikatakan linear sebab hubungan matematis ini dapat digambarkan sebagai garis lurus.

Berdasarkan penjelasan di atas, sistem persamaan linear pada umumnya memiliki variabel tunggal. Namun, ada beberapa jenis sistem persamaan linear yang memiliki variabel yang lebih dari satu, yakni sistem persamaan linear dua variabel atau SPLDV dan sistem persamaan linear tiga variabel atau SPLTV. 

**$ax + b = 0$, dengan catatan $a ≠ 0 dan b = konstanta dan penyelesaian: $x = - b/a$.**

Mengutip dari buku *Matematika* karya Ir. Sugiyono, untuk dapat memahami sistem persamaan linear, berikut contoh soal beserta cara menyelesaikannya.
![as2zip8tbpgarnb7scik](https://hackmd.io/_uploads/rJMGcmf9yl.png)
Sebelum beralih ke contoh soal, sekiranya penting untuk mengetahui bentuk umum dari sistem persamaan linear. Adapun bentuk umum dari sistem persamaan linear ialah:

**Contoh 1**
Jika x + 1 = 5, berapakah nilai x?
Penyelesaian: 
x + 1 = 5
x = 5-1
x = 4
## Solusi Persamaan Linier
Solusi dari persamaan linear $𝑎1𝑥1 + 𝑎2𝑥2 + ⋯ + 𝑎𝑛𝑥𝑛 = 𝑏$
adalah suatu urutan dari 𝑛 bilangan $𝑠1, 𝑠2, … , 𝑠𝑛$ sedemikian
rupa sehingga persamaan tersebut akan terpenuhi jika kita
menggantikan $𝑥1 = 𝑠1, 𝑥2 = 𝑠2, … 𝑥𝑛 = 𝑠𝑛.$ Kumpulan semua
solusi dan persamaan itu disebut **himpunan solusi (solution
set) atau solusi umum (general solution)** dari persamaan
tersebut. 

*Mencari Himpuna Solusi*
Tentukan himpunan solusi untuk


---

$a) 4𝑥 − 2𝑦 = 1$
$b) 𝑥1 − 4𝑥2 + 7𝑥3 = 5$


---
1. Untuk mencari solusi, Kita dapat menetapkan nilai sebarang untuk 𝑥 dan menyelesaikan
persamaan untuk memperoleh 𝑦 atau kita menetapkan nilai sebarang untuk 𝑦 dan
menyelesaikan persamaan untuk memperoleh 𝑥.
Misal 𝑥 = 𝑡 maka

    $\begin{aligned}
    4t - 2y &= 1 \\
    -2y &= 1 - 4t \\
    y &= 2t - \frac{1}{2}
\end{aligned}$

    Jika $𝑡 = 3$ maka $𝑦 = 2 (3) - \frac{1}{2} =\frac{11}{2}$

    Misal $𝑦 = 𝑡$ maka
    
    $\begin{aligned}
    4x - 2t &= 1 \\
    4x &= 2t - 1 \\
    x &= \frac{1}{2}t - \frac{1}{4}
\end{aligned}$

1. Untuk mencari solusi kita dapat menetapkan nilai sebarang dua variable dan
menyelesaikan persamaan tersebut untuk variable ketiga. Misal, jika kita menetapkan nilai
sebarang $𝑠$ dan $𝑡$, berturut-turut untuk $𝑥_2$ dan $𝑥_3$ dan menyelesaikan $𝑥_1$ maka kita peroleh
    
    $x_1 = 5 + 4s - 7t, \quad x_2 = s, \quad x_3 = t$
    
    Himpunan terbatas dari persamaan linear dalam variable $𝑥_1, 𝑥_2 … , 𝑥$ disebut **sistem persamaan linear atau sistem linear.**

Secara umum, sistem linear dari 𝑚 persamaan dengan variable 𝑛 tak diketahui dapat ditulis sebagai:
    

\begin{aligned}
    a_{11}x_1 + a_{12}x_2 + \cdots + a_{1n}x_n &= b_1 \\
    a_{21}x_1 + a_{22}x_2 + \cdots + a_{2n}x_n &= b_2 \\
    \vdots \quad &\quad \vdots \quad \vdots \\
    a_{m1}x_1 + a_{m2}x_2 + \cdots + a_{mn}x_n &= b_m
\end{aligned}

Dimana $𝑥_1, 𝑥_2 … , 𝑥_𝑛$ merupakan variable dan 𝑎 dan 𝑏 merupakan konstanta.

Urutan sejumlah bilangan $𝑠_1, 𝑠_2, … , 𝑠_𝑛$ merupakan solusi dari sistem persamaan linear jika
$𝑥_1 = 𝑠_1, 𝑥_2 = 𝑠_2, … , 𝑥_𝑛 = 𝑠_𝑛$ merupakan solusi dari setiap persamaan di dalam sistem tersebut.

**Suatu sistem persamaan Linear dapat tidak memiliki solusi, memiliki tepat satu solusi
atau memiliki tak hingga banyak solusi.**

Suatu sistem persamaan yang tidak memiliki solusi disebut **tidak konsisten (inconsistent)**, Sedangkan jika terdapat paling tidak satu solusi dalam sistem disebut **konsisten.**

![Cuplikan layar 2025-02-23 073109](https://hackmd.io/_uploads/rkIw31ucJg.png)
**Tidak Punya Solusi**
Garis $𝑙_1$ dan $𝑙_2$ mungkin sejajar, yang berarti kedua garis tidak berpotongan dansebagai konsekuensinya sistem tidak memiliki solusi.

![Cuplikan layar 2025-02-23 073342](https://hackmd.io/_uploads/H1bZaydc1x.png)
**Memiliki Satu Solusi**
Garis $𝑙_1$ dan $𝑙_2$, mungkin berpotongan hanya pada 1 titik, yang berarti sistem hanyamemiliki tepat satu solusi.

![Cuplikan layar 2025-02-23 073533](https://hackmd.io/_uploads/B1VvaJdqyx.png)
**Memiliki Tak Hingga Solusi**
Garis $𝑙_1$ dan $𝑙_2$ , mungkin berhimpitan, yang berarti jumlah titik potongnya tak terhingga dan sebagai konsekuensi terdapat tak terhingga banyaknya solusi untuk sistem tersebut.


---

**Contoh: Sistem Linear dengan satu Solusi**
Selesaikan sistem persamaan linear berikut:

$𝑥 − 𝑦 = 1$
$2𝑥 + 𝑦 = 6$

Penyelesaian:
Eliminasikan variable $𝑥$ dengan menambahkan $− 2$ kali persamaan pertama dengan persamaan kedua. Sehingga menghasilkan

$𝑥 − 𝑦 = 1$
$3𝑦 = 4$

Kita peroleh $𝑦 = 4/3$ . Subsitusikan nilai tersebut ke persamaan pertama $𝑥 = 1 + 𝑦 = 1 + \frac{4}{3} = \frac{7}{3}$. Sehingga persamaan memiliki solusi
Tunggal.


---


**Contoh: Sistem Linear dengan Tanpa
Solusi**
Selesaikan sistem linear berikut:

$𝑥 + 𝑦 = 4$
$3𝑥 + 3𝑦 = 9$

Penyelesaian:
Eliminasikan variable $𝑥$ dengan menambahkan $−3$ kali persamaan pertama dengan persamaan kedua. Sehingga menghasilkan

$𝑥 + 𝑦 = 4$
$0 = −3$

Persamaan kedua inkonsisten, jadi sistem persamaan yang diberikan tidak memiliki solusi.

---

*Contoh: Sistem Linear dengan solusi tak hingga*
Selesaikan sistem linear berikut:

$2𝑥 − 4𝑦 = 1$
$8𝑥 − 16𝑦 = 4$

Eliminasi variable $𝑥$ dengan menambahkan $−4$ kali persamaan pertama dengan persamaan kedua. Sehingga menghasilkan

$2𝑥 − 4𝑦 = 1$
$0 = 0$

Dengan demikian

$x = \frac{1}{2} + 2y$

Misalkan $𝑦 = 𝑡$ maka $𝑥 = \frac{1}{2} + 2t$

Dari bentuk tersebut kita memperoleh banyak solusi secara spesifik dari persamaan ini dengan mensubtitusi nilai-nilai untuk paramaternya. Contoh: $𝑡 = 0$ maka $𝑥 = \frac{1}{2} ,t = 1$ maka $𝑥 = 5/2.$


### Eliminasi
Metode ini bekerja dengan cara mengeliminasi (menghilangkan) variabel-variabel di dalam sistem persamaan hingga hanya satu variabel yang tertinggal.

Pertama-tama, lihat persamaan-persamaan yang ada dan coba cari dua persamaan yang mempunyai koefisien yang sama (baik positif maupun negatif) untuk variabel yang sama. Misalnya, lihat persamaan $(1)$ dan $(3)$.Koefisien untuk $y$ adalah $1$ dan $−1$ untuk masing-masing persamaan. Kita dapat menjumlah kedua persamaan ini untuk menghilangkan $y$ dan kita mendapatkan persamaan $(4)$.

![upload_1072bb644df09b0c9c54d7dc79a99ed0](https://hackmd.io/_uploads/rk4TYlOqkl.png)

Perhatikan bahwa persamaan $(4)$ terdiri atas variabel $x$ dan $z$. Sekarang kita perlu persamaan lain yang terdiri atas variabel yang sama dengan persamaan$(4)$.Untuk mendapatkan persamaan ini, kita akan menghilangkan $y$ dari persamaan $(1)$dan $(2)$. Dalam persamaan $(1)$ dan $(2)$, koefisien untuk $y$ adalah 1 dan 3 masing-masing. Untuk menghilangkan $y$, kita kalikan persamaan $(1)$ dengan $3$ lalu mengurangkan persamaan $(2)$ dari persamaan $(1)$.

![upload_e189b88ad14dafd653a04146d781bb58](https://hackmd.io/_uploads/SycKqgd5ke.png)

Dengan persamaan $(4)$ dan $(5)$, mari kita coba untuk menghilangkan $z$.

![upload_50fef1ae76c909a8f1392a3b0bb7aa6d](https://hackmd.io/_uploads/SyYCcgd5kx.png)

Dari persamaan $(6)$ kita dapatkan $x = 2$. Sekarang kita bisa subtitusikan (masukkan) nilai dari $x$ ke persamaan $(4)$ untuk mendapatkan nilai $z$.

![upload_ab822f283c5c419b89a06a24e6862f11](https://hackmd.io/_uploads/ByvVsl_c1x.png)

Akhirnya, kita substitusikan (masukkan) nila dari $x$ dan $z$ ke persamaan $(1)$ untuk mendapatkan $y$.

![upload_7517237020e0f89b91e8531cfb35befe](https://hackmd.io/_uploads/B188ild5kl.png)

Jadi solusi sistem persamaan linier di atas adalah $x = 2, y = 3, z = 4$.

### Eliminasi Gaus
Sistem persamaan liniear yang terdiri atas persamaan-persamaan $(1), (2)$ dan $(3)$ dapat juga dinyatakan dalam bentuk matriks teraugmentasi seperti berikut

![upload_4944d6b5adbc48f1db7c7ecf4cdbccf5](https://hackmd.io/_uploads/BJnJheO9kg.png)

Dengan melakukan serangkaian operasi baris (Eliminasi Gauss), kita dapat menyederhanakan matriks di atas untuk menjadi matriks Eselon-baris.

![upload_3d6a6c26fb2e311ee99648cf3ed22906](https://hackmd.io/_uploads/B1Dl2g_5Jl.png)


Kemudian kita bisa substitusikan kembali nilai-nilai yang kita dapat untuk mencari nilai dari semua variabel. Atau, kita juga bisa meneruskan dengan serangkaian operasi baris lagi sehingga matriks di atas menjadi matriks yang Eselon-baris tereduksi (dengan menggunakan Eliminasi Gauss-Jordan).

![upload_ee950f6dfa7e887a6aa38a13edd9f314](https://hackmd.io/_uploads/BJTZ3gu9kl.png)


Dengan melakukan operasi Eliminasi Gauss-Jordan, kita mendapatkan solusi dari sistem persamaan linier di atas pada kolom terakhir: $x = 2, y = 3, z = 4.$

### h3Solusi Grafik
Penyelesaian sistem persamaan linier dengan metode grafik dilakukan dengan cara menggambar garis garis atau bidang planar yang merupakan representasi dari persamaan-persamaan yang ada dalam sistem tersebut. Solusinya adalah koordinat-koordinat yang merupakan titik potong dari garis-garis ataupun bidang-bidang planar itu.

Sebagai contoh, marilah kita lihat sistem persamaan liniear dengan dua variabel berikut ini.

![upload_19675a5d9e1ed893095f73e85b4ba7f1](https://hackmd.io/_uploads/BkfP2ldcyg.png)


Gambar kedua garis dari persamaan-persamaan di atas.

![upload_b986ac74b51191f5c91de1b4a77f3e5e](https://hackmd.io/_uploads/BJsvhlOqye.gif)


Seperti terlihat pada grafik di atas, kedua garis itu bertemu (mempunyai titik potong) pada titik $(0,3)$. Ini adalah solusi dari sistem persamaan linier tersebut, yaitu $x = 0, y = 3.$

Untuk persamaan linier dengan tiga variabel, solusinya adalah titik pertemuan dari tiga bidang planar dari masing-masing persamaan.

## Refrensi
https://kumparan.com/kabar-harian/sistem-persamaan-linear-dan-contoh-soalnya-1wlO01qJrrk

https://lmsspada.kemdiktisaintek.go.id/pluginfile.php/727301/mod_resource/content/3/Pengantar%20Sistem%20Persamaan%20Linear.pdf
