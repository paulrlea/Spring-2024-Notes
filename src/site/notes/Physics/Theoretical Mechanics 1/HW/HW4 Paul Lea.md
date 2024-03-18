---
{"dg-publish":true,"permalink":"/physics/theoretical-mechanics-1/hw/hw-4-paul-lea/"}
---

1. Write down the Lagrangian $L(x_{1},x_{2},\dot{x}_{1},\dot{x}_{2})$ for two particles of equal mass confined to the x axis and connected by a spring of with potential energy $U=\frac{1}{2}k(x_{1}-x_{2})^{2}$. Calculate Lagrange's diff. equations for each mass, i.e $\frac{d}{dt}\frac{ \partial L }{ \partial \dot{x}_{1} }-\frac{ \partial L }{ \partial x_{1} }=0$
$$
L = \frac{1}{2}m(\dot{x}_{1}^{2}+\dot{x}_{2}^{2}) - \frac{1}{2}k(x_{1}-x_{2})^{2}
$$
$$
L = \frac{1}{2}m(\dot{x}_{1}^{2}+\dot{x}_{2}^{2}) - \frac{1}{2}k(x_{1}^{2}+x_{2}^{2}-2x_{1}x_{2})
$$
$$
\frac{ \partial L }{ \partial \dot{x}_{1} }  = m\dot{x}_{1}
$$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{x}_{1} }  = m\ddot{x}_{1}
$$
$$
\frac{ \partial L }{ \partial x_{1} } = -kx_{1}+kx_{2} = 0
$$
$$
m\ddot{x}_{1}+kx_{1}-kx_{2} = 0
$$
$$
\frac{ \partial L }{ \partial \dot{x}_{2} } = m\dot{x}_{2} 
$$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{x}_{2} } = m\ddot{x}_{2}
$$
$$
\frac{ \partial L }{ \partial x_{2} }  = -kx_{2}+kx_{1}
$$
$$
m\ddot{x}_{2}+kx_{2}-kx_{1}=0
$$
B. Rewrite the Lagrangian L in terms of new variables $X_{cm} =\frac{1}{2}(x_{1}+x_{2})$ (the center-of- mass position) $x=x_{1}-x_{2}$ (relative distance between mass 1 and 2). The mass 1 remains at all times to the right of mass 2.
$$
L = \frac{1}{2}m(\dot{x}^{2}_{1}+\dot{x}^{2}_{2}) - \frac{1}{2}k(x_{1}-x_{2})^{2}
$$
$$
\dot{X}_{cm} = \frac{1}{2}(\dot{x}_{1}+\dot{x}_{2}); \ \ \ \dot{x} = \dot{x}_{1}-\dot{x}_{2}
$$
$$
L = m\dot{X}_{cm}^{2} + \frac{1}{2} \frac{1}{2}m\dot{x}^{2}-\frac{1}{2}kx^{2}
$$

$$
L = m\dot{X}_{cm}^{2} + \frac{1}{4}m\dot{x}^{2}-\frac{1}{2}kx^{2}
$$
C. Calculate Lagrange’s equations of motion of $X_{cm}$ and $x$. Solve the differential equations for $X_{cm}(t)$ and $x(t)$ and describe the motion (using full sentences).
Solving for $X_{cm}$
$$
\frac{ \partial L }{ \partial \dot{X}_{cm} }  = 2m\dot{X}_{cm}
$$
$$
\frac{d}{dt}  \frac{ \partial L }{ \partial \dot{X}_{cm} }  = 2m\ddot{X}_{cm}
$$
$$
\frac{ \partial L }{ \partial X_{cm} }  = 0
$$
$$
m\ddot{X}_{cm} = 0 
$$
$$
\iint m\ddot{X}_{cm}t=0 \therefore \ddot{X}_{cm} = 0
$$
$$
X_{cm}(t) = V_{0}t+X_{cm_{0}}
$$
The center of mass moves like a free particle
Solving for $x$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{x} } = \frac{1}{2}m\ddot{x}
$$
$$
\frac{ \partial L }{ \partial x } =-kx
$$
$$
2m\ddot{x}+kx=0
$$
Solve diffeq
$$
\frac{1}{2}m\ddot{x} =- kx \to \ddot{x} = -\frac{2kx}{m}
$$
$$
x(t) = c_2 \sin\left(\frac{\sqrt{2}\sqrt{k}t}{\sqrt{m}}\right) + c_1 \cos\left(\frac{\sqrt{2}\sqrt{k}t}{\sqrt{m}}\right)

