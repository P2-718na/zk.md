Sia $\vec F$ _campo vettoriale_ arbitrariamente regolare, e sia $\{\ldots \vec e_k\}$ una [[base]].
Si danno queste due definizioni (sono evidenziate in grassetto le differenze tra le due):

##### `DEF` Componente *co*variante
Si definiscono $F_k$ $:=$ `componenti covarianti di F` quelle che si ottengono tramite _proiezione euclidea del campo $\vec F$ sulla base $\{\ldots \vec e_k\}$_:
$$
F_k\ \dot =\ \vec F \cdot \vec e_k
$$
Il nome _covariante_ deriva dal fatto che, nel passaggio da una base all'altra, queste componenti saranno determinate dalla **matrice del cambio base**. Nota la posizione di $k$ in $F_k$: si trova **in basso**.

##### `DEF` Componente *contro*variante
Si definiscono $F^k$ $:=$ `componenti controvarianti di F` _le coordinate di $\vec F$ rispetto alla base base $\{\ldots \vec e_k\}$_:
$$
\vec F\ \underset{NE}{\dot =}\ F^k \cdot \vec e_k
$$
Il nome _controvariante_ deriva dal fatto che, nel passaggio da una base all'altra, queste componenti saranno determinate dalla **matrice inversa del cambio base**. Nota la posizione di $k$ in $F^k$: si trova **in alto**.
Qui è più comodo scrivere $\vec F$ in funzione di $F^k$. Il $\text{NE}$ sotto il segno di (uguale) indica che viene usata  la [[../../Algebra/Note/Notazione di Einstein]]. 

La differenza tra le due definizioni è riassunta da questa immagine (nota gli apici e pedici per indicare componenti co- e contro-varianti):
![[../File/differenza covarianti controvarianti.png]]

### Passare da co- a contro-varianti 
Si parte dalla rappresentazione *contro*variante del campo:
$$
\vec F\ \underset{NE}{\dot =}\ F^k \cdot \vec e_k
$$
Per ottenere la rappresentazione *co*variante, proiettiamo le componenti di $\vec F$ su $\{\ldots \vec e_k\}$. Otteniamo che le componenti *co*varianti $F_h$ sono date da:
$$
F_h\ \dot =\ 
    \left (\vec F \right) \cdot e_h\ \underset{NE}{\dot =}\ 
    \left(F^k \cdot \vec e_k\right) \cdot \vec e_h
$$
Ora (ricordando che sto sommando solo su *k*), se porto $\vec e_h$ dentro la sommatoria, ottengo:
$$
F_h = 
    F^k \cdot \left( \vec e_k \cdot \vec e_h \right)\ \dot = \ 
    F^k G_{hk}
$$
(dove si utilizza sempre la notazione di Einstein, sommando solo su _k_). G è la [[matrice metrica]].

`PROP` Si nota (da quanto visto sopra) che se la base $\{\ldots \vec e_k\}$ è [[ortonormale]], le due definizioni _coincidono_.
![[../File/componenti co e contro varianti in base ortonormale.png]]
^^ A sinistra, la base $\{\vec e_1, \vec e_2\}$ è ortonormale, per cui le componenti co- e contro-varianti di $\vec x$ coincidono. A destra, la base $\{\vec {e_1}', \vec {e_2}'\}$ _non_ è ortonormale, e le componenti non coincidono.

#link https://www.extrabyte.info/2017/06/15/componenti-covarianti-e-controvarianti-di-uno-stesso-vettore/
#appunti 61