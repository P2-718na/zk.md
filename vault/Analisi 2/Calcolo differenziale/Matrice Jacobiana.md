##### `DEF` Jacobiana
$A \subseteq{R}^n$ [[Insieme aperto|aperto]], $\vec{p} := (p_{1},\ \ldots,\ p_{n}) \in A$, $f := (f_1,\ \ldots,\ f_m) : A \rightarrow \mathbb{R}^m$ funzione [[Derivazione secondo un vettore#^099555|derivabile parzialmente]] rispetto a tutte le componenti di $p$. Si definisce `matrice jacobiana`$:=$
$$
J_f(p) :=
\begin{bmatrix}
    \partial_{p_1}f_1(\vec{p}) & \cdots & \partial_{p_n}f_1(\vec{p}) \\
    \vdots & \ddots & \vdots \\
    \partial_{p_1}f_m(\vec{p}) & \cdots & \partial_{p_n}f_m(\vec{p})
\end{bmatrix} \ \
\equiv
\begin{bmatrix}
    \nabla f_1(\vec{p}) \\
    \vdots \\
    \nabla f_m(\vec{p})
\end{bmatrix} \ \
$$
`THM` La jacobiana di una [[Differenziale#DEF Funzione differenziabile|funzione differenziabile]] corrisponde al suo differenziale