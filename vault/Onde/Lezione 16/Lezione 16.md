### Equazioni di Maxwell
### Introduzione storica
(in fondo, vedi: [[../../Elettromagnetismo/Equazioni di Maxwell]])

Ora, a noi interessano le equazioni delle onde, quindi partiamo semplificandoci un po' la vita.
Prendiamo le Equazioni di Maxwell nel vuoto:
![[Pasted image 20220404141955.png]]
Or,a maxwell dopo aver trovato queste equazioni si è messo a ragionarci sopra.
Lui osserva che rotore-derivata erano accoppiate in maniera strana. Lui si immagina di essere nel vuoto, in cui c'è un campo elettrico costante, e immagina che in un punto ci sia una variazione di campo elettrico.
![[Pasted image 20220404142059.png]]
Se ho una perturbazione del campo E in quel punto (= ho una derivata di e rispetto al tempo), mi nasce un rotore di campo magnetico diverso da zero. Ma questo cosa vuol dire? Siccome ne,l rotore ci sono derivbate spaziali, vuol dire che in una regione infinitesima attorno a dove ho generato quel E, ci sarà un campo B.
Questo è l'effetto di questo strano legame tra derivate rispetto allo spazio e rispetto al tempo.

Una volta che ho un campo magnetico, vuol dire che B è variato nel tempo. Facendo lo stesso ragionamento, questo mi indica che ho un rotore di campo elettrio diversop da zero.

Ora, questo rotore _non è definito in un opunto_, ma in _una regione infinitesima_ => la mia perturbazione si sposta dalla regione di partenza, me la ritrovo in un istante dt successivo che occupa una regione più grande. Ora, siccome Maxwell era anche un grande matematico, lui si è riuscito a calcolare anche la velocità con cui si muove questa perturbazione. Arriva a dire che:
![[Pasted image 20220404142340.png]]
Torniamo indietro di 120 anni... Cosa voleva dire una velocità di 3E8 m/s? Beh all'epoca, tutte le velocità conosciute erano di ordini di grandezza _molto molto_ più basi. La cosa nota, era che nel 1865, la velocità della luce variava attorno a... Vedi slide.

Insomma maxwell vede che il suo valore che ottiene è vicino a quello della luce => tira fuori l'ipotesi che la luce potesse essere interpretata come un onda elettromagnetica

##### Prime esperienze
(per valutare che la luce era un campo EM)
![[Pasted image 20220404142646.png]]
^^ All'epoca avevano questo affare. C'è un circuito primario (che noi adesso chiameremo "trasformatore"). Il secondo pezzo del circuito, collegato a delle palle ![[../../Relatività/Lezione 10/gabibbo.png]].
Accendendo e spegnendo la corrente nel circuito primario del trasformatore, si induceva dall'altra parte un transiente di corrente. Questa corrente caricava queste palle metalliche, e alla fine di tutto su queste due sfere metalliche poste a distanza < mm, poteva scoccare una scintilla.
Insomma, tutto questo meccanismo per generare una scintilla.

La dimostrazione dell'esistenza delle onde EM è data dal risonatore circolare (anello, in foto).

La cosa curiosa (e Hertz fu uno di quelli che lo scoprì anche per caso), è che quando si creano dei transienti su questo trasformatore, a distanza si crea una scintilla anche tra queste due sferette.

La domanda è: ma _come mai un oggetto che non tocca nulla di metallico, mi genera una scinitlla?_ => Chiaramente, succede qualcosa nello spazio; si generano le onde EM (come diremmo noi oggi) e si genera una scintilla.

![[Pasted image 20220404143025.png]]
Marconi ha inventato la comunicazione Wireless.
Per lui, la comunicazione wireless era una roba fatta così. A sinistra: pila, trasformatore, due sferette piccoline; una delle due sferette collegate a terra, l'altra collegata a un filo collegato a un aquilone.

Il collegamento a terra e all'aquilone era la _prima antenna radio_, a tutti gli effetti. Nel momento in cui si accende/spegne la cosa nel condensatore, l'antenna emette onde radio (su uno spettro vasto di frequenze).
Lontano, Marconi aveva uno strumento ricevente. Era costituita sempre da un filo con un aquilone. Un oggetto chiamato "coesore" (un oggetto con resistenza molto alta in condizioni normali, ma diventava instant conduttivo quando era attraversato da frequenze compatibili con le onde radio). +  sempre a destra c'era anche un meccanismo per accendere/spegnere interruttore. 

