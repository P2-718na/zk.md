### Derivazione della formula di Cauchy
_La fdc stabilisce che una funzione olomorfa ha infinite derivate, che possono essere espresse sencondo la formula ..._

Abbiamo una regione semoplicemente connessa aperta nel oiano connesso, con F(z) all'interno sempre olomorfa. Definiamo un controno arbitrario gamma

Se z non appartiene ad A, l'integrale è zero (fun. olomorfa)
Se z appartiene ad A, l'integrale non sarà zero perchè l'integranda smette di essere olomorfa. Sulla curva ancora tutto è ben definito, ma dentro le aree c'è questo punto singolare Z.
Noi però abbiamo visto che l'integrale chiuso di linea non dipende dalla curva. Se abbiamo z al centro, otterremo sempre lo stesso risultato.
Scegliamo quindi una curva circolare attorno a z, di ragigio r:
![[../File/todo da lezione 4/Pasted image 20220225141711.png]]
![[../File/todo da lezione 4/Pasted image 20220225141720.png]]
^^ Con theta tra 0 e 2pi, im questo modo definiamo la curva attorno a zeta:
l'integrale si riscrive come:
![[../File/todo da lezione 4/Pasted image 20220225141933.png]]

![[../File/todo da lezione 4/Pasted image 20220225141952.png]]
L'integrale assume questa forma. Aggiungiamo e sottraiamo la stessa funzione f(z).
Poi, ricordiamo che f(z) è olomorga, e quindi anche continua. Di conseguenza, applicando la definizione di [[Limite di funzione a variabile complessa]]
(???)

Si ottiene la formula di Cauchy:
![[../File/todo da lezione 4/Pasted image 20220225142408.png]]

^^ Importante: tutta la dipendenza da z, sta nello z a denominatore sotto al segno di integrale.
Quindi, f'(z) è data da detivazione sotto al sengno di integrale. Faccio l'ipotesi che esista e abbia questa formula:
$$
f'(x) = \frac{1}{2\pi i}\int_\gamma \frac{f(z')\ dz'}{(z-z')^2}
$$
Ora dimostriamo che questa esiste davvero e ha questa forma:
Parto da definizione di rapporto incrementale [[Differenziabilità di funzione a variabile complessa]]:
![[../File/todo da lezione 4/Pasted image 20220225142645.png]]
Per calcolare questo, devo sostituire dappertutto la formula di cauchy:
$$
= -\frac{1}{2\pi i}\oint dz'\ f(z') \left[\frac{1}{(z + \Delta z - z')\Delta z} - \frac{1}{(z-z')\Delta z} - \frac{\Delta z}{(z - z')^2\cdot \Delta z}\right]
$$
Tolgo deltaz da denominatore e porto fuori. 
$$
= \frac{1}{2\pi i \Delta z}\ \oint 
$$
![[../File/todo da lezione 4/Pasted image 20220225143034.png]]
Faccio denominatore comne
$$
\frac{1}{2\pi i \Delta z}\oint \frac{dz' f(z)}{(z' - z - \Delta z)(z' - z)^2}\left[(z' - z)^2 - (z' - z)(z' - z - \Delta z) - \Delta z(z' - z - \Delta z) \right]
$$
Sviluppando la roba nelle quadre, restiamo solo con
![[../File/todo da lezione 4/Pasted image 20220225143914.png]]
Finiamo di svolgere l'integrale:

1/2piideltaz * deltaz^2 \oint ![[../File/todo da lezione 4/Pasted image 20220225143955.png]]

=> La nostra formula della derivata, in realtà, è corretta. In questo modo, ho dimostrato chje questa deri ata può essere espressa attraverso questa formula di Cauchy. (sappiano già che la derivata esiste, visto che la funzione è [[Olomorfa]]).

Ricapitolando:
f(z) = ![[../File/todo da lezione 4/Pasted image 20220225144119.png]]
f'(z) =![[../File/todo da lezione 4/Pasted image 20220225144142.png]]

Possiamo ora applicare di nuovo lo stesso teorema a f'(z), e ottenere una formula per:

f''(z) = ![[../File/todo da lezione 4/Pasted image 20220225144419.png]]


Questo significa che, _se una funzione è olomorfa, questa ha infinite derivate_.
 
COntinuando il processo, abbiamo:
$f^{(n)}(z) =$ ![[../File/todo da lezione 4/Pasted image 20220225144444.png]]

`OSS` questa dimostrazione che abbiamnmo appena fatto, in realtà si dovrebbe fare in modo rigoroso per induzione, (riguardo all'n! a numeratore).
