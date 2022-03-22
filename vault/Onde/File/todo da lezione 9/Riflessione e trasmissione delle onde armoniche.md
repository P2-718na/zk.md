### Riflessione e trasmissione
Cosa fa un'onda quando viaggia in un mezzo _non uniforme_?
![[Pasted image 20220309091639.png]]
Abbiamo visto che un'onda si propaga in un mezzo omogeneo senza cambiare di forma (almeno, su un'identità unidimensionale). Per i mezzi che non sono omogenei, può esserci una riflessione.
Quando un onda attraversa una superficie di separazione, una parte si riflette ed una si trasmette. (Es: luce sulle finestre).
![[Pasted image 20220309091917.png]]
Altro esempio: suono. Il suono si propaga in tutti i mezzi (anche attraverso i muri). In certe condizioni, posso fare un suono davanti a un muro e sentirne l'eco.
Vediamo cosa succede per una corda _non omogenea_:
![[Pasted image 20220309092105.png]]
Cosa succede quando il mio impulso arriva nella regione di discontinuità? Si osserva che dal punto di discontinuità partono due onde: una riflessa e una trasmessa.
In particolare, in questo caso osservo che l'onda riflessa, a differenza dell'onda originakle e di quella trasmessa, è solo negativa.
![[Pasted image 20220309093234.png]]
I calcoli con le onde impulsive sono più complessi. Lavoriamo con le onde armoniche:
![[Pasted image 20220309092340.png]]
\xi_i: onda iniziale, \xi_t: onda trasmessa, \xi_r: onda riflessa.
immagino di avere K e w diverse per ognuna delle tre onde.
Considero una corda fatta di due pezzi (ma con la stessa tensioe $T$). Questo vuol dire che avrò due velocità diverse:
![[Pasted image 20220309092544.png]]
. Per trovare le incognite che cerco, devo imporre qualchec ondizione:
1) Nella prima regione, possono essere presenti sia onda originale che riflessa. Posso scrivere (dove lo 0 è il punto di discontinuità):
 ![[Pasted image 20220309092732.png]].
 In più, dobbiamo imporre che:
 1) La corda sia diversa per x>0 ma _non rotta_: l'[[../../Note/Equazione di D'Alembert]] mi richiede essenzialmente solo che la mia \xi sia continua e
 2) a funzione \xi(x,\ t) derivabile due volte (soprattutto in x=0, dove dobbiamo avere derivate seconde continue).
 ![[Pasted image 20220309093204.png]]
 ![[Pasted image 20220309093244.png]]