$$
This will oscillate with angular frequency $\omega$ given by $\frac{2k}{m}$, which makes sense because without friction or gravity it will continue to oscillate indefinitely, unless $x=0$, because then there will be no potential energy. 

d. Consider the differential equations for x1 and x2 and compare them to the differential equations obtained for XCM and x. What is gained by introducing XCM and x?

By using $X_{cm}$ and $x$ we are able to get a more useful picture of the motion of the system as a whole. We are able to determine that the motion of the center of mass is not affected by the motion of the individual blocks relative to each other, and the motion of the individual blocks takes on the form of an oscillator with angular frequency given by $\frac{2k}{m}$.

2.  Consider a double pendulum made of two masses, m1 and m2, and two mass-less rods of lengths l1 and l2, as shown in the Figure (assume gravitational acceleration points down the page). The black point at the top of the Figure is a stationary anchor point.
a. Find the Lagrangian for the system in terms of $\theta_{1}$ and $\theta_{2}$
Solving for kinetic energy 
$$
x_{1} = L_{1}\sin\theta_{1} \to \dot{x}_{1} = L_{1}\dot{\theta}_{1}\cos \theta_{1}
$$
$$
y_{1} = L_{1}\cos\theta_{1} \to \dot{y}_{1}=-L_{1}\dot{\theta}_{1}\sin\theta_{1}
$$
$$
\mathbf{r_{1}} = L_{1}(\sin\theta_{1}),L_{1}(\cos\theta_{1})\tag{1}
$$
$$
T_{1} = \frac{1}{2}m_{1}(L_{1}^{2}\dot{\theta}_{1}^{2}\cos ^{2}\theta_{1}+L_{1}^{2}\dot{\theta}_{1}^{2}\sin ^{2}\theta_{1}) 
$$
$$
T_{1} = \frac{1}{2}m_{1}L_{1}^{2}\dot{\theta}_{1}^{2}
$$
Solving for energy of block 2 
Position: (refer to eq.1 above)
$$
\mathbf{r}_{1} + L_{2}(\sin\theta_{2})\mathbf{i} + L_{2}(\cos\theta_{2})\mathbf{j}
$$
Solve for velocity:
Take velocity from above (1st particle) and add:
$$
L_{2}\dot{\theta}_{2}(\cos\theta_{2}\mathbf{i}-\sin\theta_{2}\mathbf{j})
$$
Now it gets messy
Put it all together and solve for energy: 
$$
T_{2}=\frac{1}{2}m_{2}(L_{1}^{2}\dot{\theta}_{1}^{2}+L_{2}^{2}\dot{\theta}^{2}_{2}+2L_{1}L_{2}\dot{\theta}_{1}\dot{\theta}_{2}\cos(\theta_{2}-\theta_{1}))
$$
Solving for gravitational potential energy of block 1. We can take the "0 position" to be when both masses are pointed straight down.
$$
U = mgh
$$
$$
U_{1}=-m_{1}gy_{1} = -m_{1}gL_{1}\cos\theta_{1}
$$
Solving for gravitational potential energy of block 2
$$
U = mgh
$$
$$
U_{2} = -m_{2}gy_{2} = -m_{2}g(L_{1}\cos\theta_{1}+L_{2}\cos\theta_{2})
$$
Add and simplify
$$
U_\text{total}=-m_{1}gL_{1}\cos\theta_{1} -m_{2}g(L_{1}\cos\theta_{1}+L_{2}\cos\theta_{2})
$$
$$
U = -(m_{1}+m_{2})gL_{1}\cos\theta_{1}-m_{2}gL_{2}\cos\theta_{2}
$$
Now find the Lagrangian: 
$$
L=T-U
$$
$$
L=\frac{1}{2}m_{2}(L_{1}^{2}\dot{\theta}_{1}^{2}+L_{2}^{2}\dot{\theta}^{2}_{2}+2L_{1}L_{2}\dot{\theta}_{1}\dot{\theta}_{2}\cos(\theta_{2}-\theta_{1})) + \frac{1}{2}m_{1}L_{1}^{2}\dot{\theta}_{1}^{2}\dots
$$
$$
+(m_{1}+m_{2})gL_{1}\cos\theta_{1}-m_{2}gL_{2}\cos\theta_{2}
$$
(b) Now, simplify your Lagrangian using the assumption that the masses are identical and the lengths of the rods are identical. Using this simplified Lagrangian find the differential equations for θ1 and θ2.
$$
L = \frac{1}{2}m(L^{2}\dot{\theta}_{1}^{2}+L\dot{\theta}^{2}_{2}+2mL^{2}\dot{\theta}_{1}\dot{\theta}_{2}\cos(\theta_{2}-\theta_{1})) + \frac{1}{2}mL^{2}\dot{\theta}_{1}^{2}\dots
$$
$$
+2mgL\cos\theta_{1}-mgL\cos\theta_{2}
$$
$$
\frac{ \partial L }{ \partial \dot{\theta}_{1} }  = mL^{2}\dot{\theta}_{1} + mL^{2}\dot{\theta}_{1} + L^{2}\dot{\theta}_{2}\cos(\theta_{2}-\theta_{1}) = 2mL^{2}\theta_{1}+L^{2}\dot{\theta}_{2}\cos(\theta_{2}-\theta_{1})
$$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{\theta}_{1} } =2mL^{2}\ddot{\theta}_{1} + L^{2}(\ddot{\theta}_{2}\cos(\theta_{2}-\theta_{1}) - \dot{\theta}_{2}(\dot{\theta}_{2}-\dot{\theta}_{1})\sin(\theta_{2}-\theta_{1}))
$$
$$
\frac{ \partial L }{ \partial \theta_{1} } = L^{2}\dot{\theta}_{1}\dot{\theta}_{2} \sin (\theta_{2}-\theta_{1})+mgL\sin\theta_{1}
$$
E-L for $\theta_{1}$
$$
2mL^{2}\ddot{\theta}_{1} + L^{2}(\ddot{\theta}_{2}\cos(\theta_{2}-\theta_{1}) - \dot{\theta}_{2}(\dot{\theta}_{2}-\dot{\theta}_{1})\sin(\theta_{2}-\theta_{1})) \dots
$$
$$
-L^{2}\dot{\theta}_{1}\dot{\theta}_{2} \sin (\theta_{2}-\theta_{1}) - mgL\sin\theta_{1} = 0
$$

