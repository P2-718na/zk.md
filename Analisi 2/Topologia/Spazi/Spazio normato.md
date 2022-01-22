##### `DEF` Norma
$\lVert \cdot \lVert : \mathbb{X} \rightarrow \mathbb{R} :=$ `norma` $:\Leftrightarrow$
    1.  $\underset{x \in \mathbb{X}}{\forall}, (\lVert x \lVert \geq 0) \land (\lVert x \lVert = 0 \iff x = 0)$
    2.  $\underset{x \in \mathbb{X}}{\forall} \hspace{5px} \underset{\lambda \in \mathbb{R}}{\forall}, \lVert \lambda x \lVert = |\lambda| \lVert x \lVert$
    3. $\underset{x, y \in \mathbb{X}}{\forall}, \lVert x + y \lVert \leq \lVert x \lVert + \lVert y \lVert$

##### `DEF` Spazio normato
$(\mathbb{X}, \lVert \cdot \lVert)$, con $\mathbb{X} \subseteq \mathbb{R}^n$ e $\lVert \cdot \lVert$ [[#DEF Norma|norma]] $:\Leftrightarrow$ `spazio normato`.

`OSS` Se $(\mathbb{X}, \lVert \cdot \lVert)$ è spazio normato $\implies$ $(\mathbb{X}, d)$ con $d$ [[Metrica indotta dalla norma]] $d(x, y) = \lVert x - y \lVert$.