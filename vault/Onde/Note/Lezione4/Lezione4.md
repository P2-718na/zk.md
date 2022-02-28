Noi ci troviamo in una situazione in cui vogliamo risolvere una generale soluzione dalla formula (con una forzante arbitraria):
![[Pasted image 20220228141114.png]]
(vogliamo trovcare la formula per le soluzioni in forma più generale possibile).

Per farlo, dobbiamo capire quali sono le caratteristiche più generali di questa equazione.
Eq. differenziale => Cerco una funzione x(t) che risolva questa roba.

Questa equazione è _lineare e non omogenea_. La soluzione più generica (già visto), sarà quindi una somma tra soluzione dell'omogenea ed una soluzione particolare con questa forzante:
![[Pasted image 20220228141328.png]]
Osservo che le condizioni iniziali saranno sempre nell'omogenea, che quindi avrà certi parametri liberi dipendenti da esse.

Sulla parte dell'omogenea, vale il _principuo di sovrapposizione_: se x1, x2 sono soluzioni idverse generiche, allora una loro combinazione lineare con coeff. a e b arbitrari sarà soluzione dell'omogenea.
![[Pasted image 20220228141431.png]]

Proviamo ad introdurre un po' di terminologia:
un0equazioned i questo genere:
![[Pasted image 20220228141501.png]]
può essere riscritta in un linguaggio che contiene i "operatori funzionali".
Un operatore funzionale è un oggetto he contiene un operazione da fare su una funzione per ottenere un'altra funzione.
Tutto il primo membro di questa, può essere riscritto come:
![[Pasted image 20220228141541.png]]
"l cappell". Cosa intendiamo con questa scrittura? L'operatore è la _funzione matematica_ che viene applicata ad una struttura (per esempio, in questo caso trovo derivate senza funzione.)
L cappello applicato ad x varrà quindi:
![[Pasted image 20220228141619.png]]
Insomma, un operatore è un modo di rappresentare EDO di questo genere.
Quindi, in estrema sinitesi, l'eq. dell'oscillatore armonico forzato diventa di questo tipo:
![[Pasted image 20220228141656.png]]
Dove l'incognita è x(t).

Questi operatori funzionali sono particolarmente utili perchè mi danno un modo di scrivere equazioni in modo sintetico. A noi interessano in modo particolare i cosiddetti [[_operatori lineari_]], definiti da![[Pasted image 20220228141741.png]]
1) "è un po' come se questo operatore funzionale avesse una proprietà distributiva sulla somma".

Facciamo qualche esempio concreto:
![[Pasted image 20220228141958.png]]
La domanda ora è: 
se so che tutte queste robe sono operatori lineari, la domanda è:
![[Pasted image 20220228142056.png]]
questa roba, è un operatore lineare? SÌ.
Vediamo ora quali sono le proprietà di questi operatori.

1) Caso di _equazione omogenea_, mi ritrovo in:
 ![[Pasted image 20220228142151.png]]
Vale che:
![[Pasted image 20220228142206.png]]
__Questo vale $\iff$ $\hat L$ è lineare__. Facendo un esempio:
![[Pasted image 20220228142306.png]]
Questa roba, in tante circostanze è chiamata _principio di sovrapposizione._
La ragione perchè il PS vale per altri campi (elettrico...) è la stessa per cui vale qua.

