
![[../File/todo da lezione 2/Pasted image 20220224102136.png]]
vv Qui quello che vado a fare è sostituire il coseno usando la [[../../Metodi/Note/Formula di Eulero|formula di eulero]]. Il numero a destra ($e^{i\Omega t}$) è chiaramente diverso dal coseno, ma alla fine noi andremo a prendere solo la parte reale di quello.
Quello che faccio, sinteticamente, è supporre comunque una soluzione del tipo: $x(t) = Ae^{\lambda t}$ (con $A$ costante arbitraria). Per forza di cose, voglio che il termine a sinistra sia periodico con lo stesso periodo di quello a destra, quindi eguaglio gli esponenti e ottengo: $\lambda = i\Omega$. A questo punto i due esponenziali si cancellano e vado a trovare $A$ da quello che mi rimane. Così ho trovato la mia soluzione particolare.
![[../File/Pasted image 20220331205347.png]] 
Soluzione stazionaria: sempre in ritardo di fase rispetto alla forzante (slide)
vv Il risultato che otterrò sarà:
$$
A = \frac {F_0} \chi
$$
  con $\chi$ uguale a tutta la merda che c'è lì in mezzo.  Qui vado anche a sostituire $\chi$, usando la definizione di [[Impedenza meccanica]].
![[../File/todo da lezione 2/Pasted image 20220224103206.png]]
![[../File/todo da lezione 2/Pasted image 20220224103216.png]]



=== Appunti dalla lezione di fourier
---
vediamo la soluzione n-esima:
![[../File/todo da lezione 4/Pasted image 20220228150524.png]]
(vedi [[Vettori rotanti (fasori)]])
Per risolvere, quindi, si fa questo:
![[../File/todo da lezione 4/Pasted image 20220228150609.png]]
(problema già visto, dove??)
Quindi, viene fuori che questo $\lambda_n$, sarà uguale a $in\omega$ (seconda formula foto sopra).
Sull'ampiezza non cambia nulla. Vado a sostituire tutto, e quando vado a sostutiure tutto, trovo un'ampiezza:
![[../File/todo da lezione 4/Pasted image 20220228150802.png]]
Uguale a quello visto prima (dove??) tranne che ora al posto di \Omega abbiamo nw.
