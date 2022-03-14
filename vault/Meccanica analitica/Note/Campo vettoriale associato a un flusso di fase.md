##### `DEF` Campo vettoriale associato a un flusso di fase
Sia $\phi (t,\ x)$ [[Note/Flusso di fase|flusso di fase]]. Si definisce `campo vettoriale associato a phi` $:\Leftrightarrow$
$$
\vec a (x) := \left. \frac d {dt} \right|_{t=0}\ \phi^t(x_0)
$$

`OSS` $\vec a$ è un sistema di equazioni differenziali che, allo stesso modo di $\phi$, vanno a descrivere l'evoluzione del sistema. Questa definizione deriva dal fatto che, in generale, _dall'osservazione temporale di un sistema fisico NON si riesce a determinare esplicitamente il flusso di fase della trasformazione_. Tuttavia, _$\vec a$ si riesce a determinare_, e questa definizione ci da un modo per ottenere $\phi$ partendo da $\vec a$ (tramite un integrazione).

`OSS` In realtà, _Poincaré_ ci dimostra che dato un sistema di [[EDO]] generico, è _impossibile_ integrarlo con metodi algebrici o analitici. Spesso, quindi, non è possibile ricavare esplicitamente il flusso di fase partendo dal campo vettoriale.