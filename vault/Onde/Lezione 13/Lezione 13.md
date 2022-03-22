### Onde nello spazio tridimensionale
Vediamo cosa succede alle onde nello spazio 3D. Prendiamo sempre come equazione di riferimento l'[[../Note/Equazione di D'Alembert]].
![[Pasted image 20220321151342.png]]
Come si estende la trattazione allo spazio 3d?
![[Pasted image 20220321151414.png]]
Visto che aggiungiamo coordinate, la mia funzione d'onda diventa una funzione del tipo:
![[Pasted image 20220321151516.png]]
Bene, qual è l'equazione che mi estende la roba unidimensionale alle 3 dimensioni?
(E sottolineo _estende_, visto che molti dei casi che abbiamo visto per i casi unidimensionali, dovranno poter essere descritti anche in uno spazio 3d).

Andiamo a ricavare la soluzione "per simpatia".
![[Pasted image 20220321151640.png]]
^^ La mia derivata seconda della x, dovrà diventare una combinazione delle tre derivate parziali rispetto a x, y, z. In questo modo mantengo l'indipendenza lungo le 3 dimensioni. Tante caratteristiche che aveva l'eq. di D'alembert in una dimensione me le ritroverà in 3 dimensioni.
`OSS` Quella roba qua sopra, in realtà non è altro che il [[../Note/Operatore Laplaciano]] di $\vec r$.

#### `TMH` Equazione di d'Alembert in tre dimensioni
![[Pasted image 20220321151948.png]]

In più, questa roba gode delle seguenti proprietà:
EDO differenziale in variabili, alle _derivate seconde_, _lineare_ (vale [[Principio di Sovrapposizione]]) e _omogenea_.
Posso quindi associare anche a questa equazione un [[../../Algebra/Note/Operatori lineari|operatore lineare]]:
![[Pasted image 20220321152211.png]]
Questo operatore è noto come _Operatore di D'Alembert/d'Alembertiano_, ed è indicato con il quadratino: $\square$. 
Vediamo come si applica questa roba alle onde che conosciamo: ci aspettianom che questa eq in 3d abbia come limite l'eq. di d'Alembert in una dimensione:
![[Pasted image 20220321152449.png]]
Devo ritrovare esattamente la mia stessa equazione di d'alembert in una dimensione.
![[Pasted image 20220321152507.png]]
Troviamo proprio quello che ci aspettiamo.

Ora, vediamo come si comportano le soluzioni in tre dimensioni:
![[Pasted image 20220321152713.png]]
Si verifica che (non lo dimostriamno):
![[Pasted image 20220321152732.png]]
Per ogni direzione $\hat u$ nello spazio 3d, per ogni funzione [[continua]] e derivabile due volte, le due funzioni lì sopra $f$ e $g$ _sono soluzioni_.
Se al posto di $\hat u$ ci mettiamo $\hat x$, ci ritroviamo proprio nel caso unidimensionale. 

Andiamo ad analizzare quello che succede per le onde di tipo progressivo. Chiamo S 

oh no mi sono distratto un attimo porcodio che cabbo ha detto
![[Pasted image 20220321153201.png]]

![[Pasted image 20220321153211.png]]
A secondo membro succede la stessa cosa di quello che vedo in una dimensione:
![[Pasted image 20220321153345.png]]
. Insomma per ogni funzione di questo tipo,
![[Pasted image 20220321153426.png]]
Questa funzione di soluzione è 
![[Pasted image 20220321153438.png]]
E chiamiamo questa roba 
![[Pasted image 20220321153448.png]]. ![[Pasted image 20220321153522.png]]

Vediamo ora di capire come sono fatte queste onde.
Partiamo semplificandoci la vita, scegliendo onde a due dimensioni:
![[Pasted image 20220321153626.png]]
(prendiamo dei versori nel piano $O_{xy}$).
L'argomento della funzione contiene un prodotto scalare, quindi ottengo $xu_x + yu_y$... Quindi l'onda $\xi(\vec r,\ t)$ si scrive così (^^).
Facciamo un esempio di questa roba con una funzione semplice (prendiamo un onda impulsiva, a un solo massimo).
![[Pasted image 20220321153754.png]]
![[Pasted image 20220321153815.png]]
. Mi metto quindi sul piano xy. Piazzo il mio versore \hat u a caso. 
![[Pasted image 20220321153921.png]]
![[Pasted image 20220321154137.png]]
(???)
_Il luogo dei punti con la stessa ampiezza/fase è un piano._
Queste onde, vengono chiamate _onde piane_. 
![[Pasted image 20220321154534.png]]
Il luogo dei punti di uguale ampiezza è detto _fronte d'onda_. Queste onde qui, sono appunto dei piani che in linea di principio si estendono su tutto l'universo.

Queste robe qua, spesso e volentieri sono _approssimazioni_ di quello che succede nella realtà. Facciamo un esempio:
a volte sembra che le onde provengano da un punto. Molto lontano dal punto c'è un microfono. 
![[Pasted image 20220321154747.png]]
Il microfono ha un area di pochi millimetri. Quindi, questa roba _non distingue_ dall'onda piana che sta arrivando. Ceh, l'onda effettiva magari è sferica, però _localmente sembra un onda piana._ 
Questo vale anche se la sorgente non è un punto, ma qualcosa di più complicato:
![[Pasted image 20220321154845.png]]

Quindi, prendiamo queste onde _non_ come una rappresentazione della realtà, ma come un'approssimazione di quello che sta succedendo, magari all'interno di un laboratorio.

### Onde armoniche piane
Come abbiamo fatto nel caso unidimensionale, ad un certo punto noi siamo passati da un'onda progressiva alle onde armoniche (ricordo: _ogni onda può essere rappresentata come somma di onde armoiniche, con la serie di fourier_). Anche nello spazio 3d, qualunque funzione _può essere rappresentata come una sovrapposizione di onde amroiniche_:
![[Pasted image 20220321155054.png]]
Nel caso di un onda piana, io posso scrivere un _onda armonica piana_. L'unica cosa che cambia essenzialmente è l'argomento, dove stavolta compare un prodotto scalare.

##### `DEF` Vettore d'onda:
![[Pasted image 20220321155241.png]]

_ATTENZIONE_ NOn confondere $\vec k$ con il versore dell'asse z: $\hat k$
![[Pasted image 20220321155452.png]]
![[Pasted image 20220321155517.png]]
QUindi la soluzione più generica possibile dell'equazione di d'alembert è una somma di onde armoniche. Nota che sopra i $\vec k$ possono essere diversi. Quando questa sommatoria viaggia su un insieme discreto, parlerò di _insieme di fourier_ e quando su un insieme contionuo (???).