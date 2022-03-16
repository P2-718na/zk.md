### Integrale primo come curva di livello
Per definizione, un [[Integrale primo del moto|integrale primo]] rimane costante per tutta la durata di un moto.
Questo significa che, se prendo il mio $H$ e lo eguaglio ad una costante arbitraria $E$
$$
H = E
$$
ottengo una [[curva di livello]] dell'energia nello spazio delle fasi. Questa considerazione è _molto importante_ perché, una volta che conosco l'energia in un qualsiasi punto di un [[orbita]] del mio sistema, posso determinarne la [[Legge oraria]]. I sistemi dove posso fare questo, sono detti [[Sistemi integrabili]].

Per il campo di Newton, possiamo svolgere direttamente i calcoli...
### Ricavare la legge oraria per il campo di Newton tramite l'integrale primo
Prendiamo l'[[Integrale primo per il campo di Newton]] ed eguagliamolo ad una costante $E$ fissata. Questa sarà l'energia meccanica totale del mio sistema in un punto qualsiasi di una certa orbita.
$$
H(r,\ p)\ \dot =\ \frac 1 2 \frac {p^2} m + V(r) = E
$$
Questa non è altro che una [[EDO del primo ordine a variabili separabili]]. Per definizione, infatti, abbiamo che $p\ \dot =\ m\dot r$. Ottengo quindi:
$$
\frac 1 2 m \cdot  \left( \frac{d\ r}{dt} \right)^2 + V(r) = E
$$
Lascio a sinistra $\dot r$, porto tutto il resto a destra ed estraggo la radice:
$$
\frac{d\ r}{dt} = \sqrt{\frac 2 m [E - V(r)]}
$$
(Prendo solo la soluzione positiva per $\dot r$ visto che ??).
Ora separo le variabili (voglio tutte le cose in funzione di $r$ dallo stesso lato di $dr$) e integro:
$$
\int_{t_0}^t d \bar t =
\int_{r_0}^r \frac
    {d \bar r}
    {\sqrt{\frac 2 m [E - V(\bar r)]}}
$$
(Ricordandomi di dare un nome diverso agli estremi e alla variabile di integrazione)...
Il risultato che ottengo è una _relazione funzionale_ tra $t$ e $r$:
$$
t = \int_{r_0}^r \frac
    {d \bar r}
    {\sqrt{\frac 2 m [E - V(\bar r)]}}
$$
Questo risultato è _importante_ perché quando ottengo questa relazione, vuol dire che ho davanti a me un sistema [[Sistemi integrabili|integrabile]]. _Non_ importa se l'integrale è risolvibile analiticamente o meno; già trovare questa relazione ci apre diverse possibilità. In particolare, se la relazione è invertibile, possiamo usarla per determinare la [[Legge oraria]] del sistema.

`OSS` I sistemi integrabili sono _pochi_. ( #deepen qui ci andrebbe tutto un discorso su come siamo arrivati a capire quali sistemi sono integrabili o quali no ). In generale, solo i sistemi a una dimensione (o riconducibili a tale) sono integrabili. Un esempio di sistema _non integrabile_ è dato dal _pendolo doppio_.