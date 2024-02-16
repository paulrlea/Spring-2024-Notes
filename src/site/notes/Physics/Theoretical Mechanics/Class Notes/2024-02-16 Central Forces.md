---
{"dg-publish":true,"permalink":"/physics/theoretical-mechanics/class-notes/2024-02-16-central-forces/"}
---

## Fields and forces
- Fields are a useful concept we use to describe action at a distance
- Examples include electricity, magnetism and gravitation. 
- There is a time dependent component to field that requires a certain amount of time for the field to "update" at a point 

## Gravitational Potential
- Gravitational potential $\neq$ Gravitational potential energy 
$$
\vec{g}  = -\vec{\nabla}\phi
$$
$$
-\frac{d\phi}{dr} = -\frac{GM}{r^{2}} \implies \phi=\frac{-GM}{r}
$$
- Force and Gravitational potential energy on one side, Fields and potentials on the other side. 
- This dichotomy divides between physical quantities and mathematical concepts.

> What is phi?

$$
\vec{F} = -\vec{\nabla}u
$$
$$
\vec{g} = -\vec{\nabla} \phi
$$
$$
\therefore u = m\phi
$$
For an extended object, the force of gravity is defined as below 
$$
\vec{F}_{g} = -Gm \int \frac{\rho(\vec{r})}{r^{2}}\hat{e}_{r} \, dV 
$$
How to get little g?
$$
\vec{g} = -G\int\limits_{V}^{} \frac{\rho(\vec{r})}{r^{2}}\hat{e}_{r} \, dV  
$$

	> Figure 1 here 
	
$$
\phi =  -\frac{Gm_{1}}{r_{1}}- \frac{Gm_{2}}{r_{2}}
$$
$$
-Gm\left( \frac{1}{r_{1}}+\frac{1}{r_{2}} \right)
$$
Want to generalize to all possible locations of $p$. 
$$
r_{1}= \sqrt{ (x-a)^{2}+y^{2} }
$$
$$
r^{2} = \sqrt{ (x+a)^{2}+y^{2} }
$$
$$
\phi= -Gm\left[ \frac{1}{\sqrt{V(x-a)^{2}  }}+ \frac{1}{\sqrt{(x+a)^{2}+y^{2}}} \right]
$$