continuo con il sistema..
![[Pasted image 20220309093306.png]]
Osservo che nell'onda trasmessa, questo w2 non può essere arbitrario: dovrà essere uguale ad w. (Questo perchè, il periodo dipende solamente dalla sorgente. "sei io faccio uno schiocco ogni secondo, lo sentono anche dall'altra parte del muro una volta ogni secondo").
Anche w1 dovrà avere lo stesso periodo. (mini discorso su come si riesce a dimostrare che tutte e tre le w sono uguali, sfruttando la serie di fourier ??).
Una volta che abbiamo fissato gli w, restano fissati anche i k:
![[Pasted image 20220309093538.png]]
Mi resta da trovare solo le ampiezze. Le cose che ho trovato finora mi permettono di dire:
![[Pasted image 20220309093729.png]]
Questo è un sistema _lineare non omogeneo_ => se c'è soluzione, è unica. Risolvo il sistema e trovo:
![[Pasted image 20220309093944.png]]
Scritto così non mi piace perchè sembra che onde armoniche diverse si comportino in modo diverso. In realtà non è così: andiamo a far sparire i k:
![[Pasted image 20220309094120.png]]
=>
![[Pasted image 20220309094215.png]]
Rimettendo questo nel sistema, sia a numeratore e denominatore raccolgo \frac w t e ottengo una relazione:
![[Pasted image 20220309094250.png]]
In cui vedo che le ampiezze dipendono solamente dalle due _impedenze_ dei tratti di corda. (non dipendono ne' da pulsazione ne' da numero d'onda). 
La cosa bella è che, una volta trovate queste due relazioni, il coefficiente di proporzionalità è sempre questo. => Questa formula vale anche per onde non armoniche (anche onde impulsive, per esempio).
##### Casi importanti:
1) Semicorde con stessa impedenza: è come se avessi una corda omogenea.
2) ![[Pasted image 20220309094455.png]]
3) La corda è NON-omogenea: ho sempre riflessione
 ![[Pasted image 20220309094615.png]]
 
 Altri casi limite:
 1) "Parto dalla gomena e vado alla corda da pesca.."
 ![[
![[Pasted image 20220309094713.png]]
![[Pasted image 20220309094743.png]]
Oppure:
![[Pasted image 20220309094832.png]]
![[Pasted image 20220309094900.png]]
"quel punto di discontinuità aggiunge una fase pari a un mezzo periodo: trasforma +cos in -cos".

Questi sono i principi di radar, sonar, ecografia.... Analizzando quello che mi torna indietro, posso capire se la regione che sto studiando è più o meno denso di quello di aprtenza.
##### Valutazion energetica.
Cosa succede all'energia? Da quello che abbiamo visto nella [[../Lezione 8/Lezione 8]]...
![[Pasted image 20220309095148.png]]
Parto quindi scrivendomi le intensità delle tre onde (abbiamo visto che l'energia di un'onda armonica dipende dalla sua densità):
![[Pasted image 20220309095203.png]]
Che relazioni ci sono tra queste tre intensità?
Vado a sviluppare tutti i calcoli, sviluppando $I_t$ (sostituisco al posto di A_t la roba che c'è sopra in rosso). Ottengo che:
$I_t$ = ![[Pasted image 20220309095257.png]]
Faccio lo stesso gioco con l'onda riflessa:
![[Pasted image 20220309095317.png]]
Mettendo assieme ottengo che:
![[Pasted image 20220309095411.png]]
Il termine finale corrisponde proprio al valore dell'intensità dell'onda incidente. Quindi, il risultato è che:
![[Pasted image 20220309095541.png]]
Considerazioni fisiche: l'intensità è una potenza media. Questo risultato non sorprende, visto che ci aspettiamo che l'energia si conservi.

Da tutte queste osservazioni, si definiscono:
![[Pasted image 20220309095701.png]]
Dicono rispettivamente quanta della mia potenza riesco a trasmettere e quanta riesco a riflettere.

 Da lezione 10
 ===
Mega Riassunto volta scorsa:
![[../todo da lezione 10/Pasted image 20220314140858.png]]

Per la lezione di oggi ci interessa particolarmente il fatto che se ho impesenza alta nel secondo mezz. l'ampiezza trasmessa va a zero:
![[../todo da lezione 10/Pasted image 20220314141433.png]]

---
Concludiamo il discorso fatto la lezione scorsa
![[../todo da lezione 10/Pasted image 20220314141541.png]]
Se ci troviamo con un onda rappresentata tramite serie di FOurier, abbiamo:
![[../todo da lezione 10/Pasted image 20220314141559.png]]
Poichè il fattore con le Z (in rosso) non dipende da nessun tipo di onda in particolare, lo porto guori dalla sommatoria e scopro che:
- [ ] ![[../todo da lezione 10/Pasted image 20220314141651.png]]
Di fatto la mia onda riflessa non è altro che un onda uguale a prima ma di cui cambia solo l'ampiezza:
![[../todo da lezione 10/Pasted image 20220314141717.png]]
=> Un onda riflessa, _non cambia la forma_, ma semplicemnte _me la trovo di ampiezza scalata_.
Questo è vero anche se io rappresento l'onda in una forma diversa da quella della serie di fourier:
![[../todo da lezione 10/Pasted image 20220314141756.png]]
Vediamo come l'onda riflessa ha il coeff di scala dato dalle impedenze.
(Mettendo dentro i dati, osserviamo che questo coeff varia tra +1 e -1).

Per le onde trasmesse è un attinmo più difficile, visto che cambiano le lunghezze d'onda (e quindi le velpocità) delle onde trasmesse. Prendiamo una generica onda incidente:
![[../todo da lezione 10/Pasted image 20220314141923.png]]
DOve i kn sono multipli di un numero d'onda. Quando vado nella regione 2, ognuna di queste onde cambia:
![[../todo da lezione 10/Pasted image 20220314141947.png]]
Il motivo è che qui non abbiamo più kn ma abbiamo k'n.
L'ampiezza di questa onda trasmessa segue quindi questa regola qua.
Ora, questo k'n è quello che collega la velocità con v2 (in rosso) (??)
=> La forma non è esatamente la stessa, abbiamo qualcosa che cambia.

Possiamo far vedere che questa formula qua sopra vale  in forma serie di fourier. Se lavoro con una generica onda progressiva, avrò:
![[../todo da lezione 10/Pasted image 20220314142115.png]]
La forma non cambia, ma appare scalaat sia in ampiezza che in larghezza.
