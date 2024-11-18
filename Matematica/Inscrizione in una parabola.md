Come primo step per inscrivere un rettangolo e un quadrato nello spazio tra una parabole e l'asse delle ascisse poniamo una retta ipotetica, parallela all'asse delle $x$, quindi di equazione $y=k$, dove $k$ è un numero qualsiasi ancora da determinare. Fatto questo troviamo i punti di intersezione tra la retta e la parabola:
$$
\left\{
\begin{gather*}
y=k \\
y=ax^2+bx+c
\end{gather*}
\right.
$$
Così troviamo due punti $A$ e $B$, che quindi proiettiamo sull'asse delle $x$, chiamiamo queste proiezioni $C$ e $D$, questi due punti chiaramente avranno come coordinate $(x,0)$

```tikz
\begin{document}
	\begin{tikzpicture}
		\draw[help lines,dashed] (0,0) grid (10,10);
		\draw[very thick,-latex] (0,5) -- (10,5) node[below]{$x$};
		\draw[very thick,-latex] (5,0) -- (5,10) node[left]{$y$};
		\draw (7,9) parabola (5,0);
		\draw (7,9) parabola (9,0);
		\draw (0,8) -- (10,8);
		\fill[red] (6.325,8) circle (0.04);
		\fill[red] (7.65,8) circle (0.04);
		\draw[dashed] (6.325,8) -- (6.325,5);
		\draw[dashed] (7.65,8) -- (7.65,5); 
		\fill[red] (6.325,5) circle (0.04);
		\fill[red] (7.65,5) circle (0.04);
		\node[text width=1cm] at (6.45,8.2){A};
		\node[text width=1cm] at (8.25,8.2){B};
		\node[text width=1cm] at (6.45,4.75){C};
		\node[text width=1cm] at (8.25,4.75){D};
	\end{tikzpicture}
\end{document}
```

Determinati questi quattro punti solitamente possiamo determinare il valore di $k$ attraverso un'equazione da impostare attraverso i dati fornitici dal problema, ad esempio in un quadrato poniamo $\overline{AB}=\overline{AC}$, risolviamo l'equazione e troviamo il valore di $k$

C'è però da dire che spesso troviamo due valori di $k$, che quindi potrebbero anche non essere accettabili, per verificare se un valore di $k$ è accettabile basta calcolare la coordinata $y$ del vertice della parabola, e se $k>y_{V}$ allora non è accettabile