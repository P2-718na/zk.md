Ripasso vv

Serie di fourier complessa
Quello che abbiamo visoto ieri è che
presa una funzione opeirodica arbitraria, questa può essere approssimata come una somma di tanti fasori. Se ho una funzione periodica, ho un periodo, se ho un periodo ho una fulsazione.
I fasori che vado a creare hanno pulsazioni multiple di questa \omega.
Per come funziona la serie complessa![[Pasted image 20220301091132.png]]
Questo n può diventare positivo, negativo...
Nella formula sopra i c_n si determinano con
![[Pasted image 20220301091203.png]]
La formual qua sotto che descrive come si estraggono i c_n è essenzialmente un modo per dire "valuto quanto fasore c'è nella mia funzione arbitraria per \omega".

==> quindi, io posso pensare una funzione come somma di fasori, tutti con una pulsazione multipola di una pulsazione base. In questo modo, noi possiamo sempre risolvere il nostro problema.

![[Pasted image 20220301092009.png]]

Fine ripasso
==========


### Trasformata di Fourier
La difficoltà nell'applicare il [[Teorema di Fourier]] si ha quando abbiamo una forzante _non periodica_.
In questo caso facciamo questa osservazione: tutti i problemi che andrò a studiare, generalmente, avranno un intervallo _finito_. Immaginiamo allora che questo fenomeno che vogliamo andare a studiare sia periodico con periodo _maggiore al mio tempo di osservazione_. 

Quello che faccio, quindi, è cosniderare una funzione periodica ti T infinito:
![[Pasted image 20220301092226.png]]
.
(I passi che andiamo a vedere non sono una vera dimostrazione, serve solo per giustificare quello che stiamo facendo).

Quindi, prendiamo la nostra funzione forzante non periodica, e prendiamo un intervallo di tempo ampio T, lo centriamo attorno all'origine (-T/2, T/2) (per comodità) e cerchiamo di rispòvere la nostra funzione ![[Pasted image 20220301092332.png]] in quell'intervallo.

Quello che faccio quindi è battezzare la mia f(t) periodica con periodo dato da T, e andare ad analizzare lo sviluppo in serie.
Faccio poi lo sviluppo, e ottengo che il mio sviluppo approssima la mia funzione con una \epsilon scelta.
Se voglio una soluzione appena più generica, considero un T sempre più largo fino ad avere T -> +inf.

Quali problemi ho, quando faccio questa cosa?
Prendiamo la serie complessa...
![[Pasted image 20220301092545.png]]
Osserva come calcolo i c_n nel periodo che mi sono scelto all'inizio (l'integrale di c_n è fatto su un periodo). La pulsazione che compare  a sinistra è data da $2\pi /T$ . Posso avere una serie di problemi: se l'integrale (c_n) lo faccio tra 0 e inf, questo potrebbe anche non convergere. Poi, ho un fattore 1/T davanti, quindi se T va a infinito, rischio che tutti i coefficienti vadano a zero.
Altro problema, anche \omega_0 va a zero quando T va a zero.

Partiamo risolvendo un problema alla volta:
partiamo considerando solo funzioni "gentili":
![[Pasted image 20220301092759.png]]
(vado a prendere funzioni che a +/- inf vanno a zero, e regolari).
Ora, faccio un passaggio al continuo. Se T va a infinito, \omega (calcolato secondo la definizione) va a zero: ![[Pasted image 20220301092854.png]]

Quindi, questo 1/T lo  posso chiamare, volendo:![[Pasted image 20220301092919.png]]

Ma ora mi resta che ho un termine (\omega_0) piccolo a piacere, ed ho un n (nell'integrale) che può essere grande a piacere. Faccio che il prodotto n\omega_0, lo vado a chiamare \omega.
In questo modo, se uno dei due è piccolo ed  uno è grande, questa roba è "nel mezzo" e può assumere qualsiasi valore.
![[Pasted image 20220301093031.png]].

Nelle approssimazioni che stiamo facendo, quindi, questa \omega è una variabile continua (ovvero, il prodotto nd\omega è denso sui \mathbb{R}).

Tenendo presente tutte queste formule, il c_n inizia a cambiare forma:
![[Pasted image 20220301093202.png]]
(dove il passaggio al limite non l'ho fatto per tutti gli elementi dell'integrale).
Ora, tutte le costanti davanti all'integrale le porto a sinistra, e vado a riscrivere ancora l'integrale:
![[Pasted image 20220301093336.png]]
L'ultimo oggetto è un integrale che dipende dalla mia funzione, che sto integrando su tutti i tempi possibili (=> il risultato di quell'integrale non dipende dal tempo). Osservo che dentro all'integrale c'è un \omega, che se cambia fa cambiare anche l'integrale. Questo vuol dire che quell'integrale è essenzialmente una roba che descrive l'andamento di \omega.
la tilde sopra $h$ (notazione) mi dice che sto lavorando con inversi di tempi, e non tempi.

