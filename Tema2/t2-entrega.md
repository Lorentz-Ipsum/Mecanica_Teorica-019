
# Del tema 1

$$
\begin{aligned}
-\frac{aq_1}{(q_1^2 + q_2^2)^{\frac{3}{2}}} + mb^2 q_1 &= m \ddot{q_1}\\
-\frac{aq_2}{(q_1^2 + q_2^2)^{\frac{3}{2}}} + m b^2 q_2 &= m \ddot{q_2} \\
m b^2 q_3 &= m \ddot{q_3}
\end{aligned}
$$

# Sistemas Hamiltonianos
 
 
$$
\dot{p}_\alpha = - \frac{\partial H}{\partial q^\alpha} \quad \quad  \dot{q}_\alpha = \frac{\partial H}{\partial p^\alpha}
$$

$$
\begin{aligned}
	\frac{d q^1}{d s}= \dot{q_1} &=  \frac{\partial H}{\partial p^1} = U^1 =  - b q_{1} + \frac{p_{1}}{m} \\
	\frac{d q^2}{d s}= \dot{q_2} &= \frac{\partial H}{\partial p^2} = U^2 = \frac{p_{2}}{m} \\
	\frac{d q^3}{d s}= \dot{q_3} &= \frac{\partial H}{\partial p^3} = U^3 = \frac{p_{3}}{m} \\
\end{aligned}
$$

### Corchetes de Poisson
$$
\begin{aligned}\left\{j_{\alpha}, f\right\} &=\epsilon_{\alpha \beta \gamma}\left\{x^{\beta} p_{\gamma}, f\right\}=\epsilon_{\alpha \beta \gamma} x^{\beta}\left\{p_{\gamma}, f\right\}+\epsilon_{\alpha \beta \gamma}\left\{x^{\beta}, f\right\} p_{\gamma} \\ &=\epsilon_{\alpha \beta \gamma}\left[-x^{\beta} \partial f / \partial x^{\gamma}+p_{\gamma} \partial f / \partial p_{\beta}\right] \end{aligned}
$$


$$
\begin{aligned}
	 \dot{p_1} &= \frac{ \partial H}{\partial q^1} =  \frac{a q_1}{(q_1^2 + q_2^2)^{\frac{3}{2}}} - bp_1 \\
	 \dot{p_2} &= \frac{ \partial H}{\partial q^2} = \frac{aq_2}{(q_1^2 + q_2^2)^{\frac{3}{2}}} \\
	 \dot{p_3} &= \frac{ \partial H}{\partial q^3} = 0\\
\end{aligned}
$$


### Coordenadas unificadas

$$
H(\xi^i) = \frac{1}{2m} \xi^{j} \xi_{j} + \frac{a}{\sqrt{(\xi^1)^2 + (\xi^2)^2}} - b \xi^1 \xi_4 \quad j = 4, 5, 6.
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

La derivada de Lie a lo largo del vector dinámico $\Delta$ da la evolución de g:

$$
\mathcal{L}_{\Delta}g = \frac{d}{dt} g =\partial_j f \dot{\xi}^j = \partial_j f \omega^{jk} \partial_k H = \{g,H\}
$$

1. Construir $\Delta_H$:

$$
\begin{aligned}
	 \Delta_H \Omega &= -dH \\
	 \Delta_H &= \omega^{jk} \partial_k H \partial_j
\end{aligned}
$$

2. Encontrar curvas integrales $\gamma_H$:

$$
\dot{\gamma}_H =\Delta_H = \frac{d\gamma_H}{dt}
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

## Teorema de Darboux

Existe una carta local en la que:

$$
\Omega = dp_\alpha \wedge dq^\alpha = \frac{1}{2} \omega_{ij} d\xi ^i \wedge d\xi^j
$$

1. Elegir una variable dinámica $g$.
2. Encontar $f$ tal que $\{f, g \} = 1$

$$
\Omega = dg \wedge df+ \Omega | _{\mathcal{L}_g}
$$

Con $\Omega | _{\mathcal{L}_g}$ una restricción en la variedad a $g$ constante y $\mathcal{L}_g$ una variedad de dimensión $2n-2$

> Written with [StackEdit](https://stackedit.io/).

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTk2MDQyODg0LC04Nzk4MTA2NDEsLTMwNT
gwODUxMiwtMTk0MTkwNTMwMywxNjUwODkyOTIxLDE5Mjk2MTY3
OTIsLTE5NTA1ODI5NzcsLTE0NjAzMjc4NzAsNzMwOTk4MTE2XX
0=
-->