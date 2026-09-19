# Que es una onda electromagnética?

Una onda electromagnética es una perturbación del campo eléctrico y magnético, su característica primordial es que se propaga por el espacio transportando energía,también lo puede hacer en el vacío.Principalmente viajan a la velocidad de la luz,no necesitan de algún medio como el agua o el aire para propagarse, ya que esto lo realizan mediante oscilaciones de campos eléctricos y magnéticos, que se mantienen en retroalimentación de lazo cerrado.

<img src="../Imagenes/img2.png">

# Ecuaciones de Maxwell.

Las ecuaciones de maxwell son un conjunto de cuatro ecuaciones, las cuales tardaron al rededor de 9 años en formularse, ya que fue un conjunto de conocimiento de diferentes científicos como: 

* Johann Carl Friedrich Gauss
* Michael Faraday
* André-Marie Ampère 
* James Clerk Maxwell 

Maxwell científico el cual formula toda una teoría,en 1864 publica **A Dynamical Theory of the Electromagnetic Field** Una teoría dinámica del campo electromagnético.Con este conjunto de las cuatro ecuaciones de maxwell se explica cualquier fenómeno electromagnético.

## Johann Carl Friedrich Gauss
1.-Ley Campo electrico

El flujo de un campo eléctrico a traves de una superficie cerrada, es igual a la razón de la carga encerrada en esa superficie y la permitividad del vacío.

Forma integral:

$$
\oint_S \vec{E}\cdot d\vec{A}=\frac{Q_{\mathrm{enc}}}{\varepsilon_0}
$$

**Donde:**

- $Q_{\mathrm{enc}}$: carga encerrada dentro de la superficie.
- $\varepsilon_0$: permitividad eléctrica del vacío.

Forma diferencial:

$$
\nabla \cdot \vec{E} = \frac{\rho}{\varepsilon_0}
$$

2.- Ley de campo magnetico

Un campó  magnético es una region del espacio donde una carga en movimiento experimenta una fuerza.Se denota **B** y se mide en Teslas.

Forma integral

El flujo que atraviesa cualquier superficie cerrada siempre sera igual a cero.

$$
\oint_S \vec{B}\cdot d\vec{A} = 0
$$

Forma diferencial

La divergencia del campo magnético siempre sera cero en todo punto del espacio.

$$
\nabla \cdot \vec{B} = 0
$$

## Michael Faraday

Ley de faraday

Describe como un campo magnético que cambia en el tiempo genera un campo eléctrico.

Forma Integral

$$
\oint_C \vec{E}\cdot d\vec{l}=-\frac{d\Phi_B}{dt}
$$

**Donde:**

$$
\Phi_B=Flujo magnético
$$

$$
\Phi_B=\int_S \vec{B}\cdot d\vec{A}
$$

Ley de lenz

El campo eléctrico inducido se opone al cambio de flujo que lo genera.

$$
-\frac{d\Phi_B}{dt}
$$

Forma diferencial

El rotacional del campo eléctrico es igual a la derivada temporal del campo magnético en ese mismo punto.

$$
\nabla \times \vec{E}=-\frac{\partial \vec{B}}{\partial t}
$$

## André-Marie Ampère y James Clerk Maxwell

Ley de Ampere-Maxwell 

Esta ley principalmente describe como se genera un campo magnético a traves de una corriente como por un campo eléctrico que cambia en el tiempo.

$$
\oint_C \vec{B}\cdot d\vec{l}=\mu_0 I_{\mathrm{enc}}+\mu_0\varepsilon_0\frac{d\Phi_E}{dt}
$$

**Donde:**

$$
\Phi_E=Flujo electrico
$$

$\varepsilon_0$: permitividad eléctrica del vacío.
$\mu_0$: permeabilidad magnética del vacío.

$$
\Phi_E=\int_S \vec{E}\cdot d\vec{A}
$$

Forma diferencial

$$
\nabla\times\vec{B}=\mu_0\vec{J}+\mu_0\varepsilon_0\frac{\partial\vec{E}}{\partial t}
$$

**Donde:**

* $\nabla\times\vec{A}$: rotacional del campo A.
* $\vec{B}$: campo magnético.
* $\mu_0$: permeabilidad magnética del vacío.
* $\vec{J}$: densidad de corriente eléctrica.
* $\varepsilon_0$: permitividad eléctrica del vacío.
* $\frac{\partial\vec{E}}{\partial t}$: variación temporal del campo eléctrico.


Estas cuatro ecuaciones en conjunto forman toda la estructura electromagnética que nos ayuda a entender como se conforma el mundo de las comunicaciones.

# Derivación de la ecuación de onda para los campos Eléctrico y Magnético
