### Importanza delle onde armoniche
 Concludiamo la lezione discutendo _l'importanza delle onde armoniche._
Perché mi interessano le onde armoniche?
![[../File/todo da lezione 7/Pasted image 20220307153852.png]]
Ci mettiamo nelle condizioni più semplici possibili:
![[../File/todo da lezione 7/Pasted image 20220307153908.png]]
(ricordiamoci che l'eq di d'alembert chiedeva angoli piccoli, nella sua dimostrazione. Se gli angoli sono grandi (come per esempio in questo disegno) ci sono delle differenze...)

In questo sistema, si propagano solo onde progressive. Quello a cui devo stare attento per capire quello che succede lungo la corda è che quello che avviene nell'origine avverrà dopo un tempo parti al tempo di propagazione in un punto generico x (vedi foto: t_0 = t - x/v).
Quindi, se nell'origine ho una sollecitazione del tipo $f(t)$ arbitrario, la mia onda sarà del tipo:
![[../File/todo da lezione 7/Pasted image 20220307154110.png]]
( se la mia onda avviene in un mezzo dispersivo, non posso più fare questo giochetto).
La cosa interessante è che quando ho a che fare con un'onda progressiva, ho sempre e solo a che fare con UNA funzione di UN parametro. (il parametro t - x/v è visibile come un unico parametro s). Quindi, io posso prendere qualunque funzione f e ho la descrizione dell'onda. Per capire l'importanza delle onde armoniche, comincio a fare quello che ho fatto nei sistemi lineari. (nei sistemi lineari ??)....
![[../File/todo da lezione 7/Pasted image 20220307154319.png]]
![[../File/todo da lezione 7/Pasted image 20220307154437.png]]
(Mi conviene fare una trattazione complessa e scrivere direttamente così...)
Per ragioni estetiche, anzichè usare queste due espressioni, qiuandi si va nelle onde armoniche, si preferisce parare di argomenti del tipo kx -wt. Quindi, vado a sostituire, ponendo $m = -n$:
![[../File/todo da lezione 7/Pasted image 20220307154605.png]]
Il punto è che questa è una somma di oscillazioni armoniche. Ogni singola oscillazione armonica sulla corda diventa un'onda armonica. Cosa devo fare? Al posto del tempo t che è misurato nell'origine, vado a mettere il tempo t - x/v (come visto prima):
![[../File/todo da lezione 7/Pasted image 20220307154707.png]]
![[../File/todo da lezione 7/Pasted image 20220307154735.png]]
???
![[../File/todo da lezione 7/Pasted image 20220307154859.png]]
(nell'ultino passaggio reintroduco la n ma cambio c in c').
Scritto così, quella csi è l'onda generata su un qualunque mezzo.
![[../File/todo da lezione 7/Pasted image 20220307155016.png]]
( e qui, se sono fortunato questa roba è una costante. Se non sono fortunato, questa roba varia.)
=> Io posso descrivere un'onda periodica attraverso sovrapposizioni di onde armoniche. (Sto riscrivendo sfruttando la linearità dell'eq di d'alembert)

Ricapitolando:
- Se sollecito il primo punto della corda con un moto periodico, mi si innesca sulla corda un'onda periodica.
- Se sul primo punto della corda ho una componente omega, una 2omega, una 3omega... e basta, nell'onda che viaggia io mi troverò un'onda armonica di pulsazione omega, una di pulsazione 2w e una di puls 3w => L'onda che sta viaggiando è una sovrapposizione di onde armoniche.
- __Quindi, lavoreremo tanto con le onde armoniche, dato che sono l'elemento più piccolo che mi definisce un'onda. Se voglio un'onda arbitraria, comincio a sommare onde armoniche.__

Cosa succede se metto in moto il primo punto della corda con una funzione con un andamento che non è periodico? In questo caso, quella funzione non la posso rappresentare con una serie di Fourier, ma la posso rappresentare attraverso un'antitrasformata di Fourier (passando dal dominio discreto al dominio continuo) => anche l'onda sarà un'antitrasformata di Fourier.
Varrà quindi sempre il principio di sovrapposizione.

Se ho una semicorda e metto in moto un punto, ho onde progressive.
Se non ho una semicorda e metto in moto un punto, da quel punto partiranno onde progressive verso destra e regressive verso sinistra. Può capitare che su certi sistemi
![[../File/todo da lezione 7/Pasted image 20220307155502.png]]
