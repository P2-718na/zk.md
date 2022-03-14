#### `DEF` Integrale primo del moto
Sia $\Sigma$ [[spazio delle fasi]] riferito ad un [[Sistema dinamico]]. Si definisce `integrale primo del moto` $:=$ una funzione (arbitrariamente regolare):
$$
H : \Sigma \to \mathbb{R}
$$
tale che:
1) è [[iniettiva]]
2) è _costante_: $\frac{d\ H(x)}{dt} = 0$ ^b9c705
3) è definita $\underset{x \in \Sigma}{\forall}$

`APPL` Un integrale primo del moto, quando esiste, ci permette di determinare la _legge oraria_ di un sistema (e quindi, per definizione, il suo [[Flusso di fase]]).

`OSS` #lezione Queste richieste danno ad $H$ _vincoli di tipo geometrico_: 
 Ogni [[orbita]] apparterrà ad una ed una sola [[curva di livello]] dell'integrale primo. Un orbita non potrà quindi cambiare superficie, e dalle osservazioni della superficie in cui si trova possiamo ottenere informazioni riguardo al moto.

`OSS` #lezione Generalmente (ma _non_ sempre), gli integrali primi sono connessi alla _conservazione dell'energia meccanica_ di un sistema.

---
### Integrale primo del moto per sistemi a due dimensioni
Dalla definizione di integrale primo del moto, non possiamo dire niente sulla sua unicità. Infatti, per un dato campo vettoriale, possono esistere più integrali primi (per esempio, le funzioni costanti rispettano tutte la definizione).
Le condizioni di [[#^b9c705|conservazione temporale]] e [[Flusso di fase#^f703dc|conservazione delle aree]] ci suggeriscono una scelta naturale per un integrale primo del moto:
##### `DEF` Integrale primo del moto per sistemi a due dimensioni
Prendiamo un [[Campo vettoriale associato a un flusso di fase|campo vettoriale]] del tipo:
$$
    a(r,\ p) = a(\dot r,\ \dot p) := (a_r,\ a_p)
$$
l'integrale primo del moto $H$ associato soddisfa:
$$
\left\{
    \begin{array}{l}
        \frac{\partial\ H}{\partial r} &= -a_p\\
        \frac{\partial\ H}{\partial p} &= a_r
    \end{array}
\right.
$$
Integrando separatamente queste due equazioni (e _ricordando_ che $a_r$ e $a_p$ sono entrambe funzioni di $r$ e $p$), possiamo trovare esplicitamente $H(r,\ p)$ (vedi: [[Integrale primo per il campo di Newton]]).

`DIM` #todo (la dimostrazione mo stra la ragionevolezza della scelta)