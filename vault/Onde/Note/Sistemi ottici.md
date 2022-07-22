### Sistemi ottici
Si parla di sistemi ottici quando abbiamo più superfici (lenti/specchi) che interagiscono.

##### Aberrazioni
Effetti non previsti dalle nostre formule, dovute al fatto che noi in realtà stiamo approssimando (angoli piccoli, superfici sottili...).


__Partiamo considerando due lenti sottili vicine:__
![[Pasted image 20220517091532.png]]
Vicine == distanza piccola in confronto alle lunghezze focali.
Il punto immagine della prima lente diventa l'oggetto per la seconda lente. Nella foto, formule a sinistra delle lenti sono riferite alla prima. Quelle a destra sono riferite alla seconda.
Le distanze q' e p', quando abbiamo visto la lente spessa, si otteneva che erano uguali a L.
Se io ho lenti sottili vicine, e indico con l la distanza tra le due lenti, nell'ipotesi in cui la distanza va a zero, i vertici coincidono e sto misurando tutte le distanze dallo stesso punto.
Quindi, mettere L a zero equivale a imporre che p' = -q'.
(Ricorda le convenzioni sui segni!!).

Quindi, vado a sostutuire, sommo membro membro e ottengo la roba in rosso.

Ora, in realtà, fino ad ora non abbiamo considerato che la focale dipende dalla lunghezza d'onda. Quindi luce di diverso colore si comporta in modo leggermente diverso.
Ora, se io metto due lenti vicine, se i materiali sono scelti in maniera opportuna, si possono realizzare dei doppietti detti "doppietti acromatici", tale che questa focale ha una dipendenza dalla lunghezza d'onda _molto minore._

### Microscopio ottico
![[Pasted image 20220517092347.png]]
A noi interessano _lente obiettivo_ (piccola focale) e _lente oculare_ (focale maggiore).
Tutti i microscopi ottici sono costruiti per creare un immagine alla distanza migliore per vedere.
Vediamo un attimo com'è fatto:
![[Pasted image 20220517092455.png]]
Io ho lente obiettivo con focale piccola ( a sinistra). I due punti rossi sono i fuochi di questa lente.
A destra, ho la seconda lente, con i suoi due fuochi.
Sono entrambe lenti convergenti.
Chiamo L la distanza positiva tra i due fuochi più vicini. L'oggetto che voglio studiare lo metto a sinistra del primo fuoco.

La costruzione per immagini si fa una lente alla volta:
parto dalla prima lente e mi costruisco l'immagine di questo oggetto:
(freccia rossa piccolina).
Le lenti sono costruite in modo che l'immagine della prima lente capiti tra fuoco e centro della seconda lente.
Ora prendo i due raggi dalla mia immagine, li prioietto nello spazio oggetto e vedo che non convergono. => Lavoro quindi con i prolungamenti di questi due raggi. Questi finiscono a siniistra (freccia grande).
![[Pasted image 20220517092855.png]]
d_0 è la "distanza di migliore visione", che (per esempio nel microscopio) è fissata:
![[Pasted image 20220517093005.png]]
Nella pratica, la prima distanza p è approssimativamente uguale a f1, e la distanza p' viene spostata in modo che sia uguale a f2.
In questo modo, in ogni microscopio è quasi come se tutte le grandezze fossero fissate.

Un po' più in scala...
![[Pasted image 20220517093442.png]]
`OSS` Non si può salire a più di 1k per un microscopio ottico. Questo limite è legato alla diffrazione. Per esempio, per gli occhi:
![[Pasted image 20220517093539.png]]
(potere risolutivo).
Per il microscopio, sotto i 10um abbiamo problemi.

### Telescopio rifrattore
![[Pasted image 20220517093913.png]]
Prendo un fascio di raggi paralleli (verde). Questi convergono nel fuoco della prima. Lì ci metto il fuoco della seconda, e dopo la seconda lente se ne escono paralleli.
![[Pasted image 20220517093941.png]]
La cosa interessante è quando i raggi sono parallleli tra di loro, ma entrano con un certo agnolo \alpha rispetto ad asse ottico (in rosso).
Nelle approssimaxzioni solite (\alpha piccolo), questi raggi paralleli convergono in un unico punto sul piano focale.
Se i due fuochi delle due lenti coincidono, anche i due piani focali coincidono => la luce che arriva lì e converge nel punto, per la seconda lente è un oggetto che si trova sul piano focale. Tutti i raggi quindi arrivano a destra che sono paralleli.

Se considero solo un raggio, riesco a capire qual è l'ingrandimento di questo telescopio.
L'ingrandimento è di natura angolare:
![[Pasted image 20220517094154.png]]

### Cannocchiale galileiano
Poi arriva [[../../Relatività/Note/Galileo Galilei]] e costruisce il suo bel cannocchiale.
È essenzialmente la stessa cosa, con l'unica differenza che la lente oculare non  è convergente ma è divergente:
![[Pasted image 20220517094424.png]]
La lente divergente viene messa prima del piano focale. L'unica attenzione è che il fuoco della seconda lente ha una lunghezza convenzionalmente negativa, e si va quindi a lavorare sul secondo fuoco. L'immagine della prima lente è a roba a destra con h.
Quando costruisco l'immagine della seconda lente, tutto sembra provenire dal fuoco f2. Questo mi da un angolo \beta.
![[Pasted image 20220517094601.png]]

Un altra tecnica da usare è la 
### Lente di Barlow.
Cos'è la lente di Barlow? È una semplice lente convergente, che viene usata in una configurazione particolare.
La lente non è particolare, è particolare l'uso.
![[Pasted image 20220517094757.png]]
Se io mi metto ad una distanza pari a due volte la focale e inizio a costruire l'immagine, quello che scopro è che l'immagine finisce ad una distanza pari a due volte la focale, ed è semplicemente invertita.
![[Pasted image 20220517094835.png]]
![[Pasted image 20220517095151.png]]

### Binocoli
 ![[Pasted image 20220517095239.png]]
 Nei binocolo il problema delle immagini swappate si fixa con dei prismi.
Ora, osservo che le lenti in foto sono fatte di più di due pezzi.
Il fatto che i pezzi siano di più serve per correggere un aberrazione cromatica.

I binocoli dritti, invece, hanno esattamente lo stesso principio costruttivo, ma in mezzo ci sono dei prismi che fanno la stessa roba, ma i raggi in ingresso e uscita sono lungo lo stesso asse.
Il prisma a tetto lavora su tre riflessioni totali; il prisma di smhmidt è pazzo sgravato, ma il concetto è sempre lo stesso.