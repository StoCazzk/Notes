Forze come la quella di attrito sono definite forze dissipative dato che diminuiscono la quantità di energia meccanica in un sistema, dato che compiono sempre un lavoro negativo. La formula per calcolare il lavoro quando sul corpo agiscono delle forze dissipative è:
$$
W_{tot}=\Delta K+\Delta U=K_{f}-K_{i}+U_{f}-U_{i}
$$
**Esempi di problemi**
Simone tiene ferma nella sua mano una pallina di 0,320 $kg$ ($m$) a 1,2 $m$ ($h$) dal suolo. Su di essa applica una forza per lanciarla verso l'alto e la pallina arriva fino a 3,5 $m$ ($h_{1}$) di altezza prima di tornare giù. Trascurare la forza di attrito dell'aria. Calcola il lavoro compiuto da Simone.
Dato che in entrambi i casi fornitici la pallina è completamente ferma, in questo caso $\Delta K=0$, quindi possiamo ometterla nell'equazione, otteniamo quindi:
$$
W=\Delta U
$$
riscriviamo $\Delta U$ come differenza delle energie potenziali:
$$
W=mgh_{1}-mgh
$$
raccogliamo quindi $mg$ e otteniamo:
$$
W=mg(h_{1}-h)
$$
sostituiamo quindi con i numeri:
$$
W=0,32(9,81)(3,5-1,2)\ J=7,2 \ J
$$


```tikz
\begin{document}
	\begin{tikzpicture}
		\draw[thick] (0,0) circle(0.5);
		\draw[thick, ->] (0,0) -- (0,-1);
		\draw[thick] (0,-4) circle(0.5);
		\draw[thick, ->] (0,-4) -- (0,-3);
		\draw[thick] (1,0.5) -- (1,-4.5);
		\draw[thick] (0.9,0.5) -- (1.1,0.5);
		\draw[thick] (0.9,-4.5) -- (1.1,-4.5);
		\draw[thick] (1,-4.5) -- (1,-6.5);
		\draw[thick] (0.9,-6.5) -- (1.1,-6.5);
		\draw (-3,-6.5) -- (3,-6.5);
		\node[draw] at (-2,-4) {$U_{1}=mgh$};
		\node[draw] at (-2,0) {$U_{2}=mgh_{1}$};
		\node[draw] at (2,-2.5) {$h_{1}$ =3,5m};
		\node[draw] at (2,-5.5) {$h$ =1,2m};
	\end{tikzpicture}
\end{document}
```
