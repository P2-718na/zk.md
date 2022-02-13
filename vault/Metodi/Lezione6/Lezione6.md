L'ultima volta abbiamo introdotto il concetto di residuo:

### Teorema dei residui
Prendo una curva di Jordan gamma, in cui sono presenti all'interno un numero finito di punti singolari z1, z2, z3...

Il teorema dice che:
![[Pasted image 20220302161754.png]]

Vediamo la dimostrazione. Facciamo una dimostrazione dello stesso tipo di quando abbiamo introdotto le serie di laurent:
1) facciamo un cerchio attorno a uno dei punto, e colleghiamo questo cerchio all'esterno con un canale che ha due sponde molto vicine:
2) ![[Pasted image 20220302161844.png]]
poi, facciamo la stessa cosa con tutti gli altri punti:
![[Pasted image 20220302161901.png]]
Ora percorriamo tutta la linea (vedi le frecce in figura)
La curva data da 
- ![[Pasted image 20220302162100.png]]
- è una curva chiusa (di jordan) e al suo interno non ha punti singolari.
- Questo signidica che posso applicare il teorema di Cauchy, e possiamo scrivere:
(integrale di linea lungo tutte le robe.) (naturalmente, gli integrali sui canali piccoli vanno a compensarsi perchè sono molto vicini).
![[Pasted image 20220302162340.png]]
(??)
![[Pasted image 20220302162402.png]]
E quindi, si ottiene il teorema dei residui
(oss f(z1)... non sono definite, visto che sono singolarità. Sono definiti però i resti)

(qui c'è una parte che ho saltato perchè mi sono distratto)


### Residuo di una funzione all'infinito
Un punto si trova a inf del piano complesso. Quindi, per definire il residuo, bisogna disegnare una circonferenza con un raggio "Piuttosto grande", ovvero, dobbiamo poter disegnare una circonferenza tale che tutti i punti al suo esterno (eccett inf) si comporti in modo non singolare.

Rispetto a questa curva, il punto inf deve essere interno
Se noi vogliamo interpretare tutto il resto del piano complesso, noi dobbiamo invertire il nostro percorso. Quindi, possiamo dire che Res f(z) valutato a z= inf sarà
![[Pasted image 20220302164925.png]]


Supponiamo che (???)


### Derivata logaritmica
![[Pasted image 20220302171927.png]]
(?)

Consideriamo ora una funzione che nel punto z = z_0 ha un polo:
![[Pasted image 20220302172136.png]]