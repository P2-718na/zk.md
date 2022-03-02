#### `THM` Formula di Taylor con resto di Peano
Sia $f : [a,\ b] \to \mathbb{R}$ funzione, sia $x_0 \in [a,\ b]$ e siano definite $f^{(1)}(x_0),\ \ldots,\ f^{(n)}(x_0)$ (derivate $(n-1)$-esime della funzione in $x_0$). Preso $h$ tale che $f$ sia definita in $B_h(x_0)$ [[Palla#DEF Intorno circolare aperto chiuso equiv Palla aperta chiusa|palla chiusa]], vale $:\Leftrightarrow$ 
$$
    f(x) = \sum_{i=0}^{n} \left( \frac{ f^{(i)}(x_0) }{ i! } (x-x_0)^i \right)
        + O\left[ (x-x_0)^{n+1} \right]
$$
`OSS` Al posto di $O\left((\cdots)^{n+1}\right)$ posso scrivere (equivalente): $o\left((\cdots)^{n}\right)$.