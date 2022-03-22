Molti sistemi fisici sono caratterizzati dalla presenza di una [[forzante]]. Quando questo è il caso, il [[Campo vettoriale associato a un flusso di fase|campo vettoriale]] associato _non è più esprimibile tramite un sistema lineare_ (vedi: [[FDF associato a un sistema lineare omogeneo]]).
La forma generica di un _campo vettoriale con forzante_ sarà infatti del tipo:
$$
\dot x = Ax + f(t)
$$
La soluzione (particolare) per questo tipo di sistema è data dalla funzione:
$$
x(t) = e^{At} x_0 +  \int_0^t{
    f(s) \cdot e^{A(t-s)}\ ds
}
$$
(ricordo che $f(s)$ è la forzante. $s$ è una variabile che emerge dal cambio di variabile utilizzato per arrivare a questa soluzione).
(vedi anche: [[FDF di un sistema forzato, metodo pratico]]).

`OSS` #appunti Questo integrale viene detto _integrale di convoluzione_. È molto importante per la Teoria d'Informazione.

`DIM` #todo appunti 23/24