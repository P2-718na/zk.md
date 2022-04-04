### Onde nello spazio tridimensionale
Vediamo cosa succede alle onde nello spazio 3D. Prendiamo sempre come equazione di riferimento l'[[../Note/Equazione di D'Alembert]].
![[../File/todo da lezione 13/Pasted image 20220321151342.png]]
Come si estende la trattazione allo spazio 3d?
![[../File/todo da lezione 13/Pasted image 20220321151414.png]]
Visto che aggiungiamo coordinate, la mia funzione d'onda diventa una funzione del tipo:
![[../File/todo da lezione 13/Pasted image 20220321151516.png]]
Bene, qual è l'equazione che mi estende la roba unidimensionale alle 3 dimensioni?
(E sottolineo _estende_, visto che molti dei casi che abbiamo visto per i casi unidimensionali, dovranno poter essere descritti anche in uno spazio 3d).

Andiamo a ricavare la soluzione "per simpatia".
![[../File/todo da lezione 13/Pasted image 20220321151640.png]]
^^ La mia derivata seconda della x, dovrà diventare una combinazione delle tre derivate parziali rispetto a x, y, z. In questo modo mantengo l'indipendenza lungo le 3 dimensioni. Tante caratteristiche che aveva l'eq. di D'alembert in una dimensione me le ritroverà in 3 dimensioni.
`OSS` Quella roba qua sopra, in realtà non è altro che il [[../Note/Operatore Laplaciano]] di $\vec r$.

#### `TMH` Equazione di d'Alembert in tre dimensioni
![[../File/todo da lezione 13/Pasted image 20220321151948.png]]

In più, questa roba gode delle seguenti proprietà:
EDO differenziale in variabili, alle _derivate seconde_, _lineare_ (vale [[Principio di Sovrapposizione]]) e _omogenea_.
Posso quindi associare anche a questa equazione un [[../../Algebra/Note/Operatori lineari|operatore lineare]]:
![[../File/todo da lezione 13/Pasted image 20220321152211.png]]
Questo operatore è noto come _Operatore di D'Alembert/d'Alembertiano_, ed è indicato con il quadratino: $\square$. 
Vediamo come si applica questa roba alle onde che conosciamo: ci aspettiamo che questa eq in 3d abbia come limite l'eq. di d'Alembert in una dimensione:
![[../File/todo da lezione 13/Pasted image 20220321152449.png]]
Devo ritrovare esattamente la mia stessa equazione di d'alembert in una dimensione.
![[../File/todo da lezione 13/Pasted image 20220321152507.png]]
Troviamo proprio quello che ci aspettiamo.

Ora, vediamo come si comportano le soluzioni in tre dimensioni:
![[../File/todo da lezione 13/Pasted image 20220321152713.png]]
Si verifica che (non lo dimostriamo):
![[../File/todo da lezione 13/Pasted image 20220321152732.png]]
Per ogni direzione $\hat u$ nello spazio 3d, per ogni funzione [[continua]] e derivabile due volte, le due funzioni lì sopra $f$ e $g$ _sono soluzioni_.
Se al posto di $\hat u$ ci mettiamo $\hat x$, ci ritroviamo proprio nel caso unidimensionale. 

Andiamo ad analizzare quello che succede per le onde di tipo progressivo. Chiamo S 

oh no mi sono distratto un attimo porcoddio che cabbo ha detto
![[../File/todo da lezione 13/Pasted image 20220321153201.png]]

![[../File/todo da lezione 13/Pasted image 20220321153211.png]]
A secondo membro succede la stessa cosa di quello che vedo in una dimensione:
![[../File/todo da lezione 13/Pasted image 20220321153345.png]]
. Insomma per ogni funzione di questo tipo,
![[../File/todo da lezione 13/Pasted image 20220321153426.png]]
Questa funzione di soluzione è 
![[../File/todo da lezione 13/Pasted image 20220321153438.png]]
E chiamiamo questa roba 
![[../File/todo da lezione 13/Pasted image 20220321153448.png]]. ![[../File/todo da lezione 13/Pasted image 20220321153522.png]]

Vediamo ora di capire come sono fatte queste onde.
Partiamo semplificandoci la vita, scegliendo onde a due dimensioni:
![[../File/todo da lezione 13/Pasted image 20220321153626.png]]
(prendiamo dei versori nel piano $O_{xy}$).
L'argomento della funzione contiene un prodotto scalare, quindi ottengo $xu_x + yu_y$... Quindi l'onda $\xi(\vec r,\ t)$ si scrive così (^^).
Facciamo un esempio di questa roba con una funzione semplice (prendiamo un onda impulsiva, a un solo massimo).
![[../File/todo da lezione 13/Pasted image 20220321153754.png]]
![[../File/todo da lezione 13/Pasted image 20220321153815.png]]
. Mi metto quindi sul piano xy. Piazzo il mio versore \hat u a caso. 
![[../File/todo da lezione 13/Pasted image 20220321153921.png]]
![[../File/todo da lezione 13/Pasted image 20220321154137.png]]
(???)
_Il luogo dei punti con la stessa ampiezza/fase è un piano._
Queste onde, vengono chiamate _onde piane_. 
![[../File/todo da lezione 13/Pasted image 20220321154534.png]]
Il luogo dei punti di uguale ampiezza è detto _fronte d'onda_. Queste onde qui, sono appunto dei piani che in linea di principio si estendono su tutto l'universo.

Queste robe qua, spesso e volentieri sono _approssimazioni_ di quello che succede nella realtà. Facciamo un esempio:
a volte sembra che le onde provengano da un punto. Molto lontano dal punto c'è un microfono. 
![[../File/todo da lezione 13/Pasted image 20220321154747.png]]
Il microfono ha un area di pochi millimetri. Quindi, questa roba _non distingue_ dall'onda piana che sta arrivando. Ceh, l'onda effettiva magari è sferica, però _localmente sembra un onda piana._ 
Questo vale anche se la sorgente non è un punto, ma qualcosa di più complicato:
![[../File/todo da lezione 13/Pasted image 20220321154845.png]]

Quindi, prendiamo queste onde _non_ come una rappresentazione della realtà, ma come un'approssimazione di quello che sta succedendo, magari all'interno di un laboratorio.