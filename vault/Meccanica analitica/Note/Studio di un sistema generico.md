### Studio di un sistema generico
Supponiamo di avere un _campo di forze conservativo_ generico, agente su un _punto materiale_ di massa $m$.
Un sistema di questo tipo ammette integrale primo (vedi: [[Integrale primo per il campo di Newton]]), dato da:
$$
H(r,\ p) = \frac 1 2 \frac {p^2} m + V(r)
$$
dove $V(r)$ è un potenziale di tipo variabile (in base al sistema).

##### Studio delle curve di livello
Ora studiamo le curve di livello di $H$. Fissiamo quindi un valore $H(r,\ p) = E$ (con $E$ determinato dalle condizioni iniziali del mio sistema).
In questo modo, otteniamo delle curve di livello date da:
$$
E = \frac 1 2 \frac {p^2} m + V(r)
$$

##### Simmetria rispetto all'asse $x$
Partiamo ricavando $p$ dall'equazione sopra:
$$
p = \pm \sqrt{2m[E-V(r)]}
$$
Questo ci permette di osservare che __tutte le curve di livello sono simmetriche rispetto all'asse $r$__. Possiamo quindi studiare il sistema solamente nel semiasse positivo delle $p$. (E questa osservazione resta valida _per tutti i sistemi dinamici di questo tipo_, indipendentemente dalla forma del potenziale).

##### Ricavare i punti fissi
Procediamo, usando la definizione di [[Punti fissi|punto fisso]] (vogliamo trovare le soluzioni che _non_ dipendono dal tempo, e che quindi annullano il campo vettoriale):
$$
\left\{
    \begin{array}{l}
        \dot x = 0 \\
        \dot p = 0
    \end{array}
\right .
$$
Ricordando che stiamo lavorando con il [[Campo di Newton]], si ottiene quindi:
$$
\left\{
    \begin{array}{l}
        \frac p m = 0\ (\implies p = 0) \\
        - \frac {\partial\ V} {\partial r} = 0
    \end{array}
\right .
$$
Questo sistema ci da due informazioni importanti:
1) __Tutti i punti fissi del sistema giacciono sull'asse $r$__.
2) __I Punti fissi corrispondono ai punti critici del potenziale__.

##### Studio del sistema in un intorno di un punto fisso
Da qui in poi direi che va bene continuare sugli appunti. Vedi ance, come esempio: [[potenziale cubico.ipynb]]
#todo