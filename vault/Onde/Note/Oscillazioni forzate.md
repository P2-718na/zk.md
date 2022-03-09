### Oscillazioni FORZATE
Simile a prima, ma stavolta l'EDO non è omogenea.
![[../File/todo da lezione 2/Pasted image 20220222095306.png]]
Andiamo a vedere la tecnica generale per risolvere questa roba:
La strategia è "divide et impera". Andiamo quindi a splittare il problema in due:
![[../File/todo da lezione 2/Pasted image 20220222095451.png]]
(ovviamente qusta roba si dimostra che funzioni, noi la prendiamo per buona).
Osservo che:
![[../File/todo da lezione 2/Pasted image 20220222095535.png]]
Come faccio a trovare la soluzione particolare?

Partiamo facendo un esempio: forza costante.
![[../File/todo da lezione 2/Pasted image 20220222095735.png]]
Prendiamo il nostro punto materiale e lo appendiamo al soffitto grazie ad una molla.
Il punto O è il pt di equli della molla (in assenza di forza peso, oscillazione avviene attorno a quel punto).
La mia EDO sarà quindi:
![[../File/todo da lezione 2/Pasted image 20220222095900.png]]
In questo caso molto ez definisco un nuovo punto di equilibrio stabile (lo trovo annullando derivacta prima risp a x):
![[../File/todo da lezione 2/Pasted image 20220222095946.png]]

di consegurnza, traslo il mio sistema di riferimento. pongo :
![[../File/todo da lezione 2/Pasted image 20220222100024.png]]
e ^^ così trovo un'equazione nella variabile y che è uguale a quella dell' [[#Oscillatore armonico smorzato]].  Da qui:
![[../File/todo da lezione 2/Pasted image 20220222100117.png]]

Continua: [[Oscillazioni con forzante periodica]]