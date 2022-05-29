Seminari swag:
![[Pasted image 20220404111924.png]]

## Fenomeni ottici e relatività

### Collimazione relativistica
Fenomeno ben noto per chi fa ricerca con gli acceleratori circolari di particelle. Vediamo di cosa si tratta:
(Si possono trovare esercizi che descrivono fenomeni di questo tipo)

Immaginiamo di avere una sorgente di luce puntiforme che si trova in $O'$ e che emette fotoni in maniera isotropa (tutte le direzioni con simmetria sferica):
![[Pasted image 20220404112359.png]]
$O'$ è l'origine di un sistema di riferimento $S'$. $v = \beta c$ è la velocità della sorgente che si muove lungo l'asse x.
Prendiamo un fotone a caso. La sua direzione può essere indicata con l'angolo $\theta'$ (angolo formato con l'asse delle $x$ positive).

Possiamo definire un angolo:
![[Pasted image 20220404112518.png]]

E analogamente per $S$ definiamo $\theta_{\frac 1 2}$ .

(Questi due angoli saranno diversi, visto che il semicono in cui vengono emessi i fotoni dipenderà dalla velocità del sistema).
![[Pasted image 20220404112631.png]]
Visto che i fotoni sono emessi in cerchio, nel sistema di riferimento S' della sorgente, la distribuzione di questi fotoni è questa zona sferica (in grigio). $\theta'_{\frac 1 2}$ sarà l'angolo retto (metà di questa sfera). Andiamo a vedere come varia questo angolo nel sistema S.

Consideriamo intanto che se un fotone è emesso in $S'$ con angolo $\theta'$, noi possiamo considerare due componenti delle velocità del fotone:
![[Pasted image 20220404112816.png]]
e possiamo applicare le leggi di trasformazione di lorentz se vogliamo sapere cosa succede nel sistema S.
![[Pasted image 20220404112908.png]]
Le formule per le trasformazioni sono:
![[Pasted image 20220404112912.png]]
(ricordo che voglio trasformare da $S'$ a $S$).
^^ vado a sostituire $v_x'$ e $v_y'$ e ottengo la roba con i seni e coseni.

A questo punto, per definizione di coseno:
$\cos \theta\ \dot =\ \frac {v_x} c$
quindi, sostituendo nelle due formule:
![[Pasted image 20220404113048.png]]
Bene, ora possiamo sostituire in questa formula $\theta' = 90 ^\circ$ per trovare il mio $\cos \theta_\frac 1 2$ che stavo cercando. Si ricava:
![[Pasted image 20220404113152.png]]

Osservo che se la sorgente è ferma, theta1/2 = 90°, e man mano che la sorgente accelera l'angolo si restringe.

Questo angolo quindi tende a zero quando $\beta$ tende a 1.

Questo è chiamato `beaming effect`, "_effetto faro_".
![[Pasted image 20220404113327.png]]
^^ Questa figura mostra come varia l'angolo in funzione di $\beta$.
Quindi, questa sorgente noi la vediamo che si muove con una emissione dei suoi fotoni sempre più collimata nella sua direzione del moto.

Allora, cosa centra questo effetto con gli acceleratori circolari?
![[Pasted image 20220404113452.png]]
Dunque, gli acceleratori di particelle possono essere di vario genere. All'inizio, all'epoca di Rutheford, erano acceleratori lineari/elettrostatici.... Via via si sono poi evoluti. Dopo è arrivata l'idea dei campi elettrici alternati.
Adesso ci sono i _sincrotroni_ (guide magnetiche, alternate con cavità a radiofrequenza, dove vengono applicati campi elettrici ad una certa frequenza, per accelerare le particelle). In questo modo si possono raggiungere energie molto elevate. A questo punto si possono fare due cose: o si estrae la particella e la si manda a sbattere contro un bersagio, oppure si può ancora fare di meglio: si immagina che mella stessa pista magnetica si fanno girare particelle in un verso e edelle altre particelle in un altro verso, per poi farle scontrare. Questo è il principio dei collisori di particelle (LHC). Il vantaggio di un collider è quello di avere a dispositzione per le collisioni di partiecelle di un energia _molto maggiore_. In questo modo, nelle collisioni, per l'equivalenza massa/energia posso produrre _tante_ particelle.

Ora, il problema dei sincrotroni è che queste particelle emettono fotoni e perdono energia => si perde un po' di efficacia nel sistema.
Questo tipo di perdita di energia è proprio legato al fenomeno che abbiamo appena visto:
siccome io ho una particella accelerata, soggetta ad una forza centripeta; siccome questa è accelerata e perde energia si comporta proprio come una sorgente di fotoni. E questa emette fotoni, tanto più sarà veloce, in un cono sempre più stretto.
Quindi, in pratica, se noi abbiamo un orbita...
Supponiamo di avere un elettrone su quest'orbita. Questo elettrone è soggetto ad un accelerazione centripeta e quindi emette una radiazione:
![[Pasted image 20220404114113.png]]
Il fenomeno si chiama: magnetic bremmstralungh.

Per fare i calcoli, bisogna ragionare con l'approssimazione del sistema di riferimento comovente istantaneo. (vedi: [[??]])
![[Pasted image 20220404114226.png]]

Quindi avremo che i nostri fotoni avranno circa probabilità 1/2 di essere emessi lungo la velocità dell'elettrone con semiangolo di apertura dato da ... (vedi formule nella slide sopra).

La perdita di energia dell'elettrone può essere calcolata:
![[Pasted image 20220404114313.png]]
E viene fuori una certa formula (w = perdita di energia). La cosa interessanrte è che la perdita di energia per girp è proporzionale alla quarta potenza di quella rpoba tra parentesi:
![[Pasted image 20220404114340.png]]
Questa quarta potenza è molto rilevante. Se al posto dell'elettrone ci piazziamo un protone, se questa particella è più massiva dell'elettrone, vediamo che questa perdita di energia si riduce in maniera veramente significativa.

Si sta pensando di cercare di fare acceleratori con i muoni. È difficile, visto che il muone è instabile. La cosa interessante però sarebbe che, visto che il muone è più massivo dell'elettrone, sarebbe più facile accelerare questa particella.
Questo fenomeno si chiama anche _radiazione di sincrotrone_.

Per questo modo, si è potuto sostituire nello stesso anello:
![[Pasted image 20220404114606.png]]
è stato possibile ospitare nello stesso tubo dell'affare vecchio, l'affare nuovo (dove si fanno collidere però protoni). In questo modo, si è potuto arrivare ad una macchina con energia molto maggiore.
![[Pasted image 20220404114704.png]]

![[Pasted image 20220404115116.png]]
<3

##### Applicazione 
Andiamo a vedere che conseguenze ha questa roba in un acceleratore di particelle.
Una cosa che è successa da decenni, è che man mano che si aumenta l'energia a disposizione per produrre nuove particelle e studiare nuovi fenomeni, il parametro energia è stato quello più rilevante. Quando i fisici si sono messi a costruire acceleratori, l'idea era di farli con energia sempre maggiore.
![[Pasted image 20220404114914.png]]
^^ Abbiamo due particelle. p1 ha un certo impulso e una certa energia (vedi slide).

Le masse a riposo delle due particelle sono quelle del protone.

Ora, mettiamoci nel sistema dell'impulso zero (=centro di massa) delle due particelle ($S'$).
Questo sdr si muove con una certa velocità v in S. Qui le particelle avranno impulsi ed energie (vedi slide ^^).

Per definizione, inoltre, P' = 0 (visto che ci troviamo appunto nell'sdr a impulso nullo).

