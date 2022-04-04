### Energia nelle onde armoniche

rivediamo il discorso fatto sulle [[../Note/Onde armoniche]], ma dal punto di vista dell'energia.
![[todo da lezione 8/Pasted image 20220308091315.png]]
CI troviamo nello stesso caso di ieri, ma stavolta al posto di avere un moto imposto, abbiamo una forzante periodica.
Prendiamo una foto della corda in un certo tempo. All'origine ci sarà una certa tensione. Tutti i punti della corda avranno una certa tensione.
Per studiare la dinamica del _primo punto della corda_, ho tutti gli elementi:
$$
\vec F_e + \vec T +\vec R_v = dm\cdot \vec a
$$
Lungo le componenti ho:
![[todo da lezione 8/Pasted image 20220308091658.png]]
Il primo pezzo della corda (?) lo metto a zero:
![[todo da lezione 8/Pasted image 20220308091942.png]]
(??)

Quindi, trascrurando per il momento la reazione vincolare, ciò che mi deteremina il moto della corda è la legge della dinamica lungo y:
![[todo da lezione 8/Pasted image 20220308092016.png]]
Dove, lavorando con le piccole oscillazioni, approssimiamo $\sin\theta$ a $\tan \theta$ (ci è comodo, funziona come nella dimostrazione di D'alembert, la tangente si può sostituire a quella roba.)
Questo risultato mi fa capire che la forza lungo y è sempre una quantità che dipende dalla corda.
![[todo da lezione 8/Pasted image 20220308092143.png]]
Come abbiamo visto ieri, visto che abbiamo solo una semicorda, qui abbiamo solo onde progressive
Ricordando due passaggi:
![[todo da lezione 8/Pasted image 20220308092335.png]]
andiamo a vedere... (?)
Per le onde progressive, non vale solamente de d'alembert (che è alle derivate seconde), ma vale anche solo un'equazione alle derivate prime:
![[todo da lezione 8/Pasted image 20220308092450.png]]
(Nell'equazione di D'alambert, per le sole onde regressive, è nascosta questa roba.).
Questo ha tutta un'altra interpretazione, perchè d\csi/dt non è altro che la velocità nel punto iniziale della corda. Posso quindi scrivere che la mia forza è proporzionale a:
![[todo da lezione 8/Pasted image 20220308092656.png]]
dove si ha![[todo da lezione 8/Pasted image 20220308092704.png]]
. In pratica, qui la mia forza è come se mi stesse generando una velocità.

Ora, se la relazione è lineare, il coefficiente T/v è definito:
![[todo da lezione 8/Pasted image 20220308092748.png]]
Da questa definizione segue:
![[todo da lezione 8/Pasted image 20220308092910.png]]
Ovvero: ![[todo da lezione 8/Pasted image 20220308092918.png]]

Facciamo una piccola osservazione:
![[todo da lezione 8/Pasted image 20220308092933.png]]
In una corda posso usare tensione e densità lineare. In realtà, facendo così, ottengo formule che sono valide solo e soltanto per le corde. Invece, concetti come la velocità di un'onda, sono definiti non solo per le corde, ma per qualsiasi tipo di onde. Stessa cosa per l'impedenza, che ha un risultato più generale.

- [ ] Questa roba (cosa?) la posso interpretare come se nella corda ci fosse una forza:![[todo da lezione 8/Pasted image 20220308093248.png]]
![[todo da lezione 8/Pasted image 20220308093319.png]]
Questa forza proporzionale alla velocità ha la stessa struttura di una corda viscosa. Quindi, posso iniziare a pensare che nel mio sistema è come se ci fosse una forza viscosa nel punto iniziale della corda. Questa _forza viscosa_ (termine $-Zv_c$) assorbe il lavoro introdotto dalla mia forzante nel sistema. 
![[todo da lezione 8/Pasted image 20220308093436.png]]
Dal punto di vista dell'anellino, questa forza dissipa energia. Vediamo come, in realtà, l'energia non viene dissipata.
La cosa da osservare è che, a differenza di quello che succedeva nell'[[Oscillazioni forzate semplici]] oscillatore armonico forzato, _forza velocità e forzante_ non risultavano in fase. Solo in condizioni di risonanza si verificava questa cosa.

Vediamo ora le cose dal punto di vista quantitativo:
![[todo da lezione 8/Pasted image 20220308093635.png]]
prendiamo solo le componenti lungo y. Differenzio in t:
![[todo da lezione 8/Pasted image 20220308093701.png]]
La y è la posiziome del mio punto y nel punro della mia corda, quindi posso sostituire con \csi. Ma d\csi/dt è la velocità del primo punto sulla corda. Quindi, 
![[todo da lezione 8/Pasted image 20220308093746.png]]
Ora, immaginando di essere _non_ sul primo punto, ma sul punto di fianco al primo. Questo secondo punto, più o meno avrà un d\csi/dx simile al primo, se è molto vicino. SI muoverà quindi in modo molto simile. Per il secondo punto, ciò che lo mette in moto non è la forza esterna, ma è ciò che fa il priomo punto. Detto in altri termini, questa relazione di potenza, che contiene solo e soltanto parametri dell'onda, è decisamente èiù generale (vale per qualsiasi punto lungo x):
![[todo da lezione 8/Pasted image 20220308093958.png]]

![[todo da lezione 8/Pasted image 20220308094123.png]]
Per le onde progressive osservo che le due robe sono di fatto termini al quadrato. Siamo sicuri che la potenza sia una roba positiva.
In questa formula, T/v l'abbiamo già incontrato. È la nostra definizione di impedenza.
![[todo da lezione 8/Pasted image 20220308094213.png]]

### Densità lineare di energia
![[todo da lezione 8/Pasted image 20220308094355.png]]
Consideriamo un tratto infinitesimo di corda dx, per cui dm = \mu dx.
Il tratto considerato è in moto con una certa velocità verticale (abbiamo già detto che non si sposta dalla sua x):
![[todo da lezione 8/Pasted image 20220308094437.png]]
Quindi, un tratto ingfinitesimo lungo dx avrà una sua energia cinetica infinitesima, dove:
![[todo da lezione 8/Pasted image 20220308094503.png]]
Possiamo quindi definire una _densità lineare di energia cinetica_:
![[todo da lezione 8/Pasted image 20220308094536.png]]
. Ho trovato un'energia cinetica. Avrò anche un'energia potenziale?
Prendo lo stesso disegno:
![[todo da lezione 8/Pasted image 20220308094355.png]]
Proviamo a capire dove va a finire l'energia potenziale. 
Un tratto di corda, quando arriva un onda, si allunga di:
![[todo da lezione 8/Pasted image 20220308094745.png]]
(visto che aumenta la sua y). Per fare questo allungamento, in qualche modo ho dovuto fare del lavoro contro la tensione della corda.
Quindi, c'è un lavoro che posso scrivere come:
![[todo da lezione 8/Pasted image 20220308094751.png]]
Questo lavoro lo posso riscricere raccofliend il dx dentro a radice:
![[todo da lezione 8/Pasted image 20220308094834.png]]
(anche qui ho sostituito dy con d\csi). 
Qui, sempre con il concetto di piccole perturbazioni: 
![[todo da lezione 8/Pasted image 20220308094931.png]]
(studio solamente il caso in cui siamo nelle piccole oscillazioni). Sviluppo quindi in taylor.
Possiamo quindi definire:
_Densità lineare di energia potenziale_
![[todo da lezione 8/Pasted image 20220308095054.png]]

Ricapitolando, sommando densità di energia potenziale e meccanica:
![[todo da lezione 8/Pasted image 20220308095141.png]]
Che forma ha questa roba?
![[todo da lezione 8/Pasted image 20220308095242.png]]
questo \frac 1 2 \mu^2  diventa:
![[todo da lezione 8/Pasted image 20220308095313.png]]
In pratica, questa catena di uguaglianze mi dice che istante per istante, la densità di energia cinetica in un punto è uguale alla densità di energia potenziale. _Non è come l'oscillatore armonico_.
Quindi, se la densità di energia cinetica è uguale a quella potenziale, la densità di energia ( che è la somma di questi due ) sarà uguale a:
![[todo da lezione 8/Pasted image 20220308095424.png]]

Legame tra energia e potenza:
![[todo da lezione 8/Pasted image 20220308095450.png]]
Se prendo la potenza scritta così e vado a sostituire, osservo che:
![[todo da lezione 8/Pasted image 20220308095516.png]]
Scopro quindi che in un sistema la potenza è proprzionale alla densità di energia meccanica:
![[todo da lezione 8/Pasted image 20220308095544.png]]
Questa formule è _generale_. È stata ricavata nel caso della corda ma è decisamente più generale.
_Potenza ed energia trasmessa sono proporzionali_.

##### Scambi di energia
![[todo da lezione 8/Pasted image 20220308091315.png]]
Parto da una situazione imperturbata di una corda tesa, l'energia immessa dalla forzante serve ad indurre un'onda nella corda.
Quando metto in moot il promo punto, in realtà sto mettendo in moto anche il secondo punto della corda. E poi il terzo, quarto....
Che ruolo ha quella forza viscosa che abbiamo visto prima? Essenzialmente è un modo per rappresentare che dal primo punto della corda io ho un canale di perdita dell'energia., visto che io a catena metto in moto tuti gli altri punti della corda.
Quel ruolo della forza proporzionale alla veocoità, sul primo punto di fatto è in canale di perdita di energia _sul primo puntio_, ma non fa perdere energia _al sistema_. Semplicemente, l'energia si trasferisce da punto in punto. L'energia mi serve per mettere in moto via via pezzi asempre più lontani della mia corda.
Quindi, questa forza proporzionale alla velocità diventa un modo di trasferire dell'energia da un punto a quello vicino. In pratica sto trasportando dell'energia da un punto iniziale a punti sempre più lontani.

Facciamo un esempio:
![[todo da lezione 8/Pasted image 20220308101404.png]]

Quando ho una sollecitazione di questo tipo, l'onda che si produce è del tipo (progressiva):
![[todo da lezione 8/Pasted image 20220308101437.png]]
![[todo da lezione 8/Pasted image 20220308101600.png]]
Quindi, la potenza è:
![[todo da lezione 8/Pasted image 20220308101619.png]]
![[todo da lezione 8/Pasted image 20220308101755.png]]
Mettendo tutte assieme le cose che mi interessano:
![[todo da lezione 8/Pasted image 20220308101813.png]]
in u_p, ho usato il fatto che v^2 = T/\mu.

`OSS` _tutte queste energie soddisfano l' [[../Note/Equazione di D'Alembert]]_.
Tutte le grandezze che abbiamo introdotto, infatti, sono funzioni di (x - vt).
![[todo da lezione 8/Pasted image 20220308102217.png]]
Queste grandezze fisiche (potenza, densità di energia) sono quantità scalari. 
Quindi, quando io ho un'onda su una corda, ho un'onda meccanica, ma anche un'onda di potenza e un'onda di densità di energia.

