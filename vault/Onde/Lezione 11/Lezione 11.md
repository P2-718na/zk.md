### Analisi energetica delle onde sonore
![[Pasted image 20220315093543.png]]
Se mi metto in questo tuob, per generare l'onda avrò uno speaker/diaframma/qualcosa all'imboccatura che mette in moto le molecole all'interno. Immaginiamo che la $\xi(\bar x, t)$ ci venga data (con \bar x punto fissato). Questa csi genera localmente un onda di pressione (formula in basso a destra in ^^).
Un onda di pressione vuol dire che le molecole del mio gas si metteranno in oscillazione con una certa velocità. Questa velocità sarà la derivata della \xi rispetto al tempo:
![[Pasted image 20220315093717.png]]
Mediamente, la velocità media delle particelle sarà zero (non ho un moto degli atomi lungo il mio tubo, in media questi rimarranno fissi).
![[Pasted image 20220315093846.png]]
La forza applicata dal diaframma sarà sempre lungo l'asse del mio tubo; lo spostamento è solo lungo x. Al posto della forza metto Sezione\*pressione, e il mio dx sarà una velocità per un tempo.
Noi in realtà possiamo andare a sostituire altre robe lìì dentro:
![[Pasted image 20220315094016.png]]
Osservo che tutti e due i termini sono proporzionali al tempo.
Posso calcolare la potenza immessa nel tubo con:
![[Pasted image 20220315094045.png]]
E osservo che questa roba, rispetto alla corda c'è un termine in più. Ora osservo però che, visto che a me interessa ragionare in media, avrò:
![[Pasted image 20220315094151.png]]
(per le considerazioni che abbiamo visto prima sulla velocità media).
=> Il primo termine non mi interessa più di tanto. Andiamo a vedere solo il secondo:
![[Pasted image 20220315094219.png]]
La struttura di questo è molto più simile a quella della corda (le due derivate rispetto a x e tempo); ha davanti un coefficiente che tiene conto della sezione del tubo.

L'energia è  una grandezza _estensiva_. Il fattore S che ho davanti mi racconta che la mia potenza immessa dipende dalla sezione del tubo. Più è grande il tubo e più, a partià di tutte le altre condizioni, riuscirò ad immettere potenza.

L'_intensità_, invece, è una grandezza (che io vorrei avere) _intensiva_. Di conseguenza, per questo caso, non posso definire l'intensità come potenza media (perchè così avrei una grandezza estensiva). Di conseguenza, si definisce l'Intensità:
![[Pasted image 20220315094501.png]]
.

---
### Impedenza acustica specifica
Ragioniamo un attimo su questa intensità:
![[Pasted image 20220315094555.png]]
Sempre nell'ipotesi del nostro tubo, abbiamo che si propagano delle onde progressive.
Vado a sostituire la roba a destra nella roba a sinistra ^^:
![[Pasted image 20220315094623.png]]
Ora, il coefficiente che chiamiamo a sinistra, lo chiamiamo
![[Pasted image 20220315094647.png]]
In analogia con quanto definito per una corda.
Il termine "specifica" indica che questa roba Z varia in base al punto dello spazio dove mi trovo, visto che potrebbero variare gamma P0 e v).
Si può esprimere anche in funzione della densità (utile per esercizi):
![[Pasted image 20220315094747.png]]
![[Pasted image 20220315094937.png]]

Ora, cerchiamo il _rapporto causa effetto_ dell'impedenza nel caso delle onde sonore.
Partendo dalla formula di prima (dove??), la ri esprimo in forma "variazionale": \delta p è la mia perturbazione che attraversa il tubo.
![[Pasted image 20220315095007.png]]
Nel nostro caso, dove dentro al tubo viggiano delle onde progressive, d\xi/dx è collegato a d\xi/dt. Posso quindi riscrivere:
![[Pasted image 20220315095104.png]]
Osservo che il coefficiente che ho davanti quando cambio la derivata è proprio la mia Z impedenza definita prima.  
![[Pasted image 20220315095127.png]]
Insomma, se uno da una piccola variazione di pressione in un punto del gas, io ho uno spostamento che si propaga lungo tutto il gas. L'impedenza mi permette di interpretare tutto in forma di rapporto causa/effetto.
as

### Orecchio
![[Pasted image 20220315095304.png]]
Un orecchio è essenzialmente fatto in 3 pezzi. Il suono attraversa padiglione e condotto uditivo, viene preso su dal timpano, che fa vibrare gli ossicini. Un movimentl degli ossicini fa un movimento piccolo del liquido che c'è nella conchiglia e questo robo viene sentito dai sensori lì all'interno.

"Per un fisico, un timpano è un diaframma che si comporta come un oscillatore armonico forzato".
Come sarà il [[Fattore di qualità]] del nostro oscillatore/timpano?
_Basso_ (così da poter sentire un insieme ampio di suoni, $20Hz-20kHz$).
![[Pasted image 20220315095748.png]]
La minima intensità di suono percepibile varia da persona a persona e dalla frequenza. In modo convenzionale, si definisce un _Intensità minima percepibile_ (da ricordare):
![[Pasted image 20220315095827.png]]
Se i suoni sono troppo alti, questi possono provocare dolore. La soglia del dolore è di:
![[Pasted image 20220315095851.png]]
Se vado sopra rompo l'orecchio:
![[Pasted image 20220315095920.png]]
. Riassumento tutto in un grafico:
![[grafico orecchio.png]]
__13 ordini di grandezza di intensità sonora!__

