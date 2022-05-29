### Relatività ristretta di Minkowski
Nello spazio euclideo, vale il teorema di pitagora per calcolare la distanza fra due punti:
![[Pasted image 20220503111845.png]]
![[Pasted image 20220503111849.png]]
Se ora passiamo ad un sistema di riferimento ad un altro, la lunghezza che abbiamo considerato è una grandezza invariante:
![[Pasted image 20220503111922.png]]
Queste sono trasformazioni che non coinvolgono il tempo. 
Questa cosa continua a valere se siamo in uno spazio a 4 dimensioni.

Ora, nella relatività speciale, la quarta coordinata non è una coordinata spaziale ma temporale. ( o meglio, c * t ).

![[Pasted image 20220503112114.png]]
In realtà osservo che questa grandezza non risulta invariante per trasformazioni di Lorentz. Mentre al contrario risulta invariante per t.l. la grandezza:
![[Pasted image 20220503112239.png]]
Se pongo w = ict, allora vale la somma dei quadrati delle coordinate.
![[Pasted image 20220503112248.png]]
=> Se voglio aggiungere il tempo alle coordinate, sono costretto ad introdurre una coordinata immaginaria. La cosa interessante è che questa distanza, ora può essere anche negativa! A differenza delle distanze euclidee!
Con questo osservo che il tempo è una cosa di natura diversa rispetto alle 3 coordinate x, y, z.

Volendo, potrei anche dire che le coordinate spaziali sono immaginarie e t reale, non cambia. L'importante è che siano sia immaginarie che reali:
![[Pasted image 20220503112453.png]]
QUando si usa questa convenzione, conviene definire le 4 coordinate come:
![[Pasted image 20220503112530.png]]
(questa roba si presta di più alla trattazione della relatività generale.).

Questo quadrivettore ha quattro componenti che rappresentano appunto ct, x, y, z.

Nella notazione tensoriale, questo quadrivettore legato alle coordinate si scrive x con apice:
![[Pasted image 20220503112730.png]]
Il modulo/norma di questo affare è 
![[Pasted image 20220503112744.png]]
![[Pasted image 20220503112751.png]]
Nel tensore, i g_\mu\nu sono detti coefficienti metrici:
![[Pasted image 20220503113020.png]]
Questi coefficienti definiscono la metrica che sto usando. Nella teoria della relatività ristretta, sono:
![[Pasted image 20220503113053.png]]
![[Pasted image 20220503113248.png]]

Bene, questo spazio e questa metrica sono noti come Spazio (e metrica) di Minkowski:
![[Pasted image 20220503113330.png]]
Nello spazio di Minkowski, questo affare è detto "cono di luce".
Abbiamo un asse x, una y e un asse verticale t.
Questo affare rappresenta come si propaga in questo spazio una particella priva di massa (fotone). Se il fotone è generato al centro e viaggia verso il futuro, il cono si apre. Se noi consideriamo quello che fa il fotone a partire da questo punto, si può simmetrizzare la figura. (?? ok boh non si capisce).

### Quadrivettori
Rivediamo le relazioni che abbiamo visto in termini di quadrivettori.
Nei testi più avanzati si usa questa notazione:
![[Pasted image 20220503113719.png]]
Parto da un punto nello spazio (x, y, z, t).
(O meglio, dire "punto" è improprio. Sarebbe più corretto dire "evento").
![[Pasted image 20220503113846.png]]
![[Pasted image 20220503114013.png]]
![[Pasted image 20220503114142.png]]
![[Pasted image 20220503114215.png]]
![[Pasted image 20220503114444.png]]
Oss il quadrivettore con l'indice in basso ha le seguenti caratteristiche: la componente temporale è la stessa, ma le x1, x2, x3 sono cambiate di segno.

Ora, torniamo al nostro R^2. Questo modulo al quadrato si pul anche scrivere come prodotto scalare di quadrivettori: uno con indice in alto e uno con indice in basso:
![[Pasted image 20220503114955.png]]

(??? Mi sono distratto)

![[Pasted image 20220503115358.png]]

Consideriamo due quadrivettori: A, B
![[Pasted image 20220503115543.png]]
Le componenti saranno A0, B0 per la parte temporale e \vec a \vec b per la parte tipo spazio. Io posso definire per ciascuno di essi un modulo quadro, e posso anche definire un prodotto scalare di uno per l'altro. Questo prodotto scalare può essere scritto come (??)
Il risultato è che questo prodotto scalare è uguale a prodotto delle parti temporali meno il normale prodotto scalare tra \vec a e \vec b.
Ora, trasformazioni di Lorentz: quello che abbiamo visto nel caso del quadrivettore relativo alle coordinate può essere generalizzato al caso di un qualsiasi quadrivettore:
se io passo da un sistema S a S', 

![[Pasted image 20220503121443.png]]

Non sto seguendo
