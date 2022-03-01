##### `DEF` Gruppo

>Un gruppo è un insieme $G$ munito di un'operazione binaria $*$, che ad ogni coppia di elementi $a,b$ di $G$ associa un elemento, che indichiamo con $a*b$, appartenente a $G$, per cui siano soddisfatti i seguenti assiomi:
> 1.(Proprietà associativa):  $\forall a,b,c \in G$ vale  $$(a*b)*c = a*(b*c)$$
> 2.(esistenza dell'elemento identità): esiste in $G$ un elemento neutro $e$ rispetto all'operazione $*$,   cioè tale che $$a*e = e *a = a, \forall a \in G$$  intolre tale elemento è unico;
> 3.(Esistenza dell'inverso): per ogni elemento di $G$ esiste un elemento $a'$, detto inverso di $a$,  tale che 
> $$a*a' = a' * a = e$$        

Un gruppo si dice *abeliano* o commutativo se l'operazione binaria interna gode della proprietà commutativa, ossia il gruppo $(G,*)$ è abeliano se
$$a * b = b*a \ \ \forall a,b \in G$$

%%Un insieme $G$, munito di una _operazione binaria_ $+$, che ad ogni coppia di elementi $(a,\ b) \in G$
associa un elemento $a + b \in G$, è detto `gruppo` $:\Leftrightarrow$ valgono le seguenti proprietà:
$$
\begin{array}{l}
  &\text{1.} &\underset{a,\ b,\ c\ \in\ G}{\forall} &(a+b)+c = a+(b+c) &\text{"proprietà associativa"} \\
  &\text{2.} &\exists! \mathcal{e} \in G\ &|\ a + \mathcal{e}  = \mathcal{e} + a = a \underset{a\ \in\ G}{\forall}$ &\text{"esistenza dell'elemento neutro"} \\
  &\text{3.} &\underset{a,\ \in\ G}{\forall} \exists a^{-1} \in G\ &|\ a + a^{-1} = a^{-1} + a = \mathcal{e} &\text{"esistenza dell'inverso"} \\
  &\text{4.} &\underset{a,\ b\ \in\ G}{\forall} &a+b = b+a &\text{"proprietà commutativa*"}
\end{array}
$$
La (4) può anche _non valere_. Se vale, il gruppo si dice `abeliano`.%%
