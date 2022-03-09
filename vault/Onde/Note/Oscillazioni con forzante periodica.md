
![[../File/todo da lezione 2/Pasted image 20220224102136.png]]
Soluzione stazionaria: sempre in ritardo di fase rispetto alla forzante (slide)
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

---


![[../File/todo da lezione 2/Pasted image 20220224103401.png]]
![[../File/todo da lezione 2/Pasted image 20220224103415.png]]
![[../File/todo da lezione 2/Pasted image 20220224103454.png]]
![[../File/todo da lezione 2/Pasted image 20220224103517.png]]
![[../File/todo da lezione 2/Pasted image 20220224103530.png]]

---
Continua: [[Impedenza meccanica]]


---
Da lezione 3
Sviluppo di soluzione stazionaria
![[../File/todo da lezione 3/Pasted image 20220223091252.png]]
posso scrivere la funzione particolare come:
![[../File/todo da lezione 3/Pasted image 20220223091308.png]]
con due termini. Uno che oscilla uguale alla forzante e l'altro sfasato di 90°.
La cosa è talmente importante che i coefficienti hanno un nome proprio:
![[../File/todo da lezione 3/Pasted image 20220223091344.png]]
.
Andiamo ora a vedere che significato hanno cos(delta) e sen(delta)
Ricordando che la fase delta è l'argomento di questo numero complesso chi:
![[../File/todo da lezione 3/Pasted image 20220223091526.png]]
=>
cos(delta) = Re(\chi)/|\chi|
sen(delta) = Im(\chi)/|\chi|
^^ Inserendo queste due relazioni nella formula sopra (in rosso), otteniamo:
![[../File/todo da lezione 3/Pasted image 20220223091705.png]]
Questo cosdelta può essere positivo o negativo (vedi numeratore). Stesso discorso per il seno di delta.

Andiamo a vedere quindi quello che stiamo facendo:
### Ampiezza elastica
![[../File/todo da lezione 3/Pasted image 20220223091847.png]]
(dove |A| vale:
![[../File/todo da lezione 3/Pasted image 20220223091902.png]]
). ALla fine, quello che mi interessa studiare è Ael in funzione della pulsazione:
![[../File/todo da lezione 3/Pasted image 20220223091933.png]]
Graficando questa roba:
![[../File/todo da lezione 3/Pasted image 20220223091950.png]]
Interessante il fatto che questa roba la troviamo negli oscillatori armonici forzati, ma anche in materiali dove, apparentemente, non ce ne sono. Se si trovano forme di questo genere, spesso indica che in mezzo ci sono oscillatori forzati.
Qua'è il significato? Per Omega piccolo, il corpo si muove lentamente (nel grafico, prima della prima freccia blu). Aumentando omega, le oscillazioni diventano sempre più grandi, fino a quando non mi trovo nella regione in mezzo.
In realtà, quello che succede è perchè io sto guarndando quella fase di oscillazione che è in fase con la forzante. QUando vado vicino alla zona di risonanza, l'oscillazione sta in fase (?) NON SI CPAISCE UN CAZZO

Lo zero si raggiunge solo quando Omega = omega, e quindi i due sono sfasati di 90°

### Ampiezza assorbitiva
![[../File/todo da lezione 3/Pasted image 20220223092732.png]]
facendo il prodotto a destra
![[../File/todo da lezione 3/Pasted image 20220223092753.png]]
Andandola a graficare, ottengo una curva di questo tipo:
![[../File/todo da lezione 3/Pasted image 20220223092814.png]]
La larghezza del picco al centro è dominata da gamma, mentre l'altezza di questa funzione è inversamente proporzionale. => Tanto più è stretta, tanto più è larga.

### Analisi ener∂getica
Per capire meglio. Nel nostro oscillatore forzato, abbiamo 3 tipi di forza:
- elastica
- forzante (avrà una propria potenza...)
- viscosa (proporzionale a velocità / carica...)

In generale, ognuna di queste tre forze, avrà una certa potenza che posso scrivere come:
![[../File/todo da lezione 3/Pasted image 20220223093223.png]]
Per capire cosa succede, assumo di trovarmi a tempi lunghi (no oscillazini smorzate) e mi calcolo la media della potenza di ogni forza su un periodo della forzante:
![[../File/todo da lezione 3/Pasted image 20220223093314.png]]
\dot{x} lo posso scrivere in due modi quindi: o derivo l'espressione delle due A, oppure derivo la posizione data dal vettore originale:
![[../File/todo da lezione 3/Pasted image 20220223093409.png]]

#### Forza elastica
f(t) = -kx
^^ Ci aspettiamo che questa sia zero lungo un ciclo, visto che è una forza conservativa. Di conseguenza, tra i due punti di un ciclo, l'energia sarà la stessa.
La potenza media è una cosa diversa, ma ci aspettiamo comunque che venga zero, svolgendo i conti:
![[../File/todo da lezione 3/Pasted image 20220223093617.png]]

(analogamente, per i circuiti RLC, la parte elastica è data dalla capacità del sistema).

#### Forza viscosa
Mi aspetto di avere una potenza totale negativa, visto che la forza è dissipativa.
![[../File/todo da lezione 3/Pasted image 20220223094033.png]]
Se vado a calcolare esplicitamente la potenza dissipata (usando la formula in rosso), ottengo che:
![[../File/todo da lezione 3/Pasted image 20220223094240.png]]
Dove R(\Omega) è la funzione di risposta

#### Forzante
Qui ci aspettiamo di sicuro un valore positivo. Come espressione, ci aspettiamo di sicuro qualcosa collegato all'energia dissipata dal moto viscoso (la forzante dovrà mettere più potennza id forza viscosa, altrimenti il corpo smette di muoversi):
![[../File/todo da lezione 3/Pasted image 20220223094538.png]]
(???)

=> In un ciclo, tanta energia entra quanto esce.

![[../File/todo da lezione 3/Pasted image 20220224103642.png]]