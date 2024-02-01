1.证明下列等值式和蕴含式

(1)$\neg (\exists x)(\exists y)(P(x)\wedge P(y)\wedge Q(x)\wedge Q(y)\wedge R(x,y))=(\forall x)(\forall y)((P(x)\wedge P(y)\wedge Q(x)\wedge Q(y))\rightarrow \neg R(x,y))$

证明：
$(\forall x)(\forall y)((P(x)\wedge P(y)\wedge Q(x)\wedge Q(y))\rightarrow \neg R(x,y))=(\forall x)(\forall y)(\neg (P(x)\wedge P(y)\wedge Q(x)\wedge Q(y))\vee \neg R(x,y))=(\forall x)(\forall y)\neg(P(x)\wedge P(y)\wedge Q(x)\wedge Q(y)\wedge R(x,y))=(\forall x)\neg(\exists x)(P(x)\wedge P(y)\wedge Q(x)\wedge Q(y)\wedge R(x,y))=\neg(\exists x)(\exists x)(P(x)\wedge P(y)\wedge Q(x)\wedge Q(y)\wedge R(x,y))$

(3)$(\forall x)(P(x)\vee q)\rightarrow (\exists x)(P(x)\wedge q)=((\exists x)\neg P(x)\wedge \neg q)\vee ((\exists x)P(x)\wedge q)$

$(\forall x)(P(x)\vee q)\rightarrow (\exists x)(P(x)\wedge q)=\neg ((\forall x)(P(x)\vee q))\vee ((\exists x)(P(x)\wedge q))=(\exists x)\neg(P(x)\vee q)\vee((\exists x)P(x)\wedge q)=(\exists x)(\neg P(x)\wedge \neg q)\vee((\exists x)P(x)\wedge q)$

(5) $(\forall x)P(x)\rightarrow q=(\exists x)(P(x)\rightarrow q)$

$(\forall x)P(x)\rightarrow q=\neg ((\forall x)P(x))\vee q=(\exists x)\neg P(x)\vee q=(\exists x)(\neg P(x)\vee q)=(\exists x)(P(x)\rightarrow q)$

2.判断下列各公式哪些是普遍有效的并给出证明，不是普遍有效的举出反例。

(2)$((\exists x)P(x)\leftrightarrow (\exists x)Q(x))\rightarrow (\exists x)(P(x)\leftrightarrow Q(x))$

不是普遍有效的。

在$\{1,2\}$上分析，$P(1)=Q(2)=\text{T},P(2)=Q(1)=\text{F}$，左边成立，但右边发现并不存在一个$x_0\in\{1,2\}使得P(x)\leftrightarrow Q(x)=\text{T}$。

(4)$(\forall x)(P(x)\rightarrow Q(x))\rightarrow((\exists x)P(x)\rightarrow (\forall x)Q(x))$

不是普遍有效的。

在$\{1,2\}$上分析，$P(1)=Q(1)=\text{F},P(2)=Q(2)=\text{T}$，$P(2)\rightarrow Q(1)=\text{F}$

4.求下列(2)的前束范式，(9)的 Skolem 范式（只含$\forall$）

(2) $(\forall x)(\forall y)(\forall z)(P(x,y,z)\wedge ((\exists u)Q(x,u)\rightarrow (\exists w)Q(y,w)))$

$(\forall x)(\forall y)(\forall z)(P(x,y,z)\wedge ((\exists u)Q(x,u)\rightarrow (\exists w)Q(y,w)))=(\forall x)(\forall y)(\forall z)(P(x,y,z)\wedge (\neg ((\exists u)Q(x,u))\vee (\exists w)Q(y,w)))=(\forall x)(\forall y)(\forall z)(P(x,y,z)\wedge ((\forall u)(\neg Q(x,u))\vee (\exists w)Q(y,w)))=(\forall x)(\forall y)(\forall z)(P(x,y,z)\wedge ((\forall u)(\exists w)(\neg Q(x,u)\vee Q(y,w))))=(\forall x)(\forall y)(\forall z)(\forall u)(\exists w)(P(x,y,z)\wedge (\neg Q(x,u)\vee Q(y,w)))$

(9) $(\forall x)(P(x)\rightarrow (\exists y)Q(x,y))\vee (\forall z)R(z)$

$(\forall x)(P(x)\rightarrow (\exists y)Q(x,y))\vee (\forall z)R(z)=(\forall x)(\neg P(x)\vee (\exists y)Q(x,y))\vee (\forall z)R(z)=(\forall x)(\exists y)(\neg P(x)\vee Q(x,y))\vee (\forall z)R(z)=(\forall x)(\exists y)(\forall z)(\neg P(x)\vee Q(x,y)\vee R(z))=(\forall x)(\forall z)(\neg P(x)\vee Q(x,f(x))\vee R(z))$
