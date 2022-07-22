#cleanme
--- Da lezione 16 onde
![[Pasted image 20220404141634.png]]

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



====
Da lezione di relatività
=====

### Equazioni di Maxwell
le EDO omogenee di Maxwell si scrivono:
![[../Relatività/File/todo da lezione 4/Pasted image 20220301122611.png]]
In assenza di cariche diventano:
![[../Relatività/File/todo da lezione 4/Pasted image 20220301122652.png]]
Queste equazioni verificano l'[[Equazione di D'Alembert]].
Ora, con questa roba avevamo un problema perchè l'eq di d'alembert non è invariante per trasformazioni galileiane:
![[../Relatività/File/todo da lezione 4/Pasted image 20220301122819.png]]
Ora, supponiamo di fare la stessa cosa, ma con le trasformazioni di Lorentz:

![[../Relatività/File/todo da lezione 4/Pasted image 20220301123045.png]]
Le derivate sopra e sotto sono calcolate rispetto alle trasformazioni (sotto, in grigio).
![[../Relatività/File/todo da lezione 4/Pasted image 20220301123224.png]]
![[../Relatività/File/todo da lezione 4/Pasted image 20220301123237.png]]
![[../Relatività/File/todo da lezione 4/Pasted image 20220301123348.png]]
La cosa figa delle eq di Maxwell è che hanno resistito perfettamente sia alla relatività che alla quantizzazione.

Quindi, le onde elettromgnetiche che soddisfano l'eq di d'alembert, se cambuano sistemi di riferimento con trasgft. di Lorentz sono perfettamente invarianti.