Ora, ci si può chiedere quante _combinazioni lineari indipendenti_ si possono fare. (Per esempio, ricordo uno dei problemi dell'oscillatore armonico smorzato in cui delta=0 da una sola soluzione). Vale che:
![[Pasted image 20220228142557.png]]
Per l'oscillatore armonico, quindi:
![[Pasted image 20220228142718.png]]
Le costanti sono arbitrarie. Per esempio, per il moto armonico smorzato, usiamo ampiezza e fase.
Quali sono le due condizioni iniziali? Basta che siano due condizioni indipendenti, che mi permettono di fissare univocamente la mia condizione. Per esempio
![[Pasted image 20220228142812.png]]
Una domanda tipo è: "se ti do due velocità in due istanti diversi, riesco a trovare una soluzione univoca, riesco a trovare una soluzione?" => La risposta è NO, perchè poi quando vado ad integrare una velocità per trovare una soluzione, mi rimane una costante arbitraria per trovare una soluzione.


### Caso b) equazione non omogenea
![[Pasted image 20220228143017.png]]
In questo caso, la mia soluzione è data da una somma di due pezzi:
![[Pasted image 20220228143031.png]]
Una che può non avere nessun parametro libero (soluz particolare),
l0altra quella omogenea. Si riesce a vedere che la somma di queste due è soluzione. La dimostrazione è abbastanza facile, una volta introdotta la notazione $\hat L$.
![[Pasted image 20220228143112.png]]
.
Altra cosa che mi interessa è se la soluzione per una forzante arbitraria passa per questo caso: supponiamo che il termin noto sia esprimibile come somma di due funzioni:
![[Pasted image 20220228143248.png]]Si può dimostrare che se uno mi da le due soluzioni per le due diverse forze:
![[Pasted image 20220228143318.png]]
Allora, la somma di queste due soluzini particolari è una soluzione dell'equazione di partenza.
"se ho un problema con una funzione somma di 10 pezzi, io risolvo tutti assieme e poii li sommo tra di loro".
NOTA:  dentro a x1 e x2, può esserci la soluzione dell'omogenea. Questa soluzione sarà sempre la stessa, quindi se me la trovo due volte e la sommo, alla fine finirà che una di queste due va via.
Altro esempio:
![[Pasted image 20220228143546.png]]
Problema con forza peso, forzante1 (coseno) e forzante2 (seno).
Dobbiamo scomporre il problema. Avremo questi diversi problemi da risolvere:
![[Pasted image 20220228143720.png]]
Prima, soluzione omogenea, poi soluzione (facile) a forzante costante (-mg)
poi abbiamo le due particolari:
![[Pasted image 20220228143744.png]].
Le soluzioni, assieme, andranno ad essere queste:
![[Pasted image 20220228143924.png]]
![[Pasted image 20220228144027.png]]

### Esempi di op lineari
quanti operatori lineari abbiamo visto?
![[Pasted image 20220228144124.png]]
Le equazioni di maxwell sono equazioni lineari (non necessariamente omogenee).
Rotore e divergenza sono operatori lineari.
Anche l'equazione delle onde è un0equazione che contiene un operatore lineare:
![[Pasted image 20220228144245.png]]
Altre equazioni avranno tutte la stessa struttura. Per esempio:
![[Pasted image 20220228144331.png]]

### Serie di fourier
Ferrarino pheega
![[Pasted image 20220228145632.png]]
![[Pasted image 20220228145639.png]]
Vogliamo risolvere un0equazined di questo genere con una forzante arbitraria, posto il fatto che $\hat L$ è un op lineare e ha tutte le prorpeità del caso.
Questa rquazione la sappiamo risolvere ora per forzanti semplici (forza costante, oscillatoria, somma di forzanti che sappiamo gestire). Noi però, ora, lo vogliamo risolvere per fornzanti arbitrarie. Questo lo facciamo in due passi.
Primo: consideriamo una f(t) periodica di periodo t. Andiamo alla caccia di una soluzione per una forzante periodica, prima particolare e poi generica. Una volta che abbiamo una soluzione per una funzione peridoica gnerica, il apssaggio ad avere funzioni non periodiche, lo facciamo in maniera molto semplice:: andiamo a prendere un peridoo di quella funzione arbitrariamente lungo. ![[Pasted image 20220228145854.png]]
La parte difficile, quindi, è la prima.

. Partiamo prendendo una funzione periodica con qualche parametro libero (vedremo dopo il perchè dei parametri liberi scelti in questo modo:)
![[Pasted image 20220228145959.png]]
Ogni singoolo termine ha una sua ampiezz F_n. Omega è la pulsazione associata. nw vuol dire che vado a prendere pulsazioni multipli interi di w. Ci metto anche la possibilità di avere uno sfasamento delle diverse forze per i diversi n. Se vado ad analizzare questa funzione, siccome ho multupli dell'w più piccolo, quando vado a ragionare nel periodo di queste oscillazioni, ho che i periodi associati ad w vanno:![[Pasted image 20220228150146.png]]

=> Ogni singolo termine, dopo un periodo T si ripete. => Complessivamente, f(t) è periodica di periodo T.
Io voglio risolvere un problema dove questa forzante qui è la forzante di un oscillatore armonico. 
![[Pasted image 20220228150303.png]]
(??)
La prorp di lcap è take che questa roba si risolve facendo:
![[Pasted image 20220228150323.png]]
In questo modo, per la prop. 3 degli operatori lineari, la soluzione lineare sarà
![[Pasted image 20220228150406.png]]. Regola generale: Ho un problema complesso che non so risolvere => lo separo in tanti problemi più piccoli che (magari) so risolvere più facilmente. Dopo metto tutto assieme e sbam sesso duro.

Come troviamo queste soluzioni? La parte cosgtante è facile, vediamo la soluzione n-esima:
![[Pasted image 20220228150524.png]]
(vedi [[Vettori rotanti (fasori)]])
Per risolvere, quindi, si fa questo:
![[Pasted image 20220228150609.png]]
(problema già visto, dove??)
Quindi, viene fuori che questo \lambda_n, sarà uguale a inw (seconda formula foto sopra).
Sull'ampiezza non cambia nulla. Vado a sostituire tutto, e quando vado a sostutiure tutto, trovo un'ampiezza:
![[Pasted image 20220228150802.png]]
Uguale a quello visto prima (dove??) tranne che ora al posto di \Omega abbiamo nw.
=> La soluzione complessa non è particolarmente diversa da quello già visto. => (omttendo i conti), si ha:
![[Pasted image 20220228150853.png]]
. Se vado a fare un confronto dalla roba vista settimana scorsa, la differenz aè solo la fase e nw nelle formule. Tutto il resto è uguale.
Quando vado a prendere la soluzione, la soluzione reale è quindi:
![[Pasted image 20220228150938.png]]
(???) $x_n(t) = A_ncos(n\omega t + \phi_n - \delta_n)$
![[Pasted image 20220228151051.png]]
Si può eliminare le fasi, ottenendo:
![[Pasted image 20220228151104.png]]
Quando si preferisce usare seno e coseno piuttosto che una fase, si rinominano i vari coefficienti.
![[Pasted image 20220228151205.png]]

QUINDI, anche il problea iniziale divent riscritto come un oggetto fatto così:
![[Pasted image 20220228151224.png]]
(dovee sono andato a togliere le fasi dalla roba).
Se noi sappiamo risolvere questo prob, sappiamo risolvere anche questo:
![[Pasted image 20220228151251.png]]
^^ Insomma, quello che era il probl iniziale, lo sono andato a riscrivere tramite somme di coseni e seni.
Ora la domanda è: quanto è generale una funzione scritta così?
![[Pasted image 20220228151407.png]]
- Beh, di sicuro è periodica... E qui, ci viene ad aiutare Fourier:
#### `THM` Teorema delle serie di Fourier
![[Pasted image 20220228151500.png]]
^^ Una funzione fatta così (periodica, limitata, numero finito di discontinuità), può _sempre_ essere approssimata con questa serie^^.
LA cosa interessante è che, la formula da cui siamo partiti, riscritta in questo modo, può approssimare _tutte_ le funzioni periodiche.
=> Quello che abbiamo visto prima, in realtà, è proprio quello che ci serve. Visto che ogni funzione periodica arbitraria può essere riscritta così, allora può anche essere approssimata (e sopratttuto, sappiamo risolvere il problema dell'oscillatore armonico forzato).
Quindi, se qualcuno mi da una funzione periodica, tutta la mia difficoltà diventa: come posso scrivermela in termini di coseni e seni?
Cioè, quali saranno i valori di tutti i coeff a_n e b_n che mi danno quello che  cerco?
(qui avremo un teorema (non dimostrato), per cui però è bene dare la definizione di serie di funzioni convergente:)
![[Pasted image 20220228151925.png]]
l'integrale deve essere svolto su _un periodo_. (estremi a scelta, basta che siano su un period). Diciamo che la nostra funzione converge se quell'integrale può essere piccolo a piacere.

QUindi come troviamo i coefficienti? Skippiamo al dimostrazione, vediamo solo che indicativamente questa roba funziona: (NON FACILE):
Per giustificare l'espressione dei coeff a e b, abbiamo bisogno di alcune prorpeità di _ortonormalità_ delle funzioni coseno e seno:
(non sappiamo un cazzo, diamo tutto per buono, seeee)
è possibile dimostrare che valgono queste tre identità:
![[Pasted image 20220228152243.png]]
Dove l'integrale è su un periodo, T definito da \omega. Si riesce a dimostrare che questi tre integrali valgono quelle tre robe.

Bene, date queste formule, per trovacre i coefficienti devo definire una funzione di scarto. La \epsilon nella definizione prima, la chiamo \lambda_n, e sarà una funzione sui parametri definita come:
![[Pasted image 20220228152513.png]]
I coefficienti a e b migliori,  i dovranno determinare una lambda piccola (vorrei avere una lambda che vale zero, per avere un'approssimazione buona).
Riscrivo questa roba:
![[Pasted image 20220228152600.png]]
Se la penso per una funzione di un generico elemento, osservo che lambda è sempre positiva.
![[Pasted image 20220228152615.png]]
In più, osservo che questa è funzione di un numero infinito di parametri
(( non sto capendo una sega perchè mi sono distratto))
![[Pasted image 20220228152735.png]]
(??) scopro che lamdba sarà quadratica in N. Detto in altri modi, questa funzione come funzione di un parametro alla volta, mi descrive una para bola. Quindi, mi descrive una funzione di questo tipo, in funzione di a_m
![[Pasted image 20220228152827.png]]
Per prendere la migliore approssimazione, minimizzo la funzione degli scarti (minimizzo \lambda_m) (trovo punto dove derivata proima prima si annulla).
(???)
![[Pasted image 20220228153123.png]]

![[Pasted image 20220228153134.png]]
Queste robe si cavano perchè:
1) cos integrato su un periodo fa sempre zero
2) quando vado a fare la sommatroia, trovo tanti zeri tranne quando ??
3) contnua..
 ![[Pasted image 20220228153258.png]]
 Trovo quindi il risultato che mi da il valore di a_m che mi serve.

 Allora, m è una variabile muta, quindi rimetto n sia a primo che a secondo membro
