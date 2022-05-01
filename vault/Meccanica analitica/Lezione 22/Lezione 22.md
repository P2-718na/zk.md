Cambio di coordinate: devo fissare in maniera univoca x, y, z e viceversa (il viceversa in realtà potrebbe non essere richiesto su tutte le possibili configurazioni, visto che le coordinate in ogni caso hanno un carattere locale.)
![[Pasted image 20220406141528.png]]
Qui, come sempre per le coord sfetiche. l'origine è un punto singolare perchè per r=0, qualunque valore di \varphi da l'origine => se volessimo studiare il nostro sistema in quel punto, dovremmo studiare quel punto separatamente e vedere che succede.

In più, le mie 3 cpprdomnate devpno essere indipendenti (la scelta di r, NON deve in nessun modo influire sulla scelta di \varphi). La parte _difficile_ è la scelta delle coordinate, visto che devo effettivamente andare lì e pensarci. Le altre parti, invece, vanno da sé quasi in automatico.

==> Scrivo la lagrangiana

Attento ai segni. Alla fine ricorda che noi stiamo cercando solamente solo soluzioni _fisiche_. Se un (-) rende una soluzione _non fisica_, allora non la consideriamo


![[Pasted image 20220406145640.png]]
Se io prendo una matrice 3x3 antisimmetrica e ci faccio l'esponenziale, ho che:

(l'esponenziale di a ) trasposto = esponenziale di (a trasposto) = esponenziale di (-A)

Quando ho un autovettore con autovalore = 1 vuol dire che quel coso è invariante per applicazioni della matrice. Questo vuol dire che qualunque cosa io stia facendo, ci sarà sempre un asse che rimane fisso.
![[Pasted image 20220406150010.png]]
Quest'asse è quello corrispondente all'autovalore = 1 nella matrice di rtazione o all'autovalore = 0 nella sua rappresentazione attraverso matrice antisimmetrica.

Questo fatto qui vuol dire che, in ogni movimento di rotazione che io posso fare, esiste sempre un asse _istantaneo_ di rotazione fisso (tale che io sto ruotando attorno a quell'asse). Istantaneamente io sto ruotando sempre attorno ad un solo asse. Se fossi in uno spazio 4d, questa cosa _non_ sarebbe vera.

Ora, a questo punto, una matrice di rotazione, quindi, istantaneamente è una rotazione attorno ad un asse => Se identifico l'asse la matrice mi identifica la rotazione attorno a quell'asse lì.

La matrice quindi mi p identificata dalla matrice di rotazione e dalla rotazione attorno a quell'angolo lì (??)

?? 

QUesto inrealtà mi dice che _le rotazioni infinite non commutano_, mentre le _le rotazioni infinitesime commutano_. Il fatto che le rotazioni infinitesime commutino, significa dal punto di vista fisico che noi poossiamo _sommare vettorialmente_ velocità angolari.

_Il prodotto vettoriale esiste solamente nello spazio 3D_ e deriva dal fatto che nello spazio 3d c'è un isomorfismo tra matrici antisimmetriche 3x3 e vettori a 3 coordinate.


Cosa interessante: i prodotti misti in realtà hanno un significato fisico ben definito: sono volumi di base prod vettoriale per altezza (??)
Oppur eosservo anche che questo è il determinante di una matrice 3x3 costurita da questi vettori
![[Pasted image 20220406153905.png]]
Questa cosa è interessante perchè il volume (= determinante di una matrice 3x3) non cambia per permutazioni cicliche della matrice (faccio "scalare ciclicamente i vettori"). `DEF` permutazione ciclica: numero pari di scambi

\[Il gatto di bazzani muore durante la lezione\]

## Lezione 23
\[Il gatto di bazzani muore durante la lezione\]
Dobbiamo scrivere il potenziale del campo magnetico. Sappiamo che il campo magnetico ammette il campo vettore. E sappiamo che la forza di Lorentz è data dalla sua formula.
![[Pasted image 20220407152813.png]]
(dove qui il fattore 1/c è inserito perchè bazzani è un teorico)
![[Pasted image 20220407152951.png]]
^^ ricordo che il rotore non è un vettore, ma solo un operatore. Bene, vogliamo dimostrare che (??).
Voglio esplicitare che dentro alla relazione della forza, al posto di b ci metto il vettore.

=> La forza di Lorentz si può ottenere da un potenziale generalizzato facendo ??