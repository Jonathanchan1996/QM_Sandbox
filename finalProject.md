# ELEC5210 Final Project
## Chan Chak Lam Jonathan
### May 03, 2021

Grover's search algorithm 

$
Iteration = \sqrt{\frac{N}{M}} 
$
where $M$ is the number of winner(s)


To generate an oracle
first, an oracle is needed from the 

$
f(x) =
\left\{\begin{matrix}
 -1 & Winner  
 \\
 1 & Otherwise
\end{matrix}\right.
$

Which is a diagonal matrix and the searchers cannot access to this information.  
$
O(x)=\begin{bmatrix}
(-1)^{f(0)} &0  & \cdots & 0\\ 
0 &  (-1)^{f(1)}&  & 0\\ 
\vdots  &  &  \ddots & \vdots \\ 
0 & 0 & \cdots & (-1)^{f(n)}
\end{bmatrix}
$



$
O\ket{X_n}=(-1)^{f(n)}\ket{X_n}
$

$P_x={n\choose x}\cdot p^x(1-p)^{n-x}$