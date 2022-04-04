### Trasformata di Fourier
Quindi, prendiamo la nostra funzione _forzante non periodica_, e prendiamo un intervallo di tempo ampio $T$, lo centriamo attorno all'origine $(- \frac T 2, \frac T 2)$ (per comodità) e cerchiamo di risolvere la nostra funzione $\hat L(x) = f(t)$  in quell'intervallo.

Quello che faccio quindi è _battezzare la mia $f(t)$ periodica_, con periodo dato da T, e andare ad analizzare lo sviluppo in serie.
Faccio poi lo sviluppo, e ottengo che il mio sviluppo approssima la mia funzione con una $\epsilon$ scelta.
Se voglio una soluzione appena più generica, _considero un $T$ sempre più largo fino ad avere $T \to +\infty$_.

Quali problemi ho, quando faccio questa cosa?
Prendiamo la serie complessa...
![[../File/fourier 1.png]]
Osserva come calcolo i $c_n$ nel periodo che mi sono scelto all'inizio (l'integrale di $c_n$ è fatto su un periodo). La pulsazione che compare  a sinistra è data da $\frac {2\pi} T$ . Posso avere una serie di problemi: se l'integrale ($c_n$) lo faccio tra $0$ e $\infty$, questo _potrebbe anche non convergere_. Poi, ho un fattore $\frac 1 T$ davanti, quindi se $T \to \infty$, rischio che tutti i coefficienti vadano a zero.
Altro problema, anche $\omega_0$ va a zero quando $T$ va a zero.

Partiamo risolvendo un problema alla volta:
partiamo _considerando solo funzioni "gentili"_:
![[../File/fourier 2.png]]
(vado a prendere funzioni che a +/- inf vanno a zero, e regolari).
Ora, faccio un passaggio al continuo. Se T va a infinito, \omega (calcolato secondo la definizione) va a zero: ![[../File/fourier 3.png]]

Quindi, questo 1/T lo  posso chiamare, volendo:![[../File/fourier 4.png]]

Ma ora mi resta che ho un termine ($\omega_0$) piccolo a piacere, ed ho un n (nell'integrale) che può essere grande a piacere vv. Faccio che il prodotto $n\omega_0$, lo vado a chiamare $\omega$.
In questo modo, se uno dei due è piccolo ed  uno è grande, questa roba vv è "nel mezzo" e può assumere qualsiasi valore.
![[../File/fourier 5.png]].

Nelle approssimazioni che stiamo facendo, quindi, questa $\omega$ è una variabile continua (ovvero, il prodotto $nd\omega$ è denso su $\mathbb{R}$).

Tenendo presente tutte queste formule, il $c_n$ inizia a cambiare forma:
![[../File/fourier 6.png]]
(dove il passaggio al limite non l'ho fatto per tutti gli elementi dell'integrale).
Ora, tutte le costanti davanti all'integrale le porto a sinistra, e vado a riscrivere ancora l'integrale:
![[../File/fourier 7.png]]
L'ultimo oggetto è un integrale che dipende dalla mia funzione, che sto integrando su tutti i tempi possibili (=> il risultato di quell'integrale non dipende dal tempo). Osservo che dentro all'integrale c'è un $\omega$, che se cambia fa cambiare anche l'integrale. Questo vuol dire che quell'integrale è essenzialmente una roba che descrive l'andamento di $\omega$.
la tilde sopra $h$ (notazione) mi dice che sto lavorando con inversi di tempi, e non tempi.

Si può dimostrare che se f è una funzione gentile, questa funzione $\tilde h(\omega)$ è finita ed esiste su tutto il dominio

