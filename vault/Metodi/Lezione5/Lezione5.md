Consideriamo il caso in cui abbiamo una funzione analitica olomorfa tale che f(z_0) = 0

Diciamo che una funzione f(z_0) è uno zero di ordine n se:
(rm)

![[Pasted image 20220228161959.png]]
Se noi abbiamo uno zero di ordine n nel punto z_0, questo singifica che lafunzione può essere rappresentata in questa forma.
![[Pasted image 20220228162022.png]]
Questa nozione degli zeri è molto importante. Per esempio, se abbiamo un'equazione del tipo
![[Pasted image 20220228162052.png]]
Gli zeri di questa equazione sono soluzioni

### Nozione del polo
Diciamo che una funzione ha nel punto z_0 un polo di ordine n se noi abbiamo:
![[Pasted image 20220228162141.png]]
Dove a-(n+1) = a - (n+2) = 0
In questo caso possiamo scrivere la nostra funzione come:
![[Pasted image 20220228162225.png]]
Dove 
![[Pasted image 20220228162233.png]]
h(z_0) è un punto regolare (ha valore finito).

Ora introduciamo un'altra cosa:
### Punto all'infinito
Quando noi consideriamo la retta reale, possiamo dire che se noi prendiamo punti su questa retta positivi molto grandi, tendiamo a +inf, molto piccoli => -inf.
Su R non raggiungiamo mai il punto +inf.
Nella teoria delle funzioni complesse, però, possiamo considerare inf come un punto:
Se noi abbiamo una variabile z di funzione f(z), introduciamo la variabile \xi = 1/z.
Se $\psi(\xi) = f(z)$

??
Usiamo una nozione che è la proiezione stereografica. Supponiamo di avere un poiano in due dimensioni (lo vediamo qua come una retta) Con sopra una sfera (qua un cerchio):
![[Pasted image 20220228162648.png]]
ad ogni punto del piano complesso possiamo mettere in corrispondenza un punto su questa sfera. Partendo dal polo nord della sfera, disegnamo una retta
![[Pasted image 20220228162744.png]]
E abbiamo una corrispondenza biuvicoca tra z e P.
Osservo che nel punto (0, 0) coprrisponde lo stesso punto 0 + i0 del piano complesso.
Il problema che abbiamo è che il polo nord non ha corrispettivo. Noi quindi completiamo il piano complesso esntendendolo con il punto $\infty$, che corrisponde al polo nord.