Vediamo l'andamento:
![[todo da lezione 8/Pasted image 20220308102401.png]]
Ogni singolo punto fa un moto oscillatorio $\pm A$. QUand'è che l'energia è zero?
(...)
ragioniamo sull'energia potenziale. Il minimo sarà nel punto in cui la corda non è allungata, e quindi _solamente nei picchi_. Viceversa, dove ho allungamento della corda, avrà eneergia potenziale.

Vediamo un'altro aspetto particolarmente importante:
##### Trasporto di energia e di potenza
Le onde meccaniche non trasportanpo massa, ma trasportano potenza e trasportano energia. _Perchè lo fanno?_
Prendiamo la nostra solita onda:
![[todo da lezione 8/Pasted image 20220308102904.png]]
E osservo che, se vado a prendere il valore medio dell'onda su un peirood, questo è essenzialmente zero:
![[todo da lezione 8/Pasted image 20220308102923.png]]
Se io vado a fare il valore medio della posizione, questo valore medio è sempre zero.
Se non è zero, è il valore imperturbato.

La potenza, invece, è molto diversa, perchè questa dipende da un coseno al quadrato (è sempre positiva):
![[todo da lezione 8/Pasted image 20220308103003.png]]
Quindi, quando io vado a fare la media della potenza, ho da mediare un cos^2 su un periodo, che vale 1/2.
È chiaro facendo un esempio con un onda impulsiva: prendo una corda, faccio un (1) mnoviumento impulsivo. Parte un impulso di energia- In quell'impulso c'è dell'energia che si sta trasferendo da un tratto della corda a quello vicino. Ogni punto in cui arriva un imoulso parte da una situazione statica, oscilla e trasferisce energia al punto dopo, dopo rutorna la situazione statica.
![[todo da lezione 8/Pasted image 20220308103330.png]]

