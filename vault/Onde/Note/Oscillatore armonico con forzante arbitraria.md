
### _Il ferrarino della matematica_
La necessità di sviluppare in _serie di Fourier_ deriva (almeno per noi) dal problema delle [[Oscillazioni forzate semplici|oscillazioni forzate]]:
$$
m \ddot x + \beta \dot x + kx = f(t) \hspace 10px \iff \hspace 10 px \hat L(x) = f(t)
$$
Vogliamo risolvere un'equazione di questo genere con una _forzante arbitraria_, posto il fatto che $\hat L$ è un [[Operatori lineari|operatore lineare]] e ha tutte le proprietà del caso.

Noi sappiamo risolvere questa equazione ora per forzanti semplici (vedi: [[Oscillazioni forzate semplici]]) (forza costante, forza oscillatoria, somma di forzanti che sappiamo già gestire). Per risolvere questo problema per forzanti arbitrarie dobbiamo procedere in due passi:
1) Consideriamo una $f(t)$ _periodica_ di periodo $T$. Vogliamo cercare un modo di risolvere una _qualsiasi_ equazione che contiene una forzante di questo tipo.
2) Una volta che abbiamo risolto il punto (1), possiamo estendere lo stesso principio risolutivo a tutte le funzioni (abbastanza regolari), facendo tendere il periodo $T$ all'infinito.

##### (1)
Ora, per risolvere il punto (1), abbiamo anche qui due passaggi:
    1.1) Prima di tutto, vediamo come [[Moto con forzante data da somme di coseni|trattare una funzione formata da somme arbitrarie di seni e coseni]].
    1.2) Applichiamo il [[Serie di Fourier|Teorema di Fourier]].

In questo modo sappiamo risolvere il problema dell'oscillatore armonico forzato per qualunque tipo di forzante _periodica_. Quello che dobbiamo fare è semplicemente trovare i coefficienti $a_0$, $a_n$ e $b_n$ della serie in modo da ottenere lo sviluppo corretto per la nostra funzione.

##### (2)
Per spiegare questo caso, parto con due osservazioni:

`OSS` Nel caso in cui abbiamo 
$$
m \ddot x + \beta \dot x + kx = f(t)
$$
dove f è una funzione arbitraria, non posso semplicemente sostituire $e^{\lambda t}$ in $x$ e risolvere con gli stessi metodi usati per le [[Oscillazioni forzate semplici]] e [[Oscillazioni con forzante periodica - soluzione particolare]].

`OSS` Tutti i problemi che andremo a studiare, generalmente, avranno un dominio (tempo di osservazione, insomma) _finito_. Possiamo quindi immaginare che il fenomeno in questione sia periodico con periodo _maggiore al mio tempo di osservazione_. 
Quello che faccio, allora, è considerare una funzione periodica di _periodo $T$ tendente a infinito_.

Con queste premesse, si può dimostrare che il [[Serie di Fourier|Teorema di Fourier]] ci è utile anche qua. I passaggi per risolvere questo tipo di problema sono:
    2.1) Applichiamo l'operatore [[Trasformata di Fourier]] $\tilde{\mathcal F}$ a entrambe i membri dell'equazione.
    2.2) In questo modo, a sinistra potremo raccogliere un $\tilde x$ (questo è reso possibile dal fatto che con la trasformata, derivazioni si trasformano in moltiplicazioni).
    2.3) Applichiamo l'[[Trasformata di Fourier|antitrasformata di Fourier]] a $\tilde x$ e abbiamo trovato la $x(t)$ cercata.

Nel dettaglio, il punto (2.2) si concretizza in:
- Parto da qui: $m \ddot x + \beta \dot x + kx = f(t)$
- Risolvo prima il primo membro, applicando l'operatore $\tilde{\mathcal F}$:
    - $\tilde{\mathcal F}(m \ddot x + \beta \dot x + kx)$
    - Applico le proprietà degli operatori lineari a $\tilde{\mathcal F}$:
    - $\tilde{\mathcal F}(m \ddot x + \beta \dot x + kx) = m\tilde{\mathcal F}(\ddot x) + \beta \tilde{\mathcal F}(\dot x) + k \tilde{\mathcal F}(x) = (\cdots)$
    - dove ho usato la linearità di $\hat{\mathcal{F}}$. Continuo ad espandere, usando le [[Trasformata di Fourier#Proprietà della trasformata|proprietà della trasformata]]:
    - $(\cdots) = -m\omega^2 \tilde x + i \omega \beta \tilde x + k\tilde x = (\cdots)$
    - raccolgo $\tilde x$:
    - $(\cdots) = (-m \omega^2 + i \omega \beta + k) \tilde x$
- Risolvo il secondo membro
Per il secondo membro, la trasformata la chiamo $\tilde{\mathcal{F}}$. Quindi, ottengo questo:
![[../File/arb 1.png]]
Mettendo assieme i due membri, ho:
![[../File/arb 2.png]]
Da questa equazione, posso risolvere tranquillamente per $\tilde x$:
![[../File/arb 3.png]]
In questo modo, __abbiamo trovato la trasformata di Fourier della soluzione__. E sono contento, perché dopo posso applicare l'_antitrasformata_ e trovare finalmente la mia soluzione particolare:
![[../File/arb 4.png]]
