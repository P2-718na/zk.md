### Principio di minima azione relativistico
Il principio di minima azione va oltre quella che è la meccanica classica. 
Mentre l'equazione di Newton la sappiamo generalizzare alla meccanica relativistica, il principio di minima azione lo possiamo generalizzare alla meccanica relativistica.

Prendiamo l'assioma che "c è uguale in qualsiasi sistema di riferimento". Questo si può tradurre come formulazione matematica introducendo questa metrica:
![[Pasted image 20220510142332.png]]
Questa metrica funziona nello spaziotempo a 4 dimensioni di Minkowski.
![[Pasted image 20220510142347.png]]
(forma quadratica == metrica).


Esempio di altra metrica: metrica di Poincaré:
$$
dx^2 = \frac {dx^2 + dy^2}{y^2}
$$
Misura la densità d'[[../Note/Variabili azione-angolo|azione]].


Data una metrica, possiamo chiederci quali siano le trasformazioni nello spazio che la conservano. La risposta è che sono le trasformazioni ortogonali alla matrice metrica (per la metrica di Lorentz, esempio, sono le trasformazioni iperboliche).

Ora, se io voglio avere che il principio di minima azione continui a valere anche per questa metrica.
Assumo di poter cercare di scrivere un principio di minima azione dove:
$$
\delta \int_{t_a}^{t_b} \mathcal L\ dt = 0
$$
in realatività abbiamo il problema che $ct$ (quindi il tempo) è una coordianta come le altre, quindi ci aspettiamo che qualcosina sia diverso.

