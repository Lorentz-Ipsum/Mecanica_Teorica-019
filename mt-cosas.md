

1. Mecánica lagrangiana
1.1. Dinámica lagrangiana: Espacio de configuración, trayectorias y variaciones infinitesimales, principio variacional, ecuaciones de Euler-Lagrange, características de la acción, ligaduras.
1.2. Cantidades conservadas: Teorema de Noether, coordenadas cíclicas, teorema de Noether, variaciones temporales, energía, partícula en un potencial, invariancia bajo reparametrizaciones temporales, simetrías gauge.
1.3. Dinámica relativista: Acción: Partículas libres y partículas en un campo electromagnético, ecuaciones de movimiento, cantidades conservadas: Cuadrimomento, momento angular cuadridimensional, centro de inercia e invariantes de Casimir.

2. Mecánica hamiltoniana
2.1. Sistemas hamiltonianos: Transformación de Legendre, ecuaciones de Hamilton, espacio de fases, corchetes de Poisson.
2.2. Geometría simpléctica: Forma simpléctica, ecuaciones de Hamilton, flujos hamiltonianos, flujo de un campo vectorial, campos vectoriales hamiltonianos, teorema de Noether, variedades simplécticas, teorema de Darboux y reducción por simetría.
2.3. Transformaciones canónicas: Simplectomorfismos, transformaciones canonoides, función generatriz y tipos de transformaciones canónicas.
2.4. Invariantes: Teorema de Liouville, distribuciones estadísticas, invariante integral de Poincaré, espacio de fases extendido, invariante integral de Poincaré-Cartan y cantidades conservadas.

3. Integrabilidad
3.1. Teoría de Hamilton-Jacobi: ecuación de Hamilton-Jacobi, función principal de Hamilton, soluciones completas, separación de variables, hamiltonianos conservados, coordenadas cíclicas, variables separables, teorema de Huygens y analogía óptica,
3.2. Teoremas de integrabilidad: teorema de Liouville, teorema de Arnold, variables de acción-ángulo, movimiento condicionalmente periódico.

4. Temas de especialización:
4.1. Teoría cláscia de campos
4.2. Perturbaciones
4.3. Caos
4.4. Dinámica de Fluidos

# T2 2. Mecánica hamiltoniana
2.1. Sistemas hamiltonianos: Transformación de Legendre, ecuaciones de Hamilton, espacio de fases, corchetes de Poisson.
2.2. Geometría simpléctica: Forma simpléctica, ecuaciones de Hamilton, flujos hamiltonianos, flujo de un campo vectorial, campos vectoriales hamiltonianos, teorema de Noether, variedades simplécticas, teorema de Darboux y reducción por simetría.
2.3. Transformaciones canónicas: Simplectomorfismos, transformaciones canonoides, función generatriz y tipos de transformaciones canónicas.
2.4. Invariantes: Teorema de Liouville, distribuciones estadísticas, invariante integral de Poincaré, espacio de fases extendido, invariante integral de Poincaré-Cartan y cantidades conservadas.

## Wikipedia
### Mecanica avanzada
$\begin{matrix}
T\mathcal{M} & \to & T^*\mathcal{M} \\
\mathbf{v} & \to & i_\mathbf{v}\omega=\omega(\mathbf{v},\cdot)
\end{matrix}$

$i_\mathbf{v}\omega = \mathrm{d}\hat{H}$

$\mathbf{v}|_\phi =
\begin{bmatrix} \dot{p}_1\\ \dots\\ \dot{p}_N\\ \dot{q}_1\\ \dots\\ \dot{q}_N\\ \end{bmatrix}
\qquad \mathbf{\hat{H}}|_\phi^T = \begin{bmatrix} \frac{\partial H}{\partial p_1}\\ \dots\\ \frac{\partial H}{\partial p_N}\\ \frac{\partial H}{\partial q_1}\\ \dots\\ \frac{\partial H}{\partial q_N}\\ \end{bmatrix}
\qquad \omega|_\phi = \begin{bmatrix}
0     & \dots & 0     & -1   & \dots & 0    \\
\dots & \dots & \dots &\dots & \dots & \dots\\
0     & \dots & 0     & 0    & \dots & -1   \\
1     & \dots & 0     & 0    & \dots & 0    \\
\dots & \dots & \dots &\dots & \dots & \dots\\
0     & \dots & 1     & 0    & \dots & 0    \\   \end{bmatrix}$

