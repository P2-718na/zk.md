#sesso_lineare_approssimato
Praticamente, le trasformazioni lineari di coordinate (anche roba con angoli, pensa tipo alle matrici di rotazione)

##### `THM` Cambio di coordinate
(?) non c'è sul libro dell'Abenda. Scrive solo che:
$$
\int_{\Phi(K)}f(x_1,\ \ldots,\ x_n)\ dx_1,\ldots dx_n
=
\int_Kf'(u_1,\ \ldots,\ u_n)\ |detJ_\Phi(u_1,\ \ldots,\ u_n)|\ du_1,\ldots du_n
$$
Con $f'$ la funzione cambiata di variabile (ovvero, passata attraverso l'applicazione lineare).

##### `APPL` Passaggio alle coordinate polari sferiche
$$
\left\{ 
    \begin{array}{l}
        x = r\ sen(\theta)\ cos(\varphi) \\ 
        y = r\ sen(\theta)\ sen(\varphi) \\
        z = r\ cos(\theta)
    \end{array}
\right.
\hspace{50px}
(r,\ \theta,\ \varphi) \in [0,\ +\infty[\ \times\ [0, \pi]\ \times\ [0,\ 2\pi]
$$
$detJ_\Phi(r,\ \theta,\ \varphi) = r^2sen(\theta)$
((seghe mentali sul fatto che c'è una discontinuità bla bla misura nulla bla bla))

##### `APPL` Passaggio alle coordinate cilindriche
$$
\left\{ 
    \begin{array}{l}
        x = \rho\ cos(\varphi) \\ 
        y = \rho\ sen(\varphi) \\
        z = h
    \end{array}
\right.
\hspace{50px}
(\rho,\ \varphi,\ h) \in [0,\ +\infty[\ \times\ [0, 2\pi[\ \times\ \mathbb{R}
$$
$detJ_\Phi(\rho,\ \varphi,\ h) = \rho$
((stesse seghe mentali di sopra))