### Onde trasversali su corda elastica
Facciamo una dimostrazione che mi permette di trovare un'equazione delle onde.
Immaginiamo una corda elastica tesa e appoggiata su un piano liscio (assenza di attrito):
![[../File/corda 1.png]]
Introduco un _sistema di riferimento_ dove ho un _asse $x$ lungo la corda_, un _asse $y$ sul piano_ e rappresenta l'altra dimensione.
Questa corda si può muovere sul piano $O_{xy}$ (anche se la tengo tesa agli estremi, un onda può comunque viaggiare su quella corda).

Se vado a considerare un punto della corda ben definito, questo potrà fare tanti movimenti; adesso andiamo ad osservare solo quelli  _trasversali_ (punto <span color=blue>blu</span> in figura).
![[../File/corda 2.png]]
Se la corda è ferma. allora $\xi (x,\ t) = 0 \underset{x,\ t}{\forall}$ (condizione imperturbata di equilibrio iniziale).
Quando la corda si muove, quindi quando il punto $x$ oscilla, vuol dire che questa funzione $\xi$ diventa funzione del tempo, ovvero che:
$$
\frac {\partial\ \xi(x,\ t)}{\partial t} \ne 0
$$
Se $\xi$ rappresenta la posizione della y nel mio punto generico, allora
$$
\frac {\partial\ \xi}{\partial t} \equiv \text{velocità verticale della corda in } x
$$
La domanda che mi faccio ora è:
_qual è l'equazione della dinamica che $\xi(x,\ t)$ deve soddisfare?_ (Ci saranno per forza delle limitazioni, imposte da questo tipo di problema che sto considerando).
Facciamo le cose un pezzo alla volta. Consideriamo il moto di un tratto infinitesimo $dx$ della corda, che avrà massa $dm$ data da:
$$
\mu = \frac{d\ m}{dx}
$$
con $\mu$ densità lineare della corda (tutta _omogenea_).
Voglio studiare il movimento di questo $dx$ infinitesimo di corda:
![[../File/corda 6.png]]
Prendo il mio tratto infinitesimo di corda (imperturbato): $(x, x+dx)$.
Quando la corda oscilla, questo punto si sposterà in alto e in basso. In un certo momento, avrò, per esempio, questa situazione:
![[../File/corda 7.png]]
(Osserva che il pezzo di corda è lo stesso, non si sposta).
Cosa fanno i due pezzi di corda a destra e sinistra del mio tratto considerato? Questi agiscono sul mio pezzettino dx, uno tirandolo da una parte e uno tirandolo dall'altra parte.
Su questi due punti estremi, agisce da un lato una certa tensione e dall'altro un'altra tensione:
![[../File/corda 8.png]]
e questa tensione è sempre tangente alla corda in ogni suo punto (le due tensioni ai lati formano due angoli $\theta_1 e \theta_2$).

Questo pezzo deve soddisfare a $\sum \vec F = m \ddot{\vec x}$ . Qui, le forze sono le due tensioni,. quindi ho che:
![[../File/corda 9.png]]
Lavoriamo prima a secondo membro: consideriamo onde che si spostano solo lungo asse $y$:
$$
\vec a = a \hat y
$$
Assumo che quando questo dx è piccolo a piacere, questa quantità (derivata seconda di $\xi$) sia l'accelerazione per tutti i punti di questo tratto infinitesimo. (L'accelerazione è una quantità finita, che avrà, tra i due estremi, due valori estremamente vicini. Quindi prendo uno dei due a caso e uso quello).
![[../File/corda 11.png]]
Ora lavoriamo sulle tensioni delle due corde:
![[../File/corda 12.png]]
Scompongo le forze lungo le componenti
(lungo $\hat x$ non voglio avere accelerazione, visto che i pezzi di corda non si muovono avanti e indietro)

Ora c'è un passaggio fondamentale: _a noi interessano piccole perturbazioni rispetto alla condizione di equilibrio_. Se le perturbazioni sono piccole, la corda è _vicina_ alla condizione di equilibrio. Questo vuol dire che la corda, rispetto alle oscillazioni, è molto lunga. Posso quindi fare approssimazioni per angoli piccolo (theta1 e theta2, un paio di figure sopra)
![[../File/corda 13.png]]
Quando faccio questo, sulla x mi scompaiono i due coseni e dal sistema di prima ottengo:
![[../File/corda 14.png]]
Cosa vuol dire? Vuol dire che le due tensioni ai capi del mio elemento infinitesimo devono essere uguali. => Le individuo quindi con un solo termine T, che vale su tutta la corda (abbiamo ritrovato il risultato di meccanica che mi dice che in ogni punto ho la stessa tensione).
![[../File/corda 15.png]]
Facciamo questa osservazione: se l'angolo è piccolo, seno e tangente sono la stessa cosa. Ma la tangente non è altro che il coefficiente angolare della retta tangente ad un certo punto. Ed il coefficiente angolare è proprio la derivata della funzione fatta rispetto alla x. => Riscrivo la tangente come:
![[../File/corda 16.png]]
Allora, da questo ho che:
![[../File/corda 17.png]]
![[../File/corda 18.png]]
quindi, queste equazioni qui,inserendole in quella sus (T(sin...)) di prima, ottengo che:

