2.由下列真值表,分别从T和F来列写出$A$,$B$和$C$的表达式,并分别以符号$m_i$和$M_i$表示.
|$P$|$Q$|$A$|$B$|$C$|
|---|---|---|---|---|
|F|F|T|T|T|
|F|T|T|F|F|
|T|F|T|F|F|
|T|T|F|T|F|

$A=P\uparrow Q=\neg P \vee \neg Q=M_0=\neg(P\wedge Q)=\neg m_3=\vee_{0,1,2}$

$B=P\leftrightarrow Q=(\neg P \wedge \neg Q)\vee (P \wedge Q)=m_0\vee m_3=\vee_{0,3}=(P \vee \neg Q)\wedge (\neg P\vee Q)=M_1\wedge M_2=\wedge_{1,2}$

$C=P\downarrow Q=\neg P\wedge \neg Q=m_0=\neg (P\vee Q)=\neg M_3=\wedge_{0,1,2}$

4.证明

(1)$A→B$与$B^*→A^*$同永真、同可满足

通过证明重言蕴含来同时证明两者。

若$A\rightarrow B$真，则$\neg B\rightarrow \neg A$真。（逆否命题）
而$\neg A=A^{*-},\neg B=B^{*-}$，则$B^{*-}\rightarrow A^{*-}$真。（置换规则）
则假设$A=A(P_1,P_2,\cdots,P_n)$，$A^-=A(\neg P_1,\neg P_2,\cdots,\neg P_n)$，其中$P_i(i=1,2,\cdots,n)$是任意的命题，可以将$\neg P_i$代入后者，将得到$A$，也就意味着$B^*\rightarrow A^*$真。也就是

$A\rightarrow B\Rightarrow B^*\rightarrow A^*$

如果$B^*\rightarrow A^*$真，则$(A^*)^*\rightarrow (B^*)^*$永真。（上一个结论）
则$A\rightarrow B$真。（$(A^*)^*=A$)
也就是

$B^*\rightarrow A^* \Rightarrow A\rightarrow B$

综合两式，有

$A\rightarrow B\Leftrightarrow B^*\rightarrow A^*$

(i) 同永真：如果$A→B$永真，则根据永真蕴含的定义，$B^*→A^*$也将永真。反之亦然。

(ii) 同可满足：

如果$A(a_1,a_2,\cdots,a_n),B(b_1,b_2,\cdots,b_n)$是满足$A→B$真的一个条件，则根据永真蕴含的定义，$B^*→A^*$也将真。反之亦然。

(2)$A\leftrightarrow B$与$A^*\leftrightarrow B^*$同永真、同可满足

同样地，若$A\leftrightarrow B$真，则$A=B$(等值定理)，$\neg A=\neg B$(同真假),$\neg A\leftrightarrow \neg B$真(等值定理)。

之后，根据类似的推理，$A^{*-}\leftrightarrow B^{*-},A^{*}\leftrightarrow B^{*}$，也就是

$A\leftrightarrow B \Rightarrow A^*\leftrightarrow B^*$

反之，$A^*\leftrightarrow B^*$真，则$(A^*)^*\leftrightarrow (B^*)^*$真，$A\leftrightarrow B$真，也就是

$A^*\leftrightarrow B^* \Rightarrow A\leftrightarrow B$

综合两个式子有

$A\leftrightarrow B \Leftrightarrow A^*\leftrightarrow B^*$

故两者同永真，同可满足。

5.给出下列各公式的合取范式、析取范式、主合取范式和主析取范式。并给出所有使公式为真的解释。

(4) $(P\wedge Q)\vee (\neg P\wedge Q \wedge R)$

$(P\wedge Q)\vee (\neg P\wedge Q \wedge R)(析取范式)=(P\vee \neg P)\wedge (P \vee Q) \wedge (P \vee R) \wedge (Q\vee \neg P)\wedge (Q\vee Q)\wedge (Q\vee R)=(P\vee Q)\wedge (P\vee R)\wedge (Q\vee \neg P)\wedge Q\wedge (Q\vee R)=Q\wedge(P\vee R)(合取范式)$

$(P\wedge Q)\vee (\neg P\wedge Q \wedge R)=(P\wedge Q\wedge (R\vee \neg R))\vee (\neg P\wedge Q \wedge R)=(P\wedge Q\wedge R)\vee(P\wedge Q\wedge \neg R)\vee (\neg P\wedge Q \wedge R)=m_7\vee m_6\vee m_3=\vee_{3,6,7}(主析取范式)=\wedge_{\{0,1,2,4,5\}\text{补}}=\wedge_{2,3,5,6,7}(主合取范式)$

使公式为真的解释：

|$P$|$Q$|$R$|$m_i$|
|----|----|----|----|
|F|T|T|$m_3$|
|T|T|F|$m_6$|
|T|T|T|$m_7$|

(8) $(P\rightarrow Q)\vee ((Q\wedge P)\leftrightarrow (Q\leftrightarrow \neg P))$

$(P\rightarrow Q)\vee ((Q\wedge P)\leftrightarrow (Q\leftrightarrow \neg P))=(P\rightarrow Q)\vee ((Q\wedge P)\leftrightarrow (\neg Q \wedge \neg \neg P)\vee (Q \wedge \neg P))=(\neg P \vee Q)\vee [(Q\wedge P)\leftrightarrow (\neg Q \wedge P)\vee (Q \wedge \neg P)]=(\neg P \vee Q)\vee\{[(Q\wedge P)\wedge ((\neg Q \wedge P)\vee (Q \wedge \neg P))]\vee [\neg (Q\wedge P)\wedge \neg ((\neg Q \wedge P)\vee (Q \wedge \neg P))] \}=(\neg P \vee Q)\vee\{[((Q\wedge P)\wedge (\neg Q \wedge P))\vee ((Q\wedge P)\wedge(Q \wedge \neg P))]\vee [\neg (Q\wedge P)\wedge (\neg(\neg Q \wedge P)\wedge \neg(Q \wedge \neg P))] \}=(\neg P \vee Q)\vee\{\text{F}\vee[(\neg Q\vee \neg P)\wedge (( Q \vee \neg P)\wedge ( P\vee \neg Q))] \}=(\neg P \vee Q)\vee\{[(\neg Q\vee \neg P)\wedge ( P\vee \neg Q)]\wedge ( \neg P \vee Q) \}=\neg P \vee Q(析取范式、合取范式)=M_1=\wedge_1(主合取范式)=\vee_{\{0,2,3\}\text{补}}=\vee_{0,1,3}(主析取范式)$

使公式为真的解释：

|$P$|$Q$|$m_i$|
|----|----|----|
|F|F|$m_0$|
|F|T|$m_1$|
|T|T|$m_3$|