Posso quindi riscrivere il mio termine generico in funzione della mia $\tilde h$ e della mia pulsazione:
![[../File/fourier 8.png]]
Di conseguenza è colpa solo del mio $d\omega$ se i $c_n$ vanno a zero ($\tilde h$ è finita su tutto $\mathbb R$).
Ora vado a riscrivere la mia serie sostituendo $c_n$ e ho:
![[../File/fourier 9.png]]
dove ho chiamato di nuovo $n\omega_0 := \omega$.
Ora, osservo che questa sommatoria (3 step nella foto) per un d\omega è una somma di elementi infinitesimi. Quindi, di fatto, non è altro che un integrale. Quindi, questa $f(t)$, quando faccio l'ultimo passaggio al limite per $T \to \infty$, _ottengo un integrale_.

Quindi, le due formule più importanti che ho trovato lungo questi step sono:
- Per fare la trasformata servono
![[../File/fourier 10.png]]

#### `DEF` Trasformata di Fourier
![[../File/trasformata di fourier.png]]

^^ questo integrale fa la stessa cosa che faceva l'altro integrale (quello per calcolare $c_n$): estrae dalla funzione la componente di fasore $e^{in\omega t}$. (un mini discorso su come nell'integrale ci sia meno ma lui vada ad estrarre +??)

=> Una volta che uno mi da $\tilde f$, io posso riscrivere la mia funzione di partenza come una sovrapposizione di tanti fasori. Quindi, questa scrittura qui:
![[../File/fourier 11.png]]
è un modo per scrivere una funzione generica _anche non periodica_. Questa roba è detta:
![[../File/fourier 12.png]]
Mentre, quella che mi da la $\tilde f$ è la Trasformata di Fourier.

### Proprietà della trasformata:
![[../File/fourier 13.png]]
F è un [[../../Algebra/Note/Operatori lineari|operatore lineare]]. Di fatto, l'operatore trasformata mi prende una funzione del tempo e mi restituisce una funzione della pulsazione. Tuttavia è sempre lineare.

Altra osservazione della trasformata:
![[../File/fourier 14.png]]
(?? non ho capito bene questa parte)
![[../File/fourier 15.png]]
=> Le formule sono quelle delle derivate dei rotori. L'unica differenza è che qui la pulsazione è
 una quantità continua che può variare.



Osservazioni aggiuntive:
Questo problema è stato descritto attraverso un operatore lineare. Nel linguaggio degli operatori, io posso fare la trasformata di fourier di un operatore lineare:
![[../File/fourier 16.png]]
![[../File/fourier 17.png]]
Essenzialmente, succede che la trasf di Fourier di un altro operatore è un polinomio caratteristico.) (se $L$ fosse $L(\tilde x)$) avrei un $\dot{\tilde x}$ moltiplicato per il polinomio caratteristico.
Le equazioni differenziali si trasformano in polinomi in $\omega$

Seconda considerazione:
quando faccio una trasformata di Fourier, io passo _dal dominio dei tempi al dominio delle pulsazioni_. T si misura in $s$; $\omega$ si misura in $s^{-1}$. $T ed $\omega$ si dicono _variabili coniugate_. (ne esistono molte altre, per esempio, pulsazione e quantità di moto). Le variabili coniugate solo tali che una derivata(?) da una variabile, si trasforma in una moltiplicazione nell'altra variabile.
Il principio di indeterminazione id Heisenberg lavora proprio su variabili coniugate.
![[../File/fourier 18.png]]
Avvertimento: in questo corso si usa questa(sinistra) come def. di trasformata e l'altra(destra) come antitrasformata.
![[../File/fourier 19.png]]
Questo è perché fatto così si ha un significato proprio fisico. Ci sono altri ambiti in cui la definizione di cos'è la trasformata è diversa e quindi le formule sono leggermente diverse. Solo per menzionarle, abbiamo:
fisica
![[../File/fourier 20.png]]

In matematica, si cerca di rendere simmetriche trasf, e antitrasf. splittando il coeff 2\pi tra le due:
![[../File/fourier 21.png]]

In ambito ingegneristico, si va addirittura oltre. Non si lavora con la pulsazione, ma con la frequenza $\nu$:
![[../File/fourier 22.png]]
Facendo così, quello a destra diventa un differenziale della frequenza, e le due formule sono un poco più simmetriche.