![[../File/corda 19.png]]
Dove sono andato a sostituire la massa con $\mu\ dx$. Ora, da questa roba vado a sostituire anche le altre due tangenti a primo membro:
![[../File/corda 20.png]]
E porto Tensione a destra e $dx$ a sinistra:
![[../File/corda 21.png]]
Questo 1/dx è un rapporto incrementale. Nel momento in cui lo prendo piccolo a piacere, quello che ho a primo membro di fatto è una derivata (rigore matematico go brr):
Di fatto, quello che ho a sinistra, quindi, non è altro che una derivata seconda di \xi. Ottengo così, l'equazione delle onde elastiche:
![[../File/onde 24.png]]
Ho un'eguaglianza tra derivate seconde nello spazio e derivate seconde nel tempo. Il coefficiente \mu/T è un coefficiente della corda.
Questa roba, che abbiamo ottenuto per le piccole oscillazioni, in realtà si ritrova molto simile in tanti altri ambiti.ù

Il coefficiente $\frac \mu T$ ha un nome proprio in realtà: si scopre essere collegato alla velocità di propagazione delle onde in questo modo:
![[../File/corda 22.png]]
E andando a sostituire, otteniamo:
[[../Note/Equazione di D'Alembert]]
Altra domanda: v è una velocità? Facciamo l'analisi dimensionale:
![[../File/corda 23.png]]

Quello che stiamo descrivendo con l'eq d'alembert è un'andamento di un'onda trasversale su una corda, Da questo momento in avanti, ci occuperemo di trovare le soluzioni all'eq alembert.
![[../File/corda 24.png]]

---
Appunti da lezione 6 (dopo onda alembert)
Vediamo un esempio di onda (tutte le cose per quest'onda possono essere estese a qualunque funzione f).
Prendiamo un'onda _impulsiva_ progressiva. (impulsiva = abbiamo solo _1 impulso_ che si muove lungo la corda): (https://www.desmos.com/calculator/gev9e0s77w)
![[../File/todo da lezione 6/Pasted image 20220302093743.png]]
Questa ha una formula "tipo gaussiana"
 ![[../File/todo da lezione 6/Pasted image 20220302093801.png]]
Su asse x rappresento la x come funzione del parametro s. Per t=0, s \equiv x. (questo vale però solo in questo istante di tempo).
Questa funzione, ci è utile perchè avendo un solo massimo, possiamo vedere bene cosa succede quando si muove lungo la corda.
Il massimo ce l'ho quando il mio s = 0, quindi se siamo a t = 0, abbiamo xhe per x = 0 c'è massimo. ^1a9332

Cosa succede quando avanza il tempo?
La forma dell'onda è sempre la stessa, ma si sposta il picco:
![[../File/todo da lezione 6/Pasted image 20220302094133.png]]
![[../File/todo da lezione 6/Pasted image 20220302094243.png]]
Il picco si sposta di una distanza vt.
Ovviamente, questo ragionamento fatto per il picco della corda, in realtà vale per tutti i punti della corda. Tutta la curva, apparentemente, trasla linearmente.
Ogni punto della corda oscilla solo in verticale, ma l'onda progressiva si sposta verso destra.

Analogamente, l'onda regressiva, avrà lo stesso comportamento, ma si sposterà verso sinistra.

(vedo g(w) come $g(x - (-vt))$), quindi è come se fosse un'onda progressiva con velocità negativa

Osservo che questa formula x - vt è proprio una trasformazione galileiana delle velocità. Ragioniamoci sopra:
![[../File/todo da lezione 6/Pasted image 20220302094707.png]]
Consideriamo l'onda di prima:
![[../File/todo da lezione 6/Pasted image 20220302094826.png]]
Se faccio questa trasformazione, ,a mia onda diventa:
![[../File/todo da lezione 6/Pasted image 20220302094843.png]]
In questo sistema che si muove in direzione oppost acon la stessa velocità, osservo che la mia funzione \xi si comporta come se l'onda fosse ferma.
Ora, ho un problema:
_In questo modo, in S' ho una $\xi(x',\ 0)$ che non soddisfa più l'equazione di d'alembert._
Quindi, sulle onde meccaniche mi salta il principio di relatività galileiana. QUesto è perchè io ho _un mezzo_ su cui girano le odne, e tutti i calcoli li devo fare considerando questo mezzo come se fosse fermo.
Ora ho un problema: mentre per le onde meccaniche appunto possiamo scegliere il mezzo, per altre onde (em) non c'è un mezzo privilegiato a cui riferirsi (viaggiano nel vuoto). Questa cosa porterà a dei problemi...

##### parametro velocità
![[../File/todo da lezione 6/Pasted image 20220302095137.png]]
Vediano se questa cosa ci torna.
Noi possiamo avere corde con velocità lineare molto picocla (fili da pesca) oppure molto grossa (gomene delle navi) (OSS: per questo esempio, osservo che la densità _volumetrica_ di queste due corde è uguale (per ogni corda). La grandezza della corda, va ad influire sulla _densità lineare_. Per questo, a partià di materiale, una corda più grossa avrà densità lineare più grande). Più è piccola la densità lineare di massa, maggiore sarà la velocità. Questo perchè essenzialmente, se la massa è poca, con poca energia riesco a mettere in moto. Se la corda è massiccia ho bisogno di molta più eneargia, che impiegherà più tempo a trasferirsi.
Osservo anche che, più è tesa la corda, più le onde vanno veloci. (più è tesa, più è facile trasportare un'oscillazione da un punto a quello successivo della corda).

Ultimo argomento: eq alembert è lineare e omogenea: vale principio di sovrapposizione.
Posso quindi prendere tante belle funzioni di s o w, metterle assieme e trovare sempre una soluzione per l'eq di di'alembert.

Vediamo un esempio di cosa succede prendendo un'onda progressiva e un'onda regressiva che si incontrano:
https://www.desmos.com/calculator/c6gqrij9eb

