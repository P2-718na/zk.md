##### `DEF` Sistema dinamico
Genericamente, un `sistema dinamico` è un qualsiasi _processo evolutivo_, ovvero una struttra caratterizzata da:
- Uno [[spazio delle fasi]] $\Sigma$
- Il _tempo_ $t$ (parametro che può assumere valori in $\mathbb{R}$, $\mathbb{R}^+$, $\mathbb{Z}$, $\mathbb{Z}^+$)
- Una [[legge di evoluzione]]
Praticamente, _un sistema dinamico è un qualsiasi modello matematico che descrive l'evoluzione nel tempo di un sistema fisico_.

#### Assunzioni
In particolare, i [[#DEF Sistema dinamico|sistemi dinamici]] di cui tratteremo, si baseranno sulle seguenti assunzioni:
1) [[#^55f5db|Determinismo]]*
2) Dimensione finita, ovvero _ciascuno stato del sistema può essere individuato da un numero finito di parametri_
3) Differenziabilità, ovvero _lo spazio delle fasi possiede la struttura di una varietà differenziabile che è conservata dalla legge di evoluzione_.
4) "[[#^7adb31|Il cammello]]"*

1) => $\varphi^s \circ \varphi^t = \varphi^{t+s}(x)$ per ogni coppia di tempi $t$, $s$ ed ogni $x \in S$. ^55f5db
4) => Deve esistere una [[misura]] completa e invariante. Concettualmente, questo vuol dire che se ho un certo volume, questo deve rimanere costante nel tempo. #lezione ^7adb31