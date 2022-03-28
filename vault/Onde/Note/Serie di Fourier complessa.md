#### `THM` Serie di fourier complessa
![[../File/todo da lezione 4/Pasted image 20220228154607.png]]
con coefficienti c_n
![[../File/todo da lezione 4/Pasted image 20220228154617.png]]
=> La mia funzione periodica, qui, è un unica sommatoria di fasori.

^^^ Tutta questa roba che abbiamo visto, è la [[Serie di Fourier]] nel __campo reale__. Nei complessi, invece, la serie è "più simmetrica":
![[../File/todo da lezione 4/Pasted image 20220228153919.png]]
quando io prendo un termine generico dove sviluppo in serie, lo posso riscrivere in termini di questi esponenziali:
![[../File/todo da lezione 4/Pasted image 20220228153943.png]]
Osservo che questi esponenziali sono dei [[Vettori rotanti (fasori)]], uno che ruota in senso orario (+) e uno antiorario (-).
Vado a raccogliere e vedo (ultima riga foto sopra) i due fasori con [[../../Metodi/Note/Altre rappresentazioni dei complessi#Rappresentazione polare|rappre esponenziale]].
Raccolgo le parentesi prima degli esponenziali e ottengo;
![[../File/todo da lezione 4/Pasted image 20220228154125.png]]
Ora rinomino un po' di roba perchè è comodo (?)
![[../File/todo da lezione 4/Pasted image 20220228154146.png]]
Il passo successivo è osservare che nella serie di fourioer ho un termine a zero, e poi ho da 1 in avanti termini di questo tipo
![[../File/todo da lezione 4/Pasted image 20220228154222.png]]
Quindik riscrivo tutta questa roba (nota sokmatoria da 1 a +inf)
![[../File/todo da lezione 4/Pasted image 20220228154245.png]]
Oppure, equivalente
![[../File/todo da lezione 4/Pasted image 20220228154303.png]]
(insomma splitto n positivi e negativi).
I coefficienti sono quindi, per la serie complessa: (??)
![[../File/todo da lezione 4/Pasted image 20220228154434.png]]
raccolgo tutto in un singolo integrale:
![[../File/todo da lezione 4/Pasted image 20220228154505.png]]
dove ho usato il fatto che il seno è funzione pari (o dispari, non ricordo)
Il risultato finale è la tesi.

Bene, proviamo a vedere cosa succede nella pratica:
partiamo dal nostro oscillatore forzato da una f(t):
![[../File/todo da lezione 4/Pasted image 20220228155111.png]]
Devo scrivere f(t) come 
![[../File/todo da lezione 4/Pasted image 20220228155121.png]]
E calcolo i rispettivi c_n così:
![[../File/todo da lezione 4/Pasted image 20220228155135.png]]
. si ha:
![[../File/todo da lezione 4/Pasted image 20220228155150.png]]
Questo è un problema lineare, in cui al secondo membro si ha una somma di tanti termini. risolvo quindi trovando una soluzione particolare alla volta, e poi rimetto tutti assieme.
diocane
La soluzione particolare al mio problema è quindi la sommatoria di tutte le soluzione particolari, fatte tutte così:
![[../File/todo da lezione 4/Pasted image 20220228155339.png]]
Guarda caso, scritte tutte come soluzione di una serie di fourier complessa.
Alla fine, ho:
![[../File/todo da lezione 4/Pasted image 20220228155359.png]]
