 "Quando ho un problema, non posso sbatterlo direttamente in un computer. Devo prima trattarlo in modo da poter ottenere un risultato numerico con la precisione desiderata".

### Principio di minima azione
QUesto principio è fondamentale, sostanzialmente perchè mette un ottica nuova nel modo in cui noi guardiamo le equazioni del moto. Si passa da quelli che sono equazioni differenziali a quello che invece è lo _studio di funzionali_ (altra cosa, diversa dalle EDO, tecniche diverse...)

Le forze sono grandezze fisiche che descrivono le accelerazion idi sistemi meccanici attraverso coefgficienti di proporzinalit che noi chiamiamo "massa inerziale". Lagrange fa dimenticare quella che è l'equazione di Newton, e la sostituisce con l'equazione in forma covariante di Lagrange.

Il principio di Minima azione toglie completamente il concetto F = ma.
Questo punto di vista si basa comunque sulla lagrangiana. Rimane il fatto che il problema fisico denbba essere associato ad una lagrangiana. Il come associamo un problema fisico alla lagrangiana è una cosa puramente fisica. Però a questo punto, le equazioni del moto si distaccano dal concetto di EDO, ma iniziano a basarsi sul conectto che "qualcosa risulta minimo/estremale" nel momento in cui vado a considerare le equazioni del moto.

Quindi, prima diamo delle definizioni un po' generali di cosa sia un funzionale:

#### `DEF` Funzionale
Si è introdotta la parola funzionale per indicare non una funzione, ma uno spazio di funzioni (a dimensione infinita) ai numeri reali.
Per definire un funzionale, _prima di tutto devo definire un dominio_. Prendiamo quindi dei domini specifici (non qualinque). Prendiamo il dominio dove vivono le lagrangiane:
![[Pasted image 20220504142620.png]]
FUnzioniu abbastanza regolari definite su un intervallo, a valori in un certo spazio finito.
Queste funzioni hanno però la caratteristica di avere i due estremi fissati.
??
Questo è il nostro dominio.

A questo punto la definizione di funzionale è una funzione che, preso uno di questi elementi q, mi da un numeor reale.
![[Pasted image 20220504142820.png]]
Questa stessa definizione si può estendere da \mathbb{R} a \mathbb{R}^n.

Il nome "funzionale" deriva dal fatto che lo spazio in cui vive è uno spazio di funzioni, ed è infinito dimensionale.
Questo ci dice anche perchè noi troviamo una notazione di questo tipo. q non è un punto, ma tutta la funzione.
![[Pasted image 20220504143018.png]]

Siccome il funzionale è un concetto che generalizza il concetto di funzione, io posso calcolare i punti critici per un funzionale, ovvero cercare quali sono le funzioni del dominio per cui un funzionale può avere un massimo o un minmo.

Il concetto è che qui non posso calcolare la derivata. QUindi, quello che faccio è prendere il concetto di differenziale e generalizzarlo. 
Prendo insomma una funzione molto piccola, che è una "variazione dal percorso originale" e so che si annulla agli esremi (gli estremi sono fissati).

Poi facendo calcoli con metriche strane (metriche fegli spazi di funzioni) posso iniziare a parlare di incremento piccolo  \delta q.
A questo punto, posso dire che un incremento è piccolo se, variando la funzione di questa quantità deltaq, ho una roba che è più piccola di un ordine sauperoire...
![[Pasted image 20220504143351.png]]
Io dico che q è un estremale se facendo variare il funzionale, questo funzionale cambia di un valore che non è porporzionakle  alla norma di deltaq, ma è proproziaonle alla norma di deltaq^2.

Bene, a questo punto Eulero si era itnerressato di questa roba e si era posto il rpoblema di come andare a caratteriizzare le curve estremali che renodmnom minimno il funzionale. 
Allora, eulero dice che andiamo a calcolare usando la definizione cos'è f(q+ \delra q). POer definizione, qeusta roba è:
l'integrale:
![[Pasted image 20220504143551.png]]
Ora, formalmente noi cosa possiamo fare? Intanto osservo che queste funzioni q e deltaq localcmente sono piccole, però in linea di principio sono piccole solo localmente.
Tuttavia, noi possiamo sviliuppare la F in taylor nel punto q. E questo qui è un modo per rappresentare formalmente la rappresentazione del funzionale a meno di robe di O(\delta q^2).
Quindi sviluppo in taylor la mi abella funzione integranda:
![[Pasted image 20220504143718.png]]
E per q avrò un estremale di questa funzione se tutta questa roba nel mezzo sarà zero.