Insomma, concettualmente, per capire cosa trapsorta un onda, _bisogna andare a vedere l'integralea medio su un periodo. Se viene zero, non trasporto nulla. Se viene diverso da 0, sto trasortatndo quella roba_.
Esempio: corrente alternata in una spina di casa. Cosa sto trasportando? Tensione, corrente o energia?
Il valore medio della tensione è zero. Il valore medio della corrente è zero. Il valore medio dell'energia non è zero => Sto trasportando energia.

_Quanrta_ energia stiamo trasmettendo? 
Consideriamo un punto qualunque della nostra corda, e calcoliamno mquanta potenza entra in _un_ punto della cord (in un'oscillazione completa).
(stiamno sempre lavorando con unìomdan armonica => abbiamo a fispostiizione il concetto di "periopdo").
Prendiamo la nostra equazione della potenza e la andiamo ad integrare...
![[todo da lezione 8/Pasted image 20220308103602.png]]
Per elaborare questa formula e capire cosa c'è sotto, faccio queste osservazioin:
l'impedenza è una tensione/velocità. _Moltiplkico e divido per una velocità_, in modo tale che..  Sostituisco in mood che mi esca \mu.
![[todo da lezione 8/Pasted image 20220308104007.png]]
![[todo da lezione 8/Pasted image 20220308103728.png]]
Poi abbiamo visto che vT = \lambda, quindi metto anche quello. \lambda \mu non è altro che la mia massa in una lambda della corda (densità lineare * lunghezza).
La formula che si ottiene alla fine. è esattamente la stessa formula dell' [[../Note/Energia dell'oscillatore armonico]].
