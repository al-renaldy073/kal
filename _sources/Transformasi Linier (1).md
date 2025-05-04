---
title: Transformasi Linier

---

# Pembuktian Transformasi Linier
Untuk membuktikan bahwa transformasi linier $T : \mathbb{R}^2 \to \mathbb{R}^2$ yang dinyatakan dengan matriks

$A = \begin{bmatrix}
\cos \theta & -\sin \theta \\
\sin \theta & \cos \theta
\end{bmatrix}$

memiliki sifat rotasi dalam $\mathbb{R}^2$ berlawanan arah jarum jam dengan sudut $\theta$, kita dapat menggunakan koordinat polar.

Langkah-langkah Pembuktian:
1. **Representasi Vektor dalam Koordinat Polar:**
Misalkan vektor $\mathbf{v}=(x,y)$ direpresentasikan dalam koordinat polar sebagai:
$\begin{align*}
x &= r \cos \alpha, \\
y &= r \sin \alpha
\end{align*}$
di mana $r$ adalah panjang vektor $\mathbf{v}$, dan $\alpha$ adalah sudut antara $\mathbf{v}$ dengan sumbu $x$.
1. **Transformasi Vektor:**
Transformasi linier $T$ diaplikasikan pada $\mathbf{v}$ menghasilkan vektor baru $\mathbf{v'} = (x', y')$
$\mathbf{v'} = A \mathbf{v} = \begin{bmatrix}
\cos \theta & -\sin \theta \\
\sin \theta & \cos \theta
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}
= \begin{bmatrix}
x \cos \theta - y \sin \theta \\
x \sin \theta + y \cos \theta
\end{bmatrix}$

1. **Substitusi Koordinat Polar:**
Substitusi $x = r \cos \alpha$ dan $y = r \sin \alpha$ ke dalam $\mathbf{v'}$

    $x' = r \cos \alpha \cos \theta - r \sin \alpha \sin \theta = r (\cos \alpha \cos \theta - \sin \alpha \sin \theta) = r \cos (\alpha + \theta)$
$y' = r \cos \alpha \sin \theta + r \sin \alpha \cos \theta = r (\cos \alpha \sin \theta + \sin \alpha \cos \theta) = r \sin (\alpha + \theta)$

    Di sini, kita menggunakan identitas trigonometri:
    
    $\begin{align*}
\cos(\alpha + \theta) &= \cos \alpha \cos \theta - \sin \alpha \sin \theta \\
\sin(\alpha + \theta) &= \sin \alpha \cos \theta + \cos \alpha \sin \theta
\end{align*}$

    Hasil transformasi $v' = (x', y')$ dapat ditulis sebagai:
    
    $\begin{align*}
x' = r \cos(\alpha + \theta), \\
y' = r \sin(\alpha + \theta)
\end{align*}$

    Ini menunjukkan bahwa vektor $\mathbf{v}$ dirotasi sebesar sudut $\theta$ berlawanan arah jarum jam, karena sudut baru vektor $\mathbf{v'}$ adalah $\alpha + \theta$. Panjang vektor tetap $r$, yang berarti rotasi tidak mengubah panjang vektor.

**Kesimpulan:**
Matriks $A$ merepresentasikan transformasi rotasi dalam $\mathbb{R}^2$ sebesar sudut $\theta$ berlawanan arah jarum jam. Pembuktian ini menggunakan koordinat polar dan identitas trigonometri untuk menunjukkan bahwa aplikasi $A$ pada vektor $\mathbf{v}$ menghasilkan rotasi sudut $\theta$ tanpa mengubah panjang vektor.

Transformasi linier $T$ dengan matriks $A$ adalah rotasi sebesar $\theta$ berlawanan arah jarum jam.
 

