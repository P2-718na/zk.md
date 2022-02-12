#### Norme notevoli
#### 1.  Norme a dimensione finita
#####   `DEF` Norma Euclidea
  Per $X = \mathbb{R}^n$ e $K = \mathbb{R}$, si definisce `norma euclidea` $:\Leftrightarrow$
$$
|\ x\ | := \sqrt{\sum_{k=1}^n |x_k|^2}
$$
    `DIM` Si dimostra che questa è una [[Spazio normato#DEF Norma|norma]]:
	(1), (2) sono banali. (3) non è altro che la [[Disuguaglianza di Schwarz e Minkowski#THM Disuguaglianza di Minkowski|disuguaglianza di Minkowski]].
	
  `norma 1` $:\Leftrightarrow$
  ![[norma 1.png]]
  
  `norma inf` $:\Leftrightarrow$
  ![[norma inf.png]]
anche queste due norme sfruttano la [[Disuguaglianza di Schwarz e Minkowski#THM Disuguaglianza di Minkowski|disuguaglianza di Minkowski]] per le dimostrazioni.

#### 2.  Norme a dimensione infinita
#####   `DEF` Norma della convergenza uniforme
Sia $T$ un [[insieme]] e $B(T,\ \mathbb{R})$ l'insieme delle funzioni [[Insieme limitato|limitate]]. Su $B(T,\ \mathbb{R})$ si definisce `sup-norma`$:\Leftrightarrow$`norma della convergenza uniforme`$:\Leftrightarrow$
$$
\lVert f \lVert_{\infty} := sup\{|f(x)|\ : \ x \in T\}
$$
`OSS` È lecito definire questa norma su questo insieme perchè $B(T,\ \mathbb{R})$ è un [[Spazio vettoriale|sottospazio vettoriale]] (l'insieme di tutte le funzioni da $T$ a $\mathbb{R}$ è s.v., si dimostra facilmente guardando la definizione e considerando come sono definite le operazioni di somma e prodotto per scalare delle funzioni), (per definire una norma su uno spazio, è richiesto che questo sia s.v.).
`DIM` Ricordando la definizione di [[somma e prod. per scalare per funzioni]], la dimostrazione è analoga a quella per spazi finiti:
![[norma inf per spazi di funzioni.png]]

#####   `DEF` Norma della convergenza in media
#todo 


Qui il De Marco aggiunge altri esempi di norme che io non ho messo.
#deMarco 62, 63