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

Per le proprietà degli [[Onde/Note/Operatori lineari]], possiamo risolvere questa [[EDO]]  cercando
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