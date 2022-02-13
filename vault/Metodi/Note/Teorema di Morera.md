
### Teorema di Morera
In un certo senso, è un teorema inverso rispetto a quello di Cauchy. Supponiamo che noi abbiamo ancora una regione aperta connessa, e non necessariamente semplciemnte connessa (basta avere una regione connessa), e abbiamo una funzione f(z) continua
![[../File/todo da lezione 4/Pasted image 20220225144700.png]]
Se noi abbiamo una funzione continua, possiamo sempre calcolare l'integrael di contonrno, e troviamo che lungo qualsiasi curva di jordan, vale:
![[../File/todo da lezione 4/Pasted image 20220225144735.png]]
^^ se valgono queste condizioni, si dinomstra che la funzione è olomorfa.

`DIM` Consideriamo due punti P, Q e due curve: gamma1 e gamma2:
![[../File/todo da lezione 4/Pasted image 20220225144823.png]]
E calcoliamo l'integrale sul contorno chiuso:
![[../File/todo da lezione 4/Pasted image 20220225144906.png]]
Vogliamo dimostrale che la differenza dei due integrali di percorso è uguale a zero. QUesto significa che i due integrali sono sempre uguali.
Questo singnifica che l'integrale tra due punti sul campo complesso non dipende dal percorso, ma dipende solo dagli estremi (punto di partenza e punto di arrivo). (??)
Questo significa che possiamo introdurre una funzione nuova, F(z) (grazie al teroema di morera):
$$
F(z) = \int_{z_0}^z dz'\ f(z')
$$
(Dove z0 è una scelta arbi)trari. a
Ora vogliamo dimostrare che F(x) è olomorfa. Lo faccio cercando di dimostrare che questa funzione è una derivata di una funzione olomorfa. QUesto implicherà, per la formula di cauchy, che F e tutte le sue derivate saranno anch'esse olomorfe.

Facciamo Bene o male come abbiamo fatto prima.

1/\Delta z \left() 
![[../File/todo da lezione 4/Pasted image 20220225145233.png]]

= ![[../File/todo da lezione 4/Pasted image 20220225145330.png]]

Ma f(z') è una funzione continua, questo significa che questo integrale lo possiamo sostituire come:
$$ 
\frac{f(z*)\Delta z}{\Delta z} \to_{\Delta z \to 0} f(z)
$$

=> Questo implica che F ed f sono entrambe funzioni olomorfe.