Come facciamo a capire cosa ci sta qua dentro?
Ricordiamo che la Lagrangiana dipende solamente dalla fisica del mio sistema.
Intanto partiamo togliendo le forze. Consideriamo un punto materiale.
Poi, sappiamo due cose (più o meno in modo implicito):
1) La lagrangiana ha la dimensione fisica specifica dell'energia.
![[Pasted image 20220510143554.png]]
2) Quando noi abbiamo scritto il principio di minima azione per la dinamica classica, noi abbiamo sempre detto che la Lagrangiana è uno scalare. Poi, sappiamo che nei sistemi di riferimento inerziali la lagrangiana è sempre T-V. Quando cambio sistema di riferimento, semplicemente devo cambiare le variabili, ma la funzione rimane sempre la stessa, _dato che è uno scalare_. Ora, questa roba funzionava in meccanica classica perchè _il tempo è assoluto_. Ora perl in meccanica relativistica questa roba non funziona più, visto che _il tempo non è più assolito_.
Di conseguenza,  nel mio integrale di azione deve essere uno scalare solamente la parte $\mathcal L dt$ (insomma quella parte di sicuro non cambia.
Quindi, abbiamo sostanzialmente due costanti fisiche. Abbiamo la richiesta che qeull'integrale sia uno scalare e abbiamo la richiesta che quello che sta dentro deve essere un energia per un tempo (= un azione).
Qual è l'unico scalare che noi conosciamo? => $ds$. Noi questo è l'unico scalare che riusciamo a costruire <= è l'unico affare che resta invariante per trasformazioni di Lorentz. Ora, però, questo ds ha le dimensioni di uno spazio. Intanto, scriviamo:

$$
\delta \int_{t_a}^{t_b} ds
$$
Ora, trasformiamo questo spazio ds in un azione. Per cambiare le dimensioni fisiche, devo combinare $m$ e $c$.
Ricordando che un energia è massa * velocità * lunghezza,
semplicemente moltiplico (a cazzo lol):
$$
m\cdot  c \int_{t_a}^{t_b} ds
$$
Quindi, ricapitolando, da una traduzione matematica del principio di Einstein che c è assoluta, mi salta fuori questa roba che è invariate per trasformazione di Lorentz.
Ora, l'ultima cosa che devo conteollare è che questa roba qua mi ridiventi lo stesso principio variazionale della meccanica classica. Questa correzione si fa molto ez mettendo un (meno) davanti:
$$
-m\cdot  c \int_{t_a}^{t_b} ds
$$
Per finire, applichiamo la definizione del nostro ds vista prima:
![[Pasted image 20220510142332.png]]
E quindi la nostra lagrangiana diventa:
#### Funzionale per il principio variazionale del moto relativistico
$$
-mc^2 \int_{t_a}^{t_b} \sqrt{1 - \left(\frac v c\right) ^2} dt
$$
Insomma, se sono in ambito relativistico, questa roba diventa la mia Lagrangiana ez. Applico le eq. di Eulero-Lagrange e da questa derivo ez le equazioni del moto di una particella relativistica.
![[Pasted image 20220510144553.png]]
In pratica, il cambiamento dalla meccanica classica alla meccanica relativistica, nel momento in cui assumiamo che il principio di minima azione debba rimanere lo stesso (+ le due assunzioni sopra), noi scriviamo essenzialmente l'unica cosa che può essere una lagrangiana e scriviamo le equazoini di eulero e abbiamo finito.

Aggiungo anche che la mia quantità di moto relativistica sarà (definizione rimane la stessa):
$$
\frac {\partial\ \mathcal L}{\partial\dot x} = p_x
$$

### Meccanica Hamiltoniana
Abbiamo visto che Lagrange scopre che la meccanica può essere formulata in maniera covariante e che questa covarianza della meccanica diventa poi geometrica. Hamilton fa di più: fa vedere che geometria e meccanica sono _la stessa cosa_.
Hamilton da una formulazione in cui sparisce il concetto di "da un lato c'è la dinamica e dall'altra la geometria": lui mette in luce le proprietà dei sistemi meccanici.
C'è un prezzo da pagare: la geometria dei sistemi meccanici non è la geometria euclidea ma la geometria simplettica.

Noi vedremo la formulazione Hamiltoniana e il perchè la formulazione Hamiltoniana è ciò che ci permette di passare in meccanica quantistica.
La quantizzazione parte dal formalismo Hamiltoniano.
Ora, qual è l'idea che guida Hamilton nella costruzione delle sue equazioni? L'idea di Hamilton è che gli da molto fastidio avere \partial \dot q.
Le equazioni del secondo ordine non sono adatte a rappresentare lo spazio delle fasi.
Quindi lui dice: come mai dobbiamo avere a che fare con un \dot q? Ceh ok è la derivata di q, ma noi la trattiamo come una coordinata indipendente.
Quindi, andiamo a riscrivere le equazioni del moto, ma usiamo il fatto che posso riscrivere \partial \cot q in funzione di p:
![[Pasted image 20220510145646.png]]
dopotutto, è conveniente usare i momenti, soprattutto quando ho delle determinate condizioni e coordinate cicliche...
C'è una piccola cosa tecnica:
I _momenti_ sono quantità _covartianti_, le velocità sono _controvarianti_.
![[Pasted image 20220510145732.png]]
(quando derivo uno scalare per delle cose controvarianti ottengo delle cose covarianti).
In realtà, Hamilton dal suo ragionamento partiva dall'idea che voleva geometrizzare completamente la meccanica, per renderla simile alla teoria della propagazione dei raggi luminosi. Lui voleva scrivere "l'equazione dei fronti d'onda" della meccanica.

Ora, ci ricordiamo che l'equazione di Newton era scritta però con i robi punto.
![[Pasted image 20220510145854.png]]
È sempre possibile scambiare le velocità e momenti? La risposta è s'ì, visto che i sistemi meccanici hanon sempre un impostazione lagrangiana. Se io faccio la derivata seconda della velocità rispetto alla lagrangaina, ottengo una matrice metrica:
![[Pasted image 20220510145949.png]]
E quindi, teorema della funzione implicita: queste robe qui sono sempre invertibililì. Questa matrice metrica è lo Jacobiano della roba che voglio invertire (dato che J != 0 questa roba è sempre invertibile).
Quindi, ok, questa roba è sempre invertibile.
A questo punto, una cosa che Hamilton conosceva era la [[Trasformata di Legendre]].
Ora, H è il risultato della trasf di legendre, la cui def è nella nota sulla trasf.
Ora, questa trasformata non è solo calcolare l'energia, ma va anche a sostituire dentro a questa energia le robe \dot con 
![[Pasted image 20220510150324.png]]
Insomma, la trasf di Legendre fa due cose: io devo prima calcolare l'enegia, e dopo nell'energia trasformare le cvelocità \dot q con io loro rispettivi momenti (funzioni di q, p, t).
Insomma, energia è una funzione di \dot q; la funzione di Legendre è una funzione H di q, p, t.
Ora, guardacaso ha lo stesso significato dell'energia, ma questa è una coincidenza.

Bene, ora il nostro problema è: come facciamo a tradurre le equqzioni di Newton del moto con equazioni scrittein queste variabili qua?
Ora, bisogna ragionarci un attimo. Io potrei sostituire a cazzo i momenti nella lagrangiana al posto delle veloctòàà, ma mi esce la mertda.-

Noi lo facciamo usando il cocnetto di differenziale:
![[Pasted image 20220510150549.png]]
Ora, parto tenendo a mente che H = H (q, p, t). => Quando calcolo i differenziali, le regole che mi vengono date dall'analisi, sono regole che posso (e devo) rispettare in questo step.
Andiamo a calcolare:
![[Pasted image 20220510150628.png]]![[Pasted image 20220510150727.png]]
Ricordando il differenziale di un prodotto.
Ora, qui compare ancora il differenziale di \dot q. Potrei già andare a sostituire il fatto che \dot q è funzione di q, p, t, ma per ora non mi serve fare questa roba.
Dopo aggiungo il differenziale della lagrangiana...
A questo punto, mi accofrdo che de L su de \dot q non è altro che p_k. L'altro affare è \dot p_k. Quindi sostituisco...
il dL/dq_k è \dot p_k per le equzioni di Eulero-Lagrange.
Ora, formalmente il differenziale di H è:
![[Pasted image 20220510151143.png]]
Mettendo tutto assieme ottengo queste equazioni molto belle:
![[Pasted image 20220510151201.png]]
^^ Queste equazioni sono le cose che Hamilton scopre.
Queste equazioni fanno capire come ci sia una simmetria tra coordinate e momenti associati. Il segno (-) viene ereditato dal fatto che F = -gradV (questo meno). Per il resto c'è una simmetria assoluta. 

Lo spazio naturale dove esistono queste equazioni è lo spazio delle fasi. Questo spazio ha come coordinate naturali le q e i momenti.

Queste equazioni portano alle estreme conseguenze le equazioni di Newton.

Ora, ultima equazione dell'eguaglianza tra queste due sopra:
![[Pasted image 20220510151559.png]]
(Le due derivate _sono diverse_, non sono le stesse cose).

Ora, H ha il significato di Energia meccanica, ma _non_ è solo l'energia.
Quindi H è una cosa ben diversa dall'energia, questo perchè H è una funzione che permette di ricostruire tutte le equazioni del moto. Un integrale primo energia, no.

Ora, il principio variazionale lo buttiamo via?
No: anche Hamilton dice: prima cosa, facciamo vedere che le nuove equazioni che lui ha scritto derivano anche loro da un principio variazionale. Andiamo a riformularlo in modo diverso:
Cosa fa Hamilton?
I principio relazionale della meccanica classica dice:
IO prendo la Lagrangiana, costurisco ik funzionale integranod la lagrangiana nel mio spazio, fissati gli estremi => io so che quando questp è stazionario ottengo le equazioin del moto di eulero-lagrange.-
Poi io so che nel pssaggio tra lagrangiana e Hamiltoniana ho fatto la trasformazine di Legendre. Quindi io posso scrivere:
![[Pasted image 20220510153001.png]]
Per cui a questo punto vado a sostituire dentro la lagranfgiana:
![[Pasted image 20220510153018.png]]
e quando questo è zero, dovrei trovare le equazioni di Hamilton.
Però c'è un problema:
chi è il dominio=
I funzionali, dopotutto, sono robe che dipendono dal loro dominio.
Ceh, \dot q intanto non esiste più. Poi, p, cosa fa?
Non lo posso lasciare libero a fare il cazzo che gli pare. Se su p non metto nessuna limitazione, è come se cambiassi completamente il dominio in cui p era fissato (seppur indirettamente). Se io ora lascio a p la libertà di fare quello che vuole, è come se cambiassi il dominio.
Quindi, riotterrò la stessa cosa se non tocco il dominio, o devo calcolare delle condizioni su p? Ovviamente io preferirei non mettere nessuna ulteriore condizione su p, visto che altrimenti devo fare calcoli in più. Bene, quello che scopre Hamilton è che io in realtà non devo mettrere alcuna condizione su p. Questo deriva dal fatto che a sua volta la trasformazione di Legendre è basata su condizioni di estremalità (non mostratre). => quindi questa cosa quoi funziona (non banale).
LO andiamo  a verificare usando la stessa dimostrazione dei principi variazionali:
![[Pasted image 20220510153404.png]]
faccio variare leggermente q di una funzione \delta q. Ricoprdo le mie condizioni di doninio, che queste variazione siano nulle agli estremi (fissati).
A questo punto, calcolo la viariazione di questo funzionale sviluppando in taylor quello che sta all'interno dell'integrale.
![[Pasted image 20220510153507.png]]
![[Pasted image 20220510153617.png]]
???
ma se questi due sono entrambi uguali a zero, ritrovo esasttamente le equazioni canoniche => le equazioni di Hamilton conservano la struttura che le lega ai principi variazionali...
![[Pasted image 20220510153842.png]]
A questo punto, puoi di nuovo ripartire col principio di azione ridotta... ?
In realtà NO. Anche Hamilton, si accorge che il principio che lui ha scritto non è lo stesso principio di minima azione della lagrangiana, visto che cambiando il domninio ab biamo trovato qualcosa di diverso.
Questo principio variazionale ha qualcosa di profondamente diverso rispetto al principio variazionale diminima azione dei sistemi lagrangiani.
Se io questa cos qui he mmi definisc eil fuznionale la esplicito,
faccio sparire completamente le derivate. Mi rimane che il mio principio variazionale, lo posso scrivere come 
![[Pasted image 20220510154012.png]]
pdq - Hdt.
Questa non è una funzione, ma è una Forma diffrerenziale.
Il ruolo che c'è tra p e dq è los tesso che c'è tra -H e dt.
Il tempo qui perde un po' il suo status di affare privilegiato.
La cosa più importante è che qui  in questa forma differenziale posso fare un tot di operazioni.
L'operazione (che noi non faccamo ma che si potrebbe fare è che: se io ho un principio variazionale e una roba di minima azione che conserva le equazioni del moto com3 principio di minima azione, una fvolta che interpreto questo principio come una forma differenziale, comne faccio a collegarci il concetto di rendere minimo un funzionale?
Questa roba richiede di passare ad una 2-forma differenziale.
Cioè questa roba la interpretiamo non più come un principiuo dinamico ma come un prinmcipio geometrico. Le equazioni del moto diventano le _curve di rotore_ di ?? bla bla
![[Pasted image 20220510154454.png]]

_?? Tarsforamazioni canoniche_
Nella geometria simplettica, le trasformazioni che lasciano invariata la struttura sono le trasformazioni canoniche.
Le definiamo all'interno dello spazio delle fasi, e hanno le seguente proprietà:
dato un qualunque sistema meccanico, le equazioni canoniche della dinamica sono invarianti in forma (nel senso che se io prendo le equazioni di hamilton, la trasformo riscrivendola nelle nuove variabili, e poi riapplico ad h la stessa forma che mi coistruisce le stesse robe canoniche, ??
![[Pasted image 20220510154817.png]]

### Parentesi di Poisson
Definizioni
Una parentesi di Poisson è un operazione algebrica fatta a un differenziale. È ina roba chje dice che se iop prendo due funzioni definite nello spazio delle fasi, la parentesi di Poissono di qeuste rpobe è definita così:
![[Pasted image 20220510155156.png]]
Ricorda un pochino quello che è un prodotto vettore ma vabbè.
Perchè ci interessa la parentesi di Poisson? Ci sono vari motivi. IL primo motivo è che la _la parentesi di poisson diventa il commutatore in meccanica quantistica_. Questa roba diventa il principio di indeterminazione nella meccanica quantistica.
Il perché boh però insomma succede questo.
Il significato dinamico di questa roba è ben preciso. Ok è un operatore simil prodotto scalare, però il fatto è che mette in luce il fatto che le equazioni canoniche di Hamilton si possono scrivere usando questa roba.
Vediamo alcune proprietà: per come è definito, questo è un _operatore di derivazione_.
Oltre ad avere la proprietà di essere [[bilineare]] e antisimmetrico

bla bla
??????

Noi diamo per scontato che le coordinate cartesiane siano canoniche per il piano cartesiano. Ma questa è una roba che in realtà non è banale. Se prendo un altro spazio, diverso da quello del piano cartesiano, queste coordinate non valgono più.