Solving for $\theta_{2}$ E-L equation
 $$
\frac{ \partial L }{ \partial \dot{\theta}_{2} } =  mL^{2}\dot{\theta}_{2} + mL^{2}\dot{\theta}_{2} + L^{2}\dot{\theta}_{1}\cos(\theta_{2}-\theta_{1}) = 2mL^{2}\dot{\theta}_{2}+L^{2}\dot{\theta}_{1}\cos(\theta_{2}-\theta_{1})
$$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{\theta}_{2} }=2mL^{2}\ddot{\theta}_{2} + L^{2}(\ddot{\theta}_{1}\cos(\theta_{2}-\theta_{1}) - \dot{\theta}_{1}(\dot{\theta}_{2}-\dot{\theta}_{1})\sin(\theta_{2}-\theta_{1})) 
$$
$$
\frac{ \partial L }{ \partial \theta_{2} } = -L^{2}\dot{\theta}_{1}\dot{\theta}_{2} \sin (\theta_{2}-\theta_{1})+mgL\sin\theta_{1}
$$
E-L for $\theta_{2}$
$$
2mL^{2}\ddot{\theta}_{2} + L^{2}(\ddot{\theta}_{1}\cos(\theta_{2}-\theta_{1}) - \dot{\theta}_{1}(\dot{\theta}_{2}-\dot{\theta}_{1})\sin(\theta_{2}-\theta_{1}))  \dots
$$
$$
+L^{2}\dot{\theta}_{1}\dot{\theta}_{2} \sin (\theta_{2}-\theta_{1})-mgL\sin\theta_{1} = 0
$$
(c) Simplify your equations of motion for the case of small angle oscillations. To do this keep only the leading terms of the approximations
For $\theta_{1}$
$$
2mL^{2}\ddot{\theta}_{1} + L^{2}(\ddot{\theta}_{2}\cos(\theta_{2}-\theta_{1}) - \dot{\theta}_{2}(\dot{\theta}_{2}-\dot{\theta}_{1})\sin(\theta_{2}-\theta_{1})) \dots
$$
$$
-L^{2}\dot{\theta}_{1}\dot{\theta}_{2} \sin (\theta_{2}-\theta_{1}) - mgL\sin\theta_{1} = 0
$$
$$
\approx
$$
$$
2mL^{2}\ddot{\theta}_{1} + L^{2}\ddot{\theta}_{2}-L^{2}\dot{\theta}_{2}(\dot{\theta}_{2}-\dot{\theta}_{1})(\theta_{2}-\theta_{1})-L^{2}\dot{\theta}_{1}\dot{\theta}_{2}(\theta_{2}-\theta_{1})-mgL\theta_{1}=0
$$
For $\theta_{2}$
$$
2mL^{2}\ddot{\theta}_{2} + L^{2}(\ddot{\theta}_{1}\cos(\theta_{2}-\theta_{1}) - \dot{\theta}_{1}(\dot{\theta}_{2}-\dot{\theta}_{1})\sin(\theta_{2}-\theta_{1}))  \dots
$$
$$
+L^{2}\dot{\theta}_{1}\dot{\theta}_{2} \sin (\theta_{2}-\theta_{1})-mgL\sin\theta_{1} = 0
$$
$$
\approx
$$
$$
2mL^{2}\ddot{\theta}_{2}+L^{2}\ddot{\theta}_{1}-L^{2}\dot{\theta}_{1}(\dot{\theta}_{2}-\dot{\theta}_{1})(\theta_{2}-\theta_{1}) + L^{2}\dot{\theta}_{1}\dot{\theta}_{2}(\theta_{2}-\theta_{1}) - mgL\theta_{1}=0
$$


