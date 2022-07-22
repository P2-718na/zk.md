### Onde nello spazio tridimensionale
Le onde nello spazio tridimensionale seguono essenzialmente la stessa equazione che abbiamo visto per lo spazio 1-dimensionale. Si dimostra infatti che vale come equazione delle onde:

#### `TMH` Equazione di d'Alembert in tre dimensioni
![[../File/todo da lezione 13/Pasted image 20220321151948.png]]
Le soluzioni di questa rquazione sono ricavate in: [[Soluzioni per le onde tridimensionali]].
Questa equazione è una [[EDO]] _alle derivate seconde_, _lineare_ e _omogenea_.

Queste proprietà mi permettono di associare a questa equazione l'[[../../Algebra/Note/Operatori lineari|operatore lineare]]:
##### `DEF` Operatore D'Alembertiano
![[../File/todo da lezione 13/Pasted image 20220321152211.png]]
Indicato con il quadratino: $\square$. 

### Estendere l'equazione di D'Alembert alle tre dimensioni
Vediamo cosa succede alle onde nello spazio 3D. Prendiamo sempre come equazione di riferimento l'[[Equazione di D'Alembert]].
Per estendere la trattazione nello spazio 3D, inizio trasformando la mia $x$ in un raggio vettore $\vec r$:
![[../File/todo da lezione 13/Pasted image 20220321151414.png]]
Visto che aggiungiamo coordinate, la mia funzione d'onda diventa ora una funzione vettoriale a valori scalari:
![[../File/todo da lezione 13/Pasted image 20220321151516.png]]
Ora, quella che prima era una derivata spaziale rispetto alla sola $x$, ora diventerà una combinazione delle tre derivate parziali rispetto ai tre versori $\hat x$, $\hat y$, $\hat z$, in modo da mantenere l'indipendenza lungo le tre direzioni:
![[../File/todo da lezione 13/Pasted image 20220321151640.png]]
Così facendo, mi ritrovo le stesse caratteristiche dell'eq. unidimensionale nelle tre dimensioni.
Osservo che quello che ho scritto sopra non è altro che l'[[Operatore Laplaciano]] applicato a $\vec r$: $\nabla^2 \vec r$ e da qui ottenco proprio la mia equazione in tre dimensioni vista sopra.

Eee niente, sperimentalmente ok questa cosa funziona.

`OSS` Questa roba ha come limite unidimensionale l' [[Equazione di D'Alembert]]:
![[../File/todo da lezione 13/Pasted image 20220321152449.png]]
Devo ritrovare esattamente la mia stessa equazione di d'alembert in una dimensione.
![[../File/todo da lezione 13/Pasted image 20220321152507.png]]