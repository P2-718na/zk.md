#todo
Esempi di fit:
Gaussiane con diversi livelli di rumore.
![[../File/esempi di fit/Pasted image 20220301152959.png]]
Prima di tutto guardo, il fit sembra ragionevole. Considero il Chi quadro ridotto, test ipotesi ok, 
(???)

Esempio di fit sbagliato:
![[../File/esempi di fit/Pasted image 20220301153606.png]]
Qui, qualitativamente questo fit non è accettabile. Ci si potrebbe fermare qua, anche senza calolare chi2 per vedere che stiamo sbagliando.

Tornando alla gaussiana, facciamo un altro esempio:
![[../File/esempi di fit/Pasted image 20220301153743.png]]Supponiamo di aver questi dati ma con un incertezza stimata molto bassa.
Faccio il fit e ottengo questo. Qual è la conclusione di questo fit? beh, non è che il fit è sbagliato. Il problema sta che abbiamo sottostimato le incertezze => Valore molto alto del chi2

 
(per tutti questi esempi abbiamo usato gli stessi dati).

Per ribadire il concetto:
![[../File/esempi di fit/Pasted image 20220301153938.png]]

Altri esempi a caso:
- ![[../File/esempi di fit/Pasted image 20220301154209.png]]
- ![[../File/esempi di fit/Pasted image 20220301154420.png]]
- Fit con meno punti
- ![[../File/esempi di fit/Pasted image 20220301154923.png]]

Esempi sbagliati da relazioni scorse:
![[../File/esempi di fit/Pasted image 20220301155054.png]]
__QUI, ESEMpio per valutare l'incertezza corretta: prendo un punto a fine coda, dove non ci sono oscillazioni e valuto. Oppure, acnora meglio, genero un voltaggio costante e stimo incertezza conq uello.__
![[../File/esempi di fit/Pasted image 20220301155348.png]]

---
Continua: lezione3
Set di dati: Gaussiana1
Il file rumore è una simulazione di una misura ripetuta, si può usare per determinare l'errore casuale dei dati (misurando la dev. standard).
Per il rumore dei dati gaussiana1 si ottiene sigma = 0.045. Lo inserisco nella funzione di fit
Importante: essere coscienti di quello che fa il programma.
![[../File/esempi di fit/Pasted image 20220308142851.png]]
Analisi qualitativa: ottimo accordo, residuo che oscilla attorno a zero.
Ora posso valutare quantitativamente i risultati del fit:
![[../File/esempi di fit/Pasted image 20220308143155.png]]
Ricorda di sistemare le cifre significative. Osserva che R^2 non tiene conto delle incertezze sul fit.
Riportando i risultati in tabella, ricorda come sistemare le cifre significative. La cosa importante è dichiarare che tipo di errore è.
![[../File/esempi di fit/Pasted image 20220308143644.png]]
Ultima cosa da fare: esportare i dati, usare un qualunque programma di grafica per avere i dati organizzati bellini
![[../File/esempi di fit/Pasted image 20220308143933.png]]