3. A block of mass m is held motionless on a friction-less plane of mass M and an angle of inclination θ. The plane rests on a friction-less horizontal surface. The block is released from rest. Find the Lagrangian L of the block and the plane and Lagrange’s equations of motion. Solve for the accelerations of the blocks in terms of g, m, M, and θ.
$$
L = T - U 
$$
$$
T_{m} = \frac{1}{2}mv_{x}^{2} + \frac{1}{2}mv_{y}^{2}
$$
$$
T_{M} = \frac{1}{2}M\dot{x}_{1}^{2}
$$
$$
T_{total} =\frac{1}{2}m\dot{x}_{2}^{2} + \frac{1}{2}m[(\dot{x}_{1}+\dot{x}_{2})^{2}\tan ^{2}\theta]+\frac{1}{2}M\dot{x}_{1}^{2}
$$
$$
U = -mg[(x_{1}+x2)\tan\theta]
$$
$$
L=\frac{1}{2}m\dot{x}_{2}^{2} + \frac{1}{2}m[(\dot{x}_{1}+\dot{x}_{2})^{2}\tan ^{2}\theta] + \frac{1}{2}M\dot{x}^{2}_{1}+mg[(x_{1}+x_{2})\tan\theta]
$$
$$
L = \frac{1}{2}m\dot{x}_{2}^{2} + \frac{1}{2}m\tan ^{2}\theta(\dot{x}_{1}^{2}+\dot{x}_{2}^{2}+2\dot{x}_{1}\dot{x}_{2}) + \frac{1}{2}M\dot{x}_{1}^{2} + mg\tan\theta(x_{1}+x_{2})
$$
Finding [[Physics/Theoretical Mechanics 1/Class Notes/Concepts/Euler-Lagrange Equation\|Euler-Lagrange Equation]] for $x_{1}$
$$
\frac{ \partial L }{ \partial \dot{x}_{1} } = M\dot{x}_{1}+m\dot{x}_{1}\tan ^{2}\theta +m\dot{x}_{2}\tan ^{2}\theta
$$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{x}_{1} } = M\ddot{x}_{1}+m\ddot{x}_{1}\tan ^{2}\theta+m\ddot{x}_{2}\tan ^{2}\theta
$$
$$
\frac{ \partial L }{ \partial x_{1} }  = mg\tan \theta
$$
Euler Lagrange for $x_{1}$
$$
M\ddot{x}_{1}+m\ddot{x}_{1}\tan ^{2}\theta+m\ddot{x}_{2}\tan ^{2}\theta - mg\tan \theta = 0 
$$
Finding Euler Lagrange for $x_{2}$
$$
\frac{ \partial L }{ \partial \dot{x}_{2} } = m\dot{x}_{2} + m\dot{x}_{2}\tan ^{2}\theta + m\dot{x}_{1}\tan ^{2}\theta
$$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{x}_{2} }  = m\ddot{x}_{2} + m\ddot{x}_{2}\tan ^{2}\theta + m\ddot{x}_{1}\tan ^{2}\theta
$$
$$
\frac{ \partial L }{ \partial x_{2} } =mg\tan\theta
$$
Euler Lagrange for $x_{2}$ 
$$
m\ddot{x}_{2} + m\ddot{x}_{2}\tan ^{2}\theta + m\ddot{x}_{1}\tan ^{2}\theta-mg\tan\theta = 0
$$
Solving for acceleration, setting acceleration terms from both E-L equations equal to each other
$$
m\ddot{x}_{2} + m\ddot{x}_{2}\tan ^{2}\theta + m\ddot{x}_{1}\tan ^{2}\theta = M\ddot{x}_{1}+m\ddot{x}_{1}\tan ^{2}\theta+m\ddot{x}_{2}\tan ^{2}\theta
$$
Solve for $\ddot{x}_{1}$
$$
m\ddot{x}_{2} = M\ddot{x}_{1} \to \frac{m\ddot{x}_{2}}{M} =\ddot{x}_{1}
$$
Sub into E-L for $x_{2}$
$$
m\ddot{x}_{2}+m\ddot{x}_{2}\tan ^{2}\theta+m\left( \frac{m\ddot{x}_{2}}{M} \right) \tan ^{2}\theta = mg\tan\theta
$$
$$
\ddot{x}_{2}\left( m+m\tan ^{2}\theta+\frac{m^{2}}{M}\tan ^{2}\theta \right) = mg\tan\theta
$$
$$
\ddot{x}_{2} = \frac{g\tan\theta}{1+\tan ^{2}\theta+\frac{m}{M}\tan ^{2}\theta}
$$
Solve for $\ddot{x}_{2}$
$$
m\ddot{x}_{2}=M\ddot{x}_{1} \to \ddot{x}_{2} = \frac{M\ddot{x}_{1}}{m}
$$
Sub into E-L for $x_{1}$ 
$$
M\ddot{x}_{1}+m\ddot{x}_{1}\tan ^{2}\theta+m\frac{M\ddot{x}_{1}}{m}\tan ^{2}\theta - mg\tan \theta = 0 
$$
$$
M\ddot{x}_{1}+m\ddot{x}_{1}\tan ^{2}\theta +M\ddot{x}_{1} \tan ^{2}\theta-mg\tan\theta = 0
$$
$$
M\ddot{x}_{1} + m\ddot{x}_{1}\tan ^{2}\theta+M\ddot{x}_{1}\tan ^{2}\theta = mg\tan\theta
$$
$$
\ddot{x}_{1}(M+m\tan ^{2}\theta+M\tan ^{2}\theta) =mg\tan\theta
$$
$$
\ddot{x}_{1}=\frac{mg\tan\theta}{M+m\tan ^{2}\theta+M\tan ^{2}\theta}
$$
Now we have the x component of acceleration for both blocks. Lets find the y-axis acceleration for the block. 
$$
\ddot{y} = (\ddot{x}_{1}+\ddot{x}_{2})\tan\theta
$$
$$
\ddot{y} = \left( \frac{mg\tan\theta}{M+m\tan ^{2}\theta+M\tan ^{2}\theta} +  \frac{g\tan\theta}{1+\tan ^{2}\theta+\frac{m}{M}\tan ^{2}\theta} \right)\tan\theta
$$
$$
\ddot{y} = \frac{mg\tan ^{2}\theta}{M+m\tan ^{2}\theta+M\tan ^{2}\theta} +  \frac{g\tan ^{2}\theta}{1+\tan ^{2}\theta+\frac{m}{M}\tan ^{2}\theta} 
$$











 

