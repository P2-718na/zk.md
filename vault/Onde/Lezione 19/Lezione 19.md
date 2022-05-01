### Onde EM nei dielettrici
Le onde EM nei dielettrici sono regolate dalle equazioni di Maxwell nella materia (in assenza di cariche):
![[Pasted image 20220501224909.png]]
Rispetto a quello che erano le equazioni di Maxwell nel vuoto, osservo che cambia il \mu_0 in \mu e il \varepsilon_0 in \varepsilon

La soluzione di queste equazioni saranno ancora una volta le onde elettromagnetiche, con la differenza di questi due coefficienti costanti. Le caratteristiche delle onde in questo particolare mezzo sono la loro velocità, data da:
![[Pasted image 20220501225037.png]]
(dove cambia c, visto che non siamo nel vuoto).
Per molti mezzi trasparenti, la permeabilità elettrica e magnetica relativa è circa 1. Per altri mezzi, tipo l'acqua, osservo che le cose cambiano:
![[Pasted image 20220501225243.png]]
Ora però ho un problema. Se sperimentalmente vado a misurare la velocità della luce nell'acqua, osservo che la velocità è diversa da quello che mi aspetto (vale cirda \frac 3 4 c, MOLTO DIVERSA!) Come mai? 

Intanto, definiamo 
##### Indice di rifrazione nel mezzo
![[Pasted image 20220501225345.png]]
Sempre > di 1, visto che la velocità della luce nel vuoto è sempre maggiore.

E osserviamo che:
La dipendenza con l'_impedenza_ vale (per definizione):
![[Pasted image 20220501225639.png]]
(Questa particolare relazione tra impedenza e n, vale solo per le onde em).

Per rispondere alla nostra domanda, dobbiamo ragionare sul modello del nostro dielettrico. Purtroppo, quando si studiano le costanti dielettriche, le costantielettriche relative dell'acqua, vengono tutti presi in condizioni di campo elettrico costante, che induce una polarizzazione costante.
Ora, è chiaro che per un onda EM il campo elettrico non è costante => la polarizzazione non è costante. In più, un onda luminosa visibile ha frequenze molto alte, quindi la polarizzazione cambia molto fast.
Prendiamo un modello di dielettrico (condensatore che fa robe):
![[Pasted image 20220501225851.png]]
Data una certa ddp di potenziale tra le armature, posso calcolare il mio campo elettrico nel vuoto tra le armature, e posso calcolare il campo elettrico nel dielettrico conoscendo la costante dielettrica.

Dentro al dielettrico, ho un campo elettrico di Polarizzazione, che tende ad allineare le molecole polari. Se non ho molecole polari, la nuvola di elettroni viene attirata da una certa parte e il nucleo (ccon arica opposta) viene tirato dalla parte opposta.
![[Pasted image 20220501230101.png]]
![[Pasted image 20220501230105.png]]
Interpreto gli spostamenti degli atomi come piccole perturbazioni => esprimibili come una forza elastica (lineare).

Ora, cosa succede in presenza di un campo elettrico variabile? 
Un campo EM variabile implica che nel nostro modello la ddp tra le armature cambia e diventa una roba di questo tipo:
![[Pasted image 20220501230625.png]]
Un oscillazione armonica del potenziale diventa un oscillazione armonica del campo elettrico.

Ora, le mie molecole e atomi risentono ad un campo elettrico che non è più statico; ogni singola molecola ha una forzante esterna (campo elettrico), una forzante elastica che risponde alle accelerazioni
![[Pasted image 20220501230722.png]]
![[Pasted image 20220501230730.png]]
Introduco anche una forza viscosa (resistenza ??)
Quindi, il risultato che ho è che l'_equazione della dinamica di ogni singolo elettrone è data da_:
![[Pasted image 20220501230803.png]]
Forza di richiamo atomica + forza dissipativa viscosa + forza data dal campo elettrico esterno.

