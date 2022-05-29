### Pressione di Radiazione
(richiami alle onde EM e all'energia delle onde EM).
In particolare, abbiamo visto che il vettore di poynting trasporta energia, visto che la media del vettore non è nulla.
![[Pasted image 20220411142049.png]]
Per capire questa cosa, vediamo di analizzare come si comporta una particella carica che viene investita da un onda elettromagnetica.
Caso più semplice, consideriamo un onda EM del tipo:
![[Pasted image 20220411142249.png]]
Ora immaginiamo che quest'onda si propaghi nel vuoto fino a che non incontri una carica libera. Per farla semplice, prendiamo questa carica come se fosse nell'origine di un sistema di assi cartesiani.
![[Pasted image 20220411142403.png]]
Se la carica _è ferma_, il campo magnetico inizialmente non fa nulla (serve che la carica si muova). Però il campo elettrico interagisce. Vediam ocome:
Ipotizziamo di trovarci quindi in una condizione come quella riportata in figura.
Il campo elettrico applica quindi una forza del tipo \vec F = q \vec E lungo la direzione \hat x.
La forza EM induce una velocità, e quindi una _forza di Lorentz_.
![[Pasted image 20220411142623.png]]
La forza di Lorentz è lungo l'asse positivo delle \hat z (e quindi concorde con il moto dell'onda).
Riassumendo, avremo due componenti della forza: una concorde al campo elettrico e una parallela al moto dell'onda.
![[Pasted image 20220411142709.png]]
=> La risultante sarà diagonale.
Se l'oscillazione è opposta, ritrovo sempre lo stesso risultato per \vec B ma risultato opposto per \vec E:
![[Pasted image 20220411142809.png]]
Se la carica è negativa, ottengo sempre lo stesso risultato per la forza di Lorentz (in entrambi i casi):
![[Pasted image 20220411142953.png]]
Quindi, ricapitolando, _per una carica libera nello spazio, le cose funzionano così. In particolare, la forza di Lorentz è sempre nello stesso verso_.

Ora, vediamo cosa succede in un caso più reale (per esempio, lastra metallica con cariche libere).
Immaginiamo di avere una piastra metgallica di superficie \Sigma su cui sojno disposte delle cariche libere.
Arriva un onda em, e agisce sulla piastra. Som,mando l'effetto che ha su ogni elettrone, avremo che l'effetto di forza totale sarà dato da (vv formula in fondo).
![[Pasted image 20220411143230.png]]
Ora, la forza di Lorentz qua sarà molto piccola. Però, nonostante sia piccola, tenderà comunque a spingere le cariche (e quindi la piastra) sempre nella stessa direzione.
![[Pasted image 20220411143509.png]]
Ora, calcoliamo la potenza media assorbita dagli elettroni (vv prima eq.). Facciamo il calcolo con \vec F \cdot \vec v. Osservo poi che \vec v è sempre perpendicolare a \vec v \times \vec B, quindi lo tolgo.
Il risultato è quindi che _la forza magnetica non contribuisce alla potenza assorbita dell'onda_. (Mi aspetto questo visto che il campo magnetico è solenoidale e non fa lavoro) vv. A questo punto, andiamo a vedere (vv seconda eq) com'è la pressione data da questa forza (dopotutto, stiamo definendo la _pressione di radiazione_.) Nel calcolo vado a sostituire \frac {Nq} \Sigma con \sigma (densità superficiale di carica).
Ora faccio un ultima ipotesi (che mi permette di generalizzare il tutto): l'onda elettromagnetica viene completamente assorbita dalla piastra. Questo implica che (vv ultima equazione, posso prendere P = quello calcolato prima, grazie a questa assunzione).
![[Pasted image 20220411143533.png]]
Ora, è ragionevole che un onda EM venga assorbita completamente da un materiale? Beh sì, per esempio, per la luce un onda viene completamente assorbita nei mezzi opachi.

Ora che abbiamo visto questo, vediamo un attimo in dettaglio come legare questa cosa, chiedendoci _dove va a finire la forza di Lorentz_.
Ora, noi sappiamo che indipendentemente dalla fase, la forza di Lorentz spinge sempre nella stessa direzione. Posso dire quindi che, in media la forza totale è uguale solamente alla forza di Lorentz magnetica, visto che la parte dipendente dal campo elettrico in media oscilla e quindi è zero:
![[Pasted image 20220411144145.png]]
Cosa significa questo? Inizio a fare delle approssimazioni per capire _in ordini di grandezza_ di cosa sto parlando.
Prendiamo delle onde EM "normali", che si vedono tutti i giorni (es. ordine MHZ). Osservo che queste onde hanno una frequenza elevata => la velocità di inversione del campo elettrico è molto veloce. L'intensità del campo/onda è (per il campo magnetico è modulo di B, quindi è) E/c.
Bene, visto che queste oscillazioni (delle particelle) sono minori della velocità della luce, possiamo dire che il risultato della forza magnetica sia molto inferiore a quella elettrica <= rispetto al campo elettrico, il modulo del campo magnetico è 1/c => la forza elettrica è dominante rispetto a quella di Lorentz.
Ora, se la forza elettrica domina, è lecito immaginare che anche la componente velocità indotta da E sia maggiore della \vec v indotta da \vec B.
(?? continuando a fare i calcoli e sfruttando il fatto che \vec v ha la stessa direzione di \vec E, arrivo all'espressione finale??)
![[Pasted image 20220411144408.png]]
^^ Nell'ultima riga di sotto, usiamo sigma che fa robe pazze. ??

##### Applicazioni
![[Pasted image 20220411145024.png]]
^^ Bolla di vetro con dentro il vuoto. CI sono le palette nere/riflettenti.  Se schematizziamo la luce come fotoni (quantizzati) e immaginiamo di sparare la luce all'affare, è come se la luce compisse urti elastici nel lato riflettente, anelastico nell'affare nero. Ora, un urto _elastico_ in realtà trasferisce più impulso. Il problema di questo affare è che in realtà si mette a muovere in senso orario (come se gli urti che trasferiscono più impulso sono quelli anelastici). La spiegazione di questo fenomeno è che in realtà qui _non c'è il vuoto assoluto_, e quindi il moto è un effetto termodinamico (la luce sull'affare nero scalda di più le particelle di aria lì attorno e quindi il coso gira per l'effetto termico, non per l'effetto della pressione di radiazione).
![[Pasted image 20220411145031.png]]
