Differenza tra integrale di Riemann e di Lebesgue:
Per Riemann, l'integrale è l'area sottesa dalla curva. [[inteegrale di riemann]].
![[Pasted image 20220330164923.png]]

Per l'integrale di Lebesgue, partiamo disegnando la stessa curva:
![[Pasted image 20220330164956.png]]
E la andiamo a dividere, Non dove sono definite le x, ma dove sono definite le y:
![[Pasted image 20220330165057.png]]
La suddivisione quindi è per rettangoli orizzontali, non verticali.

Quando aumentiamo il numero di questi rettangoli, ci avviciniamo all'integrale sotto la curva.

Facciamo un esempio: delta di dirichelet:
![[Pasted image 20220330165221.png]]
Proviamo a calcolare questa roba con l'integrale di riemann. _Non riusciamo_ a farlo perchè \delta è irrazionale in tutti i punti.
Se invece lo calcoliamo con l'integrale di lebesgue:
Abbiamo tutti valori tra 1 e zero. tutti i punti dove c'è ?? comunque l'integrale di lebesgue è zero.

Ricordiamo che _l'insieme dei numeri razionali è numerabile_ =>
`DIM` prendiamo un \varepsilon > 0 piccolo a piacere. Prendiamo il primo numero razionale del nostro elenco e lo accoppiamo con \varepsilon. Dopo prendiamo il secondo e lo accoppiamo con \frac \varepsilon 2... Ottengo quindi una somma infinita che ha come somma 2\varepsilon
![[Pasted image 20220330165541.png]]

Quindi tuta la retta reale sta sui numeri ??

Nella retta reale, intervallo da zero a 1, sono numerabi??

Ora, vogliamo dimostrare la disuguaglianza triangolare. SE riusciamo a farlo allora abbiamo davvero ottenuto uno spazio normato.


### Problema dei due corpi
![[Pasted image 20220331143728.png]]
Prima parte: relativamente semplice:
usiamo un campo centrale per andare a calcolare la sezione di Rutheford (che è una coseguenza del problema di keplero).

QUindi, qual è il problema dei due corpi:
se prendo due oggetti ad una certa distanza, che siano isolati, in uno spazio omogeneo e isotrppo:
Come possono interagire questi due corpi?

=> L'unica interazione compatibile è un interazione che dipenda dal _modulo della distanza_. (Se dipendesse dalla direzione, lo spazio non sarebbe isotropo; se non fosse diretta lungo la congiungete non sarebbe omogeneo).

Bene, questo problema è di _natura fisica._.
Qui partiamo dall'idea di studiare cosa succede a due corpi che interagiscono, _nel momento in cui io assumo che l'interazione debba essere dipendente solamente dal modulo della distanza_.

A questo punto, noi cosa facciamo? Andiamo a ragionare come farebbe lagrange:

La lagrangiana del nostro sistema sarà:
![[Pasted image 20220331144037.png]]
(Energia cinetiva rimo punto + en cinetica 2 punto + energia potenziale).
Questa lagrangiana (visto che siamo nello spazio 3d) ha 6 gradi di libertà (3 per primo punto, 3 per il secondo). Già qui è abbastanza complicato capire se riusciamo a risolverla o no.

QUindi, andiamo a fare un cambio di variabili intelligente.
Sfruttiamo la definizione di centro di massa (sappiamo che per un sistema isolato, il cdm si muove di moto rettilineo uniforme). E poi, visto che il potenziale dipende solo dalla differenza dei due punti, sfruttiamo anche questo.

![[Pasted image 20220331144159.png]]
La nostra lagrangiana quindi, dopo il cambio avrà due variabili: la velcoità del centro id massa e la distanza tra i due punti.

Per il potenziale siamo già a posto, dobbiamo andare a sistemare solo la parte delle due energie inetiche. Vado a riscrivere le en cinetiche usando il cambio di variabile:

Vado a calcolare le derivate delle due, e poi devo risesprimere le derivate di r1 punto \dot r2 in funzione del centro di massa (??) 
![[Pasted image 20220331144317.png]]
In un sistema lineare, quindi, devo prendere questa relazione
![[Pasted image 20220331144330.png]]
Sostituisco una delle due variabili l' dentro, vado a sostituire tutta la roba, inverto la relazione per trovare la relazione che mi da r1 in funzione di vcm. (Semplicemente risolvo un problema lineare in due variabili, già visto prima).