Ora determiniamo le condizioni.
deltaq è una roba arbitraria. \delta \dot q è imparentato con \deltaq però può essenzialmente farsi i cazzi suoi,. Quindi, voglio togliere il mio \delta \dot q (dello a destra nell'integrale). Quindi, quello che faccio è andare ad integrare per parti e sfrutto il fatto che \delta q si annulla alle estremità.
![[Pasted image 20220504144048.png]]
(quella roba lì vertical enon è un segno di integrale ma è il segno di "valutato tra").
Quindi, riscrivo la mia roba
![[Pasted image 20220504144141.png]]
(nell' O a destra ci andrebbe una norma ma vabbè).
Quindi ricordo che la mia condizoine di estremalità sia che questa roba si annulli:
![[Pasted image 20220504144236.png]]
Ora, se l'integrale di una funzione è uguale a zero, _non è vero che la funzione è uguale a zero_. Se ho una funzione il cui integrale è nullo, non è vero che la funzione è nulla.
Qui sfruttiamo un teorema matematico (arnold, lo enunciamo e basta)

Praticamente, visto che il \delta q è arbitrario, vale la richiesta che la roba tra parentesi sia = 0 \iff tutto l'integrale è uguale a zero.
![[Pasted image 20220504144415.png]]

Ora, Eulero si faceva le sue seghe matematiche, però alla fine ottiene questa equazione. Lagrange ha il merito di aver riconosciuto che quelle erano equazioni della meccanica. Se al posto di F nelle equazioni di eulero io ci metto la L della lagrangiana, ho delle equazioni della meccanica.
Quindi, enlle equazioni di Eulero c'è un principio variazionale, detto "principio di minima azione". Se definisco l'azione come:
![[Pasted image 20220504144714.png]]
( definizione di azione compativbile on quella che abbiamo visto in dinamica newtoniana.)

(OSS questa roba qua si potrebbe dimostrare che localmente è un minimo. Globalmente diventa più un problema ma vabbè).

##### Esempio swag corda 
Quando devo minimizzare un funzionale con un vincolo, posso sempre usare i moltiplicatori di lagrange...
![[Pasted image 20220504152338.png]]
![[Pasted image 20220504152405.png]]Di fatto l'unica cosa che il mio moltiplicatore di lagrange mi cambia è ce ora ho un elemento in più nell'integrale. In realtà, il mio funzionale non cambia.
Q
(vedi: aggiunge solamente -\lambda nel funzionale).
Quindi le equazioni di Eulero non cambiano. Costruisco quindi le equazioni di eulero prendendo la derivata di tutta la robaa sinistra rispetto a y:
\varrho g y'(x)
e a destra devo derivare rispetto a y':
d/d(y')(...roba nell'integrale).
Mi aspetto quindi come termnini dell'equazioune:
![[Pasted image 20220504152720.png]]
ORa, visto che siamo fisici, io posso vedere questa roba (?) comes e fosse la mia lagrangiana.
Questo problema infatti ha la struttura di un problema fisico fatto con una lagrangiana. Questa lagrangiana non dipende dal tempo, ma è la stessa cosa.
Io so che quando la Lagrangiana non dipende dal tempo, esiste un integrale Energia, quindi _il mio sistema è integrabike_.
Scrivo quindi l'energia del mio sistema, e da quewta otterrl un EDO a variabili separabili integrabiki,.

Qualè l'energia di una lagrangiana che ha questa forma quO=?

Noi abbiuanom viusto che se ho una L(\dot q, q), allora l'energia per definizione è un integrale primno del motoo e la scrivo come
$$
E = \sum_k \frac{\partial L}{\partial \dot q_k} \dot q_k - L
$$

Quindi in questo caso la mia energia sarà:
$$
\frac{\partial L }{\partial y'} - L = E
$$
![[Pasted image 20220504152942.png]]
Il vantaggio è che ora non devo più risolvere una EDO a secondo ordine, ma posso risolvere la mia EDO a primo ordine in cui posos separare le variabili.ù
(bla bla bla tanta roba si semplifica).
![[Pasted image 20220504153210.png]]
per esercizio risolvi integrale
![[Pasted image 20220504153916.png]]
![[Pasted image 20220504154032.png]]
![[Pasted image 20220504154650.png]]

## Nuova lezione
Il principio variazionale delle geodesiche e della lagrangiana sono due robe leggermente diverse.
Nel principio di minima azione, il tempo ha un ruolo chairo. Questo perchè il tempo mi consente di dire 