
(...)

### Sistemi di EDO òineari del primo ordine.
Parentesi su EDO lineari al primo ordine.
È imporatnte sapere come si risolve un sistema di EDO lineare, visto che è uno dei sistemi che noi sappiamo risolvere meglio ed in modo più completo.

La matematica legata ai sistemi lioneari è molto importante  e molto legata alla fisica. La cosa importante è saper trattare queste equazioni.

Un sistema di EDO lineare è un sistema in cui la derivata di x è uguale ad Ax con A matrice:
![[Pasted image 20220223142722.png]]
Se A è costante, il sistema si risolve. Procede così_:
si cercanom soluzioni con il vettore costante ed un esponenziale con il parametro lambda (che sarà legato agli autovalori della matrice.)

Quindi, noi cerchiamo una soluzione di questa forma qui:
![[Pasted image 20220223142816.png]]
Per risolvere prendiamo questa x(t) e la andiamo a pluggare nell'EDO sopra. Con questo ci trovianom davanti ad un problema in cui dobbiamo risolvere un calcolo di [[autovalori]] e [[åutovettori]]:
![[Pasted image 20220223142908.png]]
lambda è detto spettro di A.
Questo problema lineare, quindu, si riducee alla fine in un problema non lineare. Anche se questo approccio può sembrare facile, abbiamo questo problema che può essere _non facile_. Cosa ci dicono questi autovalori lambda? Da un punto di vista dinamico, ci dicono che la soluzione avviene attraverso un esponenziale => lambda deve avere dimensioni fisiche specifiche, visto che in e^lambdat, lambda\*t deve essere adimensjonale. => Lamnda ha le dimensjoni di un tempo alla -1.
Questi lambad, quindi, sono i "tempi caratteristici delle evoluzioni" >= quanso abbiamo lambda piccoli, i tempi di evoluziini saranno molto lunghi (ordine 1/lambda) e viceversa.

In generale le matrici sono sempore diagonalizzabili (quelle che troviamo).

Inoltre, l'esponenziale è una funzione che ha un cormpportamento molto specifico: se prendo l'exp di un numero reale, se questo è positivo e^x crescerà molto rapidamente, se x è negativo, scendeeòà molto rapidamente. => gli autovalori diqueta matrice, possono essere complessi, se hanno parte reale positiva o negativa, possono succedere diverse cose:
Rex positiva => funzione esploide, la mia sokuzione tende verso l'infinito.
Se Rex negativa => soluzione decresce esponenzialmente, tende a diventare verso l'origine e a diverntare zero. 

