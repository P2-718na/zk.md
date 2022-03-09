#cleanme 
Il [[Chi quadro]] non può essere sempre minimizzato _analiticamente_: a volte servono metodi numerici. Vediamo alcuni casi.

### Fit con funzioni che dipendono linearmente dai parametri
In questo caso, possiamo ancora minimizzare chi quadro analiticamente:
![[../File/min chi2/min chi2 1.png]]
`OSS` Ci troviamo in questo caso, per esempio, quando dobbiamo fittare un polinomio:
![[../File/min chi2/min chi2 2.png]]
Anche questo caso si può risolvere analiticamente. Si fa minimizzando lo scarto tra funzione e fit. Si fa così: (nota che $1 \leq i, k \leq p$)
![[../File/min chi2/min chi2 3.png]]

La matrice di covarianza C è  l'inversa di A
![[../File/min chi2/min chi2 4.png]]

Il vettore colonna $\vec \beta$ ha $p$ elementi, definiti da:
![[../File/min chi2/min chi2 5.png]]

![[../File/min chi2/min chi2 7.png]]
La cosa interessante è che si dimostra che l'incertezza sui parametri sono gli elementi sulla diagonale della matrice di covarianza.
La covarianza sui parametri sono gli elementi fuori diagonale della matrice.
Esattamente come nel caso della regressione lineare, i coefficienti di correlazione sono (formula foto)

### Fit con funzioni non lineari
#todo
![[../File/min chi2/min chi2 8.png]]
Vediamo quindi come fittare questa roba:
![[../File/min chi2/min chi2 9.png]]
Dobbiamo capire come cambia la funzione di merito $\chi^2$ quando ci allontaniamo dal minimo.
Per esempio, se $\chi^2$ è una parabola, noi vogliamo capire quanto vale la sua apertura. Questo determina l'incertezza su questi parametri.
Vicino al minimo, ci aspettiamo questo:
![[../File/min chi2/min chi2 10.png]]
^^(Questa roba è un'espansione di taylor in uno spazio a più dimensioni)
Quindi, presso il minimo, ci aspettiamo che il chi quadro sia uguale a chi quadro minimo, sommato ad un valore piccolo dato da $(\vec{\delta a})^T A (\vec{\delta a})$, dove la matrice A  è l'hessiana:
![[../File/min chi2/min chi2 11.png]]

![[../File/min chi2/min chi2 12.png]]

Come troviamo le incertezze sui parametri. Questo è legato all'intervallo di confidenza. 
Noi, supponiamo che esistano dei _valori veri_ dei parametri, che descrivono il set di dati che abbiamo.
Noi, i valori veri non li conosciamo:
![[../File/min chi2/min chi2 13.png]]
La nostra misura è un set di coppie di dati, mediante le quali, tramite il fit facciamo una stima di questi parametri.
Noi ora supponiamo di fare una misura dell'insieme di n dati. Questi li analizziamo e facciamo una stima dei parametri
Se facessimo un'altro set di misure (altra coppia di dati), ci sono fluttuazioni casuali sulle misure delle singole y. Questo porterebbe, quindi, ad altri valori sui parametri risultanti dal fit (Infatti questa è proprio la definizione di incertezza casuale). Il problema da affrontare, quindi, è come sono distribuiti i dati dal fit attorno al valore vero.

![[../File/min chi2/min chi2 14.png]]
Prendiamo il caso semplice di due parametri. Il pallino rosso rappresenta il valore vero del parametro. Ogni volta che faccio un'altra misura, ottengo una stima diversa di questi due parametri. 
![[../File/min chi2/min chi2 15.png]]
Un intervallo di confidenza è un volume nello spazio dei parametri che contiene una certa frazione della distribuzione.
Concentriamo la nostra attenzione su parametro 1. Le due barre verticali rosse racchiudono il 68% della distribuzione del parametro a1, indipendentemente dal parametro a2.
![[../File/min chi2/min chi2 16.png]]
Stessa cosa per le due barre rosse orizzontali.
Se considero la variazione dei due parametri congiuntamente, otteniamo una figura più complicata (ellisse blu). Questo è l'intervallo di confidenza (in questo caso, superficie del piano che raggruppa congiuntamente il 68% della roba.

La cosa importante è che se prendiamo la proiezione di quest'ellisse sui due assi, questa proiezione è _maggiore_ dell'intervallo di confidenza sul parametro singolo. Questo è perchè se io ammetto la variazione congiunta dei due parametri, questi due vanno a compensarsi a vicenda.
Come ci si comporta, quindi? Nell'analisi dati, quello che si fa è trovare un set di dati che minimizza la funzione di merito (\chi^2). 
![[../File/min chi2/min chi2 17.png]]

Partendo da questo concetto, si può dimostrare che facendo un fit con \nu gradi di libertà
, gli intervalli di confidenza sono dati da :
![[../File/min chi2/min chi2 18.png]]
![[../File/min chi2/min chi2 19.png]]
![[../File/min chi2/min chi2 20.png]]
Basandosi su questo, si forniscono le cosiddette incertezze standard:
![[../File/min chi2/min chi2 21.png]]
Osservo che questa incertezza standard non dipende dalle incertezze sulle y. Questo perchè la incertezza sulla y, sotto radice, si va a compensare tra chi2 e $C_{kk}$.
