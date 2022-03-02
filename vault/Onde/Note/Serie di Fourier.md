#### `THM` Teorema delle serie di Fourier
![[teorema di fourier.png]]
Una funzione di questo tipo (_periodica_, _limitata_, _con un numero finito di discontinuità_), può semore essere approssimata con la serie di Fourier.

(qui avremo un teorema (non dimostrato), per cui però è bene dare la definizione di serie di funzioni convergente:)
![[thm fourier 1.png]]
l'integrale deve essere svolto su _un periodo_. (estremi a scelta, basta che siano su un periodo). Diciamo che la nostra funzione converge se quell'integrale può essere piccolo a piacere.

Quindi come troviamo i coefficienti? Skippiamo al dimostrazione, vediamo solo che indicativamente questa roba funziona:
Per giustificare l'espressione dei coeff a e b, abbiamo bisogno di alcune prorpeità di _ortonormalità_ delle funzioni coseno e seno:
(non sappiamo un cazzo, diamo tutto per buono, seeee)
è possibile dimostrare che valgono queste tre identità:
![[thm fourier 2.png]]
Dove l'integrale è su un periodo, $T$ definito da $\omega$. Si riesce a dimostrare che questi tre integrali valgono quelle tre robe.

Bene, date queste formule, per trovacre i coefficienti devo definire una funzione di scarto. La $\epsilon$ nella definizione prima, la chiamo $\lambda_n$, e sarà una funzione sui parametri definita come:
![[thm fourier 3.png]]
I coefficienti $a$ e $b$ migliori,  mi dovranno determinare una lambda piccola (vorrei avere una lambda che vale zero, per avere un'approssimazione buona).
Riscrivo questa roba:
![[thm fourier 4.png]]
Se la penso per una funzione di un generico elemento, osservo che lambda è sempre positiva.
![[thm fourier 5.png]]
In più, osservo che questa è funzione di un numero infinito di parametri
(( non sto capendo una sega perchè mi sono distratto))
![[thm fourier 6.png]]
(??) scopro che lamdba sarà quadratica in N. Detto in altri modi, questa funzione come funzione di un parametro alla volta, mi descrive una para bola. Quindi, mi descrive una funzione di questo tipo, in funzione di a_m
![[thm fourier 7.png]]
Per prendere la migliore approssimazione, minimizzo la funzione degli scarti (minimizzo \lambda_m) (trovo punto dove derivata proima prima si annulla).
(???)
![[thm fourier 8.png]]

![[thm fourier 9.png]]
Queste robe si cavano perchè:
1) cos integrato su un periodo fa sempre zero
2) quando vado a fare la sommatroia, trovo tanti zeri tranne quando ??
3) contnua..
 ![[thm fourier 10.png]]
 Trovo quindi il risultato che mi da il valore di a_m che mi serve.

 Allora, m è una variabile muta, quindi rimetto n sia a primo che a secondo membro
.
Queste operazioni le devo rifare tutte uguali per tutti i coefficienti di tutte le robe:
![[thm fourier 11.png]]
Le formule che si ottengono per tutta la roba sono:
![[thm fourier 12.png]]
osservo che a_0 scritto così, rappresenta il valore medio della mia funzione periodica scritto su un periodo.
=> queste sono le soluzioni per una funzione periodica arbitraria.
