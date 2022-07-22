### Bilancio energetico
Ora, nascosta nelle equazioni di maxwell, c'è anche la _non conservazione dell'energia elettromagnetica_.

Questa è l'equazione di bilancio energetico
![[Pasted image 20220404153239.png]]
(espressa con H):
![[Pasted image 20220404153250.png]]

![[Pasted image 20220404153326.png]]
Nel vuoto, la conservazione dell'energia elettromagnetica in forma locale è data da:
![[Pasted image 20220404153441.png]]
Quindi, questo termine qua,_ se non ci sono correnti_, mi descrive una conservazione dell'energia elettromagnetica.

In forma macroscopica, integro lungo tutto il volume:
![[Pasted image 20220404153543.png]]

Ora, di questa energia io vado a studiare la mia derivata. => Perché la mia energia varia? Varia perché qualcuno sta spostando la mia densità di carica.

S mi rappresenta una sorta di densità di corrente. Ceh non è una roba che sta trasportando una carica, ma è una cosa che mi trasporta energia elettromagnetica
Se andiamo a vedere le dimensioni di S: 
![[Pasted image 20220404153553.png]]
Nel sistema internazionale, questo vettore di poynting si misura in $\frac W {m^2}$.

Ora, vediamo di applicare queste cose alle onde elettromagnetiche:
abbiamo visto prima quali sono i legami tra campo elettrico e magnetico:
![[Pasted image 20220404153916.png]]
Allora. La densità di energia em è fatta in due pezzi: una componente elettrica e una magnetica. In un circuiotp lc queste possono avere qualsiasi valore. Cosa succede nelle onde em?
Nelle onde em, queste sono collegate da una relazione data da v\mu:
![[Pasted image 20220404154025.png]]
=> Scopro che la densità di energia del campo elettrico è in relazione con la densità di energia del campo magnetico.

![[Pasted image 20220404154136.png]]
???
Possiamo scrivere quindi che la densità di energia EM è data da:
![[Pasted image 20220404154230.png]]
Per semplicitù usiamo quella in funzione di H.

Il vettore di poynting com'è fatto quindi:
![[Pasted image 20220404154320.png]]
 Se ho a che fare con un onda em, vale sempre \vec E \perp \vec B. Quindi, lavorando in modulo tolgopì il prodotto vettoriale (^^). Il risultato èche $|\vec S| = \frac {\ E^2} Z$.
 Riscrivo
    ![[Pasted image 20220404154441.png]]
    ![[Pasted image 20220404154456.png]]
Ora, sfruttiamo questa roba per definire l'ingensità delle onde em. Ricordiamo che l'intensità deve essere
1) Qualcosa legata all'energia
2) Qualcosa di puntuale (vale per un certo punto).

Quando abbiamo lavorato sulle onde sonore, le onde sonore viaggiano nello spazio => noi le abbiamo confinate all'interno di un tubo con sezione costante. QUando abbiuanmo dovuto definire qualcosa che mi dava l'intensità di un onda sonora, abbiamo sì considerato la potenza che ttraversava il mio tubo, e l'abbiamo divisa per l'area => l'abbiamo resa puntaule
![[Pasted image 20220404154832.png]]
La normale alla superficie è la blu, S è il vettore di Poynting.
![[Pasted image 20220404154906.png]]
Quindi io ho una densità di energia che ha lo stesso genere di periopdo.
Se io ho un onda periodica, quello cbhe mi succede qua è che ho una roba del tipo:
![[Pasted image 20220404154931.png]]
(è positiva quando l'energia cresce, negativa quando cala => sul periodo la media è nulla).
Un vettore che ha divergenza nulla è un vettore _solenoidale_. Qui non siamo _esattamente_ in quella condizione, ma ci siamo solamente se lavoriamo in media. QUesto vuol dire che io posso, associa
??????????????
Vediamo cosa sucede per un intervallino di tempo dt. 
![[Pasted image 20220404155212.png]]
Se questa altezza t è altezza dl, tutta la roba dentro esce.

QUindi ??????

![[Pasted image 20220404155335.png]]

Si definisce quindi:
![[Pasted image 20220404155426.png]]
Che è esattamente quello che abbiamo fatto per le onde sonore.
QUindi, da questo deriva che:
![[Pasted image 20220404155441.png]]
Se ho a che fare con un onda armonica, tutto mi si semplifica.

Il fattore 1/2 deriva dal cos^2 che nella media diventa \frac 1 2.

Confrontando l'intensità delle onde em con quella delle onde meccaniche:
![[Pasted image 20220404155834.png]]
per le onde meccaniche, \dot \xi era la velocità di un punto sulla corda, dato da (causa) Una forza. La potenza di questa forza che metteva in moto la corda, mediata nel tempo non era altro che l'intensità.
Per le onde em, c'è esattamente lo stesso concetto: l'intensità è la media del vettore di Poynting. Il modulo del vettore di Poynting è campo elettrico per h; il mio effetto è quindi H, causato da una variazione del campo elettrico.
Questa variazione è lineare, descritta da questo fattore Z (Impedenza). => Dobbiamo quindi iniziare a pensare che il campo elettrico per un onda EM è una sorta di "causa" e il campo magnetico è una sorta di "Effetto".


![[Pasted image 20220404160157.png]]
![[Pasted image 20220404160200.png]]
^^ Questa roba dipende da kz -wt => risolve l'equazione di d'alembert, con velocità w/k: 
![[Pasted image 20220404160221.png]]
Vettore di poynting, quindi, lo vado a scrivere anche questo come:
![[Pasted image 20220404160242.png]]
e osservo che anche questo dipende da kz - wt => anche questo risolverù una sua eq di d'alemnbert:
![[Pasted image 20220404160255.png]]

Quindi, quando parliamo di onde EM, parliamo di _onde di campo elettromagnetico_ e _non le possiamo separare_, ma parliamo nello stesso momento anche di un _onda di intensità di energia_ e _onda di vettore di poynting_.