### Equazioni di maxwell - teoria
Vediamo come ricavare il fatto che le equazioni di maxwell generano onde EM dal punto di vista teorico.
![[Pasted image 20220404143515.png]]
Per la nostra trattazione, è comodo usare il vettore $\vec H$, visto che rende le cose più _simmetriche_.
Le Equazioni di maxwell, sono
![[Pasted image 20220404143550.png]]
(Osservo che _non posso separare la coppia (E, B) o (E, H)_). Ricordiamo che __vale il P.S.__.

Come ci convinciamo che lì dentro ci sono le onde EM? Per convincersi, bisogna mostrare che esce fuori l'[[../Note/Equazione di D'Alembert]].
![[Pasted image 20220404143931.png]]
Prendiamo questo, verifichiamo che queste verificano l'equazione di D'Alembert.
Partiamo dimostrando questa relazione tra prodotti vettoriali:
![[Pasted image 20220404144014.png]]
^^ si dimostra ez, tramite [[../../Analisi 2/Calcolo differenziale/Teorema di Schwartz|teorema di Schwartz]].

Parto prendendo la (2), e faccio membro membro l'operazione di rotore:
![[Pasted image 20220404144127.png]]
Mi concentro un attimo solo sul secondo membro. Uso Schwartz per scambiare l'ordine di derivazione e ottengo quello che cerco.
Il primo membro uso la relazione trovata sopra, ricordo che $\nabla \cdot \vec E = 0$ e bella. 

In questo caso qua, ottengo che la grandezza fisica che mi rappresenta l'onda è il campo elettrico:
![[Pasted image 20220404144452.png]]
E questa l'ho ottenuta partendo dalla (2). Se invece fossi partito dalla (4), avrei ottenuto un equazione indentica, con campo \vec B al posto di \vec E. (=> dentro le equzioni di maxwell, ci sono due equazioni di d'alembert: una per il campo elettrico e una per il campo magnetico).
Sono tutte equazioni delle onde; hanno tutte la stessa velocità di propagazione.![[Pasted image 20220404144556.png]] (ricordando che $\mu_0\varepsilon_0 = \frac 1 {c^2}$ e che $c\ \dot = \ 299'792'458 \frac m s$).

Ora, sottolineiamo (importante):
_QUESTE TRE_:
![[Pasted image 20220404144556.png]]
__NON SONO LE EQUAZIONI DELLE ONDE ELETTROMAGNETICHE!__ vedendo solo queste, sembra infatti che campo E e B siano effettivamente indipendenti. Queste sono solo robe nascoste dentro le equazioni di EM, ma NON SONO LE EQUAZIONI DELLE ONDE!
Quindi, _quali sono le equazioni delle onde elettromagnetiche?_ => la risposta giusta sono __LE equazioni di maxwell punto.__. Le tre robe sopra sono solamente _contenute_ lì in mezzo.

Quindi, riguardiamo le equazioni di Maxwell dicendo che _contengono le equazioni di d'alembert_. Contengono le equazioni delle onde, sono una roba lineare e omogenea nella coppia di campo magnetico. => Le soljuzioni saranno funzioni che mi danno sia campo E e B come dipendenti dallo spazio e dal tempo, ma ricordo che devo _sempre lavorare sulla coppia (E, B)_.
![[Pasted image 20220404145018.png]]

##### Andiamo a vedere un esempio di onda EM
La cosa più facile da fare è lavorare con le [[../Note/Onde armoniche piane]].
Quindi, io prendo un onda armonica di questo genere:
![[Pasted image 20220404145230.png]]
Campo elettrico = \vec E_0 moltiplicato per un fasore (quando andrò a cercare il valore fisico di questa roba dovrò prendere solo la parte reale); poi vado a prendere un campo magnetico e _lo stesso_ fasore. 
Questa qui, è un onda piana che è in moto nella direzione individuata dal vettore d'onda $+ \vec k$.
Quando è che queste due soddisfano le equazioni di Maxwell?

Partiamo ragionando prima su come sono le derivate di queste due espressioni:
![[Pasted image 20220404145408.png]]
=> Le derivate rispetto al tempo diventano una moltiplicazione per $-i\omega$. Nota: il fatto che qua ci sia un segno ($-$), deriva dalla direzione del tempo. Quando abbiamo studiato originalmente i fasori, lì sopra compariva un segno (+), ora c'è il meno perchè prendo fasore con un (-) a esponente.

