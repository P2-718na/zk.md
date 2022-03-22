### Battimenti
Il fenomeno dei battimenti è concettualmente simile alla interferenza ma ha risultati diversi. Questa volta richiediamo di avere due pulsazioni _vicine_, _NON uguali_.
![[../File/todo da lezione 12/Pasted image 20220316091936.png]]
(con k1 e k2 numeri d'onda).
Le prendo in questo modo:
![[../File/todo da lezione 12/Pasted image 20220316092100.png]]
Questa volta non ci mettiamo uno sfasamento, perchè, se mi fissp in un punto dello spazio, w1t e w2t sono due fasi diverse. => In generale. c'è sempre una differenza di fase tra le due onde, _che varia nel tempo_.

Per capire cosa succede quando queste due si trovano nello stesso punto dello spazio, vado a chiamare
![[../File/todo da lezione 12/Pasted image 20220316092220.png]]
e così posso lavorare più semplicemente nel campo complesso:
![[../File/todo da lezione 12/Pasted image 20220316092237.png]]
Mi è utile lavorare nello spazio di Argand-Gauss:
![[../File/todo da lezione 12/Pasted image 20220316092625.png]]
(NOTA CHE questo è un _rombo_, le due ampiezze sono uguali)
dove ho i miei due fasori. 
L'angolo di apertura tra i due fasori è variabile nel
 tempo. Per analizzare questa roba, quindi, faccio una foto ad un certo istante di tempo. L'ampiezza risultante è data dalla somma dei due vettori. Uso la regola del parallelogramma... 
 vabbè, ottengo:
 ![[../File/todo da lezione 12/Pasted image 20220316092650.png]]
 ![[../File/todo da lezione 12/Pasted image 20220316092732.png]]
 (ricordando che i due \phi dipendono da spazio e tempo)
.
Ora, se faccio la stessa cosa con (??) trovo un onda più complicata:
![[../File/todo da lezione 12/Pasted image 20220316092906.png]]
A questo punto, chiamo i due coefficienti:
![[../File/todo da lezione 12/Pasted image 20220316092932.png]]

(?) Visto che ero partito con i due k vicini, avrò questo w0 che è vicino a entrambi. => la differenza deltaw è piccola (?)

Quindi, la mia \xi avrà ora questa forma:
![[../File/todo da lezione 12/Pasted image 20220316093124.png]]
Osservo che dentro a quest'onda ho due diverse periodicità. Due spaziali e due temporali. COncentriamoci sul tempo:
_una_ periodicità deriva dall'ultimo fattore \omega_0. Questa periodicità è _più o meno_ la stessa delle onde di partenza.
Quindi, l'aspetto nuovo arriva dal primo termine, dove ho un \Delta \omega. Visto che questo \Delta \omega è piccolo, la periodicità di questo termine (\tau) è _molto più grande_.
![[../File/todo da lezione 12/Pasted image 20220316093427.png]]
_Il fenomeno dei battimenti è dovuto a questo termine modulante_.Riguardo alla frequenza dei battimenti, a volte si definisce con o senza il fattore 2 a denominatore.
![[../File/todo da lezione 12/Pasted image 20220316093516.png]]
^^ scritta così ci indica che stiamo modulando l'AMPIEZZA. Se w_0 fosse funzione del tempo, avremmo una modulazione di frequenza.

Quindi, visualizzando:
Prendo una prima onda armonica, la seguo in un certo punto (t variabile):
![[../File/todo da lezione 12/Pasted image 20220316093728.png]]
Ne prendo un'altra, con w leggermente diversa:
![[../File/todo da lezione 12/Pasted image 20220316093751.png]]
La loro somma, ha questo tipo di andamento:
![[../File/todo da lezione 12/Pasted image 20220316093801.png]]

L'onda risultante quindi, avrà queste proprietà:
![[../File/todo da lezione 12/Pasted image 20220316093942.png]]
L'intero battimento (l'inviluppo) è una cosa separata e si muove seguendo quest'altra regola:
![[../File/todo da lezione 12/Pasted image 20220316094033.png]]

Ultima considerazione:
![[../File/todo da lezione 12/Pasted image 20220316100020.png]]
Nei mezzi non dispersivi, il legame tra w e k è lineare. Nei mezzi _dispersivi_, questo legame non è lineare, visto che la velocità di fase dipende da k.

\[Qui ha fatto l'esperimento con Audacity\].

Quando ho una traccia armonica finita, la trasformata di fourier è piccata all'iniziio e poi è continua (?)
![[../File/todo da lezione 12/Pasted image 20220316095155.png]]
Questo è uno spettro: ho qualcosa che è proprorzionale al quadrato dei coefficienti della trasformata di fourier.

vv spettro di una registrazione audio della voce.
![[../File/todo da lezione 12/Pasted image 20220316095351.png]]