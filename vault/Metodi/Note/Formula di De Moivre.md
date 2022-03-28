### Formula di De Moivre
La formula di De Moivre deriva direttamente dalla [[Formula di Eulero]]. È molto utile per calcolare seni e coseni dei multipli di un angolo (o, equivalentemente, di esprimere seni/coseni di multipli di un angolo come un polinomio in seno/coseno):
$$
cos(n\theta) + i\ sen(n\theta) =
e^{in\theta} =
\left(e^{i\theta}\right)^n =
[cos(\theta) + i\ sen(\theta)]^n
$$
`DIM` Volendo, si può dimostrare anche per induzione, usando le [[../../../Analisi 1/Note/Formule trigonometriche/Formule di addizione e sottrazione]].

`ESEMPIO`:
Vogliamo esprimere $cos(3\theta)$ come polinomio di coseni. Partiamo da
$$(cos\theta + i\ sen\theta)^3$$
sviluppiamo esplicitamente i calcoli
$$(cos\theta + i\ sen\theta)^3 =
cos^3\theta + 3i\ cos^2\theta\ sen\theta - 3cos\theta\ sen^2\theta + i\ sen^3\theta
$$
a sinistra applichiamo De Moivre, a destra raccogliamo $i$
$$
cos(3\theta) + i\ sen(3\theta) =
cos^3\theta - 3cos\theta\ sen^2\theta + i(3\ cos^2\theta\ sen\theta + sen^3\theta)
$$
e per finire, eguagliamo parte reale e parte complessa e applichiamo l'[[Identità fondamentale]]:
$$
\left\{ 
\begin{array}{l}
    cos(3\theta) &= cos^3(\theta) - 3cos(\theta)sen^2(\theta) &=
        4cos^3(\theta) - 3cos(\theta)\\
    sen(3\theta) &= 3cos^2(\theta)sen(\theta)-sen^3(\theta) &=
        -4sen^3(\theta) + 3sen(\theta)\\
\end{array}
\right.
$$
.