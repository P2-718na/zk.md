##### `DEF` Flusso di fase (FDF)
Sia $x_0,\ x \in \Sigma$ [[spazio delle fasi]], $t \in \mathbb{R}^+$ e sia:
$$
\begin{array}{c}
\phi: &\mathbb{R}^+ \times \Sigma &\to &\Sigma \\
&\phi^t(x_0) &\mapsto &x(t) \in \Sigma 
\end{array}
$$
per cui valgono le seguenti proprietà:
1) $\phi^0(x_0) = x_0$ ^230fab
2) $\phi^t \circ \phi^s = \phi^{t + s}$ ^e1d196
3) Scelta una [[../../Analisi 2/Calcolo integrale/Intervalli/Misura|misura]], il flusso di fase la deve conservare. In simboli: $\int_A d\mu = \int_{\phi^t(A)} d\mu$ 
In questo caso _si definisce_ $\phi :=$ `flusso di fase` di `condizione iniziale x_0`. $x(t)$ è detta `legge oraria del moto`. ^f703dc

Discorsivamente, un flusso di fase è una legge che, _data una condizione iniziale di un sistema, ne descrive l'evoluzione temporale_. Le tre proprietà richiedono che:
1) Al tempo zero il sistema è nel suo stato iniziale.
2) "Determinismo": il punto di partenza da cui iniziamo a considerare il flusso di fase non influisce sull'evoluzione del sistema.
3) "[[Conservazione dei volumi]]".

#todo esempio pag 8 appunti