Si può dimostrare che se f è una funzione gentile, questa funzione $\tilde h(\omega)$ è finita ed esiste su tutto il (??)

Posso quindi riscrivere il mio termine generico in funzione della mia \tilde h e della mia pulsazione:
![[Pasted image 20220301093643.png]]
Di conseguenzal è colpa solo del mio d\omega se i cosi vanno a zero (\tilde h è finita su tutto R).
Ora vado a riscrivere la mia serie sostituendo c_n e ho:
![[Pasted image 20220301093722.png]]
dove ho chiamato di nuovo $n\omega_0 := \omega$.
Ora, osservo che questa sommatoria (3 step nella foto) per un d\omega è una somma di elementi infinitesimi. Quindi, di fatto, non è altro che un integrale. Quindi, questa $f(t)$, quando faccio l'ultimo passaggio al limite per $T \to \infty$, _ottengo un integrale_.

Quindi, le due formule più importanti che ho trovato lungo questi step sono:
- Per fare ela trasformata servono
![[Pasted image 20220301093946.png]]

#### `DEF` Trasformata di Fourier
![[Pasted image 20220301094031.png]]

^^ questo integrale fa la stessa cosa che faceva l'altro integrale (quello per calcolare c_n): estrae dalla funzione la componente di fasore $e^{in\omega t}$. (un mini discorso su come nell'integrale ci sia meno ma lui vada ad estrarre +??)

=> Una volta che uno mi da \tilde f, io posso riscrivere la mia funzione di partenza come una sovrapposizione di tanti fasori. Quindi, questa scrittura qui:
![[Pasted image 20220301094227.png]]
è un modo per scrivere una funzione generica _anche non periodica_. Questa roba è detta:
![[Pasted image 20220301094250.png]]
Mentre, quella che mi da la \tilde f è la Trasformata di Fourier.

### Proprietà della trasformata:
![[Pasted image 20220301094411.png]]
F è un [[Operatori lineari|operatore lineare]]. Di fatto, l'operatore trasformata mi prende una funzione del tempo e mi restituisce una funzione della pulsazione. Tuttavia è sempre lineare.

Altra osservazione della trasformata:
![[Pasted image 20220301095015.png]]
(?? non ho capito bene questa parte)
![[Pasted image 20220301095027.png]]
=> Le formule sono quelle delle derivate dei rotori. L'unica differenza è che qui la pulsazione è
 una quantità continua che può variare.

Tornando al nostro oscillatore armonico forzato...
![[Pasted image 20220301095159.png]]
( dove ho usato la linearitàdi $\hat{\mathcal{F}}$) . Continuo ad espandere, ho che:
![[Pasted image 20220301095300.png]]
^^ così ho trasformato il primo membro.
Per il secondo membro, la trasformata la chiamo \tilde \mathcal{F}. Quindi, ottengo questo:
![[Pasted image 20220301095404.png]]
Mettendo assieme i due membri, ho:
![[Pasted image 20220301095417.png]]
Da questa equazione, posso risolvere tranquillamente per $\tilde x$:
![[Pasted image 20220301095439.png]]
In questo modo, __abbiamo trovato la trasformata di Fourier della soluzione__. E sono contento, perchè dopo posso applicare l'_antitrasformata_ e trovare finalmente la mia soluzione particolare:
![[Pasted image 20220301095533.png]]

Osservazioni aggiuntive:
Questo problema è stato descritto attraverso un operatore lineare. Nel linguaggio degli operatori, io posso fare la trasformata di fourier di un operatore lineare:
![[Pasted image 20220301095742.png]]
![[Pasted image 20220301095708.png]]
Essenzialmente, succede che la trasf di Fourier di un altro operatore è un polinomio caratteristico.) (se L fosse L(\tilde x)) avrei un \dot \tilde x moltiplicato per il polinomio caratteristico.
![[Pasted image 20220301095827.png]]

