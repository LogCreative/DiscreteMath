8.设$B=P(P(P(\varnothing)))$。

（1）是否$\varnothing\in B$？是否$\varnothing\subseteq B$？

$B=P(P(P(\varnothing)))=P(P(\{\varnothing\}))=P(\{ \varnothing,\{\varnothing \} \})=\{ \varnothing,\{ \varnothing \},\{ \{ \varnothing \} \},\{ \varnothing,\{ \varnothing \} \} \}$

$\varnothing\in B$ 是一个元素

$\varnothing \subseteq B$ 空集包含于任何集合

（2）是否$\{ \varnothing \}\in B$？是否$\{ \varnothing \}\subseteq B$？

$\{\varnothing\}\in B$ 是一个元素

$\{ \varnothing \}\subseteq B$，其元素空集是$B$的一个元素

（3）是否$\{ \{ \varnothing \} \}\in B$？是否$\{ \{ \varnothing \} \}\subseteq B$？

$\{ \{ \varnothing \} \}\in B$ 是一个元素

$\{ \{ \varnothing \} \}\subseteq B$ 其元素$\{ \varnothing \}$是$B$的一个元素

12.设全集$E=\{1,2,3,4,5\}$，集合$A=\{1,4\},B=\{1,2,5\},C=\{2,4\}$。求下列集合。

（1）$A\cap -B$.

$A\cap -B=\{1,4\}\cap\{3,4\}=\{4\}$

（2）$(A\cap B)\cup -C$.

$(A\cap B)\cup -C=\{1\}\cup\{1,3,5\}=\{1,3,5\}$

（3）$-(A\cap B)$.

$-(A\cap B)=-\{1\}=\{2,3,4,5\}$

（4）$P(A)\cap P(B)$.

$P(A)\cap P(B)=P(A\cap B)=\{\varnothing,\{1\}\}$

（5）$P(A)-P(B)$.

$P(A)-P(B)=\{\varnothing,\{1\},\{4\},\{1,4\}\}-\{\varnothing,\{1\},\{2\},\{5\},\{1,2\},\{1,5\},\{2,5\},\{1,2,5\}\}=\{\{4\},\{1,4\}\}$

14.写出下列集合

(1)$\cup \{ \{3,4\},\{ \{ 3 \},\{4\} \},\{3,\{4\}\},\{ \{3\},4 \} \}$

$\cup \{ \{3,4\},\{ \{ 3 \},\{4\} \},\{3,\{4\}\},\{ \{3\},4 \} \}=\{ 3,4,\{3\},\{4\} \}$

(2)$\cap \{ \{1,2,3\},\{2,3,4\},\{3,4,5\} \}$

$\cap \{ \{1,2,3\},\{2,3,4\},\{3,4,5\} \}=\{3\}$

17.设$A$、$B$和$C$是任意的集合，证明:

（1）$(A-B)-C=A-(B\cup C)$

$(A-B)-C=(A\cap -B)-C=(A\cap -B) \cap -C=A\cap(-B\cap -C)=A\cap - (B\cup C)=A-(B\cup C)$

（4）$A\subseteq C\wedge B\subseteq C\Leftrightarrow A\cup B\subseteq C$

$A\subseteq C\wedge B\subseteq C=(\forall x)(x\in A\rightarrow x\in C)\wedge(\forall x)(x\in B\rightarrow x\in C)=(\forall x)((x\in A\rightarrow x\in C)\wedge(x\in B\rightarrow x\in C))=(\forall x)((x\in A \vee x\in B)\rightarrow x\in C)=(\forall x)(x\in A \cup B\rightarrow x\in C)=A\cup B\subseteq C$

（6）$A\cap B=\varnothing \Leftrightarrow A\subseteq -B\Leftrightarrow B\subseteq -A$

a. $A\cap B=\varnothing$. 设$x\in A\Rightarrow x\in A-\varnothing=A-(A\cap B)=A\cap-B\Rightarrow x\in -B$

$A\subseteq -B$.

b. $A\subseteq -B$. $\forall x$，$x\in B\Rightarrow x\notin -B\Rightarrow x\notin A(A\subseteq -B)\Rightarrow x\in -A$

$B\subseteq -A$.

c. $B\subseteq -A$. $\forall x$，$x\in A\Rightarrow x\notin -A \Rightarrow x\notin B(B\subseteq -A)$

$\forall x$，$x\in B\subseteq -A\Rightarrow x\notin A$

$A\cap B=\varnothing$

得证。

27.足球队有38人，篮球队有15人，排球队有20人，三个队队员共58人，其中3人同时参加三个队，问同时参加两个队的人有几个。

解：设足球队队员的集合为$A$，篮球队队员的集合为$B$，排球队队员的集合为$C$

$|A|=38,|B|=15,|C|=20,|A\cup B\cup C|=58,|A\cap B\cap C|=3$

包括同时参加三个队的人：

$|A\cap B|+|B\cap C|+|A\cap C|-2|A\cap B\cap C|=|A|+|B|+|C|-|A\cup B\cup C|+|A\cap B\cap C|-2|A\cap B\cap C|=38+15+20-58-3=12$