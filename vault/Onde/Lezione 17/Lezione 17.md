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

### Produzione delle onde EM
Allora, partiamo dal generatore di campo EM: una carica.
PRendiamo quindi una carica. Facciamo l'ipotesi che la mia carica sia positiva, ferma nell'origine, Cosa succede? Questa genera un campo elettrostatico radiale in tutto lo spazio (_aspettando un po' di tempo..._)
![[Pasted image 20220411151913.png]]
![[Pasted image 20220411151958.png]]
In questo caso non posso avere un onda elettromagnetica, visto che le leggi della fisica devono essere le stesse in tutti i sistemi di riferimento.
A dirci che non si generano onde EM, c'è anche il fatto che le onde EM trasportano energia, ma una carica che si muove di moto rettilineo uniforme non è che può produrre energia => se ci fossero le onde EM così io avrei energia prodotta dal nulla.

Allora rimane un solo caso: onde EM prodotte da un moto arbitrario (sostanzialmente, a noi ci interessa il fatto che sia accelerato).
Cominciamo perciò a vedere come funziona.
Immaginiamo di avere una carica _ferma_ al tempo $t = 0$. ![[Pasted image 20220411152252.png]]
Prima del tempo $t=0$ la carica era ferma in origine, e stava emettendo un campo Elettrico uniforme. Ora, pensiamo di spostarla al tempo t0 verso destra, di un moto accelerato, per un certo tempo \delta t (e dopo diciamo che si ferma).
![[Pasted image 20220411152351.png]]
Ora, lei che si è mossa non emetterà più il campo ES dal punto originale, ma lo emetterà dal punto in cui si trova ora. Per un certo periodo (mentre si muove la carica) non si genera campo ES, quindi non posso sapere bene come sono fatte le linee di campo.
Al di fioro di questo cerchio (orizzonte degli eventi), la perturbazione reseta sempre uguale a prima che la mia particella si muovesse.
![[Pasted image 20220411152514.png]]
((qui ci sarebbero le animazioni dalle slide che vanno prese))
Ora vediamo cosa succede per un \delta t << t:
![[Pasted image 20220411152543.png]]
![[Pasted image 20220411152552.png]]
Intanto, la mia carica inizia a emetter un nuovo campo ES radiale dal nuovo punto di origine. QUesto stato del sistema, però, è diverso da prima (le direzioni delle linee di campo sono differenti, non parallele)![[Pasted image 20220411152633.png]]
Il punto però è che le linee di campo non possono avere disposizioni tali (devono essere continue). Come si raccordano quindi? Devo trovare un modo per collegarle...
![[Pasted image 20220411152709.png]]
Nella regione "sconosciuta" ci dovranno essere delle linee di campo fatte così (come la linea rossa) e qui le linee di campo non saranno radiali.
Bene, cerchiamo di capire bene cosa succede in questa regione, dove ci sono queste linee di campo non radiali.
La domanda quindi è: come raccordiamo il segmento? Lo facciamo nell'approssimazione in cui la velicità media con cui si muove la carica (media perchè il moto è accelerato) sia molto minore di c.
In questo caso, se le linee di collegamento devono essere fatte come ^^:
![[Pasted image 20220411152939.png]]
![[Pasted image 20220411153444.png]] 
?? questa parte ho seguito poco
 ![[Pasted image 20220411153514.png]]
 POSSo esprimere in questo modo il campo di radiazione
 ![[Pasted image 20220411153738.png]]
 ??? Posso fare un ipotesi che il moto di radiazione è impulsivo
 ![[Pasted image 20220411153916.png]]
 Oppure posso fare un ipotesi che il moto sia armonico.
 
 tutto questo per dire che cosa?
 La linea di campo che collega i due campi deve dare luogo ad una componente di campo trasversa, che noi chiamiamo "campo di radiazione".
Bene, questa roba, se ci pensiamo, è proprio la _componente dell'onda EM_.

Minimop di applicazione: generatore di un onda EM. Ci sono infiniti modi di generarla:
vv Dipolo di Hertz
![[Pasted image 20220411154328.png]]![[Pasted image 20220411154610.png]]

![[Pasted image 20220411154710.png]]
![[Pasted image 20220411154934.png]]
![[Pasted image 20220411155045.png]]
Ricordo che questa forma non indica la velocità di propagazione dell'onda, ma indica solamente l'intensità. => L'onda sarà più intensa all'equatore, poi calerà lungo i bordi e sarà zero ai poli.
![[Pasted image 20220411155155.png]]
?????? Tutte queste cose ho seguito poco.
Per concludere possiamo vedere anche la variazione media di energia lungo una superficie:
![[Pasted image 20220411155415.png]]
![[Pasted image 20220411155755.png]]