Zero, in realtà, è una soluzione pargicolare di questo sistema, che non posso considerare facilm,ente (x=0 è una saoluzione banale che considero a priori, visto che altrimenti non opotrei davvero annullare l'esponenziale).
In particolare, zero è una soluzione  in cui il sistema rimane sempre nel suo stato iniziale. È detto "pinto di equilibrio". Perchè è una soluzione particolare? Perchè da un certo punto di vista, una soluzuine di questo tipo (non banale) è una traiettoria, e ha la dimensione di una retta. Se prendo il punto fisso, la dimensione della soluzione è zero (abbiamo una degenerazione da una traiettoria di dimensione 1 ad una di dimensione zero). => 0 sono punti critici, che possono essere usati come punti chiave per capire come funzionano i sistemi dinamici.

Quindi, tolte le due soluzioni (verso infinitio e attratta dal punto zero), quali altre possibilità abbiamo per trovare soluzioni non di uesto tripo? se lambda è immaginario puro, allora l'esponenziale non cresce e non decresce

==> i sistemi lineari hanno 3 possibilirà: o divergonoall'inifinito, o vengono contratti a zero, o hanno un comporatmento periodico quando lo spettro è imamgnnario puro.

In realtà, visto che noi abbiamo richiesto che la dimensione conservi la misura, questa richiesta mette dei vincoli sullo spettro di questa matrice. => In tantissime situazioni fisiche, noi ci troveremo ad avere numeri immaginari puri.

Altra domanda che ci poniamo: le solzuioni che abbiamo trovato in questa soluzione esponenziale, sono tutte e sole? La risposta è Sì. Per teorieamd di (xx?), ogni soluzione che troviamo sarà una combinazione lineare delle altre soljzioni (??)

I coefficienti Clambda sono trovabili imponendo le condizioni iniziali. Per trovare i C, avremo un altro sistema lineare. I coefficienti Còlambda sono univocamente determinati dalla soluzione iniziale. Siccome noi abbiamo un teorema di esistenza e unicirà, siamo in grado di costruire tutte le possibili soluzioni della mia EDO lineare.

Questo oin realtà è un terorema più generale: data la mia EDO lineare, se io sono in grado di trovare una base di soluzioni, allora ho risolto completamente il problema.

=> risolvere compleatmente una EDO, richiede di riuscire a calcolare una baase di soluzioni tale che, combinate linearmente, riescano a rappresentare una qualcuniqeue soluzione del mio sistema.

Riassumendo:
![[Pasted image 20220223144406.png]]
Oss. Se la matrice è reale, anche se ho autocalori immaginari queste son osempre reali.


PEr un sistema lionere, qundi i punti fissi sono x=0. Per un sistema non lineare:
![[Pasted image 20220223144638.png]]
Devo annullare il camppo vettoriale, per torvare i punti fissi.

Problema: come rappresento il flusso di fase associato ad una EDO?
Se voglio capire alcune prorpietà puramente formali, non occorre per forzia diagonalizzare. Io posso rappresentare in modo formale quello che è il FDF associato ad una EDOç
![[Pasted image 20220223144904.png]]
dove si fa uso di [[Esponenziale di una matrice]].

L'ogge
Boh non ho capito un cazzo, però questo tipo di rappresentazione è molto adatto per mettere in luce quello che succede per sistemi lineari.

^^ Insomma, per calcolare esplicitamente devo sempre diagonalizzare. Se devo fare operazioni algebriche, posso usare la rappresentazione con l'esponenziale.

Tornando all'esempio del rotatore...
![[Pasted image 20220223145501.png]]
Se derivo, A= 
![[Pasted image 20220223145517.png]]
E questo lo posso riscrivcere come:
![[Pasted image 20220223145533.png]]
La matrice 0 1 -1 0 è utile perchè è corrispondente all'unitàò immaginaria per lo spazio delle matrici 2x2. Non si capisce una sega

---
Altri esempi di spazi delle fasi:
QUest è un rotatore:
![[Pasted image 20220223145759.png]]

Questo è un oscillatore armonico:
![[Pasted image 20220223145820.png]]

La differenza che salta fuori è che il rotatore muove il punto lungo dei cerchi. Un oscillatore armonico muove il punto lungo delle ellissi.

Ora è vero che un0ellissèè un cerchio deformato, però se metto roba in più inizio ad ottenrere roba strana. (se cambio freq di un rotatore lui fa poco di diverso. Se cambio w di oscillatore armonico lui inizia a fare roba strana).

^^ questi due fdf sono esempi da ricordare a memoria. Anche qui si possono verificare le proprietà che questo sia un flusso di fase.

Quelle due amtrii però hanno una cosa in comune che balza all'occhio: Il loro determinante è 1. CHe siginidicato geometrico ha il determinante di una matrice. Il determinante ha il significato geometrico dell'area dei vettori che ne formano le (??). Questo vuol dire che queste due matrici, ENTRAMBE CONSERVANO L'area. Questo è consistente con la richiesta [[Sistema dinamico#^7adb31]]
L'esempio dell'oscillatore armonico è un esempio fisico, anche se in reealtà le forze di per se sono locali (la forza elastica, così per come l'abbiamo definita, non è una vera forza fisica).

Se hou n sistema non lineare, cosa succede? Si può dimostrare un teroema:
"se io prendo una trasformazione dallo spazio R2 a R2, quella che  è una trasf che rappresenta un flusso di fase (da S sdf a S sdf), se voglio che questa trasf conservi i volumi, devo calcolare determinante del jacobiano della trasformazione, se questp è uguale a 1 allora conserva i volumi".

Il fatto che il determinante sia uno, ha una conseguemza immediata sullo spettro, visto che sappiamo che il determinante è il prodotto dei due autovalori => Questo implica che se lambda1 è autoval, 1/lambda1 è autovalore. Questo è interessante perchè se ho due autovalori reali, questo implica che i due saranno uno più grande e uno meno grande di uno => secondo un atuoverttore la matrice espande, sencondo l'altero la matrice contrae.
Se siamo nei complessi, la possibilità è che questi due numeri siano sul cerchio unitario dei numeri complessi => la mia dinamica sarà una frequenza rotazione con frequeza omega.
Ma come faccio a capire qual è la conseguenza della conservazione ellle aree a livello di campo vettoriale? Per il campo vettoriale (che è appunto quello che io calcolerei derivando il fdf nel tempo zero)
La conseguenza è data da:
![[Pasted image 20220223151659.png]]
QUi io devo calcolare
Io so che il flusoo di fase è legato a cambpp obettoreiale quando faccio la sua derivata in t=0. Quello che io vado a calcollare adeso è la derivata daftta rispetto al tempo nel tempo uguale a zero nel temèpo del determinante di questa matrice, che so essere uguale ad 1 = costante. => il primo risultato deve essere uguale a zero. Però. io voglio farlo in modo formale, perchè voglio capire la relazione che c'è tra questa cosa qui ?? 
??
Quindi io devo calcolare esplicitamente il detreminnatnte per capire come la condizione che det=1 si riflette sulla matrice A, e lo faccio calcolando la dertivat in t=0. QUesta tecnica (la useremo spesso), è legata alle priopriartà di gruppo del fdf:: per deetreminare le proprietà di un gruppo, basta andare a vedere cosa succede all'identità di gruppo in un punto particolare. QUestperchè la struttura di gruppo mi permette di spostare le prorpietà di un punto del grupp a tutti gli altri. Qursta tecnica si può applicare quando avremo a che fare con dei gruppio. => Possiamo dimostraere che calcolando una osa localmente per l'identità genera iuna cosa che vale per tutto il grupoiò.
Se t è piccolo e io calcolo l'exp della matrice, lo posso espandere in tayor.
Dovrei calcolare il determinante di questa roba, ma è complicatisisimo => vado a calcolare il determinante di solamnete i temrini del temrine con la potenza più  bassa di t. this is because all terms with greater T power are (??)

Se ho una matrice con identità (??) the onluy terms that enter as determinant are the trace of A

The only way of creating a linear term is (=)

=> the det of the identity times T is ...

![[Pasted image 20220223152153.png]]

From this follows that id the determinant of e^At = 0, then the trace of A =0.

Qundi la corrispndenza sdta nel flusso di fase, nel caso lineare ad una matricce e questa matrice deve avere det = 1 perhè questa conservi le aree. Nel campo lineare ho un altra matrifce che ?? se il fdf conserva le aree, la traccia di questa matrice deve esssere nulla. Se la traccia è nulla io sono certo che il fdfd conserva le aree.

Quindi con l'equazione di newton io sono sicuro chge tutte le matrici che fanno robe hanno traccia =0 .

QUindi quando h oun EDO e mi doman ((?????))

DEF integrale primo del moto: 
Funzione regolare ad _un solo valore_ non dipendente dal tempo, definita nello spazio delle fasi. Nel nostro caso una H(p, t) senza dipendenza dal taempo.
Quest è necessario perchè l'integrale primo del moto risolve molti problemi perchè definisce una condizione geometrica. Se prendo la mia funzione H e la metto uguale ad una costante, questa mi divide lo spazio delle fasi in suoerfici di livello (ovvero divide lo sdf in tante superficii dove si incolla la traierttoria). Questo carattere geometrico che ha l'integrale primo del moto è ??

QUindi per cercare il mio ipdm, devo cercare una funzione di questo tipoL
![[Pasted image 20220223154712.png]]