Vediamo ora il rotore/divergenza/gradiente di queste robe:
![[Pasted image 20220404145548.png]]
Facendo i calcoli, osserviamo che l'operatore divergenza diventa uguale a "prodotto scalare per i \vec k".
Di conseguenza (lol), vale:
![[Pasted image 20220404145849.png]]
(dove le ultime due cose a destra si dimostrano lungo le linee di questa dimostrazione).

Riscriviamo le equazioni di maxwell e mettiamoci dentro le relazioni appena trovate:
![[Pasted image 20220404150040.png]]
(sostituisco mu0 epsilon0 con 1/c)
Sostituendo le relazioni vettoriali si trova:
![[Pasted image 20220404150101.png]]
^^ Il campo magnetico ed elettrico della mia onda piana, _non possono essere indipendenti_: devono soddisfare queste quattro (equivalenti a Equazioni di Maxwell) equazioni.

In particolare, queste relazioni col vettore d'onda \vec k, ci fanno dedurre che:
![[Pasted image 20220404150252.png]]
=> E e B sono perpendicolari alla direzione di propagazione dell'onda. => Le onde EM sono _trasversali_.
In più, trovo anche che $\vec B \perp \vec E$ :
![[Pasted image 20220404150405.png]]
(questo si ricava dalla (4), invertendo l'ordine e usando prop anticommutativa di p vett.; moltiplico e divido per modulo di k  => Posso semplificare questa espressione per velocità
). La (2), mi da la stessa cosa.
=> \vec B è perpendicolare sia a k che E.

Tutto questo si riassume dicendo che:
![[Pasted image 20220404150721.png]]
(Importante l'ordine!; E_0, B_0 sono campi E e B quando la fase è allo zero).

Quindi, per tutta l'onda, si ottiene che \vec E e \vec B sono sempre collegati (anche in modulo):
![[Pasted image 20220404150825.png]]

Qui ci sarebbe l'esempio che non ho seguito:
![[Pasted image 20220404151133.png]]

##### Onde nei mezzi ottici
Se ho a che fare con mezzi in cui non ci sono correnti, vado a prendere le Equazioni di Maxwell espresse in termini di H e  ?
Il risultato che si ottiene è:
![[Pasted image 20220404151435.png]]
(resta ancora la relazione lineare tra E ed H). Dove però sono nella materia, questa velocità v è 1/\sqrt{\mu\varepsilon}.
Si scopre che v\mu è una roba interessante. La si definisce come quantità Z:
![[Pasted image 20220404151531.png]]
Questa quantità ha tutte le proprietà di una impedenza.

### Bilancio energetico
Ora, nascosta nelle equazioni di maxwell, c'è anche la _non conservazione dell'energia elettromagnetica_.

Questa è l'equazione di bilancio energetico
![[Pasted image 20220404153239.png]]
(espressa con H):
![[Pasted image 20220404153250.png]]

![[Pasted image 20220404153326.png]]
Nel vuoto, la conservazione dell'energia elettromagnetica in forma locale è data da:
![[Pasted image 20220404153441.png]]
Quindi, questo termine qua,_ se non ci sono correnti_, mi descrive una conservazione dell'energia elettromagnetica.

In forma macroscopica, integro lungo tutto il volume:
![[Pasted image 20220404153543.png]]

Ora, di questa energia io vado a studiare la mia derivata. => Perché la mia energia varia? Varia perché qualcuno sta spostando la mia densità di carica.

S mi rappresenta una sorta di densità di corrente. Ceh non è una roba che sta trasportando una carica, ma è una cosa che mi trasporta energia elettromagnetica
Se andiamo a vedere le dimensioni di S: 
![[Pasted image 20220404153553.png]]
Nel sistema internazionale, questo vettore di poynting si misura in $\frac W {m^2}$.

Ora, vediamo di applicare queste cose alle onde elettromagnetiche:
abbiamo visto prima quali sono i legami tra campo elettrico e magnetico:
![[Pasted image 20220404153916.png]]
Allora. La densità di energia em è fatta in due pezzi: una componente elettrica e una magnetica. In un circuiotp lc queste possono avere qualsiasi valore. Cosa succede nelle onde em?
Nelle onde em, queste sono collegate da una relazione data da v\mu:
![[Pasted image 20220404154025.png]]
=> Scopro che la densità di energia del campo elettrico è in relazione con la densità di energia del campo magnetico.

![[Pasted image 20220404154136.png]]
???
Possiamo scrivere quindi che la densità di energia EM è data da:
![[Pasted image 20220404154230.png]]
Per semplicitù usiamo quella in funzione di H.

Il vettore di poynting com'è fatto quindi:
![[Pasted image 20220404154320.png]]
 Se ho a che fare con un onda em, vale sempre \vec E \perp \vec B. Quindi, lavorando in modulo tolgopì il prodotto vettoriale (^^). Il risultato èche $|\vec S| = \frac {\ E^2} Z$.
 Riscrivo
    ![[Pasted image 20220404154441.png]]
    ![[Pasted image 20220404154456.png]]
Ora, sfruttiamo questa roba per definire l'ingensità delle onde em. Ricordiamo che l'intensità deve essere
1) Qualcosa legata all'energia
2) Qualcosa di puntuale (vale per un certo punto).