### Rappresentazione integrale di Cauchy
Se abbiamo una funzione analitica , possiamo scriverla sempre così:
![[Pasted image 20220228163133.png]]
Ora, consideriamo una sfera di raggio r e centro z_0. Per questo, abbiamo che $z = z_0 + re^{i\theta}$
- ![[Pasted image 20220228163102.png]]E applichiamo questa formula a questa sfera:
![[Pasted image 20220228163326.png]]E rimaniamo con una formula più semplcie (semplificando)
![[Pasted image 20220228163436.png]]
Questa è detta formula del valore medio. Significa che se noi abbiamo un cerchio, il valore della funzione olomorfa nel centro del cerchio è la media del valore della funzione olomorfa integrata sulla circonferenza.
![[Pasted image 20220228163507.png]]
Scriviamo:
![[Pasted image 20220228163514.png]]
=> Il valore medio sulla circonferenza di una funzione olomorfa coincide con il valore di questa circonferenza.
Questo vuol dire che se noi prendiamo e valutiamo il modulo di questa funzione, abbiamo che il modulo nel centro è minore dell'integrale del modulo.
Questa roba mi dice che il modulo di una funzione olomorfa non può raggiungere mai il massimo (all'interno di un certo intorno).
(Osservo che non esiste il massimo di una funzione olomorfa, visto che non c'è un ordine naturale sul piano complesso).

Questo non è tutto, perchè possiamo considerare anche una funzione f(z), olomorfa e tale che non ha zeri. Se è così, possiamo definire una funzione 1/f(z) che sarà anche lei olomorfa. (infatti, in questao caso 1/f(z) sarebbe olomorfa ovunque tranne dove f(z) ha zeri).

Come conseguenza dello stesso problema di prima, osservo che una funzione olomorfa non pul raggiungere il minimo in modulo assoluto in nessun punto.

ora, noi possiamo prendere una funzione olomorfa f(z) e considerare la funzione olomorfa esponenziale $e^{f(z)}$. Anche questa sarà olomorfa (l'esponenziale non ha zeri). Amche il modulo di questa funzione non può raggiungere ne massimo ne minimo. Ma quanto vale il modulo di questa funzione?
Sappiamo che vale: [[Formula di Eulero]]
![[Pasted image 20220228164113.png]]
E questo significa che anche la parte reale di una funzione olomorfa non può raggiungere il massimo.
Ma non ci fermiamo qui, perchè possiamo anche introdurre un'altra funzione olomorfa:
![[Pasted image 20220228164149.png]]
In questo caso, il modulo di questa funzione sarà uguale ad 
![[Pasted image 20220228164208.png]]
Anche in questo caso possiamo concludere che la parte immaginaria di una funzione olomorfa non può raggiugnere max e min nei punti interni all'olomorfismo.

### Teorema di liouville
Il mio ultimo teorema che appartiene a liouville
Una funzione f(z) [[intera]] (= olomorfa in tutto il piano complesso) e tale che è limitata, allora questa funzione per forz adeve essere una costante:
![[Pasted image 20220228164401.png]]
Questo è ez, basta ricordare la rappresentazione integrale per la derivata di una funzione:
f'(z) = (per contorno prendo una circonferenza):
![[Pasted image 20220228164505.png]]
espando (formula esatta per la derivata)
![[Pasted image 20220228164652.png]]
Adesso vogliamo valutare il suo modulo:
usiamo una relazione nota:
(modulo di f <= integrale del modulo):
![[Pasted image 20220228164729.png]]
Ma visto che la funzione è limitata, |f| è < di una certa costante positiva. MAggioriamo, quind:
![[Pasted image 20220228164851.png]]
Ma questo valore di R è illimitatao (lo possiamo prendere grande a piacere, visto che la funzione è [[intera]])=> tutto tende a zero, quindi la derivata è uguale a zero, quindi la funzione è costante.

esempi di funzioni intera:
    z^n  sen(z) 

### Residuo di una funzione
Sappiamno che una funzione olomorfa vale:
![[Pasted image 20220228173324.png]]
E sappiamo che se abbiamo al _massimo_ un punto singolare, abbiamo che:
![[Pasted image 20220228173358.png]] l'integrale di linea non cambia in base a gamma.

Possiamo allora deifinire il residuo:
![[Pasted image 20220228173414.png]]
.
Ora, facciamo un'analogia tra questa roba e la fluidodinanmica in due dimensioni.
Supponiamo di avere un fluido che si muove nel piano (incomprimibile) (significa che densità \rho = cost.) => possiamo caratterizzare il moto di questo fluido sapendo la velocità di questo fluio in ogni punto dello spazio:
![[Pasted image 20220228173636.png]]
"moti solenoidali", quando si ha questa roba:
![[Pasted image 20220228173708.png]]
Questo significa che la quantità di acqua non cambia. Non ci sono pozzi né sorgenti.
Poi c'è un'altra caratteristica del moto: il moto che soddisfa a :
![[Pasted image 20220228173743.png]]
Il rotore del moto è zero.
(non abbiamo vortici).
Come è òlegata tutta questa roba alle variabili complesse?
chiamo queste funzioni:
![[Pasted image 20220228173850.png]]
Possiamo costruire come al solito funzioni delle variabili complesse:
f(z) = u + iv, e da questo otteniamo, nel nostro caso:
f(z) = v_x - iv_y
A questo punto, trattiamo le due condizioni (divergenza e rotore = 0) come condizioni di Cauchy.
Di conseguenza, abbiamo che 
![[Pasted image 20220228174044.png]]
Se noi possianno costruire delle componenti delle nostre velocità copme funzioni di variabile complessa e abbiamo un moto solenoidale conservativo, siamo sicuri che abbiamo una funzioone olomorfa.

Secondo passo: se una funzione non è olomorfa?
Prendiamo f(z):
![[Pasted image 20220228174127.png]]
(per esempio).
Questa roba corrisponde a:
![[Pasted image 20220228174201.png]]
In questo caso, V_x sarà uguale a 
![[Pasted image 20220228174234.png]]
e V_y
![[Pasted image 20220228174242.png]]
Adesso possiamo calcolare la divergena di V.
![[Pasted image 20220228174400.png]]
Adesso, la divergenza sarà zero ovunque tranne nel punto zero.  diocca non si capisce un cazzo)
![[Pasted image 20220228174521.png]]

(il prof cancella tutta la lavagna)
![[Pasted image 20220228174655.png]]
Nope qua non si capisce un cazzo di quello che sta facendol