$i_\mathbf{v}\omega|_phi = \mathrm{d}\hat{H}|_\phi \Rightarrow 
\begin{bmatrix} \dot{p}_1\\ \dots\\ \dot{p}_N\\ \dot{q}_1\\ \dots\\ \dot{q}_N\\ \end{bmatrix} =
\begin{bmatrix}
  0     & \dots & 0     & -1   & \dots & 0    \\
  \dots & \dots & \dots &\dots & \dots & \dots\\
  0     & \dots & 0     & 0    & \dots & -1   \\
  1     & \dots & 0     & 0    & \dots & 0    \\
  \dots & \dots & \dots &\dots & \dots & \dots\\
  0     & \dots & 1     & 0    & \dots & 0    \end{bmatrix}
\begin{bmatrix}
\frac{\partial H}{\partial q_1}\\ \dots\\ \frac{\partial H}{\partial q_N}\\ \frac{\partial H}{\partial p_1}\\ \dots\\ \frac{\partial H}{\partial p_N} \end{bmatrix}
\Rightarrow \begin{cases}
   \dot{p}_i = -\cfrac{\partial H}{\partial q_i}\\
   \dot{q}_i = +\cfrac{\partial H}{\partial p_i} \end{cases}$


#### Flujo hamiltoniano
La función diferenciable <math>\hat{H}</math> a través de la ecuación {{eqnref|5}} un campo vectorial continuo sobre toda la variedad simpléctica. Las [[Curva integral de un campo vectorial|curvas integrales]] de este campo vectorial son las trayectorias de las partículas a lo largo del espacio fásico. Esas curvas definen una [[foliación]] unidimensional o flujo hamiltoniano sobre la variedad. De hecho para cada intervalo de tiempo ''s'' se puede definir una aplicación:
{{ecuación|
<math>U_s(p(t),q(t)) = (p(t+s),q(t+s))\;</math>
||left}}
De hecho la anterior aplicación es una [[transformación canónica]] o [[simplectomorfismo]]. El conjunto <math>\{U_s:\mathcal{M}\to\mathcal{M}| s\in\mathbb{R}\}</math> de todas las aplicaciones anteriores constituye un [[grupo uniparamétrico]] de simplectomorfismos. Si consideramos cualquier magnitud física definida como una función diferenciable sobre la variedad simpléctica, su variación a lo largo de una trayectoria, viene dada por la siguiente derivada temporal:
{{ecuación|
<math>\frac{d}{dt} f=\{f,\hat{H}\} = -(i_{\tilde{\omega}(\mathrm{d}H)}\omega)(\mathrm{d}f)</math>
||left}}
Tal como se demuestra más adelante. De hecho en mecánica estadística se usan [[distribución de probabilidad|distribuciones de probabilidad]] sobre el espacio fásico. Fijada una distribución ρ esta en general "evolucionará" con el tiempo según la ley:
{{ecuación|
<math>\frac{d\rho}{dt}  = - \{\rho , \hat{H}\}.</math>
|6|left}}
Esta última expresión se llama [[Teorema de Liouville (mecánica hamiltoniana)#Ecuación de Liouville|ecuación de Liouville]], en particular una distribución tal que el corchete de Poisson con el hamiltoniano se anule se llama '''distribución estacionaria'''.

Cada función diferenciable G, sobre la [[variedad simpléctica]] genera una familia uniparamétrica de [[simplectomorfismo]]s y si {G, H}=0, entonces G se conserva y los simplectomorfismos son transformaciones de simetría.

#### Álgebra de Poisson
{{AP|Álgebra de Poisson}}
A su vez el corchete de Poisson se expresa de modo muy simple en términos de la función inversa de <math>i_{(\cdot)}\omega</math> denotada mendiante <math>\tilde{\omega}</math>:
{{ecuación|

$[F,G] = (i_{\tilde{\omega}(\mathrm{d}F)}\omega)(\mathrm{d}G)\;$

Hay otra generalización que podemos hacer. En vez simplemente de mirar el [[álgebra asociativa|álgebra]] de funciones diferenciables sobre una [[variedad simpléctica]], la mecánica hamiltoniana se puede formular como un álgebra de Poisson [[número real|real]] [[unital]] [[Conmutatividad|comutativa]] general.

En esta formulación alternativa un [[estado (análisis funcional)|estado]] es una [[funcional lineal]] [[Continuidad (matemática)|continua]] en el álgebra de Poisson <math>\mathcal{A}</math>, equipada de alguna [[espacio topológico|estructura topológica]] conveniente. Las álgebras de Poisson son importantes en el estudio de [[grupo cuántico|grupos cuánticos]]<ref>[http://arxiv.org/PS_cache/q-alg/pdf/9704/9704002v2.pdf introduction to Quantum groups (inglés)]</ref> usados en la [[teoría cuántica de campos]] conforme, algunos modelos de [[cuantización]] de [[espacio-tiempo]], etc.


## Prueba 1
### 2.1. Sistemas hamiltonianos: 
Transformación de Legendre, ecuaciones de Hamilton, espacio de fases, corchetes de Poisson.

### 2.2. Geometría simpléctica: 
Forma simpléctica, ecuaciones de Hamilton, flujos hamiltonianos, flujo de un campo vectorial, campos vectoriales hamiltonianos, teorema de Noether, variedades simplécticas, teorema de Darboux y reducción por simetría.

### 2.3. Transformaciones canónicas: 
Simplectomorfismos, transformaciones canonoides, función generatriz y tipos de transformaciones canónicas.

### 2.4. Invariantes: 
Teorema de Liouville, distribuciones estadísticas, invariante integral de Poincaré, espacio de fases extendido, invariante integral de Poincaré-Cartan y cantidades conservadas.



# Trabajo Campos Clasicos

https://es.wikipedia.org/wiki/Campo_de_Yang-Mills

https://es.wikipedia.org/wiki/Teor%C3%ADa_de_campos

https://es.wikipedia.org/wiki/Transici%C3%B3n_de_fase

https://en.wikipedia.org/wiki/Ginzburg%E2%80%93Landau_theory

https://en.wikipedia.org/wiki/Thermodynamic_free_energy

SCH: classical field phase transition
SCH: abrikosov phase transitions
SCH: field phase transitions
SCH: classical fields phase transition

https://en.wikipedia.org/wiki/Continuum_percolation_theory

https://en.wikipedia.org/wiki/Percolation_theory

https://en.wikipedia.org/wiki/Topological_quantum_field_theory

https://books.google.es/books?id=qZbhBwAAQBAJ&pg=PA833&lpg=PA833&dq=classical+fields+phase+transition&source=bl&ots=QCjNtsWf8W&sig=ACfU3U1WLqvH6CmcIut8fVSs_WN4F_JtFg&hl=es&sa=X&ved=2ahUKEwjn2MnJ_8blAhWOHRQKHa0eCqY4ChDoATAHegQICBAB#v=onepage&q=classical%20fields%20phase%20transition&f=false

https://www.researchgate.net/publication/229025146_Phase_Transitions_and_Collective_Phenomena

https://www.researchgate.net/figure/Comparison-of-the-time-evolution-with-quantum-and-classical-fields-Lattice-site_fig5_323549977

https://iopscience.iop.org/article/10.1088/1751-8121/aaea02/meta

https://books.google.es/books?id=-mRdGjStX-4C&pg=PA61&lpg=PA61&dq=classical+fields+phase+transition&source=bl&ots=TSVUJi2HAF&sig=ACfU3U0KEiex61doz9QuoK03iSzctJzCcg&hl=es&sa=X&ved=2ahUKEwjn2MnJ_8blAhWOHRQKHa0eCqY4ChDoATAFegQIBxAB#v=onepage&q=classical%20fields%20phase%20transition&f=false

Jaeger, Gregg (1 May 1998). "The Ehrenfest Classification of Phase Transitions: Introduction and Evolution". _Archive for History of Exact Sciences_. **53** (1): 51–81.

Longo, G.; Montévil, M. (1 August 2011). ["From physics to biology by extending criticality and symmetry breakings"](https://www.academia.edu/23155991). _Progress in Biophysics and Molecular Biology_. Systems Biology and Cancer. **106** (2): 340–347. [arXiv](https://en.wikipedia.org/wiki/ArXiv "ArXiv"):[1103.1833](https://arxiv.org/abs/1103.1833).

## External links

![](https://upload.wikimedia.org/wikipedia/en/thumb/4/4a/Commons-logo.svg/30px-Commons-logo.svg.png)

Wikimedia Commons has media related to _**[Phase changes](https://commons.wikimedia.org/wiki/Category:Phase_changes "commons:Category:Phase changes")**_.

-   [Interactive Phase Transitions on lattices](http://www.ibiblio.org/e-notes/Perc/contents.htm) with Java applets
-   [Universality classes](http://www.sklogwiki.org/SklogWiki/index.php/Universality_classes) from Sklogwiki
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTA2OTgwNzM4MF19
-->