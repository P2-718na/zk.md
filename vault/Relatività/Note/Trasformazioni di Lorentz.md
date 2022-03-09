### Storia delle trasformazioni di Lorentz.
Per quanto riguarda la relatività ristretta,  questa si basa sulle trasformazioni di Lorentz, dovute a diversi scienziati...
![[../File/todo da lezione 4/Pasted image 20220301114744.png]]
Quindi, abbiamo parlato degli [[../Note/Esperimento di Michelson e Morley]]. 
Tutti questi, per via dei problemi di etere e cazzi vari avevano provato a scrivere equazioni matematiche già precedenti a quelle di Lorentz. Quasi tutte,  in realtà, erano state introdotte un po' Ad-Hoc, per salvare l'etere. Lorentz, quindi, 1899 mette tutto assieme.
Subito dopo, Poincaré pubblicò dei lavori in cui, indipendentemente da Einstein, arrivò molto vicino alla formulazione della relatività ristretta, basandosi proprio sulle trasformazioni di Lotentz. Einstein pubblica i suoi lavori famosissimi nel 1905. Parte da un approccio diverso di Lorentz, (parte dai suoi postiulati), e a partire da questo arriva alle equazioni di Lotentz.

Cosa fece Einstein?
Lui parte da certe assunzioni:
![[../File/todo da lezione 4/Pasted image 20220301115129.png]]

Isotropia dello spazio significa che Einstein non pensa che esistano direzioni "privilegiate" del moto. Il risultato che ricava lui avrà validità generale.
Omogeneità dello spazio tempo: se un corpo ha una certa velocità di modulo costante v in un certo sdr, questa velocità, una volta misurata in un altro sdr inerziale, rimarraà costante. QUesto cosa significa? Significa che le trasformazioni di Lorentz, sono delle _trasformazioni lineari_

Se io considero un sdr S fisso e un sdr S' che si muove ad una certa velocità v, abbiamo queste proprietà per le trasformazioni di Lorentz:
![[../File/todo da lezione 4/Pasted image 20220301115352.png]]
3) COnsideriamo velocità che siano sempre parallele a due assi cartesiani.  In più, le trasf di Lorentz si riconducono a quelle galileiane quando la velocità v è piccola rispetto a c.ù
4) In ALTRE parole, per queste trasformazioni, io avrò espressioni che coinvolgono x, t e v, ma NON COINVOLGERANNo y e z, che sono le direzioni perpendicolari rispetto a dove si sta avendo il moto (questo è perchè le due dovrebbero essere equivalenti, il che non sarebbe vero se queste due includessero esplicitamente anche y e z)

Le trasformazioni di Lorentz, appartengono ad un "gruppo di trasformazioni" (categoria matematica). Il gruppo di quelel di Lorentz, appartengono al Gruppo di Poincaré, e in particolare fanno parte del gruppo più generale di trasformazkoni _ortogonali nel gruppo di Minkowsky_.

=>= >Per questo primo approcci di Einstein di come dedurre le trasformazioni di Lorentz, ci sono quindi poche assunzioni fondamentali.

![[../File/todo da lezione 4/Pasted image 20220301121214.png]]
Possiamo dire che la coordinata x' e (??) siano lineari con coerrifcienti che dobbiamo determinare. Questo è lo schema dei "boost" di Lorentz.

Noi vogliamo che la luce si muova con una stessa velocità c sia in S che in S0'. Immaginiamo di avere un raggio vettore in S che va da un punto O ad un certo punto P. 

Se il raggio vettore ha modulo xx + yy + xx, la distanza percorsa dalla luce sarà (ct)^2. Posso fare lo stesso ragionamento in S'.

