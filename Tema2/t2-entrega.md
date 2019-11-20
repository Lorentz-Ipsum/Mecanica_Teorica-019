
# Del tema 1

$$
\begin{aligned}
-\frac{aq_1}{(q_1^2 + q_2^2)^{\frac{3}{2}}} + mb^2 q_1 &= m \ddot{q_1}\\
-\frac{aq_2}{(q_1^2 + q_2^2)^{\frac{3}{2}}} + m b^2 q_2 &= m \ddot{q_2} \\
m b^2 q_3 &= m \ddot{q_3}
\end{aligned}
$$

# Sistemas Hamiltonianos
 
### Coordenadas unificadas

$$
H(\xi^j) = \frac{1}{2m} \xi^{i+3} \xi_{i+3} + \frac{a}{\sqrt{(\xi^1)^2 + (\xi^2)^2}} - b \xi^1 \xi_4
$$

$$
\begin{aligned}
	\frac{d q^1}{d s}= \dot{q_1} &=  \frac{\partial H}{\partial p^1} = U^1 =  - b q_{1} + \frac{p_{1}}{m} \\
	\frac{d q^2}{d s}= \dot{q_2} &= \frac{\partial H}{\partial p^2} = U^2 = \frac{p_{2}}{m} \\
	\frac{d q^3}{d s}= \dot{q_3} &= \frac{\partial H}{\partial p^3} = U^3 = \frac{p_{3}}{m} \\
\end{aligned}
$$

$$
\begin{aligned}
	 \dot{p_1} &= \frac{ \partial H}{\partial q^1} =  \frac{a q_1}{(q_1^2 + q_2^2)^{\frac{3}{2}}} - bp_1 \\
	 \dot{p_2} &= \frac{ \partial H}{\partial q^2} = \frac{aq_2}{(q_1^2 + q_2^2)^{\frac{3}{2}}} \\
	 \dot{p_3} &= \frac{ \partial H}{\partial q^3} = 0\\
\end{aligned}
$$

$$
X_H = \left( - b q_{1}  + \frac{p_{1}}{m} \right) \frac{\partial}{\partial q^1} +   \frac{p_{2}}{m} \frac{\partial}{\partial q^2}  +  \frac{p_{3}}{m} \frac{\partial}{\partial q^3} + \left( \frac{a q_1}{(q_1^2 + q_2^2)^{\frac{3}{2}}}  -  bp_1 \right) \frac{\partial}{\partial p^1} + \frac{aq_2}{(q_1^2 + q_2^2)^{\frac{3}{2}}}\frac{\partial}{\partial p^2} 
$$

# Curvas Integrales


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
eyJoaXN0b3J5IjpbMTY1MDg5MjkyMSwxOTI5NjE2NzkyLC0xOT
UwNTgyOTc3LC0xNDYwMzI3ODcwLDczMDk5ODExNl19
-->