Le `variabili azione-angolo` costituiscono un [[../../Analisi 2/Calcolo integrale/Cambiamento di variabile|cambiamento di variabile]] molto utile per studiare sistemi _nell'intorno di un punto ellittico_ (o meglio, le variabili AA hanno senso solamente quando le utilizziamo per un orbita _periodica_; per esempio, all'interno di una buca di potenziale. In generale, per lo studio di ogni sistemi, si procede appunto "_a pezzi_", studiando localmente il sistema nei punti che ci interessano. #lezione)

#### `DEF` Azione
Per un sistema 1-dimensionale, con $H$ [[Integrale primo del moto|integrale primo]], e $H=E$ [[curva di livello]],  si definisce `azione` $I :=$
$$
I := \frac 1 {2\pi}\oint_{H=E}
    p\ dr
$$
`OSS` Il termine $\frac 1 {2\pi}$ lo metto perché è il periodo di un angolo. #lezione
`OSS` L'integrale nella definizione di $I$ corrisponde all'area sottesa da una certa orbita ed _è funzione solo dell'energia_. ( #appunti 54, questa cosa è da controllare perché io negli appunti di lezione ho scritto roba leggermente diversa ) Di conseguenza, posso scrivere:
$$
I = \frac {A(E)}{2\pi}
$$

`OSS` Possiamo ricavare $p$ dall'[[Integrale primo del moto]], (come abbiamo visto in [[Studio di un sistema generico#Simmetria rispetto all'asse x|studio di un sistema generico]]) ed esprimere $I$ come:
$$
I = \frac 1 {2\pi}\oint_{H=E}
    \sqrt{2m[E-V(r)]}\ dr
$$

#### `DEF` Angolo
Accoppiata con l'azione, si definisce la variabile `angolo` $\theta$ $:=$
$$
\theta := \frac \partial {\partial I}
\oint_{H=E}^{\bar r}
    p\ dr
$$
ricavando $p$ (come per l'azione), $\theta$ diventa:
$$
\theta = \frac \partial {\partial I}
\oint_{H=E}^{\bar r}
    \sqrt{2m[E-V(r)]}\ dr
$$
`OSS` Questa definizione tiene conto della necessità di [[Flusso di fase#^f703dc|conservare le aree]] nello spazio delle fasi.
