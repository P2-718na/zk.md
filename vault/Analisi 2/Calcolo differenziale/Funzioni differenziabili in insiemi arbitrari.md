Nelle definizioni di [[Funzione differenziabile|differenziale]] date fino ad ora, si ha sempre lavorato dentro a spazi aperti, senza restrizioni particolari. Per questo capitolo, è utile usare la seguente definizione, che funziona in insiemi generici.
(Praticamente quello che fa questa definizione è prendere un punto in un insieme generico; la funzione sarà differenziabile in quel punto se riesco a trovare un intorno generico di quel punto dove è definita un altra funzione (uguale alla prima), differenziabile in senso "normale").

##### `DEF` Funzione differenziabile (per insiemi arbitrari)
Siano $X$, $Y$ due $\mathbb{K}$-[[../Topologia/Spazi/Normato/Spazio normato|spazi normati]]; $D \subseteq X$; $f: D \to Y$ funzione; $x_0 \in D$.
$f :=$ `differenziabile in x_0` $:\Leftrightarrow$ esistono:
1) $U \subseteq X$  [[../Topologia/Intorni/Intorno di un punto|intorno]] aperto di $x_0$
2) $g: U \to Y$ [[Funzione differenziabile|differenziabile]] (per aperti)
3) $g_{|U \cap D} \equiv f_{|U \cap D}$

`OSS` La nozione di _intorno aperto_ dipende dalla topologia scelta.

##### `DEF` Funzioni di classi $C^l$
- Fissato $l \in [1,\ +\infty]$, diremo che `f è di classe C^l in x_0` $:\Leftrightarrow$
    la funzione $g$ necessaria per la [[#DEF Funzione differenziabile per insiemi arbitrari|differenziabilità]] può essere presa di classe $C^l(U,\ Y)$.
- $f \in$ `classe C^l in D` $\equiv$ $f \in C^l(D,\ Y)$ $:\Leftrightarrow$
  $f \in C^l$ $\underset{x_0 \in D} {\forall}$.

##### `DEF` $C^l$-diffeomorfismo
Siano $X$, $Y$ due $\mathbb{K}$-[[../Topologia/Spazi/Normato/Spazio normato|spazi normati]]; $D \subseteq X$; $E \subseteq Y$.
Diremo che $C$, $E$ sono `C^l-diffeomorfi` $:\Leftrightarrow$
- $\exists$ un [[../Topologia/Spazi/Omeomorfismo|omeomorfismo]] $\omega : D \to E$ tale che:
    1) $\omega \in C^l(D,\ Y)$
    2) $\omega^{-1} \in C^l (E,\ X)$
 Tale $\omega$ è detto `C^l-diffeomorfismo di D su E`.

#todo manca la definizione di classe $C^l$ generica(?). Probabilmente andrebbe messa in [[Funzione differenziabile]].