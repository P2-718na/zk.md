''##### `DEF` Funzione differenziabile 
Siano $A \subseteq \mathbb{R}^n$ [[Insieme aperto#DEF Insieme aperto|aperto]], $f := (f_1,\ \ldots,\ f_m) : A \rightarrow \mathbb{R}^m$, $x_0 \in A$. $f :=$ `differenziabile in x_0` $:\Leftrightarrow$
$$\underset{L \in M_{n, m}(\mathbb{R})}{\exists}\ |\ f(x) = f(x_0) + L(x-x_0) + o(\lVert x - x_0 \lVert)$$
equivalente a (applicando la definizione di [[o piccolo]]):
$$\lim_{x  \to 0} \frac{
    f(x) - f(x_0) - L(x-x_0)
}{
    \lVert x - x_0 \lVert
} = 0$$
Ovvero, deve esistere il piano tangente alla funzione in quel punto.
In questo caso, $L(x-x_0)$ è detto `differenziale di f in x_0` e si indica con:
$$\partial f(x_0) \hspace{20px} \equiv \hspace{20px} df_{x_0}$$

`NOTA` Questa definizione vale per funzioni vettoriali a valori vettoriali. Per funzioni a vettori scalari, vale questa definizione (equivalente):
Siano $A \subseteq \mathbb{R}^n$ [[Insieme aperto#DEF Insieme aperto|aperto]], $f: A \rightarrow \mathbb{R}$, $x_0 \in A$. $f :=$ `differenziabile in x_0` $:\Leftrightarrow$
$$\lim_{\lVert x - x_0 \lVert \to 0} \frac{f(x) - f(x_0) - \langle m,\ x - x_0 \rangle_I}{\lVert x - x_0 \lVert} = 0$$
Ovvero, deve esistere il piano tangente alla funzione in quel punto.
In questo caso, $\langle m,\ x - x_0 \rangle_I$,  è detto `differenziale di f in x_0`.
`OSS` Qui viene usato il prodotto scalare euclideo semplicemente per indicare il prodotto riga per colonna dei due vettori $m$ e $x - x_0$. 

---------
##### `PROP` Condizione necessaria alla differenziabilità
$f$ è [[#DEF Funzione differenziabile|differenziabile]] in un punto $x_0 \implies$ $f$ ammette in $x_0$ derivate secondo ogni vettore.
#deepen dimostrazione

--------------
##### `OSS` Condizione sufficiente alla differenziabilità
Ci è data dal [[Teorema del differenziale totale#THM Teorema del differenziale totale|teorema del differenziale totale]].

--------------
##### `THM`  Conseguenze della differenziabilità
$f$ è [[#DEF Funzione differenziabile|differenziabile]] in un punto $x_0 \implies$
    1) $f$ [[Continuità#DEF Funzione continua|continua]] in $x_0$
    2) $L \equiv J_f(x_0)$
`OSS` Se una funzione è differenziabile in un punto, il suo differenziale esiste ed è unico, e corrisponde alla sua [[Matrice Jacobiana|Jacobiana]]. (de marco 224)
#deepen 