Ora, se vediamo, il sistema deve conservare delle simmetrie per (??); quindi se io voglio vedere se questa espressione che ho ottenuto è più o meno corretta, _posso ragionare andando a vedere cosa succede se scambio r1 con r2_: ci aspettiamo (come infatti accade), che vcm resti esattamente uguale, e che r cambi di segno. => questa roba ceh abbiamo fatto, quindi, ha l'aria di essere corretta.

Quindi, questo è anche un modo per ricordarsi anche un po' a memoria le robe.

A questo punto, chi sarà l'energia cinetica? Per calcolare l'energia cinetica, devo sostituire dentro  a T ^^ r1^2 e r2^2.

![[Pasted image 20220331144610.png]]
Quindi sicuramente questi due termini mi creano dentro questa roba delle robe

bla bla

Arrivo a definire la massa ridotta $\mu$

Quindi la nostra lagrangiana si riduce a:
![[Pasted image 20220331145011.png]]
E quindi, la nostra lagrangiana assume la forma di una lagrangiana di un punto materiale che abbia massa somma delle masse, non dipende dalle singole velocità ma solo dalla vcm. E soprattutto, qiestp primo termine non interagisce con il secondo pezzo della lagrangiana.

![[Pasted image 20220331145103.png]]

Quindi, questo sistema diventa un sistema di _due oggetti non interagenti_: _moto di centro di massa_ e _moto relativo delle masse dovuto all'interazione_. QUindi, possiamo studiare questo sistema lagrangiando spezzando i due:
![[Pasted image 20220331145140.png]]
Le edm della prima parte della lagrangiana ci dicono che:
![[Pasted image 20220331145152.png]]
Perchè sono coordinate cicliche. QUindi noi troviamo in formalismo lagrangiano che la quanitàt di moto del centro di massa deve essere un IPM. => Il cdm si deve muovere a veòpcotù rettilinea uniforme.
(La copsa interessante è che questo stesso risultato lo potrei ottenere in dinamica relaitivistica, visto che la lagrangiana è giàù a adatta a fare meccnaica relativistica ristretta).
(Non lo facciamo perchè non possiamo usare la relaitvità ristretta con il potenziale di keplero => Serve quindi la relatività big)

Cosa ci rimane quindi? Ci rimane questa lagrangiana qui:
![[Pasted image 20220331145356.png]]
Questa roba qua in realtà è la lòagrangiana di un piuntp materiale di massa ridotta nello spazio, soggetto a potenziale centrale.
Le forze centrali, si può sfruttare la simmetria del sistema, nei campi centrali sono forze che conservano il ?? del moto. => Il prodotto della massa per r per la velocità è invariante:
![[Pasted image 20220331145447.png]]
Allora, cosa vuol dire questa roba?

??

CI mettiamo nel "Piano del moto", e quindi vediamo qeusto sistema come un sistema a 2 gdl, invece che un sistema a 3. => Lo vediamo esattamente come un sinstema con un èpotenziale centrale.

==> _Il problema dei due corpi si riduce al problema di calcolare il moto di una particella di massa ridotta in un piano e con un potenziale di un campo centrale._ E a questo punto, questo qui potrebbe essere il sistema che mi dice qual è il moto relativo delle due particelle se mi metto nel sistema di riferimento centrato nel centro di massa.

Questo mi dice che le lagrangiane _non_ sono invarianti se io faccio un cambiamento di sistema inerziale o no. Ma in realtà sì perchè se mi metto in un sistema non inerziale questo cambiamento è ininfluengte ??? 


Ultima cosa: a me non interessa sapere il moto relativo; mi interess sapere il moto delle particelle. Quindi, cosa devo fare? Mi basta riscalare la ?
![[Pasted image 20220331145957.png]]

E a questo punto vado a vedere se m2 >> m1, questo (![[Pasted image 20220331150044.png]])
tende a diventare zero. Quest'altro invece
![[Pasted image 20220331150055.png]]
Tende a diventre ~= r.
![[Pasted image 20220331150107.png]]


Esempio, per terra/sole, la terra fa esattamente un'ellisse kepleriana e il sole non lo vediamo muovere, visto che il sole fa una piccola ellisse attorno al suo centro e la sua massa  è troppo grande perchè si veda.

Da qui lascio continuare agli appunti.