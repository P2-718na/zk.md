### Derivazione della formula di Cauchy
_La fdc stabilisce che una funzione olomorfa ha infinite derivate, che possono essere espresse sencondo la formula ..._

Abbiamo una regione semoplicemente connessa aperta nel oiano connesso, con F(z) all'interno sempre olomorfa. Definiamo un controno arbitrario gamma

Se z non appartiene ad A, l'integrale è zero (fun. olomorfa)
Se z appartiene ad A, l'integrale non sarà zero perchè l'integranda smette di essere olomorfa. Sulla curva ancora tutto è ben definito, ma dentro le aree c'è questo punto singolare Z.
Noi però abbiamo visto che l'integrale chiuso di linea non dipende dalla curva. Se abbiamo z al centro, otterremo sempre lo stesso risultato.
Scegliamo quindi una curva circolare attorno a z, di ragigio r:
![[Pasted image 20220225141711.png]]
![[Pasted image 20220225141720.png]]
^^ Con theta tra 0 e 2pi, im questo modo definiamo la curva attorno a zeta:
l'integrale si riscrive come:
![[Pasted image 20220225141933.png]]

![[Pasted image 20220225141952.png]]
L'integrale assume questa forma. Aggiungiamo e sottraiamo la stessa funzione f(z).
Poi, ricordiamo che f(z) è olomorga, e quindi anche continua. Di conseguenza, applicando la definizione di [[Limite di funzione a variabile complessa]]
(???)

Si ottiene la formula di Cauchy:
![[Pasted image 20220225142408.png]]