Seconda considerazione:
quando faccio una trasformata di f, io passo dal dominio dei tempi al dominio delle pulsazioni. T si misura in $s$ $\omega$ si misura in $s^{-1}$. T ed \omega si dicono _variabili coniugate_. (ne esistono molte altre, per esempio, pulsazione e quantità di moto). Le variabili coniugate solo tali che una derivata(?) da una variabile, si trasforma in una moltiplicazione nell'altra variabile.
Il principio di indetermonazione id heisenberg lavora proprio su variabili coniugate.
![[Pasted image 20220301100116.png]]
Avvertimento: in questo corso si usa questa(sinistra) come def. di trasformata e l'altra(destra) come antitrasformata.
![[Pasted image 20220301100154.png]]
Questo è perchè fatto così si ha un significato proprio fisico. Ci sono altri ambiti in cui la definizione di cos'è la trasformata è diversa e quindi le formule sono leggermente diverse. Solo per menzionarle, abbiamo:
fisica
![[Pasted image 20220301100249.png]]

In matematica, si cerca di rendere simmetriche trasf, e antitrasf. splittando il coeff 2\pi tra le due:
![[Pasted image 20220301100312.png]]

In ambito ingegneristico, si va addirittura oltre. Non si lavora con la frequenza, ma con la pulsazione $\nu$:
![[Pasted image 20220301100324.png]]
Facendo così, quello a destra diventa un differenziale della frequenza, e le due formule sono un poco più simmetriche.

Esercizi
![[Pasted image 20220301100436.png]]


### Onde
Ogni volta che abbiamo un'equazione lineare con termine noto "gentile", possiamo risolverla con Fourier.
In origine, Fourier era partito da un altro problema: Come si distrubuisce il calore nella conduzione? Anche quello era un problema lineare (anche se molto complesso) e quindi lui si è inventato questa roba.

Abbiamo fatto tutto questo lavoro perchè i punti che oscillano, di fatto sono l'essenza delle onde.
Ciò che deve rimanere in mente dall'analisi di Fourier è che qualunque fenomeno dipendente dal tempo può essere espresso come somma di fenomeni oscillatori semplici.

- COncetti fondamentali delle onde (ripasso):
![[Pasted image 20220301102009.png]]
### Onde meccaniche
![[Pasted image 20220301102113.png]]
Le onde meccaniche sono di natura vettoriale. Quando lavoriamo con onde vettoriali, possiamo distinguerle in base a modo di propagazione (onde trasversali/longitudinali)
![[Catenalong.gif]] ![[Catenatrasv.gif]]
### Onde EM
sono _solo_ trasversali
![[Pasted image 20220301102654.png]]

### Onde trasversali su corda elastica
Facciamo una dimostrazione che mi permette di trovare un'equazione delle onde.
Immaginiamo una corda elastica tesa e appoggiata su un piano liscio (assenza di attrito):
![[Pasted image 20220301102907.png]]
Introduco un sistema di riferimento dove ho un asse x lungo la corda, un asse y sul piano e rappresenta l'altra dimentsione.
Questa corda si può muovere sul piano xy, la tengo tesa agli estremi, però un onda può comunque viaggiare su quella corda.
Quindi, se vado a considerare un punto della corda ben definito, questo potrà fare tanti movimenti, ma adesso andiamo ad osservare solo i movimenti _trasversali_ (punto <span color=blue>blu</span> in figura).
![[Pasted image 20220301103126.png]]
Se la corda è ferma. allora $\xi (x,\ t) = 0 \underset{x,\ t}{\forall}$ (condizione imperturbata di equilibrio iniziale).
Quando la corda si muove, quindi quando il punto x oscilla, vull dire che questa funzione $\xi$ diventa funzione del tempo, ovvero che:
![[Pasted image 20220301103249.png]]
Se $\xi$ rappresenta la posizione della y nel mio punto generico, allora
![[Pasted image 20220301103307.png]]
La domanda che mi faccio ora è:
_qual è l'equazione della dinamica che $\xi(x,\ t)$ deve soddisfare?_ (Ci saranno per forza delle limitazioni, imposte da questo tipo di problema che sto considerando).
Facciamo le cose un pezzo alla volta. Consideriamo il moto di un tratto infinitesimo dx della corda, che avrà massa dm data da:
![[Pasted image 20220301103515.png]]
\mu densità lineare della corda (tutta omogenea).
Voglio studiare il movimento di questo dx infinitesimo di corda:
![[Pasted image 20220301103600.png]]
Prendo il mio tratto infinitesimo di corda (imperturbato): x<->x+dx.
Quando la corda oscilla, questo punto si sposterà in alto e in basso. In un certo momento, avrò, per esempio, questa situazione:
![[Pasted image 20220301103654.png]]
(Osserva che il pezzo di corda è lo stesso, non si sposta).
Cosa fanno i due pezzi di corda a destra e sinistra del mio tratto considerato? Questi agiscono sul mio pezzettino dx, uno tirandolo da una parte e uno tirandolo dall'altra parte.
Su questi due punti estremi, agisce da un lato una certa tensione e dall'altro un'altra tensione:
![[Pasted image 20220301103804.png]]
e questa tensione è sempre tangente alla corda in ogni suo punto ( le due tensioni ai lati formano due angoli theta1 e theta2).

