
Adesso possiamo introdurre:
### Serie di Laurent
Per funzioni che sono olomorfe in tutto lo spazio tranne al più un punto, possiamo farne una particolare rappresentazione in serie, diversa però dalla serie di taylor. Supponiamo di avere un certo punto z0 e supponiamo di avere due raggi:
![[../File/todo da lezione 4/Pasted image 20220225152821.png]]
r1 pi colo ed r2 più grande, ed in questa regione circolare (tra r1 ed r2.), abbiamo una funzione olomorfa. 
Noi vogliamo rappresentare questa f(z) come una serie. Come possiamo fare? 
Prendiamo un punto z che sta dentrop alla corona circolare, e facciamo un canale e poi un cerchio attorno a z:
![[../File/todo da lezione 4/Pasted image 20220225152945.png]]
E adesso dDiamo anche i nomi a tutte queste curve:
![[../File/todo da lezione 4/Pasted image 20220225153045.png]]
Se noi seguiamo tutto il percorso, a sinistra, secondo il teorema di jordan, abbiamoche sia z0 che z stanno al di fuori dell'area interna.
Questo significa che se noi prendiamo la somma di tutti gli integrali: (gamma piccolo ha il meno davanti perchè cambia il senso di rotazione):
![[../File/todo da lezione 4/Pasted image 20220225153326.png]]
Il rapporto:
![[../File/todo da lezione 4/Pasted image 20220225153333.png]]
Deve essere uguale a zero, secondo il Teorema di Cauchy.
Infatti, vediamo che gli integrali vanno a cancellarsi:
l1/l6, l4/l3
![[../File/todo da lezione 4/Pasted image 20220225153434.png]]
Rimango con:
![[../File/todo da lezione 4/Pasted image 20220225153502.png]]
Ma la cosa scritta con gamma tilde, secondo il teorema di Cauchy, è uguale a f(z) (questa gamma tilde circonda il punto z senza uscire dall'area di )?


Quindi, alla fine, f(z) varrà:
![[../File/todo da lezione 4/Pasted image 20220225153652.png]]
Questa è la formula che vogliamo usare per esprimere questa funzione f(z).
Adesso dobbiamo rappresentare questi due integrali come serie.

Cominciamo con il primo integrale su gamma grande. Iniziamo:
![[../File/todo da lezione 4/Pasted image 20220225153849.png]]
Osservo che ho la stessa struttura di prima:
z_0 - z' è una certa distanza, l'altra è l'altra. In questo modo, mi trovo sempre con un rapporto sempre minore di uno (in modulo). Uso ancora la serie geometrica:
![[../File/todo da lezione 4/Pasted image 20220225153954.png]]
l'esponente che non si legge è un n+1, a denominatore.

La differenza quindi starà nel secondo integrale:
![[../File/todo da lezione 4/Pasted image 20220225154051.png]]
La struttra è simile, ma la differenza delle distanze è opposta. Scriviamo, mettendo un meno davanti:

![[../File/todo da lezione 4/Pasted image 20220225154218.png]]
Il rapporto, qua, sarà semopre un complesso con il modulo di 1. Applichiamo ancora la serie geometrica. Avremo:
![[../File/todo da lezione 4/Pasted image 20220225154416.png]]
(ottenuto usando la formula per le serie geometriche).
Quesllo che succede qua ( a differenza di prima) è che sono scambiati numeratore e denumeratore. Riscrivendo ancora:
![[../File/todo da lezione 4/Pasted image 20220225154552.png]]
Ora vogliamo cambiarae un po' notazione, per avere questa parte simile a quella precedente, e avere un solo indice che includa tutte e due le serie. Introduciamo:
$n + 1 = -k \Leftrightarrow k = - (n + 1) \Leftrightarrow k = -n -1$
e riscriviamo la sommatoria come:
![[../File/todo da lezione 4/Pasted image 20220225154750.png]].
Ora possiamo rimettere assieme tutte e due le cose...
f(z) = 
![[../File/todo da lezione 4/Pasted image 20220225154943.png]]

La cosa importante è che la forma della prima serie e la forma della seconda coincidono. Ci sono due differenze:
la prima è che gli indici corrono in senso opposto.
La seconda differenza è che sopra abbiamo gamma e sotto gamma piccolo.
La cosa interessante è che negli integrali è sparito zeta, e resta solo z0. Rispoetto a z0, però, non ci sono differenze tra gamma piccolo e grande, visto che entrambi racchiudono z0. 
Quindi possiamo riscrivere tutto questo in forma seguente:
=![[../File/todo da lezione 4/Pasted image 20220225155202.png]]
Si può notare ancora che i coefficienti sono corrispondeenti alledderivate (?)

Come sono fatte queste serie? Qui possiamo introdurre:
suppiniamo di avere una serie fatta di questo tipo:
![[../File/todo da lezione 4/Pasted image 20220225155345.png]]
tale che:
![[../File/todo da lezione 4/Pasted image 20220225155353.png]]
Sono tutti uguali a zero.

Facciamo un esempio:
![[../File/todo da lezione 4/Pasted image 20220225155421.png]]
Abbiamo una singolarità isolata, chiamata "polo di ordine n".
