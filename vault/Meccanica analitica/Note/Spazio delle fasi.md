#wikipedia
##### `DEF` Spazio delle fasi
Si chiama `spazio delle fasi di un sistema con n gradi di libertà` lo spazio i cui punti rappresentano univocamente _tutti e soli i possibili stati del sistema_.
Di fatto, se la $n$-upla $(q_1,\ \ldots,\ q_n)$ rappresenta uno [[spazio delle configurazioni]], il corrispondente _spazio delle fasi_ è rappresentato dalla $n$-coppie $\left((q_1,\ p_1)\ \ldots,\ (q_n,\ p_n)\right)$.

#turchetti 24
`APPL` Se uno stato di un sistema a $N$ particelle è rappresentato da $3N$ g.d.l (vettori posizione) + $3N$ g.d.l (vettori velocità), lo spazio delle fasi del sistema è semplicemente il prodotto diretto dello spazio delle configurazioni $3N$-dimensionale per lo spazio delle velocità $3N$-dimensionale. In questo esempio, un vettore $\vec{x}$ dello spazio delle fasi è rappresentato da:
$$
\vec{x} = 
\begin{pmatrix}
    x_1 \\
    v_1 \\
    \vdots \\
    x_{3N} \\
    v_{3N}
\end{pmatrix}
$$
per dare un esempio concreto (s.d.f $2N$ dimensionale):
![[esempio spazio delle fasi.png]]

`OSS` #lezione Tuttavia, quando si parla di _spazio delle fasi_, è opportuno associare ad ogni punto dello [[spazio delle configurazioni]] un _momento_, e NON una velocità.

`OSS` #lezione la forza di Newton è una [[EDO]] alle derivate _seconde_. Se fosse stata alle derivate _prime_, per descrivere la dinamica dei sistemi, non sarebbe stato necessario associare uno spazio delle fasi allo spazio delle configurazioni. Visto che è alle derivate seconde, però, c'è questa necessità.