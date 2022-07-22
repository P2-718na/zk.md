### Interferenza di onde Elettromagnetiche
Questa roba vale sull'intero spettro elettromagnetico. Noi lo vedremo però solo per quanto riguarda la banda ottica.
Avevamo già toccato questa roba con le onde sonore e con il principio di Huygens-Fresnel. Oggi cerchiamo di quantificare un po' queste cose.
Faremo una serie di esperimenti concettuali e pratici:

![[Pasted image 20220509141214.png]]
Hooke, sostenitore della teoria ondulatoria ha subito un grandissimo torto: è legit morto prima di Young, quindi le sue teorie sono state dimenticate per un po', per poi venire riscoperte in futuro.

![[Pasted image 20220509141405.png]]
Young quindi si costruisce un apparato dove vengono messi in rilievo le parti ondulatorie della luce:
![[Pasted image 20220509141515.png]]
Sorgente di luce che blocca tutto, tranne una singola fenditura (molto piccola) al centro. Se il foro in s1 è abbastanza piccola, la luce andava a sbattere su s2 tramite fenomeno della diffrazione. Su s2 trovava altri due buchi di fessure molto piccole.
Già il fatto che la luce non si muovesse dritta dritta ma si incurvasse, era molto amogus.
![[amogus?.png]]
In più, le due altre fenditure si comportano come sorgenti secondarie di luce.
![[Pasted image 20220509141653.png]]

Ora, la singola fenditura iniziale mi serve per fare in modo che alle altre due fenditure arrivino solamente delle onde _coerenti_ (= differenza di fase costante).
Siccome le onde luminose sono ad altissima frequenza, diventa fondamentale che all'origine ci sia _la stessa sorgente_. Se io prendessi due laser rossi diversi, non troverei mai oscillazioni coerenti (ci sarebbe sicuramente una qualcge differenza nelle frequense).

Per tutto il 1700, nessuno sapeva cosa fosse la luce. Per tutta la prima metà del 1800 si sapeva che la luce fosse un onda, ma non che tipo di onda.
Queste sono figure ideali nel caso di luce monocromatica:
![[Pasted image 20220509142029.png]]
La figura di inteferenza dipende dalla lunghezza d'onda.
Ora, andiamo a studiare il fenomeno dell'interferenza.
Partiamo concentrandoci su uno schermo con due fenditure. In queste fenditure immaginiamo di avere una sorgente di luce coerente; e uno schermo finale.
![[Pasted image 20220509142240.png]]
La luce coerente è un onda EM che oscilla:
![[Pasted image 20220509142254.png]]
Su F1 c'è un certo campo \vec E_1.
Sulla fenditura F2, non vogliamo farci del male, ci semplifichiamo la vita al massimo.

Osservo che i due campi EM percorrono dei cammini di distanza leggermente diversa. Quindi, quando arrivano sullo schermo, l'_intensità_ che vedo sarà il _campo elettrico mediato al quadrato._

Diciamo che la distanza tra i due affari L è molto più grande della distanza tra le due fenditure. Quando arrivo in P quindi i due campi hanno più o meno la stessa intensità.
![[Pasted image 20220509142534.png]]
La difrerenza di fase la si valuta in funzione della differenza di cammino.

Vediamo cosa succede in P:
![[Pasted image 20220509142718.png]]
Il campo sarà la somma dei due E(P):
![[Pasted image 20220509142801.png]]
^^ (la figura è sbagliata, manca una i nel secondo esponenziale).

Quello che succede sullo schermo dipende in gran parte dai due termini $e^{ikr}$
Raccolgiendo i due fattori, il risultato è che io ho un certo esponenziale con una certa fase.

Quindi, quello chec 'è dentro la parentesi (nell'ultima delle tre equazioni ^^) va tra 2 e zero. (2 = esattamente il doppio di quello che ho per una singola onda. 0 = lì non misuro campo elettrico).

Ora, guardando la figura zoommata, posso valutare la differenza di cammino $r_2 - r_1$.
![[Pasted image 20220509143222.png]]
Sullo schermo quindi avrò ragioni di intensità x alternate a regioni di intensità nulla.
Queste due regioni estreme, vengono chiamate regioni di interferenza costruttiva o distruttiva.
Se ragioniamo in termini di fasi:
![[Pasted image 20220509143331.png]]
QUesti tre elementi sono quelli che mi entrano nella descrizione della mia roba.
Se ho interferenza costruttiva
![[Pasted image 20220509143352.png]]
L'interferenza costruttiva ce l'ho in questa condizione.
Questa condizione sulla fase, diventa una condizione sull'angolo $\sin \theta$. Elimino a destra e sinistra, risolvo per $\sin\theta$. Il seno dell'angolo in cui osservo dei massimi è quindi ^^ $\frac {n\lambda} d$ (dove $n$ è un _numero intero_.) Cosa succede in queste condizioni? questo (??) fattore vale due. Il modulo max del campo E vale 2 volte l'ampiezza amx di ogni singola onda. Se l'ampiezza di un onda ha una sola intensità luminosa che io chiamo I_0. L'intensità quindi è 4 volte l'intensità di partenzA (esarttamente quello che ci succedeva con il suono).

