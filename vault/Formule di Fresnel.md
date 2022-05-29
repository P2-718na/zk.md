### Formule di Fresnel
Considerazioni iniziali:
![[Pasted image 20220503093315.png]]
![[Pasted image 20220503093324.png]]
Si scopre che la luce che è polarizzata nel piano di incidenza (e parallela) si comporta nella riflessione e nella riflazione alla luce che è polarizzata perpendicolarmente al piano di incidenza. 
Questo non vuol dire che mi cambiano gli angoli, quello che cambia è l'intensità dell'onda (che dipende dalla polarizzazione che ho).
Allora, per essere coerenti con quello che abbiamo fatto fino ad ora, definiamo la direzione dei campi elettrici riflessi e trasmessi, immaginando quello che succede quando l'angolo di incidenza va a zero e cercando di essere coerenti con un incidenza normale.
Siccome con un incidenza normale in campo riflesso ha sempre la diurezio ???? quelli che vediamo segnati qua sono le scelte sulla direzione del campo riflesso e trasmesso per polarizzazione parallela e perpendicolare al piano di incidenza.
Ora, analizziamo una polarizzazione alla volta. Partiamo dalla _polarizzazione sul piano incidente_. (E ricordiamo che quando parliamo di polarizzazione, stiamo guardando quello che fa il campo elettrico).
![[Pasted image 20220503093557.png]]
Queste saranno le diurezioni del campo elettrico:
Ora, il campo magnetico qui sarà parallelo alla superficie di separazione dei due mezzi, quindi i calcoli per quelli sono ez. Il campo elettrico no, quindi bisogna ragionarci un attimo.

La condizione di incidenza normale del campo elettrico (che abbiamo visto in EM e anche nella lezione di ieri) oggi va ricalcolata con campi elettrici che non sono paralleli a questa superficie
![[Pasted image 20220503093853.png]]
![[Pasted image 20220503094009.png]]

??
$$
E = ZH = \frac {Z_0} n H
$$
$$
H = \frac{nE}{Z_0}
$$
Quando ho un onda, chiamo E_i // per parte elettrica, E_i perpendicolare per la parte magnetica.
Quindi alla fine ho delle equazioni bellxm che contengono dei coseni + la stessa formula di ieri.
Per risparmiarmi dei conti, divido la prima eq. dei coseni con cos(thetai), e rinomino le mie variabili:
![[Pasted image 20220503094146.png]]
Ora da queste robe voglio togliere E_i. Quindi faccio i miei bei calcolini...
![[Pasted image 20220503094320.png]]
Dalla prima equazione posso risolvere per l'incognita "campo trasmesso". Dalla seconda posso risolvere E_r e alla fine trovo il mio campo riflesso e il mio campo trasmesso.
Se ora riscrivo alfa e beta, metto tutto assieme e ottengo le _formule di fresnel_ per la luce polarizzata nel piano di incidenza.

Ora, se io prendo questi due bei fattori e li plotto
vedo come variano al variare dell'angolo di incidenza:
![[Pasted image 20220503094721.png]]

![[Pasted image 20220503094855.png]]
![[Pasted image 20220503095004.png]]
Il coseno nella formula di prima dell'intensità (?) deriva dal fatto che la luce si spreadda su una regione èiù grande (?) => quello ceh si consiserva non è tanto ll'intensità ma l'energia.
(Ricordiamo che l'intensità è una misura locale legata alla densità di energia).


Ora, facciamo un ragionamento fast su quello che succede alla polarizzazione perpendicolare:
![[Pasted image 20220503095314.png]]
I campi magnetici saranno perpendicolari al piano incidente.

Cosa cambia rispetto a prima? Visto che E\perp è parallelo alla superficie incidente, quellop che succede al campo elettricp è analogo a quello che abbiamo visto ieri per l'incidenza normale. Ora, se il campo elettrico si comporta così, il campo magnetico si comporta in maniera divetsa. Riprendo l'andamento dello stesso disegno di prima con qualche modifica.
Questo sarà il campo magnetico incidente, questo quello trasmesso, quello riflesso sarà opposot a quello incidente. (qui c'è un disegno fatto alla lavagna che non ricopierò).

![[Pasted image 20220503095546.png]]
(?? prendo le formule che abebamo visto prima...)
![[Pasted image 20220503095552.png]]
Porcodio villa skippa tutti i conti qua e droppa la slide:
![[Pasted image 20220503095700.png]]
Dove prima c'era alpha ora c'è 1, dove prima c'era beta ora c'è alpha beta.
Come prima chiamo queste due quantità t\perp e r\perp.
![[Pasted image 20220503095758.png]]
![[Pasted image 20220503100140.png]]