.
Queste operazioni le devo rifare tutte uguali per tutti i coefficienti di tutte le robe:
![[Pasted image 20220228153404.png]]
Le formule che si ottengono per tutta la roba sono:
![[Pasted image 20220228153503.png]]
osservo che a_0 scritto così, rappresenta il valore medio della mia funzione periodica scritto su un periodo.
=> queste sono le soluzioni per una funzione periodica arbitraria.

Torniamo un attimo indietro, riprendiamo thm fourier:
![[Pasted image 20220228153610.png]]
Ora abbiamo anche la parte che manca, ovvero la ricerca dei coefficienti a_n b_n e a_0.
=> Da questo momento in poi sappiamo scrivere tutto quello che ci serec e risolvere, a patto che la forzante sia periodica.
^^^ Tutta questa roba che abbiamo visto, è la serie di Furier nel __campo reale__. Nei complessi, invece, la serie è "più simmetrica":
![[Pasted image 20220228153919.png]]
quando io prendo un termine generico dove sviluppo in serie, lo posso riscrivere in termini di questi esponenziali:
![[Pasted image 20220228153943.png]]
Osservo che questi esponenziali sono dei [[Vettori rotanti (fasori)]], uno che ruota in senso orario (+) e uno antiorario (-).
Vado a raccogliere e vedo (ultima riga foto sopra) i due fasori con [[Altre rappresentazioni dei complessi#Rappresentazione polare|rappre esponenziale]].
Raccolgo le parentesi prima degli esponenziali e ottengo;
![[Pasted image 20220228154125.png]]
Ora rinomino un po' di roba perchè è comodo (?)
![[Pasted image 20220228154146.png]]
Il passo successivo è osservare che nella serie di fourioer ho un termine a zero, e poi ho da 1 in avanti termini di questo tipo
![[Pasted image 20220228154222.png]]
Quindik riscrivo tutta questa roba (nota sokmatoria da 1 a +inf)
![[Pasted image 20220228154245.png]]
Oppure, equivalente
![[Pasted image 20220228154303.png]]
(insomma splitto n positivi e negativi).
I coefficienti sono quindi, per la serie complessa: (??)
![[Pasted image 20220228154434.png]]
raccolgo tutto in un singolo integrale:
![[Pasted image 20220228154505.png]]
dove ho usato il fatto che il seno è funzione pari (o dispari, non ricordo)
Il risultato finale è che nei complessi la funzione la esprimo così:
### Serie complessa di fourier
![[Pasted image 20220228154607.png]]
con coefficienti c_n
![[Pasted image 20220228154617.png]]
=> La mia funzione periodica, qui, è un unica sommatoria di fasori.

Bene, proviamo a vedere cosa succede nella pratica:
partiamo dal nostro oscillatore forzato da una f(t):
![[Pasted image 20220228155111.png]]
Devo scrivere f(t) come 
![[Pasted image 20220228155121.png]]
E calcolo i rispettivi c_n così:
![[Pasted image 20220228155135.png]]
. si ha:
![[Pasted image 20220228155150.png]]
Questo è un problema lineare, in cui al secondo membro si ha una somma di tanti termini. risolvo quindi trovando una soluzione particolare alla volta, e poi rimetto tutti assieme.
diocane
La soluzione particolare al mio problema è quindi la sommatoria di tutte le soluzione particolari, fatte tutte così:
![[Pasted image 20220228155339.png]]
Guarda caso, scritte tutte come soluzione di una serie di fourier complessa.
Alla fine, ho:
![[Pasted image 20220228155359.png]]

Per finire, vediamo qualche esempio:
![[Pasted image 20220228155541.png]]
La domanda che ci facciamo è: riusciamno a rapparesentare cos^2 di wt come serie di fourier? Sì, usando le [[Formule di bisezione]]:
![[Pasted image 20220228155649.png]]
Esempio2
![[Pasted image 20220228155724.png]]
Una funzione che va da + certa ampiezza  a - certa ampiezza in maniera oscillatoria. Problema tipo: trovare i coeff dello svlipuppo in serie di fourier.
![[Pasted image 20220228155810.png]]
La cosa figa da vedere è qua: https://www.desmos.com/calculator/1ocbzz5ink
![[Pasted image 20220228160042.png]]
![[Pasted image 20220228160146.png]]