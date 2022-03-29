Continuiamo con le onde nello spazio 3d.
### Onde vettoriali
Spesso capita che le onde descrivano degli "spostamenti vettoriali. Per esempio, se ho una corda posso considerare lo spostamento provocato da un'onda _come scalare_, fissato il piano e la direzione del moto. In realtà, quando ho a che fare con una corda, questa si può muovere _in più di una direzione_.

##### Rappresentazione vettoriale delle onde:
![[../File/todo da lezione 15/Pasted image 20220328142031.png]]
Un onda, descriverà un' [[../Note/Equazione di D'Alembert nello spazio tridimensionale]] fatta da tre componenti (detto in altri termini, abbiamo _tre equazioni di D'alembert indipendenti_):
![[../File/todo da lezione 15/Pasted image 20220328142158.png]]
Quindi, questa equazione non mi aggiunge alcun vincolo. Le tre componenti sono completamente scollegate. A correlare le diverse componenti, ci pensa la fisica del mio sistema.
(E viceversa, osservando le correlazioni tra le mie componenti, si può provare a dedurre qualcosa sulla fisica di chi le ha generate).

Partiamo prendendo delle [[../Note/Onde armoniche piane|onde piane scalari]]; per loro soluzione dell'eq. era data da:
![[../File/todo da lezione 15/Pasted image 20220328142333.png]]
Analogamente, per un onda vettoriale piana:
![[../File/todo da lezione 15/Pasted image 20220328142401.png]]
(Visto che le tre eq. di d'alembert sono indipendenti e uguali a quella scalare, basta semplicemente ripetere la dimostrazione fatta in precedenza per ciascuna delle tre componenti.)
![[../File/todo da lezione 15/Pasted image 20220328142449.png]]
^^ IL concetto è che posso riscrivere le mie componenti come dipendenti solo da z:
![[../File/todo da lezione 15/Pasted image 20220328142612.png]]
Le onde vettoriali mi possono dare questo legame tra componenti e direzione di moto.
Le onde piane trasversalòi son oiquelle onde dove il vettore direzione \vec \xi è perpendicolare alla direzione di moto lungo \hat z.
![[../File/todo da lezione 15/Pasted image 20220328142701.png]]
Cioè, prendo la componente z identicamente nulla, e alla fine ho solo e soltanto due componenti.
![[../File/todo da lezione 15/Pasted image 20220328142744.png]]
Cosa vuol dire avere un onda trasversale? Vuol dire che se prendo la direzione di propagazione \hat u e faccio il prodotto scalare \hat u \cdot \vec f, tutte le volte che questo robo scalare va a zero, restano solo le mie componenti trasversali. Definiamo quindi
##### `DEF` Onda trasversale
Un onda è trasversale se: $$
\hat u \cdot \vec f(\hat u \cdot \vec r - vt) \equiv 0
$$

_Quali_ sono le onde trasversali? Dipende dalla fisica che c'è sotto.
![[Pasted image 20220328143001.png]]

Avevamo già detto, intanto che le onde sonore sono longitudinali...
![[Pasted image 20220328143209.png]]
Possiamo quindi definire le onde longitudinali come quelle oscillano lungo la direzione del moto:
##### `DEF` Onda longitudinale
$$
\hat u \times \vec f (\hat u \cdot \vec r - vt) \equiv \vec 0
$$
Quali sono le onde longitudinali?
![[Pasted image 20220328143436.png]]
(Per esempio, in fluidi tipo acqua, aria... ci sono onde longitudinali. (Non sulla superficie di separazione, ma proprio dentro)).
Ciò che succede sulla superficie di separazione di due materiali (per esempio, onde del mare/onde fisiche solamente superficiali), sono una _combinazione_ di questi due comportamenti (ne' completamente longitudinali, ne' completamente trasversali).

Ora, essenzialmente le onde longitudinali hanno _una sola componente_, quindi le abbiamo praticamente già descritte.
