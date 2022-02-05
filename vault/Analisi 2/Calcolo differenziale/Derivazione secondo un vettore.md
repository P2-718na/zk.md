Essenzialmente, saper derivare in $\mathbb{R}$ significa saper fare una derivata _a meno di un fattore di scala legato alla scelta del [[vettore base]]_. Questa nozione, ci permette di estendere il concetto di derivata anche a derivata _rispetto_ a un vettore.

##### `DEF` Derivata rispetto ad un vettore
$X, Y\ \ \mathbb{K}$-[[Spazio normato|spazi normati]] con $X$ [[Insieme aperto|aperto]], $f: X \rightarrow Y$ funzione, $p, \vec{u} \in X$, $t \in \mathbb{K} \setminus \{0\}$. La `derivata di f in p rispetto al vettore u` è definita come $:=$
$$
D_\vec{u} f(p) = \lim_{t\rightarrow0} \frac{f(p+t\vec{u})-f(p)}{t}
$$
se tale limite esiste. In simboli:
$$
D_\vec{u} f(p) \hspace{20px} \equiv \hspace{20px} \partial_\vec{u}f(p) \hspace{20px} \equiv \hspace{20px} \frac{\partial f}{\partial \vec{u}}(p) 
$$
`NOTA` $p, \vec{u}$ appartengono allo stesso insieme, quindi sono entrambi [[vettori]]. La freccia è indicata solo sopra ad $\vec{u}$ per accentuare il fatto che stiamo _derivando rispetto ad un vettore_.

`OSS` La richiesta di $X$ [[Insieme aperto|aperto]] in realtà si potrebbe semplificare in "$p$ è interno all'insieme" oppure, ancora più restrittivo, "$p$ è [[di accumulazione]] per l'intersezione della retta con $X$". Il motivo è che, per poter valutare il [[limite]] nella definizione, dobbiamo poter trovare punti infinitamente vicini a $p$ lungo la direzione di $\vec{u}$, ma distinti da $p$.

`OSS` $\vec{u} = 0 \implies \partial_\vec{0}f(p) = 0$

`PROP` Se esiste la derivata direzionale rispetto ad un vettore $\implies$ esiste per tutti i multipli di quel vettore ed è il multiplo della derivata originale. #deepen  (de marco 217)

`NOTA` Se ci troviamo in $\mathbb{R}^n$, le [[Derivazione secondo un vettore#DEF Derivata rispetto ad un vettore|derivate direzionali]] rispetto ai vettori della [[base canonica]] si indicano semplicemente con $\partial_kf(p)$, con $1 \leq\ k\ \leq n$.

##### `PROP` Derivata parziale
La `derivata parziale di f rispetto alla k-esima variabile` è la [[derivata]] in $p_k$ della funzione, mantenendo costanti tutte le altre variabili.
Questo vale in $\mathbb{R}^n$, fissata la [[base canonica]]. ^099555