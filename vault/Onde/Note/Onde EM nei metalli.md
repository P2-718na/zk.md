### Propagazione in un metallo
![[Pasted image 20220502141620.png]]
Prendiamo le equazioni di maxwell generali, adattiamole al caso per o conduttori. Sappiamo che la densità di carica è nulla, e la daensità di corrente vale \sigma \vec E.
Ora, questo sistema di equazioni è lineare _nella coppia (\vec E, \vec B)_. e omogeneo.
Ora, adiamo a vedere quali sono le equazioni delle onde in questo nuovo sistema di equazioni. 
Faccio esattamente lo stesso percorso che ho fatto la stessa volta in [[?? link]], prendo l'operatore rotore a entrambe i membri:
![[Pasted image 20220502142110.png]]
E questa volta osservo che non ritrovo l'equazione di D'Alembert:
![[Pasted image 20220502142138.png]]
Qui c'è un termine in più (guardacaso è proporzionale a sigma). Tutte le volte però in cui quel parametro sigma sarà vicino a zero, io ritrovo l'equazione di d'alembert.
(= quando la conducibilità elettrica va a zero, io in realtà mi trovo nel dominio dei materiali isolanti).

Ora, che caratteristica avrà mai un'onda armonica piana che entra in un metallo?
![[Pasted image 20220502142651.png]]
![[Pasted image 20220502142656.png]]
Senza mettere nessun altro particolare constraint, voglio vedere cosa mi esce fuori solamente da queste equazioni di Maxwell.
Ora, ricordando che l'operatore divergenza e rotore in un onda armonica piana valgono rispettivamente (moltiplicazione per ik) e (prodotto vettoriale per ik) (foto sopra).

Quindi, applicando queste proprietà delle onde armoniche ottengo:
![[Pasted image 20220502142817.png]]
Le prime tre sono identiche a quello che succede nel vuoto. Il pezzo in più sta nell'ultima.
In particolare, le due divergenze mi danno l'informazione che:
![[Pasted image 20220502143053.png]]
le onde EM sono trasversali anche nel metallo.
la seconda, ci dice che la direzione di B è perpendicolare sia a k che ad E. => E, B, k formano la stessa _terna destrorsa_ che abbiamo visto nelle onde EM nel vuoto.
La cosa che cambia è nell'ultima equazione. Il fatto che sia presente un coefficiente complesso ci dice che il nostro k non può essere reale, ma _deve avere una componente immaginaria_. La componente immaginaria di k fa sì che qua dentro (?) ci siano due fasi diverse, e che quindi campi E e B oscillano _non in fase_.
Vediamo come:
![[Pasted image 20220502143312.png]]
Ora partiamo dalla seconda.
![[Pasted image 20220502143325.png]]
B lo posso ritrovare dalla prima equazione, vado a sostituire. Uso il BAC-CAB
Alla fine resto con un espressione dove ho uno scalare che moltiplica il campo elettrico (ik?2/w...) per un altro scalare c
??
![[Pasted image 20220502143616.png]]
yeet
Qualcosa sul raccogliere i termini
Il passo successivo è scrivere k come radice di tutta questa roba:
![[Pasted image 20220502143714.png]]
Perchè abbiamo voluto mettere in evidenza w/v?Perchè qui si vede bene la relazione con sigma . Se la conducibilità è zero, Trovo k = w/v come avevamo visto fino ad ora. Se sigma non è zero, il mnostro metallo si comporta come mezzo dispersivo.
La nostra velcoità di fase dipende effettivamente dalla pulsazione.
Un'altra cosa da osservare è che questo k sarà un numero complesso. Io lo posso scrivere come (parte reale) + i(parte immaginaria). Qui, a differenza con i dielettrici, mi viene un segno + e non -: questo dipende dall'espressione esponenziale con cui sono partito.
![[Pasted image 20220502144047.png]]

__Assorbimento dell'onda nel metallo:__
Ora, questo k immaginario funziona esattamente come nei dielettrici: mi descrive un assorbimento. Come faccio a vederlo?
![[Pasted image 20220502144132.png]]
![[Pasted image 20220502144136.png]]
![[Pasted image 20220502144231.png]]

Qui posso fare roba
![[Pasted image 20220502144240.png]]
QUindi, questo termine mi sta a dire che quando la mia onda arriva in un metallo, la mia ampiezza diminuisce pian piano.
Ma io mi aspetto che succeda questo, visto che nel momento in cui l'onda entra nel mio dielettrico, questa mette in moto degli elettroni. Quindi, come abbiamo fatto l'altra volta, possiamo definire un coefficiente di assorbimewnto \mu e vedere come varia l'intensità in funzione di \mu.
![[Pasted image 20220502144732.png]]
![[Pasted image 20220502144738.png]]
Il fatto che k sia complesso, vuol dire che questo k lo posso scrivere come modulo moltiplicato per una certa fase. Questo vuol dire che tra i due campi c'è questa fase aggiuntiva. Quindi, qui io sto rappresentato quello che succede dentro ad un metallo per un onda elettromagnetica, dove la roba oscilla sul piano x, z. Ilcampo B oscilla in y, z. C'è iun fattore di assorbimento (i due campi decrescono in maniera esponenziale). Attenzione: nei metalli (e non nei duelettrici, oltre a questa cosa che è l'assorbimento, ho anche il fatto che il campo elettrico e magnetico non sono più in fase.)

Bene, cosa ce ne facciamo di tutte queste belle cose?
Beh, ci aiutano a capire alcuni dispositivi, come i polarizzatori: