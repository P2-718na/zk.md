Sia $M$ una varietà di $\mathbb{R}^n$. Vogliamo valutare l'azione di un gruppo additivo su $M$. 
Per definitezza, supponiamo che questo gruppo sia $(\mathbb{R},+)$ (rappresentante il tempo, nel caso fisico di
nostro interesse). 
La nozione di [[Azione di gruppo|azione]] può essere formulata come segue. \
Vogiamo definire l'*azione liscia*  $\phi$ di $\mathbb{R}$ su $M$:
$$
     \phi : \mathbb{R} \times M \longrightarrow M
$$
Sia $\phi^t$ un automorfismo di $M$ tale che
$$
\phi^t: M  \longrightarrow M
$$
$$
     m \mapsto \phi(t,m)
$$
e sia $\phi^*$ un'applicazione che manda un numero reale nell'automorfismo associato:
$$
    \phi^* : \mathbb{R} \longrightarrow \text{Aut} \ M
$$
$$
       t \mapsto \phi^t
$$
A questo punto possiamo dire che $\phi$ è un'azione liscia se soddisfa alle seguenti proprietà:
 1. $\phi$ è liscia, i.e. infinitamente [[Funzione differenziabile|differenziabile]];
 2. $\phi^*$ è un [[omomorfismo]] di $R$ in Diff($M$). 

Ciò equivale a dire che quando un gruppo $G$ agisce su una varietà induce un [[omomorfismo]] 
$$\phi^*: G \longrightarrow \text{Diff}(M)$$
`NOTA`:
Si dice che l'[[Azione di gruppo|azione]] è *effettiva* se $ker(\phi^*)$ è costituito solo da $e_G$.

Siamo ora in grado di dare la definizione:
#### Definizione
##### `DEF` Gruppo di trasformazioni ad un parametro
>Siano $\phi, \phi^t, \phi^*$ come sopra. Chiamiamo
>$$Im \ \phi^* = \{ \phi^t \}_{ t \in \mathbb{R}} $$ gruppo di trasformazioni ad un parametro.

Questa struttura induce un'[[1-param differential op|operatore differenziale]] che individua un [[1-param vector field|campo vettoriale]] caratteristico.