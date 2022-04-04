### Complessi come estensione dei reali
La necessità di introdurre i numeri complessi deriva dal voler trovare le soluzioni dell'equazione:
$$x^2 = -1$$
Sappiamo che non esistono numeri reali che la soddisfano. Introduciamo quindi il concetto di $i$, ovvero un "numero" il cui quadrato è negativo:
##### `DEF` Unità immaginaria
$$i^2 := -1 $$
algebricamente, $i$ si comporta proprio come se fosse una costante. Segue tutte le proprietà per le costanti reali, l'unica differenza è che il suo quadrato vale $-1$.

A questo punto possiamo fare un passo avanti, e definire un `numero complesso` $z$:
##### `DEF` Forma algebrica di un complesso
$$z:=a+ib\ \ \ \ a,\ b \in \mathbb{R}$$

Sono immediate le definizioni di:
##### `DEF` Parte reale e immaginaria di un complesso
Dato $z = a + ib$ [[#DEF Numeri complessi definizione operativa|numero complesso]], si definisce `parte reale di z` $:\Leftrightarrow$
$$Re(z) := a$$
e `parte immaginaria di z` $:\Leftrightarrow$
$$Im(z) := b$$
### Complessi come coppia ordinata
Si può dare una definizione "più formale" dei complessi.
##### `DEF` Insieme $\mathbb{C}$
$$
\mathbb{C} := \mathbb{R} \times \mathbb{R} \equiv \{(a,\ b)\ \lvert\ \in \mathbb{R} \}
$$
Si osserva quindi, che un numero complesso è di fatto una coppia ordinata di numeri reali. In particolare, si dimostra che l'insieme $\mathbb{C}$ è un [campo](https://it.wikipedia.org/wiki/Campo_(matematica)), definite le operazioni di somma e prodotto in questo modo (dimostrazioni banali, date le definizioni):

##### `DEF` Somma tra complessi
$$
(a,\ b) + (c,\ d) := (a+c,\ b+d)
$$
##### `DEF` Prodotto tra complessi
$$
(a,\ b)(c,\ d) := (ac-bd,\ bc + ad)
$$

`OSS` Definite in questo modo le operazioni tra complessi, osserviamo che i complessi (come coppia ordinata) si comportano proprio _allo stesso modo_ dei complessi (algebrici). In particolare, vale:
$$
(0, 1)\cdot(0, 1) = (1, 0) \hspace{20px} \equiv \hspace{20px} i^2 = -1
$$

### Altre proprietà dei complessi
##### `DEF` Complesso coniugato
Dato $z = a + ib$ complesso, si definisce `complesso coniugato di z` $:\Leftrightarrow$
$$\overline{z} := a - ib$$
`PROP` Segue subito che:
$$z \cdot\overline{z} = (a^2 + b^2)$$  (e osservo che questo ci da un numero _reale e positivo_).

##### `DEF` Modulo di un complesso
Dato $z$ complesso, si definisce `modulo di z` $:\Leftrightarrow$
$$|z| := \sqrt{z*\overline{z}} \equiv \sqrt{a^2+b^2}$$

##### `PROP` Inverso di un complesso
Si ricava attraverso una costruzione algebrica:
Dato $z = a+ib$, ho che:
$$
z^{-1}= \frac{1}{a+ib} = \frac{a - ib}{a^2 + b^2} \equiv \frac{\overline{z}}{|z|^2}
$$
dove ho moltiplicato e diviso per il [[#DEF Complesso coniugato|coniugato]] di z.

`OSS` Con la nozione di [[#DEF Complesso coniugato|coniugato]] e [[#PROP Inverso di un complesso|inverso]], ho un modo per calcolare [[#DEF Parte reale e immaginaria di un complesso|parte reale e immaginaria]] di un complesso, senza dovermi affidare alla notazione algebrica: ^b739d5
$$
\begin{aligned}
Re(z) &= \frac{z+\overline{z}}{2} \\
Im(z) &= \frac{z-\overline{z}}{2i} \\
\end{aligned}
$$

##### `PROP` Disuguaglianza triangolare
Si dimostra che vale:
$$
|z_1 z_2| = |z_1| |z_2|
$$
e (diseg. triangolare):
$$
|z_1 + z_2| \leq |z_1| + |z_2|
$$
`DIM`: basta applicare la definizione di modulo ed elevare al quadrato (due volte) membro/membro. (posso elevare visto che per def. di modulo tutti i membri sono positivi; in mezzo ai passaggi bisogna rimuovere termini uguali da entrambe i lati).

##### `DEF` Esponenziale di un complesso
Vedi: [[Formula di Eulero]]

### Rotazioni nel piano
Si osserva che, dato un numero complesso $z$, la sua moltiplicazione per un altro complesso di modulo $1$, corrisponde ad una _rotazione sul piano di Argand-Gauss_:
$$
z = \rho\ e^{i\theta}\hspace{20px} w = e^{i\varphi}
$$
$$
z \cdot w = \rho\ e^{i(\theta + \varphi)}
$$


Continua: [[Altre rappresentazioni dei complessi]]
Continua: [[Formula di Eulero]]

#youmath https://www.youmath.it/lezioni/analisi-matematica/numeri-complessi/2697-definizione-di-numero-complesso.html
#lezione