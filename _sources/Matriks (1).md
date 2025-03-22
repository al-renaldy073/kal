---
title: Matriks

---

# Matriks
## Pendahulaun
Matriks adalah susunan angka atau objek matematika lainnya yang disusun dalam bentuk baris dan kolom, dimana operasi seperti penjumlahan dan perkalian dapat didefinisikan. Umumnya, matriks di atas medan 
$F$ berisi elemen-elemen dari $F$. Sebagian besar artikel ini berfokus pada matriks riil dan kompleks, yaitu matriks yang masing-masing elemennya berupa bilangan riil atau bilangan kompleks. Jenis elemen matriks yang umum akan dibahas di bawah. Sebagai contoh, ini adalah sebuah matriks riil:

$\mathbf{A} =
\begin{bmatrix}
-1.3 & 0.6 \\
20.4 & 5.5 \\
9.7 & -6.2
\end{bmatrix}
.$

## Apa itu matriks
Matriks adalah **sekumpulan bilangan yang disusun berdasarkan baris dan kolom, serta ditempatkan di dalam tanda kurung.** Nah, tanda kurungnya ini bisa berupa kurung biasa “( )” atau kurung siku “[ ]”, ya. Suatu matriks diberi nama dengan huruf kapital, seperti A, B, C, dan seterusnya.

Oh iya, kamu tau kan bedanya baris dan kolom? Baris itu susunannya horizontal atau ke samping, sedangkan kolom susunannya vertikal atau dari atas ke bawah.

Misalnya nih, matriks di atas tadi, kita beri nama matriks A. Maka,

