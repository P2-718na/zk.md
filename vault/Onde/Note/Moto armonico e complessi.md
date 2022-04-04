#cleanme
Concettualmente, i [[../../Metodi/Note/Numeri complessi|numeri complessi]] sono molto utili nel caso in cui ci siano equazioni differenziali con soluzione sinusoidale: lavorando in $\mathbb{C}$, infatti, queste soluzioni diventano algebriche (lineari).

`APPL` __In fast__: praticamente per usare sta roba pluggo in $Ae^{i\phi}$ le equazioni del moto ($A$ = ampiezza, in $\phi$ ci metto l'argomento del coseno) e prendo la parte reale. Derivare equivale a moltiplicare per $i\omega_0$, integrare equivale a dividere per la stessa quantità.

### Moto armonico dato da un numero complesso
In particolare, la [[../../Metodi/Note/Formula di Eulero|notazione esponenziale]] ci aiuta, perchè si può dimostrare che _il moto armonico è descritto dalla parte reale di un numero complesso_. Vediamo come:
1. Partiamo da un numero complesso $z$ con una ampiezza $A$ e fase $\phi$ (funzione lineare rispetto al tempo):
$$
z(t) = Ae^{i\phi} = Ae^{i(\omega_0+\phi_0)}
$$
2. Osservo che _se vado a studiare la [[../../Metodi/Note/Numeri complessi#DEF Parte reale e immaginaria di un complesso|parte reale]] di questo numero complesso, trovo proprio la legge oraria di un moto armonico_. (Infatti, in questo caso, la parte reale è proprio data da $Acos(\omega_0 t + \phi_0)$)
![[todo moto armonico come parte reale di complesso.png]]
con $A_c := Ae^{i\phi_0}$ ampiezza complessa.

`OSS` Non farti mindfuckare troppo da questa cosa. Se prendi l'equazione dell'oscillatore armonico, le soluzioni che ottieni sono proprio reali (non "reali con parte immaginaria troncata") e il fatto che la famiglia delle soluzioni sia $A\cos{\omega t + \varphi_0}$ p determinato dalle condizioni iniziali (la parte $\sin$, che comunque _è reale_, viene tolta dalla scelta dei coefficienti fissando le condizioni iniziali, equivalenti per tutti gli oscillatori armonici).

### Comodità nell'utilizzo dei complessi
La cosa bella è che se prendo z(t) e la derivo rispetto al tempo...
![[todo derivazione complesso.png]]
questo $iw_0 \cdot z$,  è proprio una velocità nel campo complesso, che posso trovare semplicemente _moltiplicando, e non derivando_. Stessa cosa se vado ad integrare:
![[todo integrazione complesso.png]]

Riassumento:
![[todo deriv int complesso.png]]

In generale, un oggetto di questo tipo (ovvero, un vettore rotante) prende il nome di [[Vettori rotanti (fasori)|fasore]].
#lezione