Questo pezzo deve soddisfare a $\sum \vec F = m \ddot{\vec x}$ . Qui, le forze sono le due tensioni,. quindi ho che:
![[Pasted image 20220301103957.png]]
Lavoriamo prima a secondo membro: consideriamo onde che si spostano solo lungo asse y:
![[Pasted image 20220301104044.png]]
Assumo che quando questo dx è piccolo a piacere, questa quantità (derivata seconda di \xi) sia l'accelerazione per tutti i punti di questo tratto infinitesimo. (L'accelerazione è una quantità finita, che avrà, tra i due estremi, due valori estremamente vicini. Quindi prendo uno dei due a caso e uso quello).
![[Pasted image 20220301104052.png]]
Ora lavoriamo sulle tensioni delle due corde:
![[Pasted image 20220301104239.png]]
Scompongo le forze lungo le componenti
(lungo \hat i non voglio avere accelerazione, visto che i pezzi di corda non si muovono avanti e indietro)

Ora c'è un passaggio fondamentale: _a noi interessano piccole perturbazioni rispetto alla condizione di equilibrio_. Se le perturbazioni sono piccole, la corda è _vicina_ alla condizione di equilibrio. Questo vuol dire che la corda, rispetto alle oscillazioni, è molto lunga. Posso quindi fare approssimazioni per angoli piccolo (theta1 e theta2, un paio di figure sopra)
![[Pasted image 20220301104454.png]]
Quando faccio questo, sulla x mi scompaiono i due coseni e dal sistema di prima ottengo:
![[Pasted image 20220301104515.png]]
Cosa vuol dire? Vuol dire che le due tensioni ai capi del mio elemento infinitesimo devono essere uguali. => Le individuo quindi con un solo termine T, che vale su tutta la corda (abbiamo ritrovato il risultato di meccanica che mi dice che in ogni punto ho la stessa tensione).
![[Pasted image 20220301104616.png]]
Facciamo questa osservazione: se l'angolo è piccolo, seno e tangente sono la stessa cosa. Ma la tangente jnon è altro che il coeff angolare della retta tangente ad un certo punto. Ed il coeff angolare è proprio la derivata della funzione fatta rispetto alla x. => Riscrivo la tangente come:
![[Pasted image 20220301104710.png]]
Allora, da questo ho che:
![[Pasted image 20220301104734.png]]
![[Pasted image 20220301104813.png]]
quindi, queste equazioni qui ,inserendole in quella sus (T(sin...)) di prima, ottengo che:

![[Pasted image 20220301104759.png]]
Dove sono andato a sostituire la massa con $\mu dx$. Ora, da questa roba vado a sostituire anche le altre due tangenti a primo membro:
![[Pasted image 20220301104917.png]]
E porto Tensione a destra e dx a sinistra:
![[Pasted image 20220301104935.png]]
Questo 1/dx è un rapporto incrementale. Nel momento in cui lo prenso piccolo a piacere, quello che ho a primo membro di fatto è una derivata (rigore matematico go brr):
Di fatto, quello che ho a sinistra, quindi, non è altro che una derivata seconda di \xi. Ottengo così, l'equazione delle onde elastiche:
![[Pasted image 20220301105105.png]]
Ho un'eguaglianza tra derivate seconde nello spazio e derivate seconde nel tempo. Il coefficiente \mu/T è un coefficiente della corda.
Questa roba, che abbiamo ottenuto per le piccole oscillazioni, in realtà si ritrova molto simile in tanti altri ambiti.ù

Il coefficiente \mu/T ha un nome proprio in realtà: si scopre essere collegato alla velocità di propagazione delle onde in questo modo:
![[Pasted image 20220301105225.png]]
E andando a sostituire, otteniamo:
#### `THM` Equazione d'Alembert
![[Pasted image 20220301105248.png]]
Rappresenta l'equazione per un'onda che si muove in uno spazio unidimensionale con velocità v.

La domanda è: è un'equazione lineare? SÌ.
Altra domanda: v è una velocità? Facciamo l'analisi dimensionale:
![[Pasted image 20220301105448.png]]

Quello che stiamo descrivendo con l'eq d'alembert è un'andamento di un'onda trasversale su una corda, Da questo momento in avanti, ci occuperemo di trovare le soluzioni all'eq alembert.
![[Pasted image 20220301105643.png]]