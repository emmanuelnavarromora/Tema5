# Tema5
## Emmanuel Navarro Mora B65024
$
P( \text{5 o más clientes en el sistema} ) = \sum_{i=5}^{\infty} (1 - \rho) \rho^i  = 1 - \sum_{i=0}^{4} (1 - \rho) \rho^i = \rho^5
$$

que depende de $\rho = \lambda/\nu$ y del parámetro de servicio $\nu$ buscado. 

De los datos del problema: $\lambda = 2$. Para tener una fila de 3 o menos clientes el 99\% del tiempo se necesita:

$$
\begin{aligned}
P( \text{5 o más clientes en el sistema} ) = \rho^5 & = \left( \frac{\lambda}{\nu} \right)^5 \leq 0.01 \\
\nu^5 & \geq \frac{\lambda^5}{0.01} = \frac{2^5}{0.01} = 3200 \quad \Rightarrow \quad \nu \geq 5.024
\end{aligned}
