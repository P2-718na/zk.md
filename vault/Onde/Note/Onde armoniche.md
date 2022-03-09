### Onde armoniche
Le onde armoniche sono una categoria di onde. Hanno alcune proprietà molto semplici, e diventeranno un cavallo di battaglia.

Partiamo immaginandoci un sistema fisico molto molto semplice, dove c'è una _semicorda_ (corda che parte da un punto e va all'infinito.). Su questa corda continua a valere l'[[Equazione di D'Alembert|Equazione di D'Alembert]] per le onde.
![[../File/todo da lezione 7/Pasted image 20220307143042.png]]
La corda è vincolata da un anello: il suo estremo a $x=0$ può andare in su e giù, come tutti gli altri punti della corda. Visto che qui c'è un anello, possiamo pensare di metterlo in modo: se io lavoro con una corda imperturbata (= bella dritta), questa mi definisce il mio sistema di rivferimento (x lungo corda, y lungo vincolo). L'onda \xi = 0 è la soluzione _imperturbata_ dell' [[../Note/Equazione di D'Alembert]].
Movimentiamo un po' la situazione. Partiamo imponendo che il primo punto della semicorda faccia un moto deciso da noi. Il caso più semplice che possiamo studiare è quello di un moto di natura periodica:
![[../File/todo da lezione 7/Pasted image 20220307143245.png]]
(Prendiamo un seno, quello che facciamo per questo può essere esteso ad una generica funzione periodica tramite il teorema della [[Serie di Fourier]]).

![[../File/todo da lezione 7/Pasted image 20220307143450.png]]
Quando aumenta il tempo, dal punto iniziale è come se partissero delle corde che ad un certo punto si propagano sulla corda. Diciamo che _Il punto $x_0 = 0$ è una sorgente di onde progressive $\xi(x,\ t)= f(x - vt)$_. Queste onde saranno per forza progressive (visto che possono andare solo nel lato positivo delle x).
(osserva che la f sopra, vale anche se metto x=0):
![[../File/todo da lezione 7/Pasted image 20220307143756.png]]
Quello che succede nell'origine ad un certo tempo, è collegato con quello che succede in tutti i punti della corda diversi dall'origine.
![[../File/todo da lezione 7/Pasted image 20220307143937.png]]
Quello che succede all'origine nel punto a tempo t0 (f(x0 . vt0) ) succederà ugualmente in un punto diverso dall'oirigine in un tempo diverso (f(x - vt)).
Se eguaglio gli argomenti delle funzioni, ottengo che:
![[../File/todo da lezione 7/Pasted image 20220307144024.png]]
Questa relazione, la posso riscrivere risolvendo o per s o per t.
Cos'è x/v?
Se io ho una perturbazione nell'origine, quando sono in un punto di coordinata x, la distanza rappresenta la distanza dall'origine. x/v non è altro che _il tempo che una perturbazione ci mette ad andare dall'origine al tempo di coordinata x generico_.
Diventa quindi naturale che quello che succede nel tempo t0 all'orogine, arriverà anche in un tempo successivo in un punto generico x, che posso individuare in questo modo.
![[../File/todo da lezione 7/Pasted image 20220307144202.png]]
Quindi, la mia perturbazione nell'rogine (Asen(...)) la posso riscrivere come f(0 - vt0), dove al posto di t0 posso metterci t-x/v:
![[../File/todo da lezione 7/Pasted image 20220307144248.png]]
IN questo modo si verifica l'uguaglianza e la mia onda progressiva diventa:
![[../File/todo da lezione 7/Pasted image 20220307144314.png]]
sostituisco t0, sviluppo la parentesi (preferisco scrivere x - wt piuttosto che wt - x). 
Questa onda che sta viaggiando:
![[../File/todo da lezione 7/Pasted image 20220307144435.png]]
Definizco w/v come:
##### `DEF` Numero d'onda
![[../File/todo da lezione 7/Pasted image 20220307144458.png]]
E solitamente quest'onda si scrive come:
![[../File/todo da lezione 7/Pasted image 20220307144524.png]]
(nella k vado a metterci anche il segno (-) che non mi piace ).

Bene, onde del tipo
#### `DEF` Onda armonica
![[../File/todo da lezione 7/Pasted image 20220307144608.png]]
Funzioni solo del seno (oppure solo del coseno)
vengono chiamate onde armoniche.
Quelle con il (-) sono progressive, quelle col (+) sono regressive.
Anche questa roba può essere pensata come la parte reale di un [[Vettori rotanti (fasori)|faosre]]. Anche il fasore viene chiamato _Onda armonica_ (oppure, onde monocromatiche)
![[../File/todo da lezione 7/Pasted image 20220307144737.png]]
![[../File/todo da lezione 7/Pasted image 20220307144754.png]]

`OSS` Una somma di onde armoniche, non necessariamente è armonica (dipende dalle pulsazioni).