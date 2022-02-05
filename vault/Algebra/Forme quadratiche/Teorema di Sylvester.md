##### `THM` Teorema di Sylvester
$$A= \begin{pmatrix}a_{11} & a_{12}\\a_{21} & a_{22}\end{pmatrix}$$
1. $A$ è definita $\iff$ $detA > 0$
    [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|positiva]] $\iff$ $a_{11} > 0$ 
    [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|negativa]] $\iff$ $a_{11} < 0$
2. $A$ è semidefinita $\iff$ $detA = 0$
    [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|positiva]] $\iff$ $a_{11}, a_{22} \geq 0$ 
    [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|negativa]] $\iff$ $a_{11}, a_{22} \leq 0$
4. $A$ è [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|indefinita]] $\iff$ $detA < 0$

Il teorema di Sylvester ci permette di applicare il seguente criterio per studiare una matrice tramite i [[Determinante|determinanti]] dei suoi [[minori]].
##### `APPL` Criterio di Sylvester
$A \in M_{n,n}(\mathbb{R})$, $A = A^T$. Si definisce `minore di testa di ordine k`$:=$
$$A_k = \begin{pmatrix}a_{11} & \cdots & a_{1k} \\ \vdots & \ddots & \vdots \\ a_{k1} & \cdots & a_{kk}\end{pmatrix} \ \ k \leq n$$
$:\rightarrow$
1. $A$ è [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|definita positiva]] $\iff$ $detA_k > 0 \underset{k \in [n]}{\forall}$
2. $A$ è [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|definita negativa]] $\iff$ $(-1)^k\ detA_k > 0 \underset{k \in [n]}{\forall}$
#sauce: https://cosedimatematica.it/lezioni/algebra-lineare/matrici-definite-positive-e-negative/
#sauce https://www.youmath.it/lezioni/algebra-lineare/matrici-e-vettori/2694-matrice-definita-positiva-semidefinita-positiva-e-negativa.html
`APPL` In pratica, si calcolando i determinanti dei minori di testa.
Se sono tutti maggiori di zero, allora A è def. positiva. Se sono alternati i segni (-) e (+) con i (-) in posizione DISPARI (1, 3...) allora è def. negativa.
Se uno dei (-) è FUORI POSTO, allora è INDEFINITA.


Se uno dei determinanti ~TRANNE l'ULTIMO~ (CONTRollA) (quello dell'intera matrice) è ZERO, allora la matrice è SEMIDEFINITA.

`DEF` Minore di testa di ordine k
#todo
