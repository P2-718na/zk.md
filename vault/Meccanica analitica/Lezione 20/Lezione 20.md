\[Discorso sul fatto che ci spanerà il culo all'esame\]


Approccio standard dei problemi:
![[Pasted image 20220330141553.png]]
Prima cosa da fare:
scrivo la lagrangiana.
La lagrangiana si usa, _senza toccarla_.

Per questioni di simmetria (che vedremo più avanti), ci aspettiamo che la lagrangiana non dipenda da \varphi. (Se siamo in coordinate sferiche, ci aspettiamo che il nostro problema, e quindi la lagrangiana, non cambi se ruoto la sfera).

![[Pasted image 20220330141703.png]]
Qui abbiamo due IPM: energia meccanica e ??
Una volta che siamo arrivati qua, questi due IPM, che sono in numero pari a quanti sono i gradi di libertà, _diventano loro stessi le equazioni del moto_. Sono EDO al _primo ordine_. (E quindi, se sono EDO del primo ordine, con la separazione delle variabili riusciamo a ricondurre il problema ad una roba integrabile).

Ora, l'idea è che vogliamo usare tutti i cambiamenti di variabili che mi vengono in mente che possono :.
Per esempio, se arrivo qua:
![[Pasted image 20220330141849.png]]
Questa roba la posso separare come EDO, ottenendo:
![[Pasted image 20220330141902.png]]
Qui devo poi solo fare un integrale e un integrale si fa ez.

Ora, a parte questo, il calcolo tecnico dell'integrale _non ci fa capire l'analogia di questa equazione con l'equazione che viene fuori dallo studio di un problema sul piano_.
Questa analogia salta fuori nel momento in cui andiamo a fare questo cambiuo di variabili.

Ricorda: _mentre la lagrangiana NON la possiamo toccare_, l'equazione differenziale è un oggetto che possiamo modellare a nostro piacimento.

Ora, facendo tutti questi cambi di variabili a cazzo, all'inizio sembra complicato...
![[Pasted image 20220330142110.png]]
    (qui ricordo che questo cambio lo faccio in modo locale, visto che il seno di theta non è invertibile in tutto l'intervallo. Questo vuol dire che con questo cambio avrò due singolarità, e devo considerare il cambio due volte).

![[Pasted image 20220330142206.png]]
Quindi facendo tutta questa roba io ottengo una forma di energia che è esattamente la stessa di un oscillatore armonico.

Ora, una funzione di questo tipo la possiamo riportare a:
![[Pasted image 20220330142256.png]]
un equazione di un oscillatore armonico. Questo ci permette di integrarla senza fare i conti.

QUesto (cosa??) ci dice anche comne _avere pochi problemi che noi sappiamo risolvere completamente_, _ci porta a voler ricondurre tutti i problemi a questi qua_.

Ora vediamo come ragiona un fisico:
contesto dei __potenziali centrali__ che hanno la dipendenza del tipo 
$$
V(r) = kr^{\alpha}
$$
Questi potenziali essenzialmente sono gli stessi potenziali che abbiamo trovato nel l
??????????

Cosa possiamo dire di questi potenziali?

1) Sono potenziali omogenei. (r^\alpha è una funzione omogenea del raggio). E quando io ho una funzion eomogenea,. posso fare alcune consideraizoni. Per esempio, possiamo andare a vedere cosa succede nel momento in cui io cambio unità di misura da spaziale a temporale.

Ora, ![[Pasted image 20220330142615.png]]
non si capisce

La nosrra lagrangiana è $L = T-V$. 
Il fatto che la lagrangiana sia T - V Nei sistemi inerziali è un _assioma_. (equivalente di F=ma). Di fatto la teoria questa roba qua la assume sempre vera.

Quindi questo lo prendiamo per vero. La difficoltà grossa sta nel definire _cos'è un sistema inerziale_. Infatti, di solito la definizione di sistema inerziale è proprio "un SI è un sistema dove la lagrangiana è T-V". Quindi di fatto questa roba la ammettiamo.


La lagrangiana definisce le quazioni del moto attraverso la formula delle equazioni di lagrange...

Non ci interessan in questo momento scrivere le equazioni del moto, ma ci in teressa notare che se io cambio la lagrangiana aggiungendo un C davanti, anche questa operazione _non cambia le equazimni del moto_. Infatti, le EDM sono appunto equazini lineari. ?? questa roba potrebbe altraree le dimensioni fisicbhe della lagrnGIANA, ma a patrte questo le edm non cambiano,.

se faccio una trasformazionie che come effetto ha quello di moltiplicare la lagrangiana per un fattore, questa operazione lascia inalterato il miop sistema fisico. => LE soluzioni  per la lagramngiana scalata solo soluzioni per la lagramgiana di partenza. In realtà, queste potrebbero essere osluzini che non corrispondiono alle stesse condizioni di partenza. ma visto che lòe edm non cambiano le soluzini eimangono uguali.

Quindi andioamo a vedere che succede scalando tutto:
![[Pasted image 20220330143016.png]]
Scalo tempo, posizione, velocità. 
Queste tre formule mi dicono che la lagranfgiana scritta nelle variabili scalate, diventa una algrangiana in cui la parte cinetica lòa possiamo sostuìituire scrivendola come velocità (variabili iniziali) moltiplicvata per \frac \lmbda 2 ^2. La parte cinetica (raggio) scala con la variabile $\lambda$ => avrò $-k \lambda ^a * r^a$.
Se volgio usare la nuova algranfiana scalata, devo fare in nmodo che la vecchai lag sia uguale alla nuova lag scalata per un certo fattore.

(?? si comunque questa roba non ha senso, non si capisce che cazzo diuce).

Quindi, cosa deve accadere? Deve accadere che 
![[Pasted image 20220330143239.png]]
\lambda alla 2 - a deve essere uguale a \mu^2. Se accade questo, le equazinni del moto nei due casi sono le stesse (invarianti). Che conseguenza ha questo per le soluzioin? Vuol dire che se io prendo una solzuione x(t) per il sistema iniziale, e scalo le variabili sia sul tempo che sullo spazio, a questo punto la soluzione che scrivo deve essere ancora soluzione del moto.

![[Pasted image 20220330143351.png]]
??
???

Insomma questo vuol dire che da poche soluzioni io posso costruirmi tutta una famiglia.

Non solo, se la mia soluzione è periodica, vuol dire che la mia x(t) a un certo punto torna al punto di partenza. E se x(t) ha questa prop, allora anche tutte le soluzioni scalate hanno la stessa proprietà. Il periodo, però, dovrà essere riscalato rispetto al periodo iniziale tramite la costante \mu. Se quindi io riscrivo mu rispetto alla relazioni.
Quindi, il periodo dell'orbita riscalata sarà il periodo della vecchia orbita per $\lambda - \frac a 2$.
Come posso leggere questa relazione? La posso leggere che se io prendo una dimensione caratteristica dell'orbita iniziale (che può essere il raggio, una geodetica, un apocentro...), questa dimensione spaziale nell'orbita finale sojno lambda, e quindi io ho um riscalamentp su lambda nello spazio e ho un riscalamento con \lambda \mu \frac a 2 sul tempo. Quindi posso mettere in realzione una comginazine del periodo e della mia grandezza.
![[Pasted image 20220330143903.png]]

????
Il risultato è che
![[Pasted image 20220330144002.png]]

![[Pasted image 20220330144015.png]]

Andiamo a prendere i nostri potenziali che ci interessano. Il potenziale elastico, a=2 (1/r^2).
Se pluggo questa roba dentro, il periodo delle orbite chiuse non dipende dalla dimensione. E questo è un riflesso della linearità del problema. Ovvero, ho un periodo che non dipende dalla dimensione dell'orbita.

(da questo diciamo che gli orologi a pendolo, se l'oscillazione  piccola, hanno un periodo che non dipende dalla dimensione del pendolo).

Se invece prendiamo a=1, allora il periodo è proporzionale a ![[Pasted image 20220330144140.png]]
E qui ritroviamo proprio la terza legge di keplero.

"il periodo di un orbita per un pianeta era proporzionale al semiasse maggiore alla \frac 3 2".

Se keplero avesse conosciuto il potenziale di newton, avrebbe potuto dedurre la terza legge.

\[ Qui fa un discorso interessante. "Il fisico fa questi tipi di ragionamenti, dove vado a pensare cosa succede quando vado a scalare gli oggetti. Un matematico, non fa questi tipi di discorsi." \]

Nei problemi unidimensionali possiamo andare a vedere come scala l'azione in funzione dell'energia.

Ricordando la definizione di [[../Note/Variabili azione-angolo#DEF Azione|azione]], ???
quello che mi interessa non è tanto il valore dell'integrale, ma più come varia l'energia in funzione dell'azione.

((Qui la seconda metà della prima ora si è andata a fottere))

