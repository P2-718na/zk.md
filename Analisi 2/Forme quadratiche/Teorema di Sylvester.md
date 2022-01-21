##### `THM` Teorema di Sylvester (n=2)
$$A= \begin{pmatrix}a_{11} & a_{12}\\a_{21} & a_{22}\end{pmatrix}$$
1. $A$ è definita $\iff$ $detA > 0$
    [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|positiva]] $\iff$ $a_{11} > 0$ 
    [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|negativa]] $\iff$ $a_{11} < 0$
2. $A$ è semidefinita $\iff$ $detA = 0$
    [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|positiva]] $\iff$ $a_{11}, a_{22} \geq 0$ 
    [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|negativa]] $\iff$ $a_{11}, a_{22} \leq 0$
4. $A$ è [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|indefinita]] $\iff$ $detA < 0$

##### `THM` Teorema di sylvester
$A \in M_{n,n}(\mathbb{R})$, $A = A^T$
$$A_k = \begin{pmatrix}a_{11} & \cdots & a_{1k} \\ \vdots & \ddots & \vdots \\ a_{k1} & \cdots & a_{kk}\end{pmatrix} \ \ k \leq n$$
$:\rightarrow$
1. $A$ è [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|definita positiva]] $\iff$ $detA_k > 0 \underset{k \in [n]}{\forall}$
2. $A$ è [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|definita negativa]] $\iff$ $detA_k < 0 \underset{k \in [n]}{\forall}$

`DEF` Minore principale k-esimo
#todo
