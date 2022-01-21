##### `DEF` Forma quadratica
 Ad ogni matrice quadrata $n \times n$ è associata una funzione $F_A : \mathbb{R}^n \rightarrow \mathbb{R}$ detta `forma quadratica` $:=$
$$
F_A(\lambda):=\langle \lambda, \ \lambda A \rangle = \lambda^TA\lambda \hspace{20px} \forall \lambda \in \mathbb{R}^n 
$$
`DEF` definita positiva/negativa di forma quadratica #todo 

##### `THM` Classificazione di matrici simmetriche associate a forme quadratiche
$A \in M_{n,n}(\mathbb{R})$, $A = A^T$, $\lambda_1, \ldots, \lambda_n$ [[autovalori]] di A $:\rightarrow$
    1. A è `definita positiva` $\iff$ $\lambda_1, \ldots, \lambda_n > 0$
    2. A è `definita negativa` $\iff$ $\lambda_1, \ldots, \lambda_n < 0$
    3. A è `semidefinita positiva` $\iff$ $\lambda_1, \ldots, \lambda_n \geq 0,\ \exists\lambda_i = 0$
    4. A è `semidefinita negativa` $\iff$ $\lambda_1, \ldots, \lambda_n \leq 0,\ \exists\lambda_i = 0$
    5. A è `indefinita` $\iff$ $\underset{\lambda_i,\ \lambda_j}{\exists} \mid sgn(\lambda_1\lambda_2) = -1$ ^fceb71
