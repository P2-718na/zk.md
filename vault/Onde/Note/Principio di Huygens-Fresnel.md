### Principio di Huygens-Fresnel
L'isservazione da cui partono questi due è che: loro hanno capito che le onde si propagano in linea retta, _ma non sempre_.

- Per esempio, il suono, sì si propaga in linea retta, però se sei in una casa lui non si propaga in linea retta ma passa attraverso le porte ed i corridoi.
- Le onde em hanno un comportamento simile:
    ![[../File/todo da lezione 15/Pasted image 20220328151939.png]] ^^ (questo all'epoca non si sapeva), ma ora sappiamo che ci sono strati dell'atmosfera che fanno riflettere le onde em.
    Se lavoro con delle onde a frequenza sufficientemente bassa, quindi, posso inviare onde che seguono la superficie terrestre.
- Le onde del mare, stessa cosa:
  ![[../File/todo da lezione 15/Pasted image 20220328152310.png]]

Bene, il proncipio HF mi permette di capire come evolve un certo fronte d'onda nello spazio, _senza nemmeno bisogno di conoscere la sorgente delle onde_.
L'idea alla base è che:
- Supponiamo di avere un fronte d'onda ad un certo istante di tempo $t$. Per esempio. prendiamo il luogo dei massimi di un onda. Il principio di HF mi dice che se conosco un fronte d'onda all'istante $t$, allora posso conoscere il fronte d'onda all'istante successivo $t + dt$, immaginando che _ogni punto infinitesimo del fronte d'onda, sia una sorgente di onde sferiche_. ![[../File/todo da lezione 15/Pasted image 20220328152551.png]]
  Il raggio di quest'onda sferica dipende dalla velocità della roba che vado a considerare.
Nella foto sopra, a sinistra ho un esempio di un fronte d'onda sferico. L'onda successiva è l'inviluppo di tutti i fronti generati da ogni punto del primo fronte d'onda. A destra, la stessa roba per le onde piane.

Ora, c'è un attimo un problema: per l'onda sferica, bisogna ricordare che _in realtà il fronte d'onda si muove sia verso destra che verso sinistra_. Questo problema si risolve mettendo una _dipendenza angolare_:
Supponiamo che il mio fronte d'onda si stia muovendo verso destra, con una certa direzione del moto. L'ampiezza con cui viene generata l'onda da ogni sorgente di huygens è maggiore nella direzione di propagazione delle onde, minore nell'altro verso.

Huygens ha sparato a cazzo come fattore angolare:
$$
f(\theta) = \frac 1 2 (1 + \cos\theta)
$$
Questo vale $1$ quando mi muovo nella direzione di propagazione dell'onda, $0$ quando mi muovo nel verso opposto.
Fresnel ha poi dimostrato che questo è il fattore giusto.
Visualizzato:
![[../File/todo da lezione 15/Pasted image 20220328153315.png]]
![[../File/todo da lezione 15/Pasted image 20220328153324.png]]
In questo modo si riesce a descrivere il movimento del fronte d'onda.

Questa roba funziona molto bene per onde piane. Può funzionare anche quando consideriamo onde sferiche, oppure quando consideriamo la riflessione di un onda su una superficie piana.
![[../File/todo da lezione 15/Pasted image 20220328153450.png]]