##### `THM` Riduzione sui rettangoli
$I = [a,\ b] \times [c,\ d]$, $f(x,\ y) : I \to \mathbb{R}$ [[Continuità#DEF Funzione continua|continua]]su $I$ $:\rightarrow$
$G(y) := \int_a^b f(x,\ y)\ dx$ con $y \in [c,\ d]$ è [[Continuità#DEF Funzione continua|continua]] e [[sommabile]] su $[c,\ d]$ e si ha
#todo inutile per quello che serve a me. Essenzialmente, se ho un rettangolo, posso integrare area base, integrare area altezza e fare il prodotto.

##### `THM` Riduzione sui [[Dominio normale|domini normali]]
$\varphi_1$, $\varphi_2 : [c,\ d] \to \mathbb{R}$ funzioni [[Continuità#DEF Funzione continua|continue]], con $\varphi_1 \leq \varphi_2$ e $y \in [c,\ d]$.
Si consideri il [[dominio normale]] (rispetto a $x$) di $\mathbb{R} ^2$:
$$
E := \{(x,\ y) \in \mathbb{R} ^2\ |\ y \in [c,\ d],\ \phi_1(y) \leq x \leq \phi_2(y)\}
$$
. $f(x,\ y) : K \to \mathbb{R}$ [[Continuità#DEF Funzione continua|continua]] su $K$. $:\rightarrow$ La funzione:
$$
G(y) = \int_{\varphi_1(y)}^{\varphi_2(y)} f(x,\ y)\ dx,\ y \in [c,\ d]
$$
è [[Continuità#DEF Funzione continua|continua]] e [[sommabile]] su $[c,\ d]$. Vale inoltre la formula di riduzione:
$$
\iint_E f(x,\ y)\ dxdy = \int_c^ddy\ \left( \int_{\varphi_2(y)}^{\varphi_1(y)}f(x,\ y)\ dx \right)
$$
. Lo stesso teorema continua a valere scambiando $x$ e $y$, prendendo due funzioni $\psi_1$, $\psi_2$ appropriate.
#deepen (abenda 171, riscrivi altra definizione, per completezza.)