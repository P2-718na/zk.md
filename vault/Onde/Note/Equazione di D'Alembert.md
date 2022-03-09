#### `THM` Equazione d'Alembert
![[../File/Equazione di D'Alembert.png]]
Rappresenta l'equazione per un'onda che si muove in uno spazio unidimensionale con velocità v.

La domanda è: è un'equazione lineare? SÌ.

### Caratteristiche generali
Questa equazione è in due coordinate (tempo, spazio), unidimensionale, [[EDO]] alle derivate seconde, lineare ed omogenea:
![[../File/todo da lezione 6/Pasted image 20220302091416.png]]
![[../File/todo da lezione 6/Pasted image 20220302091508.png]]
La perturbazione avviene rispetto a questa soluzione \xi = 0
![[../File/todo da lezione 6/Pasted image 20220302091550.png]]
Associato a questo equazione c'è anche un concetto di operatore lineare, dato da:
![[../File/todo da lezione 6/Pasted image 20220302091610.png]]
E visto che l'eq è omogenea, posso riscrivere l'eq nella forma
![[../File/todo da lezione 6/Pasted image 20220302091652.png]]
^^ Vedremo che questa notazione sarà utile più avanti (con operatori diversi e sistemi più complicati).
_lineare_: se qualcuno mi da due soluzioni _linearmente indipendenti_, la loro somma è una soluzione dell'equazione di d'Alembert (vale il principio di sovrapposizione).
("se in questa stanza siamo in due a parlare, tutti e due sentono almeno due voci").

_alle derivate seconde_:
come faccio a trovare una particolare soluzione? Se io mi fisso su un punto x (non vado a considerare l'intera corda), quel punto fa certe oscillazioni. Per descrivere completamente il moto del punto, avrò bisogno delle sue posizioni iniziali (posizione e velocità). Devo ripetere, concettualmente, la stessa cosa su tutti i punti, quindi:
![[../File/todo da lezione 6/Pasted image 20220302092009.png]]

### Soluzioni
proviamo a vedere quali sono le soluzioni. Ricordo che siamo nello spazio delle funzioni di due variabili.
cerchiamo una $\xi(x,\ t)$ che risolva l'eq. di d'alembert.

Siamo fortunati, perchè per questa equazione, esistono combinazioni di spazio e tempo che danno soluzioni facili. In particolare, sono interessanti (si pul dimostrare, vedremo):
![[../File/todo da lezione 6/Pasted image 20220302092309.png]]
(guarda caso, s e w sono combinazioni lineari delle due coordinate x e t).
Si riesce a far vedere che una _qualunque funzione di x - vt_ è soluzione per l'eq d'alembert.
![[../File/todo da lezione 6/Pasted image 20220302092345.png]]
Anche x + vt è soluzione.
In questo modo, sono passato da funzioni di due parametri a due funzioni in una sola variabile: f(s), g(w).
Per puntualizzare, f(x +/- vt) deve essere _continua e derivabile due volte_ (visto che l'edo è alle derivate seconde).

Dimostriamo ora che f, come definite prima, è sempre soluzione (per casa, dimostra g).
Partiamo da questo:
![[../File/todo da lezione 6/Pasted image 20220302092643.png]]
Parto da questa f(s), dove s è una combinazione lineare di due variabili.
Sistemo prima il primo membrp
parto considerando le variabili rispetto allo spazio:
![[../File/todo da lezione 6/Pasted image 20220302092734.png]]
Usando la regola della catena per funzioni composte. Osservo che in realtà
![[../File/todo da lezione 6/Pasted image 20220302092825.png]]
quindi, la mia derivata di xi diventa:
![[../File/todo da lezione 6/Pasted image 20220302092837 1.png]]
(la mia derivata parziale, in realtà è una derivata totale).
Ora faccio anche la derivata seconda:
![[../File/todo da lezione 6/Pasted image 20220302092912.png]]
Qui faccio la stessa cosa. Uso la regola della catena.
Ottengo:
![[../File/todo da lezione 6/Pasted image 20220302093013.png]]
Ora sistemo il secondo membro:
![[../File/todo da lezione 6/Pasted image 20220302093031.png]]
QUi ho una situazione simile, ma de esse su de t vale (considerando l'espressione di s)
![[../File/todo da lezione 6/Pasted image 20220302093056.png]]
Quindi, ottengo:
![[../File/todo da lezione 6/Pasted image 20220302093104.png]]
Ora ripeto, devo calcolare la derivata seconda...
![[../File/todo da lezione 6/Pasted image 20220302093139.png]]
E anche qui rimarrà un -v dato dalla derivata della funzione composta:
![[../File/todo da lezione 6/Pasted image 20220302093231.png]]
Ora ho finito, posso riscrivere la funzione di d'alembert mettendoci dentro le due derivate f'' che ho appena calcolato (al posto di dxi/dx e dxi/dt):
![[../File/todo da lezione 6/Pasted image 20220302093316.png]]
Vedo che f'' (appatto che esista), soddisfa sempre l'eq alembnert.
(Esercizio: dimostra che anche g(x + vt) è soluzione).

Ricapitolando:
![[../File/todo da lezione 6/Pasted image 20220302093456.png]]
f, g sono soluzioni, la loro combinazione lineare sarà anch'esse soluzioni.
Abbiamo quindi "spacchettato" la nostra soluzione in due famiglie (quella col + e quella col -).
Le due vengono chiamate:
![[../File/todo da lezione 6/Pasted image 20220302093546.png]]
(nel senso che "progredisce" lungo una certa direzione del'asse x)
![[../File/todo da lezione 6/Pasted image 20220302093601.png]]
Una generica onda, è fatta da un pezzo di onda progressiva e un pezzo di onda regressiva. Poi, in base alle circostanze, può apparirne una sola o tutte ee due...
