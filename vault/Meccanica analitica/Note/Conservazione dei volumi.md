#### `THM` COndizione di conservazione dei volumi sul flusso di fase
Preso un generico flusso di fase $\phi^t$, la condizione necessaria affinchè sia verificata la [[Flusso di fase#^f703dc|(3)]] si riduce a:
$$
\det
    \frac {\partial\ \phi^t} {\partial t}
= 1
$$
(ovvero, vogliamo che il determinante della [[../../Analisi 2/Calcolo differenziale/Matrice Jacobiana|Jacobiana]] del flusso di fase sia $1$).

`DIM` Questa condizione deriva direttamente dal [[../../Analisi 2/Calcolo integrale/Cambiamento di variabile|teorema del cambiamento di variabile]]:
$$
\int_{\phi^t(A)} d\mu = \int_A |\det J_{\phi^t}(\mu)|\ d\mu
$$
dove facciamo però l'ulteriore richiesta di _rimuovere il modulo_: infatti, _se il determinante fosse $-1$, avremmo ugualmente la conservazione delle aree, ma il nostro sistema cambierebbe la parità_. (...discorso su parità, sistema destrogiro e levogiro #deepen).

#### `THM` Condizione di conservazione dei volumi sul campo vettoriale
Dato $\phi^t$ [[Flusso di fase]] associato al campo vettoriale $\vec a(x)$, questo _conserva i volumi_ $\iff$
$$
\nabla \cdot \vec a = 0
$$
Ovvero, se la sua [[divergenza]] è nulla in ogni punto di definizione di $\vec a$.

`DIM` La dimostrazione sfrutta una serie di lemmi. ( #deepen #todo appunti 15/16).