Riordinando e riscrivendo tutti i termini, ottengo:
![[Pasted image 20220501231752.png]]
Ora, bisogna fare attenzione ai segni. A volte si usa e^{-i\omega t}, a volte e^{i \omega t}. Questa scelta può essere che vada a cambiare un po' di segni.
Andiamo ora a risolvere questa equazione:
![[Pasted image 20220501231948.png]]
Sappiamo risolvere questa cosa:
[[?? aggiungi link]]
A noi interessa la soluzione stazionaria (tanto quella omogenea sappiamo che andrà a zero):
![[Pasted image 20220501232024.png]]
Stessa pulsazione, A è un numero complesso. Posizione e forzante non avranno la stessa fase, ma ci sarà una certa differenza di fase costante. L'ampiezza è una costante che vale:
![[Pasted image 20220501232110.png]]
Bene, questo è quello che succede quando le armature del mio condensatore hanno un potenziale che oscilla: ogni singolo elettrone si mette in moto seguendo questa forzante esterna. Ma cosa succede dal punto di vista macroscopico?
Nel macroscopico, io ho ogni singolo atomo che mi costituisce un dipolo atomico:
![[Pasted image 20220501232203.png]]
L'insieme dei tanti dipoli mi da una polarizzazione macroscopica.
Il passaggio è fatto attraverso la densità dei dipoli. Macroscopicamente definiamo il vettore polarizzazione del dielettrico:
![[Pasted image 20220501232234.png]]
Ma siccome la polarizzazione è collegata al campo elettrico tramite:
![[Pasted image 20220501232249.png]]
Io di fatto ho la possibilità di riscrivere la polarizzazione come:
![[Pasted image 20220501232303.png]]
Dove ho usato il fatto che il campo polarizzazione vale (due foto sopra). Il fasore che compare qua è esattamente uguale a quello del campo elettrico calcolato prima (tre foto sopra). => Il risultato che ho è che \vec P è qualcosa proporzionale a \varepsilon_zero \xi_e => posso scrivere esattamente cos'è \xi_e rispetto a tutta l'altra roba:
![[Pasted image 20220501232417.png]]
La mia suscettività elettrica, quindi, in questo caso, _non è costante ma dipende da una pulsazione_. Se questa roba dipende da una pulsazione, anche la mia costante dielettrica si trasformerà in una roba che dipende dalla pulsazione. Quindi, siccome la pulsante dielettrica è collegata all'indice di rifrazione $n$, anche l'indice di rifrazione dipenderà dalla pulsazione:
![[Pasted image 20220501232512.png]]
Dove espando in taylor e ho un espressione dell'indice di rifrazione in termini di pulsazione.

Tornando indietro, la _differenza tra velocità della luce nell'acqua teorica e nella realtà_, è tutta data da questo termine qua che deriva dalla pulsazione.

Ora, ragioniamo un attimo su questo termine. Che forma ha e che cosa comporta ?

