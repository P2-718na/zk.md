![[../File/todo da lezione 14/Pasted image 20220322091447.png]]
La cosa più naturale è la descrizione delle onde 3d come onde sferiche (ovvero: onde che partono da un punto solo). Questo punto diventa l'origine del nostro sistema di riferimento da cui hanno origine le onde.

È comodo usare le coordinate polari sferiche.
Ricordo che l'angolo $\theta$ è detto  angolo 1.

Qui c'è tutto il discorso su come si usano le coordinate polari sferiche.
Il risultato che si ottiene è questo:
![[../File/todo da lezione 14/Pasted image 20220322092145.png]]

E, _importante_, l' [[../Note/Operatore Laplaciano]] cambia forma.

Scelgo di avere la stessa rappresentazione per \xi, visto che comunque rappresenta sempre lo stesso elemento fisico. La forma di un'onda non deve dipendere da come la rappresento.
![[../File/todo da lezione 14/Pasted image 20220322092428.png]]
Quindi, anche l'equazione di D'Alembert non deve dipendere da come rappresento l'onda. => ![[../File/todo da lezione 14/Pasted image 20220322092527.png]]

#### Soluzione generica per onde sferiche

^f46285

![[../File/todo da lezione 14/Pasted image 20220322092550.png]]
Una _qualunque_ funzione di r-vt diviso r, moltiplicata per un _opportuna_ funzione Y, è sempre soluzione.
(DIMostrazione in basso)
Le funzioni Y sono date da:
![[../File/todo da lezione 14/Pasted image 20220322092805.png]]
Cioè, sono gli autovalori dell'operatore differenziale ![[../File/todo da lezione 14/Pasted image 20220322092823.png]] (che è una parte del laplaciano in coordinate sferiche).
Bene, questi Y sono chiamati _armoiniche sferiche_, e esistono in modo infinito ma numerabile.
Si può dimostrare che queste Y sono scritte in modo:
![[../File/todo da lezione 14/Pasted image 20220322092917.png]]
Con una parte che dipende da $\theta$ e una che dipende da $\phi$ (di fatto quest'ultima parte è semplicemente un fasore).
Ora, $m$ e $l$ _non_ sono indipendenti. $m$ va da $-l$ a $+l$, $l$ va da $0$  a $+\infty$.
^^ Di questa roba al massimo c'è da ricordare la prima riga delle robe sferiche.

Per fare un esempio, consideriamo l = 0 (=> m = 0). Prendiamo la prima riga nella foto ^^. La Y più semplice che risolve l'eq di d'alembert è data da (...).

Sempre ritornando [[#^f46285]], ![[../File/todo da lezione 14/Pasted image 20220322093355.png]], proprio come le onde piane.
Ora la seconda di queste due robe è un po' sus, visto che nelle coordinate polari r >= 0. Quindi rappresenta un onda che implode verso l'origine.

`DIM` ![[../File/todo da lezione 14/Pasted image 20220322093556.png]]
Semplicemente prendo $\nabla^2$ e lo applico a quella funzione. Osservo che tutta la parte angolare a destra si semplifica (?? come mai?):
![[../File/todo da lezione 14/Pasted image 20220322093629.png]]
e mi restano due derivate rispetto ad r da analizzare:
![[../File/todo da lezione 14/Pasted image 20220322093657.png]]
Insomma tutto il primo membro dell'eq. di D'alembert mi resta la derivata seconda della mia funzione f iniziale. A destra, succede:
![[../File/todo da lezione 14/Pasted image 20220322094002.png]]