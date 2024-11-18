Calcoliamo l'equazione di una parabola di vertice di coordinate $V(2,1)$ e di fuoco di coordinate $F\left( 2,\frac{3}{4} \right)$.
Per prima cosa mettiamo a sistema tutte le informazioni:
$$
\left\{
\begin{gather}
-\frac{b}{2a}=2 \\
\frac{b^2-4ac}{4a}=-1 \\
\frac{1-b^2+4ac}{4a}=\frac{3}{4}
\end{gather}
\right.
$$
sviluppiamo quindi il nostro sistema:
$$
\left\{
\begin{gather}
b=-4a \\
c=4a+1 \\
a=-1
\end{gather}
\right.
$$
otteniamo quindi che $a=-1,b=4,c=-3$, ovvero la parabola di equazione $y=-x^2+4x-3$

**Calcolare l'equazione di una parabola avendo due punti e l'asse**
Se abbiamo una parabola di cui sappiamo l'asse e due punti appartenenti alla parabola facciamo una cosa simile al caso precedente, difatti sostituiamo nell'equazione della parabola una volta la coordinata di un punto e una volta di un altro e poi mettiamo a sistema con l'equazione dell'asse:
$$
\left\{
\begin{gather}
y_{p_{1}}=ax_{p_{1}}^2+bx_{p_{1}}+c \\
y_{p_{2}}=ax_{p_{2}}^2+bx_{p_{2}}+c \\
x=-\frac{b}{2a}
\end{gather}
\right.
$$
chiaramente se la parabola ha asse parallelo all'asse delle $x$ il tutto si inverte, cioè:
$$
\left\{
\begin{gather}
x_{p_{1}}=ay_{p_{1}}^2+by_{p_{1}}+c \\
x_{p_{2}}=ay_{p_{2}}^2+by_{p_{2}}+c \\
x=-\frac{b}{2a}
\end{gather}
\right.
$$

**Calcolare l'equazione di una parabola avendo tre punti**
Se abbiamo tre punti, tutti appartenenti alla parabola di equazione che dobbiamo andare a trovare, usiamo lo stesso metodo usato in precedenza, quindi sostituendo le coordinate, chiaramente l'asse della parabola deve essere specificato:
$$
\left\{
\begin{gather}
y_{p_{1}}=ax_{p_{1}}^2+bx_{p_{1}}+c \\
y_{p_{2}}=ax_{p_{2}}^2+bx_{p_{2}}+c \\
y_{p_{3}}=ax_{p_{3}}^2+bx_{p_{3}}+c
\end{gather}
\right.
$$
chiaramente se la parabola ha asse parallelo all'asse delle $x$ il tutto si inverte, cioè:
$$
\left\{
\begin{gather}
x_{p_{1}}=ay_{p_{1}}^2+by_{p_{1}}+c \\
x_{p_{2}}=ay_{p_{2}}^2+by_{p_{2}}+c \\
x_{p_{3}}=ay_{p_{3}}^2+by_{p_{3}}+c
\end{gather}
\right.
$$

**Calcolare l'equazione di una parabola avendo due punti e la tangente**
Se abbiamo due punti e la tangente alla parabola per prima cosa mettiamo a sistema i due punti tra di loro sempre sostituendo le loro coordinate a quella della parabola, troviamo così un'equazione in funzione di una sola incognita a nostra scelta, mettiamo poi a sistema la nostra equazione di una parabola ad una sola incognita con l'equazione della retta tangente, troviamo così un'equazione di secondo grado, poiché la retta è tangente poniamo $\Delta=0$ e quindi risolviamo, trovando così il valore della nostra incognita. Prendiamo l'esempio di una parabola di punti $A(2,0)$ e $B(1,-1)$ e retta tangente di equazione $y=-2x+5$:
$$
\left\{
\begin{gather}
0=4a+2b+c \\
-1=a+b+c
\end{gather}
\right.
$$
sviluppiamo in funzione di $a$:
$$
\left\{
\begin{gather}
b=1-3a \\
c=2a-2
\end{gather}
\right.
$$
ora mettiamo a sistema l'equazione generica della parabola sostituendo però $b$ e $c$ con l'equazione della retta tangente:
$$
\left\{
\begin{gather}
y=ax_{2}+(1-3a)x+(2a-2) \\
y=-2x+5
\end{gather}
\right.
$$
usiamo il metodo del confronto e troviamo così un'equazione di secondo grado:
$$
-2x+5=ax^2+x-3ax+2a-2
$$
spostiamo tutto allo stesso membro:
$$
ax^2+(3-3a)x+(2a-7)=0
$$
ora poniamo $\Delta=0$:
$$
\begin{gather}
(3-3a)^2-4a(2a-7)=0 \\
9-18a+9a^2-8a^2+28a=0 \\
a^2+10a+9=0
\end{gather}
$$
ora risolviamo l'equazione di secondo grado:
$$
\begin{gather}
\Delta=\left( \frac{10}{2} \right)^2-9=16 \\
a=-5 \pm 4\rightarrow a=-9 \ \lor \ a=-1
\end{gather}
$$
ora che abbiamo i valori di $a$ sostituiamo nelle equazioni precedenti in funzione di $a$ i valori trovati:
$$
\begin{gather}
y=-1x^2(1-3(-1))+(2(-1)-2) \rightarrow y=-x^2+4x-4 \\
y=-9x^2+(1-3(-9))+(2(-9)-2)\rightarrow y=-9x^2+28x-20
\end{gather}
$$
```tikz
\begin{document}
	\begin{tikzpicture}
		\draw[help lines,dashed] (0,0) grid (10,10);
		\draw[very thick,-latex] (0,5) -- (10,5) node[below]{$x$};
		\draw[very thick,-latex] (5,0) -- (5,10) node[left]{$y$};
		\draw (7,5) parabola (4,0);
		\draw (7,5) parabola (10,0);
		\draw (6.73,6) parabola (7.35,0);
		\draw (6.73,6) parabola (6.25,0);
		\draw (10,2) -- (3.5,10);
		\fill[red] (7,5) circle (0.04);
		\fill[red] (6.5,4.85) circle (0.04);
		\node [text width=1] at (7.1,4.77){A};
	\end{tikzpicture}
\end{document}
```