![Cuplikan layar 2025-03-05 203614](https://hackmd.io/_uploads/rJodQ0Siyg.png)


Penamaan baris dan kolom dibuat urut, ya. Jadi, baris ke-1 dimulai dari atas, urut ke bawah. Sementara itu, kolom ke-1 dimulai dari kiri ke kanan.

## Operasi Aritmetika Matriks
### 1. Penjumlahan Matrik
**Konsep penjumalahan matriks:**

Penjumlahan matriks adalah operasi yang dilakukan dengan menjumlahkan elemen-elemen yang bersesuaian pada dua matriks yang memiliki ukuran yang sama.Penjumlahan matriks dapat dilakukan jika jumlah baris dan kolomnya sama.

Terdapat dua buah matriks yaitu matriks A dan matriks B yang memiliki ukuran baris dan kolom yang sama, maka penjumlahan matriks A + B akan menghasilkan matriks C = A + B

Dimana elemen 
 pada matriks hasil penjumlahan C adalah hasil penjumlahan elemen - elemen yang bersesuai pada matriks A dan B.
 
 $c_{ij} = a_{ij} + b_{ij}$
 
**Contoh penjumlahan matriks:**

Misal ada 2 matriks A dan B:

$A :
\begin{bmatrix}
1 & 3 \\
2 & 4
\end{bmatrix}$

$B :
\begin{bmatrix}
2 & 6 \\
4 & 8
\end{bmatrix}$

penjumlahan A + B adalah:

$A + B =
\begin{bmatrix}
1 + 2 & 3 + 6 \\
2 + 4 & 4 + 8
\end{bmatrix}$

Jadi hasil penjumlahan matriks A + B =

$C :
\begin{bmatrix}
3 & 9 \\
6 & 12
\end{bmatrix}$

### 2. Perkalian Matriks

**Konsep perkalian matriks:**

Perkalian matriks adalah operasi yang dilakukan antara dua matriks untuk menghasilkan matriks baru. Tidak semua matriks dapat diperkalikan, untuk dapat melakukan perkalian, jumlah kolom pada matriks pertama harus sama dengan jumlah baris pada matriks kedua.

Secara matematis, jika kita memiliki dua matriks A dan B, maka perkalian matriks $A \times B$ akan menghasilkan matriks $C$. Dengan syarat:

* Matriks $A$ memiliki ukuran $M \times P$ (m baris, n kolom)
* Matriks $B$ memiliki ukuran $N \times P$ (n baris, p kolom)

Maka hasil perkalian $C$ akan memiliki ukuran $M \times P$

**Cara melakukan perkalian matriks**

$A =
\begin{bmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
a_{21} & a_{22} & \cdots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{m1} & a_{m2} & \cdots & a_{mn}
\end{bmatrix}$

$B =
\begin{bmatrix}
b_{11} & b_{12} & \cdots & b_{1n} \\
b_{21} & b_{22} & \cdots & b_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
b_{m1} & b_{m2} & \cdots & b_{mn}
\end{bmatrix}$

Dari perkalian matriks di atas akan menghasilkan matriks $C$ dengan ukuran $M \times P$

$C =
\begin{bmatrix}
c_{11} & c_{12} & \cdots & c_{1p} \\
c_{21} & c_{22} & \cdots & c_{2p} \\
\vdots & \vdots & \ddots & \vdots \\
c_{m1} & c_{m2} & \cdots & c_{mp}
\end{bmatrix}$

Setiap elemen $C_{ij}$ (elemen pada baris ke-i dan kolom ke-j dari matriks hasil) dihitung dengan cara mengalikan elemen baris ke-i dari matriks $A$ dengan elemen kolom ke-j dari matriks $B$, lalu menjumlahkan hasil perkalian tersebut. Secara matematis:

$c_{ij} = a_{i1} b_{1j} + a_{i2} b_{2j} + \dots + a_{in} b_{nj}$

ini berarti untuk setiap elemen yang dihasilkan dalam perkalian, dengan cara mengambil elemen-elemen dari baris tertentu matriks $A$ kemudian dikalikan dengan elemen-elemen dari kolom tertentu pada matriks $B$ dan menjumlahkan hasil perkalian tersebut.

**contoh perkalian matriks**

misal memiliki 2 matriks sebagai berikut:

$A : 
\begin{bmatrix}
2 & 3 & 4 \\
1 & 3 & 5 \\
4 & 3 & 6
\end{bmatrix}$

$B :
\begin{bmatrix}
1 & 4 & 2 \\
3 & 7 & 2 \\
5 & 1 & 4
\end{bmatrix}$

untuk menghitung matriks hasil, $C = A \times B =$

$C =
\begin{bmatrix}
c_{11} & c_{12} & c_{13} \\
c_{21} & c_{22} & c_{23} \\
c_{31} & c_{32} & c_{33}
\end{bmatrix}$

Dengan elemen-elemen yang dihitung sebagai berikut:

$c_{11} = (2 \times 1) + (3 \times 3) + (4 \times 5) = 31$

$c_{12} = (2 \times 4) + (3 \times 7) + (4 \times 1) = 33$

$c_{13} = (2 \times 2) + (3 \times 2) + (4 \times 4) = 26$

$c_{21} = (1 \times 1) + (3 \times 3) + (5 \times 5) = 35$

$c_{22} = (1 \times 4) + (3 \times 7) + (5 \times 1) = 30$

$c_{23} = (1 \times 2) + (3 \times 2) + (5 \times 4) = 28$

$c_{31} = (4 \times 1) + (3 \times 3) + (6 \times 5) = 43$

$c_{32} = (4 \times 4) + (3 \times 7) + (6 \times 1) = 43$

$c_{33} = (4 \times 2) + (3 \times 2) + (6 \times 4) = 38$

maka hasil matriks C adalah:

$C =
\begin{bmatrix}
31 & 33 & 26 \\
35 & 30 & 28 \\
43 & 43 & 38
\end{bmatrix}$

### 3. Perkalian Skalar Matriks
**Konsep perkalian skalar matriks:**

Perkalian skalar matriks berati mengalikan semua elemen yang ada pada matriks dengan bilangan skalarnya. Operasi ini tetap mempertahankan dimensi matriks atau tidak merubah dimensi matriks.

**cara melakukan perkalian skalar matriks:**

Misal ada matriks berukuran $M \times N$:

$A =
\begin{bmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
a_{21} & a_{22} & \cdots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{m1} & a_{m2} & \cdots & a_{mn}
\end{bmatrix}$

dengan skalar $k_1$, maka perkalian matriks skalar adalah $KA$:

$kA =
\begin{bmatrix}
k \cdot a_{11} & k \cdot a_{12} & \cdots & k \cdot a_{1n} \\
k \cdot a_{21} & k \cdot a_{22} & \cdots & k \cdot a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
k \cdot a_{m1} & k \cdot a_{m2} & \cdots & k \cdot a_{mn}
\end{bmatrix}$
 
**contoh perkalian skalar matriks:**

Terdapat matriks:

$A :
\begin{bmatrix}
1 & 6 & 5 \\
2 & 7 & 4 \\
3 & 8 & 3
\end{bmatrix}$

dan skalar $K =2$, maka hasil perkalian skalar matriks:


$3A = 3x =
\begin{bmatrix}
1 & 6 & 5 \\
2 & 7 & 4 \\
3 & 8 & 3
\end{bmatrix} =
\begin{bmatrix}
3 & 18 & 15 \\
6 & 21 & 12 \\
9 & 24 & 9
\end{bmatrix}$
 
 
Jadi, semua elemen yang ada pada matriks $A$ dikalikan dengan skalar yaitu $3$, dan akan memperoleh matriks tersebut.

# implementasi python perka

### Ordo dan Elemen Matriks
Matriks memiliki ukuran. Ukuran matriks disebut ordo. Ordo matriks ini berdasarkan dari banyaknya baris dikali banyaknya kolom pada matriks. Jadi, kalo suatu matriks A memiliki m baris dan n kolom, maka matriks A tersebut berukuran (berordo) m x n. Supaya lebih sederhana, kita bisa menulisnya dengan $\textit{Amxn.}$

Nah, masing-masing bilangan yang terdapat di dalam matriks disebut **elemen matriks.** Elemen-elemen matriks juga ada notasinya sendiri, lho. Kalo matriks dinotasikan dengan huruf kapital, maka elemen-elemen matriks dinotasikan dengan huruf kecil dan diberi indeks yang menyatakan **letak baris dan kolomnya.**

Misalnya nih, pada matriks A di atas, jumlah barisnya kan ada 5 dan jumlah kolomnya juga ada 5, maka ordonya adalah 5 x 5, atau bisa kita tulis A5×5. Lalu, untuk elemen-elemen matriks A bisa dinotasikan dengan aij, yang menyatakan elemen matriks A pada baris ke-i dan kolom ke-j.

Supaya tidak bingung simak contoh di bawah ini.
![Cuplikan layar 2025-03-05 203806](https://hackmd.io/_uploads/ry7q40Hi1x.png)

Kita ambil contoh $\textit{a11, a12}$ dan $\textit{a53}$, seperti pada gambar.

*  $\textit{a11.}$ menyatakan elemen matriks A pada baris ke-1 kolom ke-1, nilainya adalah 0.
* $\textit{a12.}$ menyatakan elemen matriks A pada baris ke-1 kolom ke-2, nilainya adalah 1.
* $\textit{a53.}$ menyatakan elemen matriks A pada baris ke-5 kolom ke-4, nilainya adalah 2.

### Jenis-jenis Materiks
Selain punya ukuran (ordo), matriks juga terbagi menjadi beberapa bentuk yang mempunyai sifat khusus. Nah, beberapa jenis matriks khusus yang perlu kamu ketahui di antaranya sebagai berikut:

1. **Matriks Baris**
Matriks baris adalah suatu matriks yang **terdiri dari satu baris aja**. Contoh matriks baris:

    $A = \begin{bmatrix} 0 & 3 & 4 \end{bmatrix}$
    $P = \begin{bmatrix} -2 & 5 & 5 & 4 \end{bmatrix}$
    $Q = \begin{bmatrix} 3 & 2 & -1 & 6 & 1 \end{bmatrix}$

    Kalo kita lihat, matriks A, matriks P, dan matriks Q, semuanya terdiri dari satu baris dan beberapa kolom. Untuk masing-masing ordonya, berarti $A_{1 \times 3}$, $A_{1 \times 4}$, $A_{1 \times 5}$.

2. **Matriks Kolom**
Kebalikannya dari matriks baris, matriks kolom adalah suatu matriks yang **terdiri dari satu kolom aja**. Contoh matriks kolom:

    $R = \begin{bmatrix} 1 \\ 2 \end{bmatrix}, \quad
S = \begin{bmatrix} 3 \\ 4 \\ -1 \end{bmatrix}, \quad
T = \begin{bmatrix} 5 \\ -7 \\ 2 \\ 3 \end{bmatrix}$

    Matriks R, matriks S, dan matriks T sama-sama terdiri dari satu kolom dan beberapa baris. Oleh karena itu, ordo matriksnya adalah  $A_{2 \times 1}$, $A_{3 \times 1}$, $A_{4 \times 1}$.

3. **Matriks Persegi**
Matriks persegi adalah suatu matriks yang **memiliki jumlah baris dan kolom sama.** Itu tandanya, m = n. Karena jumlah baris dan kolomnya sama, maka ordo matriksnya bisa kita tulis menjadi n x n, atau matriks ordo n.

    Pada matriks persegi, terdapat **diagonal utama**, yaitu elemen-elemen matriks yang letak barisnya sama dengan letak kolomnya. Selain diagonal utama, ada juga diagonal samping atau diagonal kedua. Kalo kita tarik garis di sepanjang diagonal utama matriks, maka diagonal samping ini berada di arah sebaliknya. Contoh matriks persegi:

    ![Cuplikan layar 2025-03-05 211438](https://hackmd.io/_uploads/SypvnCSi1g.png)
    
    ![Cuplikan layar 2025-03-05 211517](https://hackmd.io/_uploads/Hkz92ABsJe.png)

    berdasarkan contoh di atas, matriks A memiliki jumlah baris dan kolom yang sama karena matriks ini merupakan matriks persegi, yaitu sebanyak 2. Maka, matriks ini merupakan matriks berordo 2. Kemudian, elemen-elemen pada diagonal utamanya adalah 8 dan 7.
    
4. **Matriks Diagonal**
Matriks diagonal adalah **matriks persegi yang elemen-elemen selain diagonal utamanya bernilai nol.** Contoh matriks diagonal:

    ![Cuplikan layar 2025-03-05 211959](https://hackmd.io/_uploads/SkG66Criyg.png)
    
    ![Cuplikan layar 2025-03-05 212010](https://hackmd.io/_uploads/BkzT6Rri1g.png)
    
    ![Cuplikan layar 2025-03-05 212023](https://hackmd.io/_uploads/HkMaaRSoyg.png)

    Elemen-elemen pada diagonal utama matriks Q adalah 3, 8, dan 5. Nah, di luar diagonal utama, semua elemennya bernilai 0. Misalnya, elemen $Q_{2 1}$ adalah 0, lalu elemen $Q_{2 1}$ juga 0.
    
5. **Matriks Identitas**
Matriks identitas adalah **matriks persegi yang semua elemen pada diagonal utamanya bernilai satu, sedangkan elemen lainnya bernilai nol.** Umumnya, matriks identitas dinotasikan dengan I disertai dengan ordonya. Contoh matriks identitas:


    $I_2 =
\begin{bmatrix}
1 & 0 \\
0 & 1
\end{bmatrix} \quad
I_3 =
\begin{bmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{bmatrix} \quad
I_4 =
\begin{bmatrix}
1 & 0 & 0 & 0 \\
0 & 1 & 0 & 0 \\
0 & 0 & 1 & 0 \\
0 & 0 & 0 & 1
\end{bmatrix}$

6. **Matriks Nol**
Sesuai namanya, matriks nol adalah **matriks yang semua elemennya bernilai nol.** Matriks nol biasanya dinotasikan dengan huruf O disertai ordonya. Contoh matriks nol:

    $O_{2 \times 1} =
\begin{bmatrix}
0  \\
0 
\end{bmatrix} \quad
O_{3 \times 2} =
\begin{bmatrix}
0 & 0  \\
0 & 0  \\
0 & 0 
\end{bmatrix} \quad
O_{2 \times 3} =
\begin{bmatrix}
0 & 0 & 0 \\
0 & 0 & 0
\end{bmatrix}$

### Transpose Matriks
Transpose matriks **adalah suatu matriks yang diperoleh dari hasil pertukaran antara elemen baris dan kolomnya.** Jadi, elemen-elemen pada baris akan kita tukar menjadi elemen-elemen pada kolom, atau sebaliknya. 

Misalnya, kita akan mentranspose matriks A dan B. Maka, matriks transposenya bisa dinotasikan dengan $A^t$ dan $B^t$.

![Cuplikan layar 2025-03-05 214817](https://hackmd.io/_uploads/S1ur4yUikg.png)

Nah, kalo kamu perhatikan kotak warna-warni pada matriks di atas, kamu pasti paham nih dengan polanya. Aku kasih contoh, ya. Coba kamu lihat matriks A dan $A^t$! Elemen-elemen baris ke-1 matriks $A^t$ (yang di kotak merah), itu merupakan pertukaran dari elemen-elemen kolom ke-1 matriks A. Begitu juga dengan elemen-elemen baris ke-2 matriks $A^t$ (yang di kotak biru), merupakan pertukaran dari elemen-elemen kolom ke-2 matriks A.

contoh soal di bawah ini. seperti yang di jalankan sebelumnya.

![Cuplikan layar 2025-03-05 215519](https://hackmd.io/_uploads/S1Ak8yUsJg.png)

 Sebetulnya, matriks itu materi yang mudah. Matriks bisa digunakan untuk menyelesaikan masalah sistem persamaan yang memiliki lebih dari dua variabel dengan cepat. Dibandingkan harus menggunakan metode substitusi atau eliminasi. Jadi, penting banget untuk memahami materi ini.
 
# sistem persamaan liear dengan menggunakan invers menggunakan obe (operasi baris elementer)
$\begin{align*}  
-7x_1 - 6x_2 - 12x_3 &= -33 \\
5x_1 + 5x_2 + 7x_3 &= 24 \\
x_1 + 4x_3 &= 5  
\end{align*}$

$A = \begin{bmatrix}  
-7 & -6 & -12 \\
5 & 5 & 7 \\
1 & 0 & 4  
\end{bmatrix}$

$x = \begin{bmatrix}  
x_1 \\
x_2 \\
x_3  
\end{bmatrix}$

$b = \begin{bmatrix}  
-33 \\
24 \\
5  
\end{bmatrix}$

Pertama Gabungkan matriks $\ [A]$ dengan matriks identitas $\ [I]$ untuk membentuk matriks augmented$\ [A | I]:$

$[A | I] = \begin{bmatrix}  
-7 & -6 & -12 & | & 1 & 0 & 0 \\
5 & 5 & 7 & | & 0 & 1 & 0 \\
1 & 0 & 4 & | & 0 & 0 & 1  
\end{bmatrix}$

pakai OBE jadi yang bagian kanan menjadi $(A^{-1}).$

Lalu kita Ubah Elemen (1,1) Menjadi 1 jadi Baris pertama dibagi dengan (-7):

$\begin{bmatrix}  
1 & \frac{6}{7} & \frac{12}{7} & \big| & -\frac{1}{7} & 0 & 0 \\
5 & 5 & 7 & \big| & 0 & 1 & 0 \\
1 & 0 & 4 & \big| & 0 & 0 & 1  
\end{bmatrix}$

Lalu Buat Elemen Kolom Pertama (2,1) dan (3,1) Menjadi 0

* Baris kedua: $( R_2 \to R_2 - 5R_1 )$
* Baris Ketiga: $( R_3 \to R_3 - R_1 )$

Hasilnya:

$\begin{bmatrix}  
1 & \frac{6}{7} & \frac{12}{7} & \big| & -\frac{1}{7} & 0 & 0 \\
0 & -\frac{1}{7} & -\frac{5}{7} & \big| & 1 & 0 & 0 \\
0 & -\frac{6}{7} & \frac{16}{7} & \big| & \frac{1}{7} & 0 & 1  
\end{bmatrix}$

Ubah Elemen (2,2) Menjadi 1 Kita bagi baris kedua dengan $( \frac{5}{7})$:

$\begin{bmatrix}  
1 & \frac{6}{7} & \frac{12}{7} & \big| & -\frac{1}{7} & 0 & 0 \\
0 & 1 & -\frac{1}{5} & \big| & 1 & \frac{7}{5} & 0 \\
0 & -\frac{6}{7} & \frac{16}{7} & \big| & \frac{1}{7} & 0 & 1  
\end{bmatrix}$

Setelah Itu Buat Elemen Kolom Kedua (1,2) dan (3,2) Menjadi 0

* Baris Pertama: $( R_1 \to R_1 - \frac{6}{7}R_2)$
* Baris Ketiga: $( R_3 \to R_3 + \frac{6}{7} R_2)$

Hasilnya:
$\begin{bmatrix}  
1 & 0 & \frac{18}{35} & \big| & -\frac{13}{35} & -\frac{42}{35} & 0 \\
0 & 1 & -\frac{1}{5} & \big| & 1 & \frac{7}{5} & 0 \\
0 & 0 & \frac{22}{35} & \big| & \frac{13}{22} & \frac{42}{22} & 1  
\end{bmatrix}$

Ubah Elemen (3,3) Menjadi 1 Kita bagi baris ketiga dengan $\left( \frac{22}{35} \right)$:

$\begin{bmatrix}  
1 & 0 & \frac{18}{35} & \big| & -\frac{13}{35} & -\frac{42}{35} & 0 \\
0 & 1 & -\frac{1}{5} & \big| & 1 & \frac{7}{5} & 0 \\
0 & 0 & 1 & \big| & \frac{13}{22} & \frac{42}{22} & \frac{35}{22}  
\end{bmatrix}$

Buat Elemen Kolom Ketiga (1,3) dan (2,3) Menjadi 0

* Baris Pertama: $( R_1 \to R_1 - \frac{18}{35}R_3)$
* Baris Kedua: $( R_2 \to R_2 + \frac{1}{5}R_3)$

Hasilnya:  

$\begin{bmatrix}  
1 & 0 & 0 & \big| & -3 & 5 & 2 \\
0 & 1 & 0 & \big| & 2 & 1 & 1 \\
0 & 0 & 1 & \big| & \frac{13}{22} & \frac{21}{11} & \frac{35}{22}  
\end{bmatrix}$  

Bagian kanan dari matriks ini adalah $( A^{-1} )$.  

Hitung $(x = A^{-1}b)$. Kita kalikan  $(A^{-1})$ dengan $(b)$:

$x = A^{-1}b = \begin{bmatrix}  
-3 \\
5 \\
2  
\end{bmatrix}$

Sehingga diperoleh:  
$x_1 = -3, \quad x_2 = 5, \quad x_3 = 2$

# Determinan Matriks
Determinan matriks adalah sebuah nilai skalar yang dihitung dari elemen-elemen suatu matriks persegi (matriks dengan jumlah baris dan kolom yang sama). Determinan digunakan dalam berbagai aplikasi matematika, seperti dalam mencari invers matriks, menyelesaikan sistem persamaan linear, dan menentukan apakah suatu matriks memiliki solusi unik.
Determinan matriks A ditulis sebagai $Det(A)$ atau $[A]$

Jika kita memiliki matriks A berukuran 2×2:

$A = \begin{bmatrix}  
a & b \\
c & d  
\end{bmatrix}$

Maka rumus determinannya adalah:

$\text{det}(A) = (a \times d) - (b \times c)$

**Contoh Perhitungan**

$A = \begin{bmatrix}  
1 & 2 \\
3 & 4  
\end{bmatrix}$

$\text{det}(A) = (1 \times 4) - (2 \times 3) = 4 - 6 = -2$

### Metode Sarrus (Hanya untuk Matriks 3×3)
Metode ini hanya berlaku untuk matriks berukuran 3×3.
Langkah-langkah:
1. Tuliskan ulang dua kolom pertama di sebelah kanan matriks.
2. Jumlahkan hasil perkalian diagonal utama, lalu kurangi hasil perkalian diagonal sekunder.
Rumus

    $\text{det}(A) = (a_{11}a_{22}a_{33} + a_{12}a_{23}a_{31} + a_{13}a_{21}a_{32}) - (a_{13}a_{22}a_{31} + a_{11}a_{23}a_{32} + a_{12}a_{21}a_{33})$

    **Contoh**
    
    $A = \begin{bmatrix} 
1 & 2 & 3 \\ 
4 & 5 & 6 \\ 
7 & 8 & 9 
\end{bmatrix}$

    Menggunakan metode Sarrus:
    
    $det(𝐴 )=(1⋅5⋅9+2⋅6⋅7+3⋅4⋅8)−(3⋅5⋅7+1⋅6⋅8+2⋅4⋅9)$
    
    $det(𝐴)= (45+84+96)−(105+48+72)=225−225=0$

### Sifat-Sifat Determinan
**Sifat Penting Determinan**
1. **Determinan Matriks Identitas:**
    det(𝐼)=1, di mana 𝐼 adalah matriks identitas.
1. **Baris atau Kolom Nol:**
    Jika ada baris atau kolom yang semuanya nol, maka det(𝐴)=0.
1. **Pertukaran Baris/Kolom:**
Jika dua baris atau kolom dipertukarkan, determinan berubah tanda.
1. **Kelipatan Baris/Kolom:**
Jika satu baris atau kolom dikalikan dengan skalar 𝑘, maka determinan menjadi 𝑘⋅det(𝐴).
1. **Matriks Singular:**
Jika det(𝐴)=0, maka matriks 𝐴 disebut singular (tidak memiliki invers).

**Mengapa Determinan Penting?**
* Digunakan untuk menentukan apakah suatu matriks memiliki invers $(det(𝐴)≠0)$.
* Digunakan dalam perhitungan invers matriks melalui rumus:

    $A^{-1} = \frac{1}{\det(A)} \cdot \text{adj}(A)$


### Minor Matriks
Minor dari suatu elemen $A_{ij}$ dalam matriks adalah determinan dari submatriks yang diperoleh dengan menghapus **baris ke-$i$ dan kolom ke-$j$** dari matriks asal.

Contoh Perhitungan Minor Matriks: Misalkan kita memiliki matriks $A$ berukuran 3×3:

$A = \begin{bmatrix}  
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9  
\end{bmatrix}$

Jika kita ingin mencari **Minor** $M_{11}$ (Minor dari elemen $A_{11}$ yaitu angka 1), maka **kita hapus baris pertama dan kolom pertama**, sehingga diperoleh submatriks:

$M_{11} = \begin{bmatrix}  
5 & 6 \\
8 & 9  
\end{bmatrix}$

Determinan dari submatriks ini adalah:

$\text{det}(M_{11}) = (5 \times 9) - (6 \times 8) = 45 - 48 = -3$

Jadi, Minor $M_{11} = -3$

### Cofaktor Matriks
Cofaktor dari elemen $A_{ij}$ Adalah **minor** $M_{ij}$ **dikalikan dengan tanda** $(-1)^{i+j}$

$C_{ij} = (-1)^{i+j} \times M_{ij}$

**Contoh Perhitungan Cofaktor Matriks:** Dari contoh sebelumnya, kita sudah menghitung **Minor** $M_{11} = -3.$

Sekarang, kita cari **Cofaktor** $C_{11}$

$C_{11} = (-1)^{1+1} \times (-3) = (1) \times (-3) = -3$

Sekarang, coba kita cari **Cofaktor** $C_{12}$ (elemen di baris ke-1, kolom ke-2, yaitu 2):
1. Hapus baris pertama dan kolom kedua, diperoleh submatriks:

    $M_{12} = \begin{bmatrix}  
4 & 6 \\
7 & 9  
\end{bmatrix}$

2. Hitung determinan:

    $\text{det}(M_{12}) = (4 \times 9) - (6 \times 7) = 36 - 42 = -6$
3. Hitung Cofaktor:

    $C_{12} = (-1)^{1+2} \times (-6) = (-1) \times (-6) = 6$
    
    Jadi, **Cofaktor** $C_{12}= 6$
###  Mencari Determinan dengan konsep Minor dan Confactor matrik. Beri contoh matrik 3x3 4x4 dan 5x5
1. **Determinan Matriks 3×3**

    $A = \begin{bmatrix}  
2 & 3 & 1\\
4 & 5 & 6\\ 
7 & 8 & 9
\end{bmatrix}$

    Rumus ekspansi kofaktor pada baris pertama:

    $\det(A) = a_{11}C_{11} + a_{12}C_{12} + a_{13}C_{13}$
$= 2C_{11} - 3C_{12} + 1C_{13}$

    Menghitung Minor dan Kofaktor:

    $M_{11} =
\begin{vmatrix} 5 & 6 \\ 8 & 9 \end{vmatrix}
= (5 \times 9 - 6 \times 8) = 45 - 48 = -3$

    $C_{11} = (-1)^{1+1} M_{11} = (-1)^2 (-3) = -3$

    $M_{12} =\begin{vmatrix} 4 & 6 \\ 7 & 9 \end{vmatrix}
= (4 \times 9 - 6 \times 7) = 36 - 42 = -6$

    $C_{12} = (-1)^{1+2} M_{12} = (-1)^3 (-6) = 6$

    $M_{13} = \begin{vmatrix} 4 & 5 \\ 7 & 8 \end{vmatrix}= (4 \times 8 - 5 \times 7) = 32 - 35 = -3$

    $C_{13} = (-1)^{1+3} M_{13} = (-1)^4 (-3) = -3$

    Menghitung Determinan:

    $\det(A) = (2 \times -3) + (-3 \times 6) + (1 \times -3)$

    $= -6 - 18 - 3 = \mathbf{-27}$

2. **Determinan Matriks 4×4**

    $B =
\begin{bmatrix} 
1 & 2 & 3 & 4 \\ 
5 & 6 & 7 & 8 \\ 
9 & 10 & 11 & 12 \\ 
13 & 14 & 15 & 16 
\end{bmatrix}$

    Rumus ekspansi kofaktor pada baris pertama:

    $\det(B) = 1C_{11} - 2C_{12} + 3C_{13} - 4C_{14}$

    * **Langkah 1: Hitung Minor dan Kofaktor**

        * Hitung $C_{11}$ (Minor dari elemen $B_{11} = 1)

            $M_{11} =
\begin{vmatrix} 
6 & 7 & 8 \\ 
10 & 11 & 12 \\ 
14 & 15 & 16 
\end{vmatrix}$

            Gunakan ekspansi kofaktor kembali untuk menentukan determinan $M_{11}$ dengan cara yang sama seperti contoh matriks 3×3.

            $M_{11} = (6 \times (11 \times 16 - 12 \times 15)) - (7 \times (10 \times 16 - 12 \times 14)) + (8 \times (10 \times 15 - 11 \times 14))$
    
            Hitung determinan matriks 3×3 dengan ekspansi kofaktor pada baris pertama:
    
            $\det(M_{11}) = 6 
\begin{vmatrix} 
11 & 12 \\ 
15 & 16 
\end{vmatrix}$

            $- 7 
\begin{vmatrix} 
10 & 12 \\ 
14 & 16 
\end{vmatrix}$

            $+ 8 
\begin{vmatrix} 
10 & 11 \\ 
14 & 15 
\end{vmatrix}$

            $= 6(11 \times 16 - 12 \times 15) - 7(10 \times 16 - 12 \times 14) + 8(10 \times 15 - 11 \times 14)$
            $= 6(176 - 180) - 7(160 - 168) + 8(150 - 154)$
            $= 6(-4) - 7(-8) + 8(-4)$
            $= -24 + 56 - 32 = 0$

            Karena $M_{11} = 0,$ maka $C_{11} = (-1)^{1+1} (0) = 0.$
    
        * Hitung $C_{12}$ (Minor dari elemen $B_{12} = 2)$

            $M_{12} =
\begin{vmatrix}
5 & 7 & 8 \\
9 & 11 & 12 \\
13 & 15 & 16
\end{vmatrix}$
    
            Hitung determinan matriks 3×3 dengan cara yang sama:
    
            $\det(M_{12}) = 5(11 \times 16 - 12 \times 15) - 7(9 \times 16 - 12 \times 13) + 8(9 \times 15 - 11 \times 13)$
            $= 5(-4) - 7(-12) + 8(-6)$
            $= -20 + 84 - 48 = 16$
            $C_{12} = (-1)^{1+2} (16) = -16$
    
        * Hitung $C_{13}$
    
            $M_{13} =
\begin{vmatrix}
5 & 6 & 8 \\
9 & 10 & 12 \\
13 & 14 & 16
\end{vmatrix}$

            $\det(M_{13}) = 5(10 \times 16 - 12 \times 14) - 6(9 \times 16 - 12 \times 13) + 8(9 \times 14 - 10 \times 13)$
            $= 5(-8) - 6(-12) + 8(-4)$
            $= -40 + 72 - 32 = 0$
            $= -40 + 72 - 32 = 0$
    
        * Hitung $C_{14}$
    
            $M_{14} =
\begin{vmatrix}
5 & 6 & 7 \\
9 & 10 & 11 \\
13 & 14 & 15
\end{vmatrix}$

            $\det(M_{14}) = 5(10 \times 15 - 11 \times 14) - 6(9 \times 15 - 11 \times 13) + 7(9 \times 14 - 10 \times 13)$ 
            $= 5(-4) - 6(-12) + 7(-4)$
            $= -20 + 72 - 28 = 24$ 
            $C_{14} = (-1)^{1+4}(24) = 24$
    
    * **Langkah 2: Hitung Determinan**
    
        $\det(B) = 1(0) - 2(-16) + 3(0) - 4(24)$
        $= 0 + 32 + 0 - 96$
        $= -64$
    
3. **Determinan Matriks 5×5**
    Matriks:
    
    $C =
\begin{bmatrix} 
2 & 3 & 1 & 4 & 5 \\ 
6 & 7 & 8 & 9 & 10 \\ 
11 & 12 & 13 & 14 & 15 \\ 
16 & 17 & 18 & 19 & 20 \\ 
21 & 22 & 23 & 24 & 25
\end{bmatrix}$

    Gunakan ekspansi kofaktor pada baris pertama:

    $\det(C) = 2C_{11} - 3C_{12} + 1C_{13} - 4C_{14} + 5C_{15}$
    
    Untuk menghitung setiap $C_{1j}$, kita harus menentukan $M_{1j}$, yang merupakan determinan matriks 4×4. Prosesnya sama seperti sebelumnya, menggunakan ekspansi kofaktor lagi.
    
    $M_{11} =
\begin{vmatrix} 
7 & 8 & 9 & 10 \\ 
12 & 13 & 14 & 15 \\ 
17 & 18 & 19 & 20 \\ 
22 & 23 & 24 & 25 
\end{vmatrix}$
    
    Gunakan ekspansi kofaktor lagi untuk menghitung determinan matriks 4×4, lalu gunakan hasil tersebut untuk mendapatkan det(C).


# Refrensi
https://id.wikipedia.org/wiki/Matriks_(matematika)

https://www.ruangguru.com/blog/mengenal-matriks-dalam-matematika-pengertian-jenis-dan-transpose
