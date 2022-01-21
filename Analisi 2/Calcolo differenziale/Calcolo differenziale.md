##### `DEF` Funzione differenziabile
Siano $A \subseteq \mathbb{R}^n$ [[Aperto#DEF Insieme aperto|aperto]], $f: A \rightarrow \mathbb{R}$, $x_0 \in A$. $f :=$ `differenziabile in x_0` $:\Leftrightarrow$
$$\underset{m \in \mathbb{R}^n}{\exists} | f(x)=f(x_0) + \langle m,\ x - x_0 \rangle + o(\lVert x - x_0 \lVert)$$
equivalente a:
$$\lim_{\lVert x - x_0 \lVert \to 0} \frac{f(x) - f(x_0) - \langle m,\ x - x_0 \rangle}{\lVert x - x_0 \lVert} = 0$$
Ovvero, deve esistere il piano tangente alla funzione in quel punto. (vedi: [[prodotto interno]], [[o piccolo]]).

In questo caso, si definisce:
##### `DEF` Differenziale di $f$ in $x_0$
$$df_{x_0} := \langle m,\ x - x_0 \rangle$$

##### `THM`  Conseguenze della differenziabilità
#todo #urgent

altra roba