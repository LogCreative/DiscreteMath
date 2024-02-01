4.设$f:\mathbf{N}\rightarrow\mathbf{N},f(x)=\begin{cases}
    1 & \text{当}x\text{是奇数,} \\
    \frac{x}{2} & \text{当}x\text{是偶数.} \\
\end{cases}$

求$f(0),f[\{0\}],f[\{0,2,4,6,\cdots\}],f[\{1,3,5,\cdots\}],f^{-1}[\{2\}],f^{-1}[\{3,4\}]$。

$\begin{aligned}
    f(0)&=0\\
    f[\{0\}]&=\{0\}\\
    f[\{0,2,4,6,\cdots\}]&=\{0,1,2,3,\cdots\}\\
    f[\{1,3,5,\cdots\}]&=\{1\}\\
    f^{-1}[\{2\}]&=\{4\}\\
    f^{-1}[\{3,4\}]&=\{6,8\}
\end{aligned}$

5.对下列函数分别确定：

(a)是否是满射的、单射的；如果是双射的，写出$f^{-1}$的表达式.

(b)写出函数的象和对给定集合$S$的完全原象.

(c)关系$R=\{\langle x,y \rangle|x,y\in\text{dom}(f)\wedge f(x)=f(y)\}$是$\text{dom}(f)$上的等价关系，一般称为由函数$f$导出的等价关系，求$R$.

(4)$f:\mathbf{N}\rightarrow\mathbf{N}\times\mathbf{N},f(n)=\langle n,n+1 \rangle,S=\{\langle 2,2 \rangle\}$

(a)不是满射，是单射。
(b)$f[\mathbf{N}]=\{\langle n,n+1 \rangle|n\in \mathbf{N}\};f^{-1}(S)=\varnothing$.
(c)$R=I_{\mathbf{N}}$

(5)$f:[0,1]\rightarrow[0,1],f(x)=\frac{2x+1}{4},S=\left[0,\frac{1}{2}\right]$.

(a)不是满射，是单射。
(b)$f([0,1])=[\frac{1}{4},\frac{3}{4}];f^{-1}(S)=[0,\frac{1}{2}]$
(c)$R_{[0,1]}$

11.对$f:A\rightarrow B$，定义$g:B\rightarrow P(A)$为$g(b)=\{x|x\in A\wedge f(x)\in b\}$.

证明：若$f$是满射的，则$g$是单射的。其逆是否成立？

证明：
对$\forall b_1,b_2\in B\wedge b_1\neq b_2,g(b_1)=\{x|x\in A\wedge f(x)\in b_1\};g(b_2)=\{x|x\in A\wedge f(x)\in b_2\}$

若$f$是满射的：$\exists a_1,a_2\in A:f(a_1)=b_1,f(a_2)=b_2$,如果$a_1=a_2$而$b_1\neq b_2$，那么$f$将不是函数，所以$a_1\neq a_2$。所以$g(b_1)\neq g(b_2)$，$g$是单射的。

逆不成立。对$\forall b\in B$，$g(b)$只能保证是独特的，并且$g(b)=\varnothing$是可以成立的，就不能保证$f$是满射的。

12.设$f:A\rightarrow B,g:C\rightarrow D,f\subseteq g,C\subseteq A$，证明：$f=g$.

证明：$\forall c\in C\subseteq A,f(c)=b,g(c)=d.f\subseteq g\Rightarrow b=d$

$a\in A-C$,若$f(a)$存在，而$f\subseteq g$，矛盾。所以$A=C$。

所以$f=g$。