Ora, consideriamo due quantità molto interessanti (relativisticamente invarianti: $E^2 -cP^2$) (vedi slide vv)
![[Pasted image 20220404115328.png]]
![[Pasted image 20220404115341.png]]
Questo vuol dire che:
![[Pasted image 20220404115349.png]]
Vado a sostituire
![[Pasted image 20220404115357.png]]
Ora, sappiamo che questa quantità è zero:
![[Pasted image 20220404115409.png]]
p2 = 0 perchè in S la particella 2 è ferma.

Sostituendo, si ottiene che:
![[Pasted image 20220404115430.png]]
Dove ricordiamo che:
![[Pasted image 20220404115442.png]]
e ricordiamo che $E'$:
![[Pasted image 20220404115458.png]]
![[Pasted image 20220404115554.png]]
%% Sinceramente qua non sono stato a seguire tutti i calcoli che fa visto che è impossibile%%
Questa relazione (circondata in grigio) ci dice qual è la relazione tra l'energia del fascio nel sistema del laboratorio ed $E'$ (energia nel sistema del cdm delle particelle).

Ora, andiamo  a calcolare il rapporto k = \frac {E'} E :
![[Pasted image 20220404115809.png]]
per calcolare k andiamo a sostituire la formula sopra...
Ora, supponiamo di avere a disposizione un'energia di 10GeV. Sappiamo che l'energia a riposo del protone è circa uguale a 1GeV. Dunque, se noi applichiamo la definizione di k, otteniamo che questo rapporto k sarà uguale a 0.2 (20%) => questo vuol dire che nel sistema del laboratorio, se voglio sapere cosa devo avere di energia nel lab per avere 10GeV nel sistema del cdm, devo avere un'energia E:
![[Pasted image 20220404115952.png]]
Siccome so che l'energia nel laboratorio è (formula sotto ^^), (non si capisce un cazzo)
Per ottenere È nellnel sistem???
==> Per avere 10GeV a disposizione, devo avere un fascio di 50GeV che vanno a sbattere.

A questo punto però, se noi invece di estrarre il fascio per mandarlo contro un bersaglio, e invece prendiamo due fasci che si scontrano, abbiamo che l'energia necessaria si abbassa di molto:
![[Pasted image 20220404120120.png]]


### Trasformazione di una forza
![[Pasted image 20220404121857.png]]
Per forze relativistiche, bisogna considerare le trasformazioni dell'impulso.
La forza quindi sarà uguale a (roba in grigio):
![[Pasted image 20220404122002.png]]
Dove il "poichè risulta" non l'ha ricavato ma si ricava facendo un po' di calcoli.

Questa scrittura fa vedere chiaramente che la forza è quindi somma di due fattori: uno parallelo all'accelerazione e uno alla velocità => in questo contesto _non è scontato_ che forza e accelerazione abbiano la stessa direzione.
![[Pasted image 20220404122216.png]]
Siccome la forza non è proprio parallela all'accelerazione, qui osserviamo subito che_ non possiamo definire nessuna massa come rapporto tra forza e accelerazione_ => cade il concetto di inerzia così com'era noto prima di Einstein.
Ora, se io moltiplico la mia forza scalarmente per v/c (4 riga ^^), ottengo tutte quelle robe.
In particolare, visto che l' appare un termine v^2/c^2, sviluppando i calcoli si trova che quella roba è proporzionale a \gamma^3.
Sostituendo sopra, si ottengono (riga 6 ^^).

Ottengo quindi le due condizioni nel caso F sia parallela a velocità o ad accelerazione.

Quindi il risultato è F/\gamma^2.
Quindi, tutto ciò, per dire, la forza non è necessariamente parallela e diretta verso l'accelerazione, _Lo è in due casi: 
![[Pasted image 20220404122548.png]]_

Bene, questo è il motivo per cui, nella fisica relativistica, si usano soprattutto energie, masse e impulsi (la forza la si lascia perdere appunto perchè la trattazione della forza è abbastanza complicata).

Ora, facciamo un passo ulteriore ("non credo che lo utilizzeremo in nessuna applicazione a livello di esercizi di esame, spunto per l'orale")
_Come si trasformano le componenti della forza attrraverso sistemi di riferimento?_
![[Pasted image 20220404122706.png]]
Allora, supponiamo che il punto di applicazione della foprza varia da \vec r a \vec r + d \vec r.
Se uno sposta il punto di applicazione, viene compiuto del lavoro, che può essere chiamato \delta w. Questo \delta W se diviso per il tempo diventa una potenza.

Ora supponiamo di acere in S una particella di massa, velocità e impulso noti.
La definizione di forza ci dice che:
![[Pasted image 20220404122853.png]]
Ora, supponiamo di considerare un sistema di riferimento $S'$, con velocità e impulso $v'$ e $p'$.
![[Pasted image 20220404122921.png]]
Ora, nel sistema di riferimento S', noi possiamo sicuramente scrivere che la componente f primo della forza sarà
![[Pasted image 20220404122941.png]]
E allora, ricordiamo ancora le [[../Note/Trasformazioni di Lorentz]]:
In S' vale:
![[Pasted image 20220404123027.png]]
![[Pasted image 20220404123320.png]]
![[Pasted image 20220404123629.png]]

Ora, vediamo un applicazione della dinamica relativistica:
### Diffusione Compton
Questa ha fatto scalpore: ci troviamo un un punto della storia in cui si è capita la relatività, si è capito che l'energia è una quantità discreta, si è capito come avviene l'effetto fotoelettrico... Però, questi quanti di energia elettromagnetica, sono appunto trattati ancora come dei pezzetti di energia. In questo fenomeno, per la prima volta si mette in evidenza come il fotone in realtà fosse una particella. 
![[Pasted image 20220404123815.png]]
Per capire un po' di date.. 
nel (1900?) Planck formula la teoria che l'emissione della radiazione è una cosa che non succede in maniera continua ma attraverso quanti di energia. => Nel 1905 einstein spiega l'effetto fotoelettrico (luce in un metallo provoca il circolo di energia in un circuiti) => Una quindicina di anni dopo, Compton riesce a mettere in evidenza proprio come questi quanti di luce si comportino a tutti gli effetti come delle particelle. Noi adesso li chiamiamo fotoni  (si chiamano così dal 1926) (termine nato da "Lewis", uno scienziato completamente dimenticato)

(?? I raggi incidenti dopo la diffusione hanno perso parte della loro energia).
![[Pasted image 20220404124340.png]]
Ora, più la frequenza aumenta più la lunghezza d'onda diminuisce. Lo spettro del visibile è un piccolissimo intervallo, che corrisponde alla sensibilità del nostro occhio. 

Quindi, se parliamo di raggi X parliamo di onde Em e di un intervallo di frequenze intorno ai 10^18Hz, variabile secondo le definizioni. 

L'apparato di Compton era costituito da due parti: una parte dove produceva i fotoni e li mandava a sbattere contro al bersaglio. Un'altra parte di apparato selezionava i fotoni diffusi lungo un certo angolo e ne misurava la lunfghezza d'onda.
![[Pasted image 20220404124623.png]]
Descrizione dell'apparato:
a sinistra abbiamo un tubo a raggi x. Questo affare può emettere raggi x, e possono essere selezionati come monocromatici. => c'è un fascio di lunghezza d'onda ben preciso che viene inviato contro un bersaglio. Nel bersaglio si ha quindi il fenomeno della diffusione. Poi, uno può selezionare un angolo rispetto alla direzione del fascio, e lo fa usando una corazza di piombo con un solo foro.
Questo è detto angolo di diffusione \theta. Una volta selezionato l'angolo, si vede che tutti i vari fotoni vanno a finire in un apparato dove se ne misura la lunghezza d'onda.

Due parole su questo apparato:
si chiama spettrometro di bragg, ma il nome corretto sarebbe "spettrometro dei bragg", visto che erano in due (padre e figlio).
![[Pasted image 20220404124831.png]]
Questo affare sfrutta il fenomeno ottico della [[Diffrazione]] dei raggi x.

Ora, siccome la lunghezza d'onda (energia) dei raggi x è molto elevata, bisogna usare un oggetto microscopico per osservare un fenomeno di diffrazione dei raggi x. (??)

Allora, i piani paralleli alla superficie del cristallo, fungono come se fossero dei piani di riflessione per questi raggi x. E quindi, se qui arriva un raggio x, questo viene riflesso dal cristallo e ca a finire nella camera di ionizzazione. Questo robo è pieno di gas; il fotone interagendo con le molecole del gas produce delle cariche elettriche che per effetto del campo elettrico si muovono e danno origine ad un segnale elettrico.

Quello che succede (e che noi interessa) è che appunto parte questo segnale.

Bene, questo affare, se è posizionato bene, si avrà un segnale lì sotto solo per raggi x che hanno una certa lunghezza d'onda, seguendo la legge dei bragg:
![[Pasted image 20220404125145.png]]
(ricordiamo che $\alpha$ e $\theta$ sono due angoli non correlati tra loro.)

Questo vuol dire che io posso misurare la distribuzione di \lambda di questi raggi x che ho selezionato, variando \alpha.
C'è una sottigliezza che in realtà quello che si osserva è una figura di diffrazione, quindi le robe interessanti si vedono per il picco principale della figura (m^^ è uguale a 1).

![[Pasted image 20220404125318.png]]
Per generare raggi x,  usavano il molibdeno. Quando questo materiale è sollecitato, i suoi elettroni fanno un salto di energia, e per tornare poi allo stato fondamentale emettono dei fotoni di quella particoalre energia. => in questo modo abbiamo un raggio monocromatico.

Il risultato è questo:
- [ ] ![[Pasted image 20220404125436.png]]Noi abbiamo il numero di fotoni in relazione con l'angolo alpha.
In realtà questo alpha è in scala con la lunghezza d'onda del fotone che viene diffuso.

Si osserva quindi questa roba a vari valori di theta.
E quindi, la prima cosa che si osserva è che via via che il nostro \theta aumenta, sembra che questo esperimento riveli una figura a due picchi, che si spostano sempre di più via via che aumenta il valore dell'angolo \theta.

Allora, per interpretare queste cose dal punto di vista sperimentale, Compton fa questo ragionamento (trattando i fotoni come se fossero delle palline![[gabibbo.png]], uguali agli elettroni).

![[Pasted image 20220404125705.png]]
Ho il mio fotone che arriva lungo una certa direzione e va a sbattere contro il mio elettrone.

Dopo la collisione (come se fossero palline), compton immagina che succeda questo: l'elettrone rimbalza secondo una direzione e ilk fotone vengfa deviato dalla sua direzione iniziale proprio di quest'angolo di scattering.

Il fotone non conserva tutta l'energia, ma in parte se la porta via l'elettrone.
![[Pasted image 20220404125945.png]]

bla bla il risultato è che la sua visione teorica di quello che succede coincide con la visione sperimentale.