### Oscillatore armonico smorzato
Se prendiamo un [[Oscillatore armonico]] reale, osserviamo che questo è sempre sottoposto a qualche tipo di attrito viscoso. Questo attrito è una forza che dipende dalla velocità, e modifica l'equazione del moto in:
$$
\vec F_e = -k \vec x \hspace{30px}
\vec F_s = -\beta \dot{\vec x} \hspace{30px}
\vec a = \ddot{\vec x}
$$
$$
\vec F_e + \vec F_s = m \vec a
$$
Posso riscrivere tutto in termini di $x$, togliendo i vettori (ci stiamo muovendo lungo solo una dimensione):
$$
-kx - \beta \dot x = m \ddot x
$$
Ora posso riordinare e ottengo una [[EDO]] alle derivate seconde, _lineare e omogenea_. (1)
![[Pasted image 20220222091227.png]]
Osservo che la x appare sempre di primo grado e moltiplicata per coeff. costanti => è lineare (rispetto ad x).
C'è il termine noto che vale zero => è omogenea.
^^ Queste due cose hanno conseguenze molto importanti (vedremo più avanti, [[Lezione4]]).

In particolare, _per ogni EDO lineare e omogenea_, vale questa proprietà:
se prendo due soluzioni particolari, allora _una combinazione lineare di queste due soluzioni_ è anch'essa soluzione.
![[Pasted image 20220222091442.png]]
Per equazioin lineari omog. del II ordine, ne bastano due. Per ordinim superiori, ne servono di più.
In fisica, diremo che questo è il "principio di sovrapposizione".

==> A questo punto, per risolvere (1), vado a cercare due soluzioni particolari e le metto assieme. Vado a cercare una soluzione del tipo $x(t)=e^{\lambda t}$. (Il problema delle grandezze verrà risolto dopo con dei coefficienti), con lambda complesso.
![[Pasted image 20220222091710.png]]
^^ queste sono quindi posizione, velocità, accelerazione nel campo complesso.  Vado a fare la combinazione lineare (sostituisco 3 righe sopra):
![[Pasted image 20220222091807.png]]
^^ Raccolgo la x. Osservo intanto che x=0 è soluzione. Non è però la soluzione che mi interessa, visto che quella è il punto di stabilità, dove so già cosa succede.
La cosa interessante è il secondo fattore. Questo è detto "polinomio caratteristico". Gli zeri del polinomio caratteristico sono le soluzioni in lambda per una particolare soluzione. (lambda andrà pluggato nell'immagine sopra, dove abbiamo trovato $\dot{x}, \ddot{x}$.

(discorso su come risolvere equazione di secondo grado)

=> A seconda del segno del ∆ del polinomio caratteristico, avrò dei casi diversi di moto armonico:
1. $\Delta > 0$  => due soluzioni diverse, reali e negative (osservo che sono negative dai segni dei coefficienti).
2. Per chiarezza, visto che so che sono soluzioni negative, quando le scrivo vado ad aggiungere (meno modulo):
3. ![[Pasted image 20220222092353.png]]

Il moto di questo tipo è:
![[moto sovrasmorzato.png]]

QUanto velocemente va a zero, dipende dalla soluzione più piccola in valore assoluto.
(oss il beta sarebbe il coeff di stokes, misura quantoa ttrito ho. In questo caso, domina beta)

- $\Delta$ = 0 => due soluzioni uguali, reali e negative:
- ![[Pasted image 20220222092555.png]]
- PROBLEMA: Mi servono due soluzioni, ma ne ho trovata solo una. Procedo quindi facendo la derivata
- (di faccio, faccio il limite del rapporto incrementale della differenza tra le due (singola) soluzioni).
- IL risultato è che:
![[Pasted image 20220222092917.png]]
(c2 cambia un po' il significato fisico ma stica).
Il moto che si va a formare è di questo tipo:
![[moto smorzato critico.png]]
[moto smorzato critico](https://www.desmos.com/calculator/gapztddj1m)

Dopo un periodo di tempo dell'ordine di:
![[Pasted image 20220222093033.png]]
Ho perso il 95% della mia energia iniziale.
^^ (esempio: questo fenomeno è quello che avviene in una bilancia).

=> Il moto oscillatorio si verifica solo nel caso in cui io ho soluzioni complesse:
$\Delta < 0$ => ![[Pasted image 20220222093248.png]]
Faccio una combinazione lineare complessa:
![[Pasted image 20220222093337.png]]
Dove e^iw è il nostro fasore.
 Volendo, posso cambiare rappresentazione al numero complesso e ottengo:
 ![[Pasted image 20220222093416.png]]
 dove A,B,C sono tutte costanti arbitrarie (legate tra di loro, non mi interessa come).
 ^^ l'ultimo passaggio è una roba che si può fare ma non ha ftto:
 "quando ho un'espressione del tipo acost + bsent, la posso quasi sempre riscrivere come
 ccos(t+delta)".
 Osservo che visto che le soluzi son ocomplesse coniugate, la parte immaginaria va via
 La cosa che mi interessa è che alla fine ho una x(t) tutta nel campo reale.
 Il moto che si ottiene è:
 ![[Pasted image 20220222093606.png]]
 La pulsazione di questo moto è:
 ![[Pasted image 20220222093626.png]]

Osservo che k/m è il quadrato della pulsazione di un _oscillatore armonico non smorzato_. Quindi, in questo caso, il periodo è leggermente più lungo (di un oscillatore armonico non smorzato).
![[Pasted image 20220222094010.png]]
Qui non ho capito un cazzo
![[Pasted image 20220222094144.png]]

==> Altri esempi di oscillatori smorzati:
##### Circuito RLC
(vedi esempio circuito LC), ci sarà sempre un po' di resistenza elettrica in un circuito. Aggiungiamo una resistenza. Immaginiamo che su C ci sia inizialmenrte una carica. QUando chiudoi il circuito, la carica inizia a spostarsi e a dare origina ed una corrente.
![[circuito RLC.png]]
Questa è l'equazione della maglia, espressa in termini di Carica che sta su C
![[Pasted image 20220222094348.png]]
Questa roba è sempre analoga ad un oscillatore armonico smorzato:
Se delta minore di zero si ha:
![[Pasted image 20220222094644.png]]
(di fatto questo apparecchio è in tutte le antenne, quindi si cerca ad avere uno smorzxamento piccolo)
![[Pasted image 20220222094653.png]]
