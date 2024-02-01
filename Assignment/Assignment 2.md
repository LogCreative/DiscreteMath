$P\rightarrow (Q\wedge R)=\neg P\vee (Q\wedge R)(\rightarrow的等值公式)=(\neg P \vee Q)\wedge(\neg P \vee R)(分配律)=(P\rightarrow Q)\wedge (P\rightarrow R)(\rightarrow的等值公式)$

 $((P\rightarrow \neg Q)\rightarrow (Q\rightarrow \neg P))\wedge R=((P\rightarrow \neg Q)\rightarrow (\neg \neg P\rightarrow \neg Q))\wedge R(逆否定理)=((P\rightarrow \neg Q)\rightarrow (P\rightarrow \neg Q))\wedge R(双重否定)=\text{T}\wedge R(等幂律)=R(同一律)$

 $P\rightarrow (Q\rightarrow R)=P\rightarrow (\neg Q\vee R)(\rightarrow的等值公式)=\neg P\vee (\neg Q\vee R)(\rightarrow的等值公式)=(\neg P\vee \neg Q)\vee R(结合律)=\neg (P\wedge Q)\vee R(摩根律)=(P\wedge Q)\rightarrow R(\rightarrow的等值公式)$

 $\neg (P\leftrightarrow Q)=\neg ((P\rightarrow Q)\wedge (Q\rightarrow P))(\leftrightarrow定义)=\neg(P\rightarrow Q)\vee \neg(Q\rightarrow P)(摩根律)=\neg(\neg P \vee Q)\vee \neg(\neg Q \vee P)(\rightarrow的等值公式)=(\neg \neg P \wedge \neg Q)\vee (\neg \neg Q \wedge \neg P)(摩根律)=(P \wedge \neg Q)\vee (Q \wedge \neg P)(双重否定)$

令$P,Q$为命题变元。

$\neg P=\neg P\vee \neg P(等幂律)=P\uparrow P(\uparrow定义)$

$\neg P=\neg P\wedge \neg P(等幂律)=P\downarrow P(\downarrow定义)$

$P\wedge Q=\neg \neg P \wedge \neg \neg Q(双重否定)=\neg P \downarrow \neg Q(\downarrow 定义)=(P\uparrow P)\downarrow (Q\uparrow Q)(上一个公式的结论)$

$P \vee Q=\neg \neg P \vee \neg \neg Q(双重否定)=\neg P\uparrow \neg Q(\uparrow定义)=(P \downarrow P)\uparrow (Q \downarrow Q)$

$P \rightarrow Q=\neg P\vee Q(\rightarrow的等值公式)=(P\uparrow P)\vee Q=((P\uparrow P)\downarrow (P\uparrow P))\uparrow (Q\downarrow Q)$

$P\leftrightarrow Q=(P\rightarrow Q)\wedge(Q\rightarrow P)=(((P\uparrow P)\downarrow (P\uparrow P))\uparrow (Q\downarrow Q)) \wedge (((Q\uparrow Q)\downarrow (Q\uparrow Q))\uparrow (P\downarrow P))=((((P\uparrow P)\downarrow (P\uparrow P))\uparrow (Q\downarrow Q)) \uparrow (((P\uparrow P)\downarrow (P\uparrow P))\uparrow (Q\downarrow Q))))\downarrow ((((Q\uparrow Q)\downarrow (Q\uparrow Q))\uparrow (P\downarrow P))\uparrow (((Q\uparrow Q)\downarrow (Q\uparrow Q))\uparrow (P\downarrow P)))$

