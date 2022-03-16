Mega Riassunto volta scorsa:
![[Pasted image 20220314140858.png]]

Per la lezione di oggi ci interessa particolarmente il fatto che se ho impesenza alta nel secondo mezz. l'ampiezza trasmessa va a zero:
![[Pasted image 20220314141433.png]]

---
Concludiamo il discorso fatto la lezione scorsa
![[Pasted image 20220314141541.png]]
Se ci troviamo con un onda rappresentata tramite serie di FOurier, abbiamo:
![[Pasted image 20220314141559.png]]
Poichè il fattore con le Z (in rosso) non dipende da nessun tipo di onda in particolare, lo porto guori dalla sommatoria e scopro che:
- [ ] ![[Pasted image 20220314141651.png]]
Di fatto la mia onda riflessa non è altro che un onda uguale a prima ma di cui cambia solo l'ampiezza:
![[Pasted image 20220314141717.png]]
=> Un onda riflessa, _non cambia la forma_, ma semplicemnte _me la trovo di ampiezza scalata_.
Questo è vero anche se io rappresento l'onda in una forma diversa da quella della serie di fourier:
![[Pasted image 20220314141756.png]]
Vediamo come l'onda riflessa ha il coeff di scala dato dalle impedenze.
(Mettendo dentro i dati, osserviamo che questo coeff varia tra +1 e -1).

Per le onde trasmesse è un attinmo più difficile, visto che cambiano le lunghezze d'onda (e quindi le velpocità) delle onde trasmesse. Prendiamo una generica onda incidente:
![[Pasted image 20220314141923.png]]
DOve i kn sono multipli di un numero d'onda. Quando vado nella regione 2, ognuna di queste onde cambia:
![[Pasted image 20220314141947.png]]
Il motivo è che qui non abbiamo più kn ma abbiamo k'n.
L'ampiezza di questa onda trasmessa segue quindi questa regola qua.
Ora, questo k'n è quello che collega la velocità con v2 (in rosso) (??)
=> La forma non è esatamente la stessa, abbiamo qualcosa che cambia.

Possiamo far vedere che questa formula qua sopra vale  in forma serie di fourier. Se lavoro con una generica onda progressiva, avrò:
![[Pasted image 20220314142115.png]]
La forma non cambia, ma appare scalaat sia in ampiezza che in larghezza.

---
[[Onde stazionarie]]

---

Usciamo dal mondo delle onde su corda:
### Onde sonore
Le onde sonore sono meccaniche (dipendono dalla presenza di un mezzo).
![[Pasted image 20220314152512.png]]
Onde longitudinali: anche se sto ragionando con un vettore spostamento, questo può seguire solo la direzione della mia onda quindi bla bla bla
Ad un certo punto lavoreremo con le onde sono re nello spazio tridkjentsionale. Per il momento, rimaniam0 ancora confinati in moti ad una sola dimensione.

Andiamo a lavorare in una sola dimensione. Di fatto, „ueso vuol dire immaginare di avere un tubo:
![[Pasted image 20220314152713.png]]
![[Pasted image 20220314152824.png]]
![[Pasted image 20220314152920.png]]

Ora, noi vogliamo capire _qual'è l'equazione che ci permette di descrivere come viaggiano queste perturbazioni_. Quindi, come sarà l'equazione delle onde in questo tubo unidimensionale?
Partiamo immaginandoci un tubo non partrivolarmente grande e andiamo a prendere una piccola regione di questo tubo:
![[Pasted image 20220314153118.png]]
    La sezione del tubo è sempre uguale (S). Andiamo ad isolare quindi un volumetto dV. Immaginiamo che ci siano due diaframmi che mi tengono separata questa quantità di aria rispetto a tutto il resto. Questi diaframmi, però, me li immagino senza massa e mobili lungo il tubo (in modo che questi psosano spingere o richiamare l'aria avanti e indietro). (I diaframmi mi servono più come idea concettu<la per isolare una certa quantutà di materia. Non sono qualcosa di fisico).
    Questo volume, sarà una funzione del tempo (i due diaframmi oscillano), mentre la massa sarà costante. Posso scrivere:
![[Pasted image 20220314153400.png]]
(??)
![[Pasted image 20220314153510.png]]
Arriva un onda, vediamo cosa succede ai miei diaframmi:
![[Pasted image 20220314153543.png]]
Se il mio volumetto iniziale lo chiamo dV0, quando arriva un'onda che sposta entrambi i diaframmi, quanto volume ho?  (vedi formule ^^)
(?? dove sfrutto le proprietà algebriche dei differenxiali).
(??
![[Pasted image 20220314153916.png]]
Detto in altri termnii
![[Pasted image 20220314153934.png]]
![[Pasted image 20220314154016.png]]
- [ ] Ora, abbiamo un gas su cui agisce una pressione. La massa sarà volume * densità imperturbata
(?? SU questa parte non ho seguito bene)
Riprendiamo l'equazione:
![[Pasted image 20220314154400.png]]
Questa quantità qui (??)
^^ QUESTA roba sopra è la prima informazione che ci serve per costruire la prima equazione dell eonde.
Per come sto impostando il problema
![[Pasted image 20220314154826.png]]
(sempre lavorando nel mondo delle piccole pertrubazioni...) ^^ ho preso i primi due termini dello sviluppo in serie.
    Questa derivata (dp/d\rhp òa chiamo \beta/rho_0 (Prendo questa come _definizione di questo \beta_)).
    Attenzione però, \rho - \rho_0 vale -\rho_0 d\xi/dx.
    Il risultato è che la mia pressione la posso scrivere come:
    ![[Pasted image 20220314155059.png]]
    Adesso cerco di capire quanto vale questo \beta:
    ![[Pasted image 20220314155139.png]]
    Io dalla termodinamica so che un gas può fare trasformazioni diverse. So quindi che nel piano pV ho tante traiettorie. Ragionandoci sopra un attimo, delle tante trasformazioni che conosciamo, ci sono quelle _isoterme_, _adiabatiche_, _isocore_, _isobare_. Se voglio studiare una dfipendenza esplicita della desnità, qui mi simarranno due candidate possibili:
    isoterma e adiabatica.
Il concetto è che le trasformazioni che fanno andare le onde sono _veloci_. La trasformazione che può essere veloce è un'adiabatica
![[Pasted image 20220314155556.png]]
Quini riasusmedo tutte le robe che ho ricavato...
![[Pasted image 20220314155730.png]]
Uguaglio questa roba, e trovo che:
![[Pasted image 20220314155740.png]]
Che praticamente è la stessa robva dell'eq di d'alenbveherbajn.
![[Pasted image 20220314155850.png]]
Questa velocità, di fattp è una previsione _teorica_ della velocità. (basata sul nostro modellop che ci siamo appena ricavati). Vediamo cosa succede se la vado a misurare:
![[Pasted image 20220314155939.png]]
Osservo anche che:
![[Pasted image 20220314155946.png]]

Le onde sonore possono essere viste da tre punti di vista, visto che le grandezze che le caratterizzano sono tutte collegate tra loro... (hanno tutte e tre le stesse caratteristiche)
![[Pasted image 20220315093250.png]]
Un onda in questo caso è una roba che oscilla attorno ad un valore di riferimento. Un onda non deve per forza oscillare attorno allo zero!