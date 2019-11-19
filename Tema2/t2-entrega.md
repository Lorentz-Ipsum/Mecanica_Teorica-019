

# Sistemas Hamiltonianos
 
### Coordenadas unificadas

$$
H(\xi^j) = \frac{1}{2m} \xi^{i+3} \xi_{i+3} + \frac{a}{\sqrt{(\xi^1)^2 + (\xi^2)^2}} - b \xi^1 \xi_4
$$

$$
\begin{aligned}
	\frac{\partial H}{\partial p^1} = U^1 = - b q_{1} + \frac{p_{1}}{m} \\
	\frac{\partial H}{\partial p^2} = U^2 = p_{2} / {m} \\
	\frac{\partial H}{\partial p^3} = U^3 = p_{3} / {m} \\
\end{aligned}
$$

$$
\begin{aligned}
	\frac{\partial H}{\partial q^1} &=  \frac{a q_1}{(q_1^2 + q_2^2)^{\frac{3}{2}}} - bp_1 \\
	\frac{ \partial H}{\partial q^2} &= \frac{aq_2}{(q_1^2 + q_2^2)^{\frac{3}{2}}} \\
	\frac{ \partial H}{\partial q^3} &= 0\\
\end{aligned}
$$

$$
X_H = - b q_{1} \frac{\partial}{\partial p^1}  + \frac{p_{1}}{m} +  p_{2} / {m} + \frac{a q_1}{(q_1^2 + q_2^2)^{\frac{3}{2}}} - bp_1 ) \frac{\partial}{\partial p^1} + \frac{aq_2}{(q_1^2 + q_2^2)^{\frac{3}{2}}} 
$$
# Flujos hamiltonianos.


$$
i_{X_F} \Omega = - df
$$

$$
\omega_{lj} \chi_j^l = -\partial_j f
$$

$$
\chi_f^j = \omega^{jk}\partial_k f
$$

$$
\chi_f = \omega^{jk}\partial_k f \partial_j
$$

Condición:

$$
d i_\chi \Omega = 0
$$

Flujo generatriz:

$$
\phi^{\chi_f} = \phi^f
$$

$$
\phi^f = exp\{ s(\mathcal{L}_{\chi_f} + \partial_s )\}
$$

$$
\mathcal{L}_{\chi_f}g = \chi_f g = \omega^{jk}\partial_k f \partial_j g = \{g,f \} = - \mathcal{L}_{\chi_g}f
$$

$$
\mathcal{L}_{\Delta}g = \frac{d}{dt} g =\partial_j f \dot{\xi}^j = \partial_j f \omega^{jk} \partial_k H = \{g,H\}
$$


### Otra forma

$$
i_{X_F} \omega = dF
$$


$$
dF= \frac{\partial F}{\partial q^\alpha} dq^\alpha +  \frac{\partial F}{\partial p_\alpha} dp_\alpha
$$

$$
\phi_s^X = e^{s\mathcal{L}_X}
$$



> Written with [StackEdit](https://stackedit.io/).

<!--stackedit_data:
eyJoaXN0b3J5IjpbODU3NTYzMDAzLC0xNDYwMzI3ODcwLDczMD
k5ODExNl19
-->