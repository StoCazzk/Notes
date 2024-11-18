
**Retta Parabola**
Come per le rette, anche per una retta ed una parabola, per trovare i punti di intersezione basta mettere a sistema le due equazioni, quindi avremo o un sistema di questo tipo:
$$
\left\{
\begin{gather*}
y=mx+q \\
y=ax^2+bx+c
\end{gather*}
\right.
$$
oppure di questo tipo:
$$
\left\{
\begin{gather*}
y=mx+q \\
x=ay^2+by+c
\end{gather*}
\right.
$$
In entrambi i casi possiamo trovare o due punti (retta secante), o un punto (retta tangente) oppure troviamo che il sistema è impossibile (retta e parabola non si incontrano).

Altro modo per determinare se una retta rispetto ad una parabola è tangente, secante oppure non incontra quest'ultima è attraverso lo studio del $\Delta$ dell'equazione di secondo grado che andiamo ad individuare attraverso il sistema.
$$
\begin{gather*}
\Delta>0\rightarrow \text{retta secante} \\
\Delta=0\rightarrow \text{retta tangente} \\
\Delta <0\rightarrow \text{la retta non incotra la parabola}
\end{gather*}
$$

```tikz
\begin{document}
	\begin{tikzpicture}
		\draw[help lines,dashed] (0,0) grid (10,10);
		\draw[very thick,-latex] (0,5) -- (10,5) node[below]{$x$};
		\draw[very thick,-latex] (5,0) -- (5,10) node[left]{$y$};
		\draw (7,9) parabola (5,0);
		\draw (7,9) parabola (9,0);
		\draw (0,0) -- (10,10);
	\end{tikzpicture}
\end{document}
```

```tikz
\begin{document}
	\begin{tikzpicture}
		\draw[help lines,dashed] (0,0) grid (10,10);
		\draw[very thick,-latex] (0,5) -- (10,5) node[below]{$x$};
		\draw[very thick,-latex] (5,0) -- (5,10) node[left]{$y$};
		\draw (7,9) parabola (5,0);
		\draw (7,9) parabola (9,0);
		\draw (0,9) -- (10,9);
	\end{tikzpicture}
\end{document}
```

```tikz
\begin{document}
	\begin{tikzpicture}
		\draw[help lines,dashed] (0,0) grid (10,10);
		\draw[very thick,-latex] (0,5) -- (10,5) node[below]{$x$};
		\draw[very thick,-latex] (5,0) -- (5,10) node[left]{$y$};
		\draw (7,9) parabola (5,0);
		\draw (7,9) parabola (9,0);
		\draw (0,0) -- (5,10);
	\end{tikzpicture}
\end{document}
```


**Parabola parabola**
Anche in questo caso mettiamo a sistema le equazioni delle due parabole, ottenendo questo tipo di sistema:
$$
\left\{
\begin{gather*}
y=ax^2+bx+c \\
y=a^`x^2+b^`x+c^`
\end{gather*}
\right.
$$
oppure questo tipo di sistema:
$$
\left\{
\begin{gather*}
y=ax^2+bx+c \\
x=a^`y^2+b^`y+c^`
\end{gather*}
\right.
$$
o ancora questo tipo:
$$
\left\{
\begin{gather*}
x=ay^2+by+c \\
x=a^`y^2+b^`y+c^`
\end{gather*}
\right.
$$
In tutti e tre i casi i casi possiamo trovare dalle 4 alle zero soluzioni, quindi dai quattro agli zero punti di intersezione.
```tikz
\begin{document}
	\begin{tikzpicture}
		\draw[help lines,dashed] (0,0) grid (12,10);
		\draw[very thick,-latex] (0,5) -- (12,5) node[below]{$x$};
		\draw[very thick,-latex] (5,0) -- (5,10) node[left]{$y$};
		\draw (7,9) parabola (5,0);
		\draw (7,9) parabola (9,0);
		\draw (9,9) parabola (6,0);
		\draw (9,9) parabola (12,0);
	\end{tikzpicture}
\end{document}
```

```tikz
\begin{document}
	\begin{tikzpicture}
		\draw[help lines,dashed] (0,0) grid (10,10);
		\draw[very thick,-latex] (0,5) -- (10,5) node[below]{$x$};
		\draw[very thick,-latex] (5,0) -- (5,10) node[left]{$y$};
		\draw (7,5) parabola (5,0);
		\draw (7,5) parabola (9,0);
		\draw (7,5) parabola (5,10);
		\draw (7,5) parabola (9,10);
	\end{tikzpicture}
\end{document}
```

```tikz
\begin{document}
	\begin{tikzpicture}
		\draw[help lines,dashed] (0,0) grid (10,10);
		\draw[very thick,-latex] (0,5) -- (10,5) node[below]{$x$};
		\draw[very thick,-latex] (5,0) -- (5,10) node[left]{$y$};
		\draw (7,9) parabola (5,0);
		\draw (7,9) parabola (9,0);
		\draw (7,1) parabola (5,10);
		\draw (7,1) parabola (9,10);
	\end{tikzpicture}
\end{document}
```