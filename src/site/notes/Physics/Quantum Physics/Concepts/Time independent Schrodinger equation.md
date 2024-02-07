---
{"dg-publish":true,"permalink":"/physics/quantum-physics/concepts/time-independent-schrodinger-equation/"}
---

#learning 
The [[Physics/Quantum Physics/Concepts/Schrodinger equation\|Schrodinger equation]] in a single dimension can be reduced to two ordinary differential equations through separation of variables. This yields one equation that is dependent on time, and one that is time independent. It is also known as the [[Physics/Quantum Physics/energy eigenvalue equation\|energy eigenvalue equation]]. 
$$
-\frac{\hbar^{2}}{2m} \frac{\partial\Psi(x,t)}{\partial x^2} + V(x)\Psi(x,t) = i\hbar  \frac{\partial\Psi(x,t)}{\partial t}
$$
Above is the Schrodinger Equation. It can be solved for a free particle. See  (i.e no potential energy, $V(x)$ term is zero). 

When $V(x)$ is independent of time, we can separate the [[Physics/Quantum Physics/Concepts/Schrodinger equation\|Schrodinger equation]] into 
$$
\frac{df(t)}{dt} = -\frac{iE}{\hbar}f(t)
$$
and
$$
-\frac{\hbar^2}{2m} \frac{\partial\psi(x,t)}{\partial x^2} + V(x)\psi(x) = E\psi(x)
$$
	The latter is known as the [[Physics/Quantum Physics/Concepts/Time independent Schrodinger equation\|Time independent Schrodinger equation]], while the former can be rather easily solved using an [[ansatz\|ansatz]] of $F(t) =f(0)e^{-iEt/\hbar}$ , or $F(t) =f(0)e^{i\omega}$ where $E = \hbar \omega$ . 

**NB**:
$$
|\Psi(x,t)|^2 = |\Psi(x)|^2
$$
Probability is Independent of time

Using the [[Physics/Quantum Physics/Concepts/Time independent Schrodinger equation\|Physics/Quantum Physics/Concepts/Time independent Schrodinger equation]], and a suitable $V(x)$ we can model a "particle in a box", also known as an [[Physics/Quantum Physics/Concepts/Infinite square well\|Infinite square well]]. We can also use the [[Physics/Quantum Physics/Concepts/Time independent Schrodinger equation\|Physics/Quantum Physics/Concepts/Time independent Schrodinger equation]] to model [[Physics/Quantum Physics/Concepts/Step Potentials\|Step Potentials]] as seen later on. 