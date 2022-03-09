Noi ci troviamo in una situazione in cui vogliamo risolvere una generale soluzione dalla formula (con una forzante arbitraria):
![[../File/todo da lezione 4/Pasted image 20220228141114.png]]
(vogliamo trovcare la formula per le soluzioni in forma più generale possibile).

Per farlo, dobbiamo capire quali sono le caratteristiche più generali di questa equazione.
Eq. differenziale => Cerco una funzione x(t) che risolva questa roba.

Questa equazione è _lineare e non omogenea_. La soluzione più generica (già visto), sarà quindi una somma tra soluzione dell'omogenea ed una soluzione particolare con questa forzante:
![[../File/todo da lezione 4/Pasted image 20220228141328.png]]
Osservo che le condizioni iniziali saranno sempre nell'omogenea, che quindi avrà certi parametri liberi dipendenti da esse.

Sulla parte dell'omogenea, vale il _principuo di sovrapposizione_: se x1, x2 sono soluzioni idverse generiche, allora una loro combinazione lineare con coeff. a e b arbitrari sarà soluzione dell'omogenea.
![[../File/todo da lezione 4/Pasted image 20220228141431.png]]

Proviamo ad introdurre un po' di terminologia:
un0equazioned i questo genere:
![[../File/todo da lezione 4/Pasted image 20220228141501.png]]
può essere riscritta in un linguaggio che contiene i "[[operatori funzionali]]".

[[../../Algebra/Note/Operatori funzionali]]

Questi operatori funzionali sono particolarmente utili perchè mi danno un modo di scrivere equazioni in modo sintetico. A noi interessano in modo particolare i cosiddetti [[../../Algebra/Note/Operatori lineari]]La domanda ora è: 
se so che tutte queste robe sono operatori lineari, la domanda è:
![[../File/todo da lezione 4/Pasted image 20220228142056.png]]
questa roba, è un operatore lineare? SÌ.
Vediamo ora quali sono le proprietà di questi operatori.

1) Caso di _equazione omogenea_, mi ritrovo in:
 ![[../File/todo da lezione 4/Pasted image 20220228142151.png]]
Vale che:
![[../File/todo da lezione 4/Pasted image 20220228142206.png]]
__Questo vale $\iff$ $\hat L$ è lineare__. Facendo un esempio:
![[../File/todo da lezione 4/Pasted image 20220228142306.png]]
Questa roba, in tante circostanze è chiamata _principio di sovrapposizione._
La ragione perchè il PS vale per altri campi (elettrico...) è la stessa per cui vale qua.

Ora, ci si può chiedere quante _combinazioni lineari indipendenti_ si possono fare. (Per esempio, ricordo uno dei problemi dell'oscillatore armonico smorzato in cui delta=0 da una sola soluzione). Vale che:
![[../File/todo da lezione 4/Pasted image 20220228142557.png]]
Per l'oscillatore armonico, quindi:
![[../File/todo da lezione 4/Pasted image 20220228142718.png]]
Le costanti sono arbitrarie. Per esempio, per il moto armonico smorzato, usiamo ampiezza e fase.
Quali sono le due condizioni iniziali? Basta che siano due condizioni indipendenti, che mi permettono di fissare univocamente la mia condizione. Per esempio
![[../File/todo da lezione 4/Pasted image 20220228142812.png]]
Una domanda tipo è: "se ti do due velocità in due istanti diversi, riesco a trovare una soluzione univoca, riesco a trovare una soluzione?" => La risposta è NO, perchè poi quando vado ad integrare una velocità per trovare una soluzione, mi rimane una costante arbitraria per trovare una soluzione.


### Caso b) equazione non omogenea
![[../File/todo da lezione 4/Pasted image 20220228143017.png]]
In questo caso, la mia soluzione è data da una somma di due pezzi:
![[../File/todo da lezione 4/Pasted image 20220228143031.png]]
Una che può non avere nessun parametro libero (soluz particolare),
l0altra quella omogenea. Si riesce a vedere che la somma di queste due è soluzione. La dimostrazione è abbastanza facile, una volta introdotta la notazione $\hat L$.
![[../File/todo da lezione 4/Pasted image 20220228143112.png]]
.
Altra cosa che mi interessa è se la soluzione per una forzante arbitraria passa per questo caso: supponiamo che il termin noto sia esprimibile come somma di due funzioni:
![[../File/todo da lezione 4/Pasted image 20220228143248.png]]Si può dimostrare che se uno mi da le due soluzioni per le due diverse forze:
![[../File/todo da lezione 4/Pasted image 20220228143318.png]]
Allora, la somma di queste due soluzini particolari è una soluzione dell'equazione di partenza.
"se ho un problema con una funzione somma di 10 pezzi, io risolvo tutti assieme e poii li sommo tra di loro".
NOTA:  dentro a x1 e x2, può esserci la soluzione dell'omogenea. Questa soluzione sarà sempre la stessa, quindi se me la trovo due volte e la sommo, alla fine finirà che una di queste due va via.
Altro esempio:
![[../File/todo da lezione 4/Pasted image 20220228143546.png]]
Problema con forza peso, forzante1 (coseno) e forzante2 (seno).
Dobbiamo scomporre il problema. Avremo questi diversi problemi da risolvere:
![[../File/todo da lezione 4/Pasted image 20220228143720.png]]
Prima, soluzione omogenea, poi soluzione (facile) a forzante costante (-mg)
poi abbiamo le due particolari:
![[../File/todo da lezione 4/Pasted image 20220228143744.png]].
Le soluzioni, assieme, andranno ad essere queste:
![[../File/todo da lezione 4/Pasted image 20220228143924.png]]
![[../File/todo da lezione 4/Pasted image 20220228144027.png]]
[[../../Algebra/Note/Operatori lineari#Esempi di op lineari]]

Per finire, vediamo qualche esempio:
![[../File/todo da lezione 4/Pasted image 20220228155541.png]]
La domanda che ci facciamo è: riusciamno a rapparesentare cos^2 di wt come serie di fourier? Sì, usando le [[Formule di bisezione]]:
![[../File/todo da lezione 4/Pasted image 20220228155649.png]]
Esempio2
![[../File/todo da lezione 4/Pasted image 20220228155724.png]]
Una funzione che va da + certa ampiezza  a - certa ampiezza in maniera oscillatoria. Problema tipo: trovare i coeff dello svlipuppo in serie di fourier.
![[../File/todo da lezione 4/Pasted image 20220228155810.png]]
La cosa figa da vedere è qua: https://www.desmos.com/calculator/1ocbzz5ink
![[../File/todo da lezione 4/Pasted image 20220228160042.png]]