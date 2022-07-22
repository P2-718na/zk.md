### Intensità di un'onda
$$
I = \frac{E(\Delta t)}{\Delta t} =
    \frac 1 {T_p} \int_0^{T_p} \mathcal{P}(x,\ t)\ dt =
    \langle \mathcal{P} \rangle = 
    \left< Z\left(\frac{\partial \xi (x,\ t)}{\partial t}^2 \right) \right>
$$
![[../File/todo da lezione 8/Pasted image 20220308104124.png]]
L'intensità è una quantità media, non una misura istante per istante. Questa formula è valida per utte le onde e le enti unidimensionali. I si misura in watt.
![[../File/todo da lezione 8/Pasted image 20220308104344.png]]
Per un'onda generica progressiva, invece:
![[../File/todo da lezione 8/Pasted image 20220308104533.png]]
bisogna scrivere la potenza usando la serie di fourier.
Se voglio l'intensità di questa roba, l'intensità sarà la media di questa potenza.: ![[../File/todo da lezione 8/Pasted image 20220308104611.png]]
Quando vado a sviluppare il calcolo dell'integrale, mi troverò dei seni * coseni, e robe simili. Quando vado a fare questo integrale (e ricordo che l'integrale lo devo valuitare su un peirodo, mi trovo in una situazione analoga allo studio che avevo fatto per le serie di Fourier).
Ormai abbiamo capito che la maggior parte di questi integrali saranno zero. Nel calcolo dell'integrale sopravvivono solo e soltanto pochi termini. Quelloi che siopravvivono sono solamente: (skippando i conti, si ottneien questo)
![[../File/todo da lezione 8/Pasted image 20220308104734.png]]
Fisicamente, questa roba mi torna. Visto che le energie si sommanbo sempre, io mi aspetto che l'energia e la potenza delle varie onde armoniche (se ce n'è più di una) che vanno su un onda, si sommino.
In realtà questa roba funziona solo e soltanto perchè abbiamo _onde armoniche di pulsazione diversa_. QUando questo non succede, entriamo in un campo di fenomeni di interferenza  e succedono robe diverse.
Fintanto che ho onde che fanno robe diverse, la somma delle intensità sta funzionando. Ogni singolo temrin equindi è un certa intensità I_n
![[../File/todo da lezione 8/Pasted image 20220308105106.png]]
Questo I_n, (visto anche come funzione di w), è chaiamto _spettro di potenza dell'onda_. Dice quanta intensità c'è ad una certa funzione dell'onda.
Domanda: Che fine ha fatto il coefficienet a0?