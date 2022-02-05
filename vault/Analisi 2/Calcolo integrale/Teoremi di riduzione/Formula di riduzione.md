##### Formula di riduzione
((Questa è la definizione del de marco. Non si capisce un cazzo))
$\mu,\ \nu \in \mathbb{N}^0 :\rightarrow$
$f : \mathbb{R}^\mu \times \mathbb{R}^\nu \to \mathbb{R}$ è [[Riemann integrabile]] $\implies$ la [[x-sezione]] $y \mapsto f(x,\ y)$ di $f$ è [[Riemann integrabile]] per $\lambda_mu$-[[q. o.|quasi ogni]] $x \in \mathbb{R}^\mu$;
la formula
$$\varphi(x) := \int_{\mathbb{R}^\nu} f(x,\ y)\ d\lambda_\nu(y)$$
definisce [[q. o.]] in $\mathbb{R}^\mu$ una funzione [[Riemann integrabile]], e si ha
    $$
    \int_{\mathbb{R}^\mu} \left(
        \int_{\mathbb{R}^\nu} f(x,\ y)\ d\lambda_\nu(y)\ 
    \right)\ 
    d\lambda_\mu(x)
    :=
    \int_{\mathbb{R}^\mu}\varphi(x)\ d\lambda_\mu(x)
    =
    \int_{\mathbb{R}^\mu \times \mathbb{R}^\nu} f(x,\ y)\ d\lambda_{\mu + \nu}(x,\ y)
$$
