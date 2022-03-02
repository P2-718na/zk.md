#lezione 
### Oscillatore armonico
Parto prendendo un punto materiale, sottoposto ad una [[Forza di Hooke|Forza di Hooke]]:
![[legge di hooke.png]]
Applicando il primo principio della dinamica, ho che:
$$
\left\{
    \begin{array}{l}
    F &= -kx \hspace 50px &\text{Legge di Hooke}\\
    F &= m \ddot x &\text{II principio della dinamica}
    \end{array}
\right.
$$
La soluzione di questo sistema (ottenuta sostituendo F) è data da
$$
m\ddot x + kx = 0
$$
Dividendo ambo i membri per $m$, si ottiene:
#### `DEF` Formula dell'oscillatore armonico
$$
\ddot x + \omega_0^2 x = 0
$$
dove si è definita:
##### `DEF` Pulsazione
$$
\omega_0 := \sqrt\frac{k}{m}
$$
Questa è detta **formula dell'oscillatore armonico**. Tutti gli oscillatori armonici la rispettano.
`OSS` L'oscillatore armonico è di importanza fondamentale, visto che _qualsiasi moto periodico può essere ricondotto ad una combinazione di moti oscillatori armonici_ (vedi: [[Serie di Fourier]]).

`OSS` #lezione
Per il moto armonico, è importante che ci sia il segno $(+)$  tra i due termini dell'equazione $m\ddot{x}$ e $kx$. Proprio per questo motivo, la pulsazione è definita con _una radice_, in modo da essere sempre positiva.

##### `THM` Equazioni del moto armonico
Un oscillatore armonico, segue questo andamento:
![[equazioni del moto armonico.png]]
Insomma, ogni volta che ho un'equazione del tipo [[#DEF Formula dell'oscillatore armonico|visto sopra]], il moto è _periodico_ e _limitato_.

`OSS` Queste forme si ricavano risolvendo l'[[EDO]] dell'oscillatore armonico. La teoria, quindi, ci dice che qualunque quazione del tipo $\ddot x + \omega_0^2 x = 0$ ha associata una soluzione del tipo $x(t) = Acos(\omega_0 t + \varphi_0)$.