Questa serie di condizioni non bastano. Possiamo già dire qualcosa sui coefficienti perchè:
![[../File/todo da lezione 4/Pasted image 20220301121435.png]]
Tornando a quelle robe di prima, ho che:
![[../File/todo da lezione 4/Pasted image 20220301121458.png]]
![[../File/todo da lezione 4/Pasted image 20220301121509.png]]
Sostituendo un po' a cazzo
![[../File/todo da lezione 4/Pasted image 20220301121623.png]]
![[../File/todo da lezione 4/Pasted image 20220301121643.png]]
![[../File/todo da lezione 4/Pasted image 20220301121754.png]]
![[../File/todo da lezione 4/Pasted image 20220301121931.png]]
![[../File/todo da lezione 4/Pasted image 20220301121935.png]]
![[../File/todo da lezione 4/Pasted image 20220301122142.png]]
Il fattore sotto radice è chiamato fattore di Lorentz. Si definiscono:
#### `DEF` Fattore di Lorentz
![[../File/todo da lezione 4/Pasted image 20220301122231.png]]
![[../File/todo da lezione 4/Pasted image 20220301122235.png]]
E le trasformazioni di Lorentz, in forma più compatta, diventano:
![[../File/todo da lezione 4/Pasted image 20220301122253.png]]
In più,
![[../File/todo da lezione 4/Pasted image 20220301122300.png]]
(questo deriva direttamente dal fatto che avviamo detto che la velocità di un sdr rispetto all'altro differisce solo di un segno -).

SI trovano anche trasformazioni che riguardano il tempo (o meglio, la distanza percorsa dalla luce nel tempo):
![[../File/todo da lezione 4/Pasted image 20220301122444.png]]
Facendo scomparire v, andando a sostituire il coeff beta:
![[../File/todo da lezione 4/Pasted image 20220301122450.png]]


### Trasformazioni delle velocità
Le trasf di lorenz dicono anche come si trasformano le velocità e le accelerazioni, passando da un sistema di riferimento ad un'altro:
![[../File/todo da lezione 4/Pasted image 20220301123654.png]]
Come si ragiona in questo caso?
beh, "basta derivare", ma rispetto a quale tempo?
Le trasfr di galilei erano ez:
![[../File/todo da lezione 4/Pasted image 20220301123745.png]]
Quindi, se ho un punto e voglio sapere la sua velocità v:
![[../File/todo da lezione 4/Pasted image 20220301123756.png]]

PEr quelle di lorenx è meno ez. Consideraimo le trasformazini:
![[../File/todo da lezione 4/Pasted image 20220301123924.png]]
Quale sarà la velocità $v'_x$? Per definizione, abbimo che:
![[../File/todo da lezione 4/Pasted image 20220301123957.png]]
Quindi, dividiamo![[../File/todo da lezione 4/Pasted image 20220301124716.png]] ![[../File/todo da lezione 4/Pasted image 20220301124252.png]]
![[../File/todo da lezione 4/Pasted image 20220301124021.png]]
QUindi si ottiene:
![[../File/todo da lezione 4/Pasted image 20220301124312.png]]
Dove beta e gamma sono sempre la stessa roba. Invertendo sdr:
![[../File/todo da lezione 4/Pasted image 20220301124428.png]]

### Trasformazione accelerazioni
Qui la roba divena difficile.
Partiamo dalle formule delle velocità, cambiando un attiom i nomi:
![[../File/todo da lezione 4/Pasted image 20220301124559.png]]
Qui abbiamo che le rispettive robe sono:
![[../File/todo da lezione 4/Pasted image 20220301124620.png]]

"non prendete nota:"
![[../File/todo da lezione 4/Pasted image 20220301124746.png]]
Il risultato finale, quindi, è questo:
![[../File/todo da lezione 4/Pasted image 20220301125007.png]]
![[../File/todo da lezione 4/Pasted image 20220301125028.png]]
![[../File/todo da lezione 4/Pasted image 20220301125033.png]]

##### Fattorid id lotenz multilptlki
Finora, abbiamo sempre parlato di fattore di lorentz (legato al sistema di riferimento S'),
Questo fattore di Lorentz, dopo entra in tutte le leggi di trasformazione delle coordinate. Però, in generale, il fattore di Lorentz può essere definito per cose diverse. Possiamo trovare problemi dove c'è più di un fattore di lorentz. Possiamo trovare problemi con più sistemi di riferimento, che si comportano in modo diverso. In quel caso ci sono più fattori di Lorentz in gioco. L'importante è considerare sempre la definizione e ricordarsi cosa si sta facendo:
![[../File/todo da lezione 5/Pasted image 20220307115540.png]]
![[../File/todo da lezione 5/Pasted image 20220307115717.png]]
^^ (per riassumere, nella formula a destra sono stati omessi i peridi \_p).
Da questo, senza perdere tempo, si ottiene che:
![[../File/todo da lezione 5/Pasted image 20220307115805.png]]
