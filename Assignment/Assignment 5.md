5.(2) 凡有理数都可写成分数。

$P(x)$表示“$x$是有理数”，$Q(x)$表示是“$x$是分数”，则
$$
(\forall x)(P(x)\rightarrow Q(x))
$$

(6) 凡实数都能比较大小。

$P(x)$表示“$x$是实数”，$Q(x,y)$表示“$x,y$可以比较大小”，则
$$
(\forall x)(\forall y)(P(x)\wedge P(y)\rightarrow Q(x,y))
$$

7.设个体域为$\{ a,b,c\}$，试将下列公式写成命题逻辑公式

(10)$(\forall y)((\exists x)P(x,y)\rightarrow (\forall x)Q(x,y))$

$(\forall y)((\exists x)P(x,y)\rightarrow (\forall x)Q(x,y))=(\forall y)(P(a,y)\vee P(b,y)\vee P(c,y)\rightarrow Q(a,y)\wedge Q(b,y)\wedge Q(c,y))=(P(a,a)\vee P(b,a)\vee P(c,a)\rightarrow Q(a,a)\wedge Q(b,a)\wedge Q(c,a))\wedge(P(a,b)\vee P(b,b)\vee P(c,b)\rightarrow Q(a,b)\wedge Q(b,b)\wedge Q(c,b))\wedge(P(a,c)\vee P(b,c)\vee P(c,c)\rightarrow Q(a,c)\wedge Q(b,c)\wedge Q(c,c))$

8.判断下列公式是普遍有效的，不可满足的还是可满足的？

(2)$(\exists x)(P(x)\wedge Q(x))\rightarrow((\exists x)P(x)\wedge (\exists x)Q(x))$

普遍有效。$(\exists x)(P(x)\wedge Q(x))=\text{T}$意味着存在一个$x_0$使得$P(x_0)=\text{T}$而且$Q(x_0)=\text{T}$，也就是$((\exists x)P(x)\wedge (\exists x)Q(x))=\text{T}$，所以普遍有效。

(6)$(\forall x)(P(x)\vee \neg P(x))$

普遍有效。因为$P(x)=\text{T}$时，$\neg P(x)=\text{F}$；$P(x)=\text{F}$时，$\neg P(x)=\text{T}$，所以$P(x)\vee \neg P(x)=\text{T}$，也就是$(\forall x)(P(x)\vee \neg P(x))=\text{T}$，所以普遍有效。

(7)$((\exists x)P(x)\wedge(\exists x)Q(x))\rightarrow (\exists x)(P(x)\wedge Q(x))$

可满足的。只有满足$P(x_0)=\text{T}$的$x_0$能够使$Q(x_0)=\text{T}$,式子才能成立。

10.设个体域为$\{a,b\}$，并对$P(x,y)$设定为$P(a,a)=\text{T},P(a,b)=\text{F},P(b,a)=\text{F},P(b,b)=\text{T}$计算下列公式的真值。

(1)$(\forall x)(\exists y)P(x,y)=(\forall x)(P(x,a)\vee P(x,b))=\text{T}$

(3)$(\forall x)(\forall y)P(x,y)=(\forall x)(P(x,a)\wedge P(x,b))=\text{F}$

(5)$(\exists y)\neg P(a,y)=\neg P(a,a)\vee\neg P(a,b)=\text{T}$

(7)$(\forall x)(\forall y)(P(x,y)\rightarrow P(y,x))=\text{T}$，由于$(\forall x)(\forall y)(P(a,b)=P(b,a))$
