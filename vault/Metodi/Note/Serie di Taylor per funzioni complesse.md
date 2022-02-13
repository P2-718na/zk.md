
### Serie di Taylor
Supponiamo di avere una funzione olomorfa, in una certa regione del piano complesso.
Prendiamo un punto z_0 e facciamo un cerchio (indicato con gamma) attorno. Consideriamo poi un punto arbitrario z, dentro a questo cerchio. Chiamiamo z' la variabile che descrive gamma.
![[../File/todo da lezione 4/Pasted image 20220225151235.png]]
Questo teorema ci dice che, in questo caso, posso scrivere:
![[../File/todo da lezione 4/Pasted image 20220225151227.png]]
A questo punto, aggiungo e sottraggo z_0 a denominatore:
![[../File/todo da lezione 4/Pasted image 20220225151254.png]]
Adesso facciamo:
![[../File/todo da lezione 4/Pasted image 20220225151346.png]]
Adesso guardiamo lìontervallo z' - z_0 e z - z_0 (rapporto sotto integrale. Si vede che il rapporto di z' - z0 è sempre maggiore (in modulo) del numeratore (basta guardare i raggi dei cerchi in figura):
![[../File/todo da lezione 4/Pasted image 20220225151439.png]]
Questo vuol dire che noi possiamo rappresentare quel rapporto a denominatore come progressione di una [[serie geometrica]] infinita:
![[../File/todo da lezione 4/Pasted image 20220225151523.png]]
che vale se |z| < 1.

Posso quindi riscrivere tutto l'integrale come:
![[../File/todo da lezione 4/Pasted image 20220225151652.png]]
=![[../File/todo da lezione 4/Pasted image 20220225151730.png]]
Visto che la funz è olomorfa, possiamo anche scambiare gli ordini di integrazione e della sommatoria:
=![[../File/todo da lezione 4/Pasted image 20220225151831.png]]
Ma questa è una serie di potenze (subito dopo sommatoria)
e quelli a destra sono una serie di coefficienti. => Possiamo quindi scricvere quello che abbiamo ottenuto cpome:
![[../File/todo da lezione 4/Pasted image 20220225151913.png]]
Dove gli an sono i coefficienti (integrali che prima erano a destra).
Esplicitamente, gli an sono:
![[../File/todo da lezione 4/Pasted image 20220225151951.png]]
E ricordando le formule di cauchy, vediamo che questa non è nient'altro che la derivata n-esima della mia funzione:
![[../File/todo da lezione 4/Pasted image 20220225152026.png]]
Questo significa che posso riscrivere la mia serie di potenze:
![[../File/todo da lezione 4/Pasted image 20220225152100.png]]
E questa è proprio una formula della serie di taylor.
In questo modo, abbiamo dimostrato che se una funzione è olomorfa, è anche analitica.
Per fare questo, abbiamo usato solo la formula della rappresentazione integrale di cauchy.

Possiamo anche dimostrare l'informazione inversa: _se una funzione è analitica, è anche olomorfa:_
supponiamo di avere questa funzione analitica:
![[../File/todo da lezione 4/Pasted image 20220225152221.png]]
Se questa funzione è analitica, possiamo applicare il teorema di Morera. Prendiamo un integrale a cazzo e lo calcoliamo esplicitamente:
![[../File/todo da lezione 4/Pasted image 20220225152324.png]]
Ma secondo il teorema di Cuchy, tutte le funzioni in sommatoria sono analitiche => il loro integrale è tutto zero. Da questo si ottiene che se la funzione è analitica, è anche olomorfa. applkicando il teorema di Morera.
