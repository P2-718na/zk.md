![[Pasted image 20220322091447.png]]
La cosa più naturale è la descrizione delle onde 3d come onde sferiche (ovvero: onde che partono da un punto solo). Questo punto diventa l'origine del nostro sistema di riferimento da cui hanno origine le onde.

È comodo usare le coordinate polari sferiche.
Ricordo che l'angolo $\theta$ è detto  angolo 1.

Qui c'è tutto il discorso su come si usano le coordinate polari sferiche.
Il risultato che si ottiene è questo:
![[Pasted image 20220322092145.png]]

E, _importante_, l' [[../Note/Operatore Laplaciano]] cambia forma.

Scelgo di avere la stessa rappresentazione per \xi, visto che comunque rappresenta sempre lo stesso elemento fisico. La forma di un'onda non deve dipendere da come la rappresento.
![[Pasted image 20220322092428.png]]
Quindi, anche l'equazione di D'Alembert non deve dipendere da come rappresento l'onda. => ![[Pasted image 20220322092527.png]]

#### Soluzione generica per onde sferiche

^f46285

![[Pasted image 20220322092550.png]]
Una _qualunque_ funzione di r-vt diviso r, moltiplicata per un _opportuna_ funzione Y, è sempre soluzione.
(DIMostrazione in basso)
Le funzioni Y sono date da:
![[Pasted image 20220322092805.png]]
Cioè, sono gli autovalori dell'operatore differenziale ![[Pasted image 20220322092823.png]] (che è una parte del laplaciano in coordinate sferiche).
Bene, questi Y sono chiamati _armoiniche sferiche_, e esistono in modo infinito ma numerabile.
Si può dimostrare che queste Y sono scritte in modo:
![[Pasted image 20220322092917.png]]
Con una parte che dipende da $\theta$ e una che dipende da $\phi$ (di fatto quest'ultima parte è semplicemente un fasore).
Ora, $m$ e $l$ _non_ sono indipendenti. $m$ va da $-l$ a $+l$, $l$ va da $0$  a $+\infty$.
^^ Di questa roba al massimo c'è da ricordare la prima riga delle robe sferiche.

Per fare un esempio, consideriamo l = 0 (=> m = 0). Prendiamo la prima riga nella foto ^^. La Y più semplice che risolve l'eq di d'alembert è data da (...).

Sempre ritornando [[#^f46285]], ![[Pasted image 20220322093355.png]], proprio come le onde piane.
Ora la seconda di queste due robe è un po' sus, visto che nelle coordinate polari r >= 0. Quindi rappresenta un onda che implode verso l'origine.

`DIM` ![[Pasted image 20220322093556.png]]
Semplicemente prendo $\nabla^2$ e lo applico a quella funzione. Osservo che tutta la parte angolare a destra si semplifica (?? come mai?):
![[Pasted image 20220322093629.png]]
e mi restano due derivate rispetto ad r da analizzare:
![[Pasted image 20220322093657.png]]
Insomma tutto il primo membro dell'eq. di D'alembert mi resta la derivata seconda della mia funzione f iniziale. A destra, succede:
![[Pasted image 20220322094002.png]]

### Onde armoniche sferiche
![[Pasted image 20220322094219.png]]
k è sempre un numero d'onda (scalare)
![[Pasted image 20220322094429.png]]

Ora, tra tutti i modi in cui può esserci una modulazione di ampiezza, noi la troviamo con una modulazione $\frac 1 r$. Qual è il significato fisico dell'andamento $\frac 1 r$?
osservo che quando una grandezza dipende da $\frac 1 {r^2}$, vuol dire che c'è una certa grandezza che si conserva (vale il teorema di Gauss). Qui ho $\frac 1 r$, quindi la situazione è diversa.

Ricordando l'[[../Note/Intensità di un'onda armonica|intensità di un onda armonica]] e l'[[Intensità di un onda sonora]]:
per le onde intensive prendevamo la potenza media.
Già nelle onde sonore prendo una potenza media per unità di superficie.
Nelle onde 3d, l'energia che viene immessa nell'onda in un punto dello spazio si distribuisce su regioni di un'onda sferica che diventa via via più grande:
![[Pasted image 20220322095043.png]]
![[Pasted image 20220322095142.png]]
Ottengo che ho una Intensità inversamente proporzionale a $r^2$.
A me però interessa descrivere questa intensità sempre con le stesse formule, quindi scrivo quella roba lì a destra nella foto.
Osservo che, quando prendo un punto dello spazio di un onda sferica, io _non riesco a distinguere_ se ho davvero un onda sferica o solo un onda ion un tubo. Quindi, la formula a destra che abbiamo trovato per le onde sonore deve essere valida anche per le onde sferiche.
![[Pasted image 20220322095327.png]]
È necessario, affinchè io abbia la conservazione dell'energia, che l'andamento dell'ampiezza sia del tipo $\frac 1 {r^2}$. Scrivo quindi l'intensità esplicitando lla mia dipendenza da $r^2$ e ottengo
![[Pasted image 20220322095437.png]]
Quindi, la risposta alla domanda _cosa ci fa lì il fattore $\frac 1 r$?_ la risposta fisica che si da è:
l'energia che viagga in un impulso sonoro/onda sferica, non viene persa durante la propagazione, ma rimane costante. Quell' $\frac 1 r$ serve per mantenere costante l'energia che si distribuisce su superfici sempre più grandi. L'A^2 deve compensare quello che fa la superficie, quindi $A^2 \propto \frac 1 {r^2}$ 

===
### Fine argomenti parziale
===

