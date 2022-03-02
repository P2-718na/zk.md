
### Serie di fourier, introduzione
_"Il ferrarino della matematica"_

La necessità di sviluppare in _serie di Fourier_ deriva (almeno per noi) dal problema delle[[Oscillazioni forzate]]:
$$
m \ddot x + \beta \dot x + kx = f(t) \hspace 10px \iff \hspace 10 px \hat L(x) = f(t)
$$
Vogliamo risolvere un'equazione di questo genere con una _forzante arbitraria_, posto il fatto che $\hat L$ è un [[Operatori lineari|operatore lineare]] e ha tutte le prorpeità del caso.

Noi sappiamo risolvere questa equazione ora per forzanti semplici (vedi: [[Oscillazioni forzate]]) (forza costante, forza oscillatoria, somma di forzanti che sappiamo già gestire). Per risolvere questo problema per forzanti arbitrarie dobbiamo procedere in due passi:
1) Consideriamo una $f(t)$ _periodica_ di periodo $T$. Vogliamo cercare un modo di risolvere una _qualsiasi_ equazione che contiene una forzante di questo tipo.
2) Una volta che abbiamo risolto il punto (1), possiamo estendere lo stesso principio risolutivo a tutte le funzioni (abbastanza regolari), facendo tendere il periodo $T$ all'infinito.

Ora, per risolvere il punto (1), abbiamo anche qui due passaggi:
    1.1) Prima di tutto, vediamo come trattare una $f(t)$ formata da _somme arbitrarie di seni e coseni_.
    1.2) Applichiamo il [[Serie di Fourier|teorema di Fourier]].
    
In questo modo sappiamo risolvere il problema dell'oscillatore armonico forzato per qualunque tipo di forzante _periodica_. Quello che dobbiamo fare è semplicemente trovare i coefficienti $a_0$, $a_n$ e $b_n$ della serie in modo da ottenenre lo sviluppo corretto per la nostra funzione.

Riguardo al punto (1.1):
#cleanme
### Moto con forzante data da somme arbitrarie di coseni
Partiamo prendendo una funzione periodica con parametri liberi (questi parametri andranno poi a trasformarsi nei coefficienti della serie di fourier):
![[forzante sen cos 1.png]]
- Ogni singolo termine ha una sua ampiezza $F_n$.
- $\omega$ è la pulsazione associata (costante per tutti i termini).
- $n\omega$ vuol dire che vado a prendere come pulsazioni multipli interi di $\omega$.
- Aggiungo anche la possibilità di avere uno sfasamento delle diverse forze per i diversi $n$.

Osservo che questa funzione $f(t)$ è una somma di funzioni di periodo $T$, $\frac 1 2 T$, $\frac 1 3 t$, $\ldots$ 
E quindi, _complessivamente_, la posso vedere come funzione periodica di periodo $T$.

Ora, studiamo come risolvere il problema dove questa funzione è la _forzante di un oscillatore armonico_:
![[forzante sen cos 2.png]]

##### Divide et impera
`OSS` Ho un problema complesso che non so risolvere. lo separo in tanti problemi più piccoli che (magari) so risolvere più facilmente. Dopo metto tutto assieme e sbam sesso duro.$_{_\text{questo non lo tolgo perchè mi fa ridere}}$

Per le proprietà degli [[Operatori lineari]], possiamo risolvere questa [[EDO]]  cercando
![[forzante sen cos 3.png]]
In questo modo, per la proprietà (3) degli operatori lineari, la soluzione lineare sarà
![[forzante sen cos 4.png]]

Ora vado a vedere come risolvere ogni termine della sommatoria:
##### Ricerca delle soluzioni
La soluzione costante è facile [[Oscillazioni forzate]].
La soluzione oscillante è uguale a come abbiamo visto nelle [[Oscillazioni con forzante periodica]].

La soluzione non è particolarmente diversa da quello già visto. => (omettendo i conti), si ha:
![[forzante sen cos 5.png]]
. Se vado a fare un confronto dalla roba vista settimana scorsa, la differenz aè solo la fase e nw nelle formule. Tutto il resto è uguale.
Quando vado a prendere la soluzione, la soluzione reale è quindi:
![[forzante sen cos 6.png]]
(???) $x_n(t) = A_ncos(n\omega t + \phi_n - \delta_n)$

##### Rimozione delle fasi
Abbiamo visto che una forzante di questo tipo la risolviamo. Ora, vediamo come ricondurci alla stessa forma della serie di fourier, partendo da qua:
![[forzante sen cos 7.png]]
Si può eliminare le fasi, ottenendo:
![[forzante sen cos 8.png]]
Quando si preferisce usare seno e coseno piuttosto che una fase, si rinominano i vari coefficienti.
![[forzante sen cos 9.png]]

QUINDI, anche il problea iniziale divent riscritto come un oggetto fatto così:
![[forzante sen cos 10.png]]
(dovee sono andato a togliere le fasi dalla roba).
Se noi sappiamo risolvere questo prob, sappiamo risolvere anche questo:
![[forzante sen cos 11.png]]
^^ Insomma, quello che era il probl iniziale, lo sono andato a riscrivere tramite somme di coseni e seni.