### Livello di intensità sonora
Per questo motivo, la scala espressa in W/m^2 è poco pratica. Introduciamo quindi il _livello di intensità sonora_:
![[Pasted image 20220315100249.png]]
Questa è una scala logaritmica...
![[Pasted image 20220315100436.png]]
E i tre limiti diventano:
![[Pasted image 20220315100504.png]]

---
_Esempio_:
![[Pasted image 20220315100523.png]]
 Pluggo i 50db nella roba:
 ![[Pasted image 20220315100713.png]]
 Il mio risultato è 
 ![[Pasted image 20220315100724.png]]
 Questa è l'intensiutà di una conversazione normale.
Ricordando che questa roba è definita come il valore medio del'impedenza per...
![[Pasted image 20220315100800.png]]
Si ottiene che
![[Pasted image 20220315100856.png]]
E che
![[Pasted image 20220315100941.png]]
Per avere un termine di paragone, questa ampiezza corrisponde a 
![[Pasted image 20220315101016.png]]
Insomma, queste ampiezze sono tipicamente molto piccole.
![[Pasted image 20220315101154.png]]
![[Pasted image 20220315101159.png]]
![[Pasted image 20220315101252.png]]
Insomma il concetto è che le perturbazioni sono piccole:
![[Pasted image 20220315101358.png]]
Da questo osserviamo che l'eq di d'alembert che abbiamo ottenuto per questa roba qui, è un ottima approssimazione di quello che succede. Il mezzo in cui viaggiano le onde sonore, quindi, è un mezzo _non dispersivo_ (tutte le onde sonore viaggiano alla stessa velocità-)

---
### Interferenza e battimenti
![[Pasted image 20220315103003.png]]

### Interferenza
![[Pasted image 20220315103031.png]]
L'interferenza è un fenomeno fisico che nasce quando nella stessa regione dello spazio mi trovo due onde armoniche con _esattamente la stessa pulsazione_. Onde armoniche con la stessa pulsazione vengono dette _coerenti_. Per assicurarci di avere onde con la stessa pulsazione (con precisione arbitraria), dobbiamo fare in modo che le due onde siano due aspetti diversi dello stesso fenomeno.

Quindi, prendo due onde con la stessa pulsazione:
![[Pasted image 20220315103221.png]]
Le prendo progressive. Queste possono differire nelle ampiezze e per una fase (che metto solo da una parte per semplicità).
Sono due onde che si presentano nella stessa regione di spazio. => L'onda complessiva è la somma lineare di queste due.ì
Sempre parlando dell'esempio del tubo, se ho due onde separate, quello che si propaga è la loro somma:
![[Pasted image 20220315103344.png]]
Per rappresentarla ez, vado nel campo complesso (qui ho i calcoli appena più facili):
![[Pasted image 20220315103354.png]]
![[Pasted image 20220315103402.png]]
Qui, sommare le due onde vuol dire somamre questi due numeri complessi. Vado nel piano di Argand-Gauss.
![[grafico di argand-gauss.png]]
In questo piano la mia onda è un vettore. Ho le mie due onde \xi_1 e \xi_2, di ampiezze e fasi diverse.
La loro somma sarà quindi:
![[Pasted image 20220315103637.png]]
La cosa che dovrebbe essere evidente da questo passaggio è che l'onda risultante è sempre un'onda armonica. La sia pulsazione sarà sempre $\omega$. => Nel momento in cui io lascio scorrere il tempo, $\xi_1$ fa un moto di rotazione orario assieme a $\xi_2$. La differenza tra le due fasi, quindi, rimane sempre fissata a $\varphi_0$. Il concetto di "stessa omega" si trasporta nel piano A-G con concetto di "differenza di fase costante".

Vediamo cosa succede all'ampiezza risultante:
![[Pasted image 20220315103918.png]]
Sviluppo i calcoli per A
![[Pasted image 20220315103958.png]]
Quindi la mia ampiezza massima sarà:
![[Pasted image 20220315104119.png]]
^^ e osservo che se non ci fosse nessuno sfasamento, avremmo una somma delle ampiezze (quello sotto la radice è un quadrato di binomio).
(Osservo che questa cosa mi ritorna anche se guardo il piano di argand-gauss).
Cosa succede se l'angolo vale \pi?
![[Pasted image 20220315104238.png]]
In questo caso i due affari sono completamente sfasati e si sottraggono.
La cosa interessante dell'interferenza distruttiva è che:
![[Pasted image 20220315104412.png]]
.
Tornando alla roba nella radice, definiamo:
![[Pasted image 20220315104507.png]]
. 
Vediamo ora cosa succede in termini di energia. Sappiamo che le intensità valgono:
![[Pasted image 20220315104600.png]]
E quindi l'intensità risultante sarà:
![[Pasted image 20220315104743.png]]
E possiamo fare anche queste considerazioni:
![[Pasted image 20220315104932.png]]
Ok questa roba ^^ è un po' sus.
![[sus.png]]Se l'inrensità dipende dall'energia, come mai la somma di due intensità uguali mi danno un'energia che è quattro volte quella di partenza?
Il fatto è che questa energia viene da altri pezzi:
![[Pasted image 20220315105317.png]]
Insomma l'intensità dipende dallo sfasamento. L'energia che appare nelle onde in fase viene rubate dagli altri pezzi.
Il _punto chiave_ è che noi stiamo lavorando su grandezze fisiche che soddisfano il principio di sovrapposizione. Semplicemente, le energie (che sono grandezze quadratiche), non si sommano normalmente. Quindi, quando ho questi fenomeni, devo "rinunciare a qualche cosa".
![[Pasted image 20220315105449.png]]
FINE LEZIONE (=?=?=?=)