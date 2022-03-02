#cleanme
![[Pasted image 20220221152915.png]]
Andiamo a vedere nel caso meccanico: Prendiamo una forza _posizionale_ arbitraria.
![[Pasted image 20220221153018.png]]
^^vv prendiamo un punto di equilibrio (ovvero, punto dove la forza vale 0):
![[Pasted image 20220221153109.png]]
In particolare, per il [[Teorema di Rolle]] almeno uno di questi due punti è di _equilibrio stabile_ (derivata prima cambia di segno per forza, visto che $f$ continua e $f(A) = f(B) = 0$):
![[Pasted image 20220221153138.png]]
^^ In A il gradiente della forza è negativo, quindi è _stabile_. ==> Vicino al punto A, quindi, 
_io posso scrivere la mia forza posizionale usando una serie_. 

Espando la mia forza generica usando la [[Serie di Taylor]]
![[Pasted image 20220221153357.png]]
E osservo che il primo termine è un numero (derivata prima valutata in $x_A$) moltiplicato per un $\Delta x$, che corrisponde proprio alla [[Forza di Hooke|Legge di Hooke]]
![[Pasted image 20220221153714.png]]

##### Esempio: pendolo fisico:
![[Pasted image 20220221153737.png]]
per descrivere questo sistema, vado ad usare la seconda equazione cardinale dei sistemi. Mi piazzo nel punto di vincolo del mio sistema e considero le forze dei momenti angolari. Il mio punto di vincolo è Oxy
![[Pasted image 20220221154021.png]]
Agisce la forza peso P, la componente verso il basso dipende dall'angolo theta => faccio tutti i conti per trovare il momento delle forze esterne $\vec M_{est}$... Il momento si calcola con la formuletta:
![[Pasted image 20220221154121.png]]
Ora abbiamo il rpoblma che la formula totenuta non è lineare (c'è un seno). Tuttavia, se le oscillazioni sono piccole, possiamo usare l'osservazione fatta a inizio pagina e approssimare $sen(\theta) = \theta$. In questo modo troviamo un'espressione lineare:
![[Pasted image 20220221154135.png]]
