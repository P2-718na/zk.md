`OSS` L'esistenza di estremanti locali su un insieme, richiede che su quell'insieme sia definita una [[Spazio topologico#DEF Topologia|topologia]] (ovvero, è necessario disporre del concetto di [[Intorno di un punto|intorno]]).

##### `DEF` Massimo (minimo) locale
$A \subseteq \mathbb{R}^n$, $f: A \rightarrow \mathbb{R}$, $x_0 \in A :=$ `punto di massimo (minimo) locale` $:\Leftrightarrow$
$$\underset{\delta > 0}{\exists} \mid \underset{x \ \in \  A \ \cap \ B_{\delta}(x_0)}{\forall} \ f(x) \leq f(x_0) \hspace{20px} (f(x) \geq f(x_0))$$
--------
##### `DEF` Punto critico
$A \subseteq \mathbb{R}^n$ [[Insieme aperto#DEF Insieme aperto|aperto]], $f: A \rightarrow \mathbb{R}$, $\exists \nabla f(x_0)=0$, $x_0 \in A:=$ `punto critico`.
    
`OSS` $x_0$ [[#DEF Punto critico|punto critico]] $\centernot\implies x_0$ [[#DEF Massimo minimo locale|massimo/minimo locale]]  

-----------------
##### `THM` Teorema di Fermat
$A \subseteq \mathbb{R}^n$ [[Insieme aperto#DEF Insieme aperto|aperto]], $f: A \rightarrow \mathbb{R}$, $x_0 \in A$, $\exists \nabla f(x_0)$ $:\rightarrow$
    $x_0$ [[#DEF Massimo minimo locale|punto di massimo/minimo locale]]   $\implies$ $\nabla f(x_0) = 0$

`DIM` #todo

----------
##### `THM` Condizioni necessarie per la classificazione di massimi o minimi locali
$A \subseteq \mathbb{R}^n$ [[Insieme aperto#DEF Insieme aperto|aperto]], $x_0 \in A$, $f \in C^{(2)}(A, \mathbb{R})$ $:\rightarrow$
1. `x_0 punto di massimo locale` $\implies$
    $\nabla f(x_0) = 0$
    $H_f(x_0)$ [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|(semi)definita negativa]]
2. `x_0 punto di minimo locale` $\implies$
    $\nabla f(x_0) = 0$
    $H_f(x_0)$ [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|(semi)definita positiva]]
dove $H_f$ indica la [[Matrice Hessiana]].

`DIM` todo

-----
##### `THM` Condizioni sufficienti per la classificazione di massimi o minimi locali
$A \subseteq \mathbb{R}^n$ [[Insieme aperto#DEF Insieme aperto|aperto]], $x_0 \in A$, $f \in C^{(2)}(A, \mathbb{R})$, $\nabla f(x_0) = 0$ $:\rightarrow$
1. $H_f(x_0)$ [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|definita positiva]] $\implies$ $x_0$ è [[#DEF Massimo minimo locale|punto di minimo locale]]
2. $H_f(x_0)$ [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|definita negativa]] $\implies$ $x_0$ è [[#DEF Massimo minimo locale|punto di massimo locale]]
3. $H_f(x_0)$ [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|indefinita]] $\implies$ $x_0$ è `punto di sella` (`DEF`)
4. Nel caso la [[Matrice Hessiana|matrice hessiana]] sia [[Forma quadratica#THM Classificazione di matrici simmetriche associate a forme quadratiche|semidefinita]], bisogna utilizzare la [[#DEF Massimo minimo locale|definizione]]:
    $\underset{\delta > 0}{\exists} \mid \underset{x \in B_\delta(x_0)}{\forall} f(x) \geq f(x_0) \hspace{20px} (f(x) \leq f(x_0)) \implies x_0$ è [[Estremanti locali#DEF Massimo minimo locale|minimo (massimo) locale]]
    $\underset{\delta > 0}{\forall}\ \ \underset{x,y\in B_\delta(x_0)}{\exists} \mid f(x) < f(x_0) < f(y) \implies x_0$ è [[pringles.jpg|punto di sella]]
    `OSS` In questo caso, le condizioni di minimo(massimo) locale e punto sella sono _complementari_.

`APPL` Per studiare più velocemente gli estremanti, si può utilizzare il [[Teorema di Sylvester]]. #deepen 