(Ricapitolando un ultima volta) siamo partiti da:
![[Pasted image 20220501232639.png]]
La scelta del + qua fa sì che si abbiano questi segni:
![[Pasted image 20220501232652.png]]
Per la scelta che abbiamo fatto, la parte immaginaria è negativa.
Separando n_r e n_i (parte reale e immaginaria dell'indice di rifrazione):
![[Pasted image 20220501232732.png]]
_Segue che:_
![[Pasted image 20220501232739.png]]
__Un dielettrico tipo l'acqua è un mezzo dispersivo per le onde EM!__

Ricapitolando le varie formule:
![[Pasted image 20220501232855.png]]
Osservo che anche il numero d'onda k è un numero complesso:
![[Pasted image 20220501232957.png]]
Ma cosa vuol dire avere un numero d'onda complesso? 
Avere un numero d'onda complesso vuol dire che quando ragiono in termini di onda armonica, questa avrà qualche caratteristica in più.

Ora, noi avevamo immaginato un campo elettrico che va su e giù per via di una differenza di potenziale. Ora, se immaginiamo che al posto delle mie armature ci sia un onda che viaggia parallelamente ad esse, mi trovo bene o male nella stessa situazione:
![[Pasted image 20220501233139.png]]
Avrò un campo elettrico (dato dall'onda EM) che vale:
![[Pasted image 20220501233151.png]]
Qui k è un numero complesso => quando lo vado a sostituire, devo considerare sia parte reale che complessa.
![[Pasted image 20220501233212.png]]
Ho quindi due termini: uno che è quello delle onde progressive che ho sempre visto, e un'altro che essenzialmente mi fa decadere esponenzialmente la mia ampiezza man mano che vado avanti lungo z.
Il risultato è che:
![[Pasted image 20220501233308.png]]
![[Pasted image 20220501233350.png]]

Ora, è più facile esprimere questa roba appena trovata in termini di intensità. Mostriamo quindi:
#### Legge di Lambert
![[Pasted image 20220501233443.png]]
Dove il coefficiente $2\beta$ viene spesso indicato con il coefficiente $\mu$ ed è chiamato 
##### `DEF` Coefficiente di assorbimento
![[Pasted image 20220501233525.png]]
L'intensità in funzione di una profondità vien chiamata Legge di Lambert:
![[Pasted image 20220501233545.png]]
(ricordiamo che questo $\mu$ è diverso da coeff magnetico assoluto).

Ora, sistemiamo altri due cocnetti:
##### Velocità di gruppo per dielettrici:
Noi avevamo definito velocità di gruppo:
![[Pasted image 20220501233800.png]]
Questa velocità di gruppo può quindi essere espressa come:
![[Pasted image 20220501233827.png]]
La velocità di fase è qualcosa in termini di indice di rifrazione.
Prendo i differenziali, li separo, divido e moltiplico per $d\omega$.
![[Pasted image 20220501234004.png]]
![[Pasted image 20220501234023.png]]
Quindi, sostituendo tutto:
![[Pasted image 20220501234041.png]]
Alla fine trovo un espressione per la mia velocità di gruppo che vale:
![[Pasted image 20220501234142.png]]
Il mio indice di rifrazione _aumenta all'aumentare di omega_. Il risultato quindi è che avrò due regioni diverse:
Una regione in cui la velocità di gruppo è minore della velocità di fase e una dov'è maggiore.
![[Pasted image 20220501234625.png]]
Fino a qua è tutta molta matematica. Per capire queste cose più in dettaglio, andiamo a vedere come effettivamente queste grandezze variano in funzione di \omega. (E in particolare, voglio vedere anche come la mia roba strana immaginaria varia.)

Prendo la mia parte immaginaria e reale dell'indice di rifrazione. Plottandole in funzione di w, ho questi valori qua:
![[Pasted image 20220501234733.png]]Toh ve questi due andamenti ricordano esattamente le robe di ampiezza elastica e assorbitiva. Sono esattamente i due andamenti di un oscillatore armonico forzato. 
Osservo nel grafico di sopra la distinzione tra le due regioni. 
Nella regione di dispersione anomala, la parte immaginaria dell'indice di rifrazione è alta => k immaginario grande => assorbimento => le onde cedono energia al mio mezzo, in questa regione. => Questa è la regione in cui il mio mezzo sarà meno trasparente.
Per questo motivo, la maggior parte dei mezzi ottici, nella regione della banda ottica si osserva una dispersione normale.

Ora, quello che abbiamo fatto vale per _un solo_ elettrone. Negli atomi/molecole ci sono più elettroni. Ogni elettrone avrà una sua frequenza di risonanza e una sua caratteristica dissipativa. Se io vado a fare le mie formule mettendo un mischione, quello che trovo ho una modifica del mio indice di rifrazione, dove la parte che dipende da gamma e dall'altra roba diventa una sommatoria su tanti elettroni ognuno con suoi parametri caratteristici:
![[Pasted image 20220501235106.png]]
Dal punto di vista dell'indice di rifrazione, una formula di questo genere vuol dire che io mi ritroverò una serie di picchi di assorbimento:
![[Pasted image 20220501235132.png]]
E un andamento un poco più complesso della parte reale dell'indice di rifrazione. (ho una regione anomala per ogni frequenza di risonanza).

Questo è quello che succede tipicamente nei mezzi.

Ora, succede una cosa interessante quando vado ad alte frequenze:
nel momento in cui vado ad alte frequenze (= sopra le frequenze di natura atomica, ovvero nella banda di raggi x e gamma), quello che mi succede è che il mio indice di rifrazione parte reale, visto che \omega >> \omega_0, 
![[Pasted image 20220501235306.png]]
Ottengo che il mio indice di rifrazione è sempre sistematicamente minore di 1.
=> Questo vuol dire che la mia velocità di fase è maggiore della velocità della luce.
![[Pasted image 20220501235400.png]]
![[amogus?.png]]
Però, se mi vado a calcolare la velocità di gruppo, qualcosa cambia. Infatti, dall'espressione su n_r trovo che:
![[Pasted image 20220501235442.png]]![[Pasted image 20220501235535.png]]
![[Pasted image 20220501235545.png]]
Quindi va bene sono contento perchè la mia velocità di gruppo (che è quella che mi _trasporta informazione_, si muove a velocità inferiore di quella della luce).