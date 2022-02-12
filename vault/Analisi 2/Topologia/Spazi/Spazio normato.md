Concettualmente, la norma di un vettore rappresenta la "lunghezza" di un vettore. Segue la definizione formale:
#### `DEF` Norma
Sia $X$ un $\mathbb{K}-$[[spazio vettoriale]]. La funzione: $\lVert \cdot \lVert : X \rightarrow \mathbb{R}$ è detta $:=$ `norma` $:\Leftrightarrow$
    1.  $\underset{x \in X}{\forall}\ (\lVert x \lVert \geq 0) \land (\lVert x \lVert = 0 \iff x = 0)$
    2.  $\underset{x \in X}{\forall} \hspace{5px} \underset{\lambda \in \mathbb{R}}{\forall}\ \lVert \lambda x \lVert = |\lambda| \lVert x \lVert$
    3. $\underset{x, y \in X}{\forall}\ \lVert x + y \lVert \leq \lVert x \lVert + \lVert y \lVert$

`OSS` Vettore nullo ha sempre norma nulla (segue da punto 2)
`OSS` Dal punto uno segue che: $\lVert x \lVert \implies x = 0$. Una norma dove non vale questa osservazione, è detta **seminorma**.

(vedi: [[Norme notevoli]])

---
#### `DEF` Spazio normato
La coppia ordinata $(X, \lVert \cdot \lVert)$, con $X$ $\mathbb{K}-$[[spazio vettoriale]] e $\lVert \cdot \lVert$ [[#DEF Norma|norma]] è detta $:=$ `spazio normato`.


#deMarco 61