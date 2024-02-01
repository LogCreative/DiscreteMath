# 第 1 次作业
*Log Creative*

1.（2）“12是质数”是命题，真值为假。
（4）“$x+y=2$”不是命题。因为不能确定真值。
（6）“结果对吗？”不是命题，它是疑问句。
（8）“假如明天是星期日，那么学校放假。”是命题，一般情况下是真值（法定节假日调休除外）。

4.（2）$\neg ((P\vee Q)\rightarrow (Q\vee P))$是永假式。证明：$P\vee Q=Q\vee P\Rightarrow (P\vee Q)\rightarrow (Q\vee P)=1\Rightarrow \neg ((P\vee Q)\rightarrow (Q\vee P))=0$.

(4) $(Q\rightarrow R)\rightarrow((P\rightarrow Q)\rightarrow (P\rightarrow R))$是重言式。

|$P$| $Q$| $R$ |$(Q\rightarrow R)$| $(P\rightarrow Q)\rightarrow (P\rightarrow R)$| $(Q\rightarrow R)\rightarrow((P\rightarrow Q)\rightarrow (P\rightarrow R))$|
|----|----|-----|-----|----|----|
|T|T|T|T|T|T|
|T|T|F|F||T|
|T|F|T|T|T|T|
|T|F|F|T|T|T|
|F|T|T|T|T|T|
|F|T|F|F||T|
|F|F|T|T|T|T|
|F|F|F|T|T|T|

(6)$(P\wedge Q)\rightarrow (P\vee Q)$是重言式。

|$P$|$Q$|$P\wedge Q$|$P\vee Q$|$(P\wedge Q)\rightarrow (P\vee Q)$|
|---|---|---|---|---|
|T|T|T|T|T|
|T|F|F||T|
|F|T|F||T|
|F|F|F||T|

5.(2)$R$：他个子高但不很胖。\
$P$：他个子高。\
$Q$：他很胖。\
则$R=P\wedge \neg Q$。

(4)$R$：他个子不高也不胖。\
$P$：他个子高。\
$Q$：他胖。\
则$R=\neg P\wedge \neg Q$。

(6)$R$：他个子矮或他不很胖都是不对的。\
$P$：他个子矮。\
$Q$：他很胖。\
则$R=\neg(P \vee \neg Q$)。

(8)$R$：如果嫦娥是虚构的，而如果圣诞老人也是虚构的，那么许多孩子受骗了。\
$P$：嫦娥是虚构的\
$Q$：圣诞老人也是虚构的。\
$S$：许多孩子受骗了。\
则$R=((P\wedge Q)\rightarrow S)$。