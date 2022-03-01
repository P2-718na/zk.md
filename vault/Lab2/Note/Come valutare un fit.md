### Come valutare un fit
Il modo migliore è partire con un esempio. Abbiamo i seguenti dati (puntini rossi) e vogliamo fittarli con una relazione lineare:
![[guida fit 1.png]]
`OSS` qui (figura sopra), le cifre significative sulle incertezze sono 2 (_mai di più_). La motivazione è che queste incertezze derivano dal risultato di un fit, cioè un'analisi statistica molto accurata. Quindi in questo caso ha senso usare anche più di una cifra significativa.

0) Si esegue il fit. Non importa con quale programma, l'importante è che si sappia il metodo di fitting utilizzato. Dobbiamo anche tenere a mente la [[Differenza tra FIT e test delle ipotesi]]
1) La _prima considerazione da fare_, senza guardare nessun dato numerico, è osservare il grafico del fit risultante. Se la funzione ottenuta è visibilmente diversa da quelli che sono i nostri dati, possiamo già rigettare il fit. Per fare questo, è utile anche plottare il grafico del _residuo_ (differenza tra scarto e fit, indicato in rosso in figura). Ci aspettiamo che questo grafico oscilli uniformemente attorno allo zero.

A questo punto, abbiamo __due casi__:
- Incertezze $\sigma_y$ note _a priori_.
- Incertezze $\sigma_y$ _non_ note.
Vediamo come procedere:

---
##### Caso incertezze note
2) A questo punto, possiamo [[Minimizzare il chi quadro]] e osservare il valore di $\tilde{\chi}^2$. La probabilità di ottenere un certo chi quadro ridotto è tabellata, e possiamo quindi associare una probabilità al nostro fit ottenuto. Dobbiamo però acceertarci che questo valore sia ragionevole (vedi: [[Esempi di fit]]).
3) Possiamo osservare le matrici di [[Matrice di covarianza|covarianza]] e [[Matrice di correlazione|correlazione]] #todo ![[guida fit 2.png]]

---
##### Caso incertezze non note
Questi sono gli stessi dati di prima, ma i fit sono stati svolti senza conoscere le incertezze:
![[guida fit 3.png]]
2) Quello che si fa in questo caso è _scegliere un valore arbitrario per $\sigma_y$_ (se vogliamo usare una [[Funzioni di merito|funzione di merito]] che lo richiede. Tanto, il minimo lo si troverà lo stesso e nello stesso posto.
3) Possiamo utilizzare il fit ottenuto per valuare, _a posteriori_ le incertezze sui parametri (vedi: [[Incertezze standard]]).
    `OSS` Ovviamente, _dopo non possiamo_ calcolare $\chi^2$ con queste incertezze, visto che _non sono state valutate in modo indipendente_. Se lo calcolassimo con questa sigma stimata, avremmo un risultato di $\tilde{\chi}^2 = 1$, privo di significato.

    `OSS` In realtà, in casi come questo (dove abbiamo una relazione lineare), possiamo comunque farci un idea statistica di quanto sia buono il nostro fit, usando il [[Coefficiente di correlazione lineare]].