Quando abbiamo lavorato sulle onde sonore, le onde sonore viaggiano nello spazio => noi le abbiamo confinate all'interno di un tubo con sezione costante. QUando abbiuanmo dovuto definire qualcosa che mi dava l'intensità di un onda sonora, abbiamo sì considerato la potenza che ttraversava il mio tubo, e l'abbiamo divisa per l'area => l'abbiamo resa puntaule
![[Pasted image 20220404154832.png]]
La normale alla superficie è la blu, S è il vettore di Poynting.
![[Pasted image 20220404154906.png]]
Quindi io ho una densità di energia che ha lo stesso genere di periopdo.
Se io ho un onda periodica, quello cbhe mi succede qua è che ho una roba del tipo:
![[Pasted image 20220404154931.png]]
(è positiva quando l'energia cresce, negativa quando cala => sul periodo la media è nulla).
Un vettore che ha divergenza nulla è un vettore _solenoidale_. Qui non siamo _esattamente_ in quella condizione, ma ci siamo solamente se lavoriamo in media. QUesto vuol dire che io posso, associa
??????????????
Vediamo cosa sucede per un intervallino di tempo dt. 
![[Pasted image 20220404155212.png]]
Se questa altezza t è altezza dl, tutta la roba dentro esce.

QUindi ??????

![[Pasted image 20220404155335.png]]

Si definisce quindi:
![[Pasted image 20220404155426.png]]
Che è esattamente quello che abbiamo fatto per le onde sonore.
QUindi, da questo deriva che:
![[Pasted image 20220404155441.png]]
Se ho a che fare con un onda armonica, tutto mi si semplifica.

Il fattore 1/2 deriva dal cos^2 che nella media diventa \frac 1 2.

Confrontando l'intensità delle onde em con quella delle onde meccaniche:
![[Pasted image 20220404155834.png]]
per le onde meccaniche, \dot \xi era la velocità di un punto sulla corda, dato da (causa) Una forza. La potenza di questa forza che metteva in moto la corda, mediata nel tempo non era altro che l'intensità.
Per le onde em, c'è esattamente lo stesso concetto: l'intensità è la media del vettore di Poynting. Il modulo del vettore di Poynting è campo elettrico per h; il mio effetto è quindi H, causato da una variazione del campo elettrico.
Questa variazione è lineare, descritta da questo fattore Z (Impedenza). => Dobbiamo quindi iniziare a pensare che il campo elettrico per un onda EM è una sorta di "causa" e il campo magnetico è una sorta di "Effetto".


![[Pasted image 20220404160157.png]]
![[Pasted image 20220404160200.png]]
^^ Questa roba dipende da kz -wt => risolve l'equazione di d'alembert, con velocità w/k: 
![[Pasted image 20220404160221.png]]
Vettore di poynting, quindi, lo vado a scrivere anche questo come:
![[Pasted image 20220404160242.png]]
e osservo che anche questo dipende da kz - wt => anche questo risolverù una sua eq di d'alemnbert:
![[Pasted image 20220404160255.png]]

Quindi, quando parliamo di onde EM, parliamo di _onde di campo elettromagnetico_ e _non le possiamo separare_, ma parliamo nello stesso momento anche di un _onda di intensità di energia_ e _onda di vettore di poynting_.

