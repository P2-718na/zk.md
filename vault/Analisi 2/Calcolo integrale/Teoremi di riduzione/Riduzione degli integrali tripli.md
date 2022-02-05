##### `THM` Riduzione di integrali tripli
$f(x,\ y,\ z)$ funzione [[Continuità#DEF Funzione continua|continua]] sul [[Dominio normale#DEF Dominio normale rispetto ad un piano|dominio normale rispetto all'asse z]] $:\rightarrow$ la funzione:
$$
(x,\ y) \in A \to \int_{\alpha(x,\ y)}^{\beta(x\, y)} f(x,\ y,\ z)\ dz
$$
risulta continua su $A$ e si ha:
$$
\iiint_E f(x,\ y,\ z)\ dxdydz
=
\iint_A dxdy \left(
    \int_{\alpha(x,\ y)}^{\beta(x,\ y)} f(x,\ y,\ z)\ dz
\right)
$$

. Se a sua volta $A$ è il [[Dominio normale#DEF Dominio normale rispetto ad una variabile|dominio normale piano]], con $\varphi$, $\psi$ [[Continuità#DEF Funzione continua|continue]], posso scrivere:
$$
\iiint_E f(x,\ y,\ z)\ dxdydz
=
\int_a^b dx
\left[
    \int_{\varphi(x)}^{\psi(x)}dy
    \left(
        \int_{\alpha(x,\ y)}^{\beta(x,\ y)} f(x,\ y,\ z)\ dz
    \right)
\right]
$$