Cosa succede se lo sfasamenteo, anzichè essere un multiplo pari du due pi, è un multiplo dispari di 2\pi
In questo caso si ha intensità distruttiva.
![[Pasted image 20220509143357.png]]
![[Pasted image 20220509143708.png]]
Quando lavoriamo con le intensità, Tutto quello che c'è prima mi da l'intensità di un onda. Tutto quello che c'è dopo è una modulante dell'intenità.
=> l'intensità è iuna funzione esplicita di questo \delta phi (che dipende dall'angolo theta).

![[Pasted image 20220509143936.png]]
Ora, nelle onde sonore ci chiedevamo come mai l'energia delle onde raddoppiasse. La stessa cosa succede qua. Però, qui forse capiamo che semplicemente l'energia si refistribuisce sullo schermo.
Insomma, normalmente so che ho due sorgenti uguali, io mi aspetterei una intensità di due sorgenti.
Ora, qui se faccio la media delle intensità trovo esattamente 2I_0, ovvero la somma delle due intensità, che è ciò che mi aspetto.
![[Pasted image 20220509143941.png]]
Quindi l'energia semplciemente è ridistribuita in modo diverso e va a mediarsi nello spazio.

Ora, andiamo ad analizzare cosa succede tipicamente.
Quello che controlla quello che io vedo sullo scehrmo è questo rapporto:
![[Pasted image 20220509144421.png]]
![[Pasted image 20220509144424.png]]

Nella pratica, spesso si tende a lavorare con più sorgenti coerenti (n fenditure, non più solo due).
![[Pasted image 20220509144806.png]]
In questo schermo S2, anzichè metterci solo e soltranto due fenditure, ne mettiamo n equispaziate.
Se le investo tutte assieme con una luce monocromatica, queste diventeranno n sorgenti armoniche monocromatiche, il risultato è che???
Cosa vedo sullo schermo ? Il risultato è sempre lo stesso di prima, ma questa volta non avrò solamente due onde da sommare, ma ne avrò n.
![[Pasted image 20220509144928.png]]

Ogni singola fenditura produce nel campo elettrico una roba 

Sviluppando i conti, otteniamo la stessa roba di prima (con l'unica differenza che ora abbiamo n termini).
![[Pasted image 20220509145344.png]]
![[Pasted image 20220509145417.png]]
dove nel penultimo step moltiplico entrambe per 2i e ottengo un seno a numeratore e denumeratore.
![[Pasted image 20220509145848.png]]
![[Pasted image 20220509150009.png]]
![[Pasted image 20220509150025.png]]
![[Pasted image 20220509150043.png]]
Tornando nell'immagione prima, gli affarini piccoli sono i massimi relativi. Quando vado su un massimo assoluto, la distanza è esattamente doppia.

# retucolo di difrazionaie
![[Pasted image 20220509150242.png]]

![[Pasted image 20220509151759.png]]
![[Pasted image 20220509151805.png]]
Interessante osservare come ci sia la necessità di cambiare il colore della luce del lettore, nel momento in cui si passa da cd a blue ray.

### Interferenza da film sottili
"più una chiacchiera, no formule".
Ho un mnateriale ottico (lamina di vetro molto sottile). Ho un raggio che entra. Questo raggio incidente farà riflessione e rifrazione. Se si infila dentro la lamina, prima o poi arriva alla seconda superficie ottica. Se qui viene riflesso, ha la possibilità di tornare sulla superficie iniziale e uscire.
![[Pasted image 20220509152006.png]]

Questi due raggi che escono, sono raggi sempre sistematicamente coerenti. Possono avere una certa differenza di fase ma sono coerenti.
Questi due raggi in uscita faranno interferenza (o costruttiva o distruttiva). Se anziché partire da luce monocromatica parto da luce bianca, questi due raggi trasportano tutte le frequenze. Quindi, alcune si troveranno in codnozioni di interferenza costruttiva, al
tri in condizione di interferenza distruttiva.

Lì dove c'è interferenza distruttiva, vedo dei colori.
![[Pasted image 20220509152207.png]]
vv kerosene
![[Pasted image 20220509152125.png]]

Trattamento antiriflesso della lente:
![[Pasted image 20220509152307.png]]
Si studia l'indice di rifrazione di questo affare in modo da darmi interferenza distruttiva per il riflesso.
Bello in teoria, però visto che la luce non è monocromatica funziona fino a un certo punto.
Si sceglie quindi un valore centrale, di solito si vede comunque qualche riflesso blu.
