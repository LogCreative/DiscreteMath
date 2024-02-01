4.设$A=\{1,2,3\}$，在$A$上有多少种不同的关系？设$\mid A\mid=n$，在$A$上有多少种不同的关系？

3个元素之间的关系可以组成$3^2=9$对，每一对都可以有相连（1）和不相连（0），所以共有$2^9=512$种关系。

如果$\mid A\mid=n$，则有$2^{n^2}$种关系。

7.对$A=\{0,1,2,3,4\}$上的下列关系，给出关系图和关系矩阵。

（2）$R_2=\{ \langle x,y \rangle \mid 0\leq x-y<3 \}$

$\left(\begin{matrix}
    1 & 0 & 0 & 0 & 0 \\
    1 & 1 & 0 & 0 & 0 \\
    1 & 1 & 1 & 0 & 0 \\
    0 & 1 & 1 & 1 & 0 \\
    0 & 0 & 1 & 1 & 1 \\
\end{matrix}\right)$

有一个图

9.设$A=\{\langle \varnothing,\{ \varnothing,\{ \varnothing \} \} \rangle ,\langle \{ \varnothing \},\varnothing \rangle  \}$，写出$A\circ A,A^{-1},A\uparrow \varnothing,A\uparrow\{\varnothing\},A\uparrow\{\varnothing,\{ \varnothing \}\},A[\varnothing],A[\{ \varnothing \}],A[\{\varnothing, \{ \varnothing\}\}]$。

$A\circ A=\{ \langle \{ \varnothing \}, \{ \varnothing,\{ \varnothing \} \}\rangle \}$

$A^{-1}=\{\langle \{ \varnothing,\{ \varnothing \} \},\varnothing \rangle ,\langle \varnothing,\{ \varnothing \} \rangle  \}$

$A\uparrow \varnothing=\varnothing$，因为$\varnothing$中没有元素。

$A\uparrow\{\varnothing\}=\{\langle \varnothing,\{ \varnothing,\{ \varnothing \} \} \rangle\}$

$A\uparrow\{\varnothing,\{ \varnothing \}\}=\{\langle \varnothing,\{ \varnothing,\{ \varnothing \} \} \rangle ,\langle \{ \varnothing \},\varnothing \rangle  \}=A$

$A[\varnothing]=\varnothing$，因为$\varnothing$中没有元素。

$A[\{ \varnothing \}]=\{\{ \varnothing,\{ \varnothing \} \}\}$

$A[\{\varnothing, \{ \varnothing\}\}]=\{\{ \varnothing,\{ \varnothing \} \},\varnothing \}$

13.对$A$到$B$的关系$R$，$a\in A$，定义$B$的一个子集$R(a)=\{b\mid aRb\}$。在$C=\{-4,-3,-2,-1,0,1,2,3,4\}$上定义

$R=\{ \langle x,y \rangle \mid x<y\}\\S=\{ \langle x,y \rangle\mid x-1<y<x+2 \}\\T=\{ \langle x,y \rangle \mid x^2\leq y \}$

写出集合$R(0),R(1),S(0),S(-1),T(0),T(-1)$。

$R(0)=\{1,2,3,4\}\\R(1)=\{2,3,4\}\\S(0)=\{0,1 \}\\S(-1)=\{ -1,0 \}\\T(0)=\{0,1,2,3,4\}\\T(-1)=\{1,2,3,4\}$