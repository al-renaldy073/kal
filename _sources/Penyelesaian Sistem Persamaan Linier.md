---
title: Penyelesaian Sistem Persamaan Linier

---

## Penyelesaian Sistem Persamaan Linier
### Operasi Baris Elemeneter
### Eleminasi Gauss


---

**Contoh Soal 1**
Selesaikan dengan menggunakan eleminasi gauss

$$
\begin{array}{cc}
x_1 + 2x_2 + 3x_3=6\\
2x_1 +4x_2+6x_3=12\\
x_3 + x_2 =2\\
\end{array}
$$

**Jawaban:**

**Langkah 1: Tulis dalam bentuk matriks**
\begin{bmatrix}
1 & 2 & 3 &| & 6 \\
2 & 4 & 6 &| & 12 \\
0 & 1 & 1 &| & 2
\end{bmatrix}

**Langkah 2: Eliminasi**
* Baris 2 dikurangi 2 × Baris 1 untuk membuat elemen (2,1) menjadi 0:
\begin{bmatrix}
1 & 2 & 3 &| & 6 \\
0 & 0 & 0 &| & 0 \\
0 & 1 & 1 &| & 2
\end{bmatrix}

* Baris kedua semuanya nol, artinya persamaan kedua tidak memberikan informasi tambahan.


**Langkah 3: Substitusi Balik**
Dari baris 3:
\begin{align*}
x_2 + x_3 &= 2 \Rightarrow x_3 = 2 - x_2 \\
\end{align*}
Dari baris 1:
\begin{align*}
x_1 + 2x_2 + 3(2 - x_2) &= 6 \\
x_1 + 2x_2 + 6 - 3x_2 &= 6 \\
x_1 - x_2 &= 0 \Rightarrow x_1 = x_2
\end{align*}
Solusi Umum:
\begin{aligned}
x_1 = x_2, \quad x_3 = 2 - x_2
\end{aligned}


Solusi berbentuk parametrik dengan $x_2$ sebagai variabel bebas.

---

**Contoh soal 2**
Selesaikan dengan menggunakan eleminasi gauss

$$
\begin{array}{cc}
x_1 + x_2 + x_3=3\\
2x_1 +x_3=5\\
x_1 + 2x_2 =3\\
\end{array}
$$

**Jawaban:**
**Langkah 1: Matriks Awal**
\begin{bmatrix}
1 & 1 & 1 &| & 3 \\
2 & 0 & 1 &| & 5 \\
0 & 1 & 1 &| & 3
\end{bmatrix}

**Langkah 2: Eliminasi**
* Baris 2 dikurangi 2 × Baris 1:
\begin{bmatrix}
1 & 1 & 1 &| & 3 \\
0 & -2 & -1 &| & -1 \\
0 & 1 & 1 &| & 3
\end{bmatrix}
* Baris 3 dikurangi Baris 1:
\begin{bmatrix}
1 & 1 & 1 &| & 3 \\
0 & -2 & -1 &| & -1 \\
0 & 1 & -1 &| & 0
\end{bmatrix}
* Baris 3 dikali 2 dan ditambahkan ke Baris 2 untuk menghilangkan elemen (2,2):
\begin{bmatrix}
1 & 1 & 1 &| & 3 \\
0 & 0 & -3 &| & -1 \\
0 & 1 & -1 &| & 0
\end{bmatrix}

**Langkah 3: Substitusi Balik**
* Dari baris 3: $x_2 - x_3 = 0 \Rightarrow x_2 = x_3.$
* Dari baris 2: $-3x_3 = -1 \Rightarrow x_3 = \frac{1}{3},$ sehingga $x_2 = \frac{1}{3}$
* Dari baris 1: \begin{align*}
x_1 + \frac{1}{3} + \frac{1}{3} &= 3 \\
x_1 + \frac{2}{3} &= 3 \\
x_1 &= \frac{7}{3}
\end{align*}

**Solusi Akhir:**

\begin{align*}
(x_1, x_2, x_3) = \left( \frac{7}{3}, \frac{1}{3}, \frac{1}{3} \right)
\end{align*}



---

**Contoh soal 3**
Selesaikan dengan menggunakan eleminasi gauss

$$
\begin{array}{cc}
2x_1 + 2x_2 =y\\
x_1 +x_2=2\\
\end{array}
$$

**Jawaban:**

**Langkah 1: Matriks**
\begin{bmatrix}
2 & 2 & | & y \\
1 & 1 & | & 2 
\end{bmatrix}

**Langkah 2: Eliminasi**
* Baris 1 dikurangi 2 × Baris 2:
\begin{bmatrix}
0 & 0 & | & y-4 \\
1 & 1 & | & 2 
\end{bmatrix}

Agar sistem punya solusi, harus $y-4=0 \Rightarrow y=4.$

**Solusi:**
Jika $y=4$, sistem menjadi:

$$
\begin{array}{cc}
x_1 + x_2 =2\\
\end{array}
$$

Solusinya adalah:

$$
\begin{array}{cc}
x_1 + 2 =x_2\\
\end{array}
$$

dengan $x_2$ sebagai variabel bebas.

---

**Contoh soal 4**
Selesaikan dengan menggunakan eleminasi gauss

$$
\begin{array}{cc}
x_1 + x_2 =5\\
x_1 +2x_3=6\\
\end{array}
$$

**Langkah 1: Matriks**
\begin{bmatrix}
1 & 1 & 0 &| & 5 \\
1 & 0 & 2 &| & 6 
\end{bmatrix}

**Langkah 2: Eliminasi**
* Baris 2 dikurangi Baris 1:
\begin{bmatrix}
1 & 1 & 0 &| & 5 \\
0 & -1 & 2 &| & 1 
\end{bmatrix}

* Kalikan Baris 2 dengan -1:
\begin{bmatrix}
1 & 1 & 0 &| & 5 \\
0 & 1 & -2 &| & 1 
\end{bmatrix}

**Langkah 3: Substitusi Balik**
* Dari Baris 2: $x_2 = 2x_3 - 1$
* Dari Baris 1: $x_1 + (2x_3 - 1) = 5$


\begin{aligned}
x_1 &= 6 - 2x_3 \\ x_2 &= 2x_3 - 1
\end{aligned}

dengan $x_3$ sebagai variabel bebas.