^^ Importante: tutta la dipendenza da z, sta nello z a denominatore sotto al segno di integrale.
Quindi, f'(z) è data da detivazione sotto al sengno di integrale. Faccio l'ipotesi che esista e abbia questa formula:
$$
f'(x) = \frac{1}{2\pi i}\int_\gamma \frac{f(z')\ dz'}{(z-z')^2}
$$
Ora dimostriamo che questa esiste davvero e ha questa forma:
Parto da definizione di rapporto incrementale [[Differenziabilità di funzione a variabile complessa]]:
![[Pasted image 20220225142645.png]]
Per calcolare questo, devo sostituire dappertutto la formula di cauchy:
$$
= -\frac{1}{2\pi i}\oint dz'\ f(z') \left[\frac{1}{(z + \Delta z - z')\Delta z} - \frac{1}{(z-z')\Delta z} - \frac{\Delta z}{(z - z')^2\cdot \Delta z}\right]
$$
Tolgo deltaz da denominatore e porto fuori. 
$$
= \frac{1}{2\pi i \Delta z}\ \oint 
$$
![[Pasted image 20220225143034.png]]
Faccio denominatore comne
$$
\frac{1}{2\pi i \Delta z}\oint \frac{dz' f(z)}{(z' - z - \Delta z)(z' - z)^2}\left[(z' - z)^2 - (z' - z)(z' - z - \Delta z) - \Delta z(z' - z - \Delta z) \right]
$$
Sviluppando la roba nelle quadre, restiamo solo con
![[Pasted image 20220225143914.png]]
Finiamo di svolgere l'integrale:

1/2piideltaz * deltaz^2 \oint ![[Pasted image 20220225143955.png]]

=> La nostra formula della derivata, in realtà, è corretta. In questo modo, ho dimostrato chje questa deri ata può essere espressa attraverso questa formula di Cauchy. (sappiano già che la derivata esiste, visto che la funzione è [[Olomorfa]]).

Ricapitolando:
f(z) = ![[Pasted image 20220225144119.png]]
f'(z) =![[Pasted image 20220225144142.png]]

Possiamo ora applicare di nuovo lo stesso teorema a f'(z), e ottenere una formula per:

f''(z) = ![[Pasted image 20220225144419.png]]


Questo significa che, _se una funzione è olomorfa, questa ha infinite derivate_.
 
COntinuando il processo, abbiamo:
$f^{(n)}(z) =$ ![[Pasted image 20220225144444.png]]

`OSS` questa dimostrazione che abbiamnmo appena fatto, in realtà si dovrebbe fare in modo rigoroso per induzione, (riguardo all'n! a numeratore).

### Teorema di Morera
In un certo senso, è un teorema inverso rispetto a quello di Cauchy. Supponiamo che noi abbiamo ancora una regione aperta connessa, e non necessariamente semplciemnte connessa (basta avere una regione connessa), e abbiamo una funzione f(z) continua
![[Pasted image 20220225144700.png]]
Se noi abbiamo una funzione continua, possiamo sempre calcolare l'integrael di contonrno, e troviamo che lungo qualsiasi curva di jordan, vale:
![[Pasted image 20220225144735.png]]
^^ se valgono queste condizioni, si dinomstra che la funzione è olomorfa.

`DIM` Consideriamo due punti P, Q e due curve: gamma1 e gamma2:
![[Pasted image 20220225144823.png]]
E calcoliamo l'integrale sul contorno chiuso:
![[Pasted image 20220225144906.png]]
Vogliamo dimostrale che la differenza dei due integrali di percorso è uguale a zero. QUesto significa che i due integrali sono sempre uguali.
Questo singnifica che l'integrale tra due punti sul campo complesso non dipende dal percorso, ma dipende solo dagli estremi (punto di partenza e punto di arrivo). (??)
Questo significa che possiamo introdurre una funzione nuova, F(z) (grazie al teroema di morera):
$$
F(z) = \int_{z_0}^z dz'\ f(z')
$$
(Dove z0 è una scelta arbi)trari. a
Ora vogliamo dimostrare che F(x) è olomorfa. Lo faccio cercando di dimostrare che questa funzione è una derivata di una funzione olomorfa. QUesto implicherà, per la formula di cauchy, che F e tutte le sue derivate saranno anch'esse olomorfe.

Facciamo Bene o male come abbiamo fatto prima.

1/\Delta z \left() 
![[Pasted image 20220225145233.png]]

= ![[Pasted image 20220225145330.png]]

Ma f(z') è una funzione continua, questo significa che questo integrale lo possiamo sostituire come:
$$ 
\frac{f(z*)\Delta z}{\Delta z} \to_{\Delta z \to 0} f(z)
$$

=> Questo implica che F ed f sono entrambe funzioni olomorfe.

### Serie di Taylor
Supponiamo di avere una funzione olomorfa, in una certa regione del piano complesso.
Prendiamo un punto z_0 e facciamo un cerchio (indicato con gamma) attorno. Consideriamo poi un punto arbitrario z, dentro a questo cerchio. Chiamiamo z' la variabile che descrive gamma.
![[Pasted image 20220225151235.png]]
Questo teorema ci dice che, in questo caso, posso scrivere:
![[Pasted image 20220225151227.png]]
A questo punto, aggiungo e sottraggo z_0 a denominatore:
![[Pasted image 20220225151254.png]]
Adesso facciamo:
![[Pasted image 20220225151346.png]]
Adesso guardiamo lìontervallo z' - z_0 e z - z_0 (rapporto sotto integrale. Si vede che il rapporto di z' - z0 è sempre maggiore (in modulo) del numeratore (basta guardare i raggi dei cerchi in figura):
![[Pasted image 20220225151439.png]]
Questo vuol dire che noi possiamo rappresentare quel rapporto a denominatore come progressione di una [[serie geometrica]] infinita:
![[Pasted image 20220225151523.png]]
che vale se |z| < 1.

Posso quindi riscrivere tutto l'integrale come:
![[Pasted image 20220225151652.png]]
=![[Pasted image 20220225151730.png]]
Visto che la funz è olomorfa, possiamo anche scambiare gli ordini di integrazione e della sommatoria:
=![[Pasted image 20220225151831.png]]
Ma questa è una serie di potenze (subito dopo sommatoria)
e quelli a destra sono una serie di coefficienti. => Possiamo quindi scricvere quello che abbiamo ottenuto cpome:
![[Pasted image 20220225151913.png]]
Dove gli an sono i coefficienti (integrali che prima erano a destra).
Esplicitamente, gli an sono:
![[Pasted image 20220225151951.png]]
E ricordando le formule di cauchy, vediamo che questa non è nient'altro che la derivata n-esima della mia funzione:
![[Pasted image 20220225152026.png]]
Questo significa che posso riscrivere la mia serie di potenze:
![[Pasted image 20220225152100.png]]
E questa è proprio una formula della serie di taylor.
In questo modo, abbiamo dimostrato che se una funzione è olomorfa, è anche analitica.
Per fare questo, abbiamo usato solo la formula della rappresentazione integrale di cauchy.

Possiamo anche dimostrare l'informazione inversa: _se una funzione è analitica, è anche olomorfa:_
supponiamo di avere questa funzione analitica:
![[Pasted image 20220225152221.png]]
Se questa funzione è analitica, possiamo applicare il teorema di Morera. Prendiamo un integrale a cazzo e lo calcoliamo esplicitamente:
![[Pasted image 20220225152324.png]]
Ma secondo il teorema di Cuchy, tutte le funzioni in sommatoria sono analitiche => il loro integrale è tutto zero. Da questo si ottiene che se la funzione è analitica, è anche olomorfa. applkicando il teorema di Morera.

Adesso possiamo introdurre:
### Serie di Laurent
Per funzioni che sono olomorfe in tutto lo spazio tranne al più un punto, possiamo farne una particolare rappresentazione in serie, diversa però dalla serie di taylor. Supponiamo di avere un certo punto z0 e supponiamo di avere due raggi:
![[Pasted image 20220225152821.png]]
r1 pi colo ed r2 più grande, ed in questa regione circolare (tra r1 ed r2.), abbiamo una funzione olomorfa. 
Noi vogliamo rappresentare questa f(z) come una serie. Come possiamo fare? 
Prendiamo un punto z che sta dentrop alla corona circolare, e facciamo un canale e poi un cerchio attorno a z:
![[Pasted image 20220225152945.png]]
E adesso dDiamo anche i nomi a tutte queste curve:
![[Pasted image 20220225153045.png]]
Se noi seguiamo tutto il percorso, a sinistra, secondo il teorema di jordan, abbiamoche sia z0 che z stanno al di fuori dell'area interna.
Questo significa che se noi prendiamo la somma di tutti gli integrali: (gamma piccolo ha il meno davanti perchè cambia il senso di rotazione):
![[Pasted image 20220225153326.png]]
Il rapporto:
![[Pasted image 20220225153333.png]]
Deve essere uguale a zero, secondo il Teorema di Cauchy.
Infatti, vediamo che gli integrali vanno a cancellarsi:
l1/l6, l4/l3
![[Pasted image 20220225153434.png]]
Rimango con:
![[Pasted image 20220225153502.png]]
Ma la cosa scritta con gamma tilde, secondo il teorema di Cauchy, è uguale a f(z) (questa gamma tilde circonda il punto z senza uscire dall'area di )?


Quindi, alla fine, f(z) varrà:
![[Pasted image 20220225153652.png]]
Questa è la formula che vogliamo usare per esprimere questa funzione f(z).
Adesso dobbiamo rappresentare questi due integrali come serie.

Cominciamo con il primo integrale su gamma grande. Iniziamo:
![[Pasted image 20220225153849.png]]
Osservo che ho la stessa struttura di prima:
z_0 - z' è una certa distanza, l'altra è l'altra. In questo modo, mi trovo sempre con un rapporto sempre minore di uno (in modulo). Uso ancora la serie geometrica:
![[Pasted image 20220225153954.png]]
l'esponente che non si legge è un n+1, a denominatore.

La differenza quindi starà nel secondo integrale:
![[Pasted image 20220225154051.png]]
La struttra è simile, ma la differenza delle distanze è opposta. Scriviamo, mettendo un meno davanti:

![[Pasted image 20220225154218.png]]
Il rapporto, qua, sarà semopre un complesso con il modulo di 1. Applichiamo ancora la serie geometrica. Avremo:
![[Pasted image 20220225154416.png]]
(ottenuto usando la formula per le serie geometriche).
Quesllo che succede qua ( a differenza di prima) è che sono scambiati numeratore e denumeratore. Riscrivendo ancora:
![[Pasted image 20220225154552.png]]
Ora vogliamo cambiarae un po' notazione, per avere questa parte simile a quella precedente, e avere un solo indice che includa tutte e due le serie. Introduciamo:
$n + 1 = -k \Leftrightarrow k = - (n + 1) \Leftrightarrow k = -n -1$
e riscriviamo la sommatoria come:
![[Pasted image 20220225154750.png]].
Ora possiamo rimettere assieme tutte e due le cose...
f(z) = 
![[Pasted image 20220225154943.png]]

La cosa importante è che la forma della prima serie e la forma della seconda coincidono. Ci sono due differenze:
la prima è che gli indici corrono in senso opposto.
La seconda differenza è che sopra abbiamo gamma e sotto gamma piccolo.
La cosa interessante è che negli integrali è sparito zeta, e resta solo z0. Rispoetto a z0, però, non ci sono differenze tra gamma piccolo e grande, visto che entrambi racchiudono z0. 
Quindi possiamo riscrivere tutto questo in forma seguente:
=![[Pasted image 20220225155202.png]]
Si può notare ancora che i coefficienti sono corrispondeenti alledderivate (?)

Come sono fatte queste serie? Qui possiamo introdurre:
suppiniamo di avere una serie fatta di questo tipo:
![[Pasted image 20220225155345.png]]
tale che:
![[Pasted image 20220225155353.png]]
Sono tutti uguali a zero.

Facciamo un esempio:
![[Pasted image 20220225155421.png]]
Abbiamo una singolarità isolata, chiamata "polo di ordine n".

### Teorema di Weierstrass
Se in un punto z0 ho una singolarità essenziale, allora
$$
\forall \epsilon > 0 \forall \delta > 0 \forall A \in \mathbb{C}, \exists z |<
|z - z0| < \delta => |f(z) - A| < \epsilon$$
