---
{"dg-publish":true,"permalink":"/physics/theoretical-mechanics-1/hw/hw-3-paul-lea/"}
---

### Question 1
Consider a box of mass m moving on a friction-less plane that forms an angle α with the horizontal. Assume that the box starts from rest on the inclined plane. Define one coordinate to point directly down the incline (with the slope) and a second coordinate that is measured horizontally across the slope (as shown in the image below). Make sure to clearly label each of your axes. (you can ignore the 3rd dimension which would be “up” from the face of the plane)

#### A. Write the Lagrangian for the problem

Up the slope is +y, to the right is +x
$$
L = T-U
$$
For y axis
$$
T = \frac{1}{2} m\dot{y}^{2}
$$
$$
U = mgh ; \ h = y\sin  \alpha
$$
$$
L(y) = \frac{1}{2}m\dot{y}^{2} - mgy\sin\alpha
$$
For x axis
$$
T= \frac{1}{2}m\dot{x}^{2}
$$
$$
U = 0 
$$
$$
L = \frac{1}{2}m\dot{x}^{2} -0 
$$
#### b.  Find and solve Lagrange equation
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{x} } - \frac{ \partial L }{ \partial x }  = 0
$$
For x axis: 
$$
\frac{d}{dt} \frac{ \partial \left( \frac{1}{2} m\dot{x}^{2} \right) }{ \partial \dot{x} } -\frac{ \partial \frac{1}{2}m\dot{x}^{2} }{ \partial x }  = 0
$$
$$
\frac{d}{dt} \left(m\dot{x} \right) -0 =0
$$
$$
m\ddot{x} =0
$$
$$
\frac{ d v }{ d t }  = 0 \to \text{constant} = v = v_{0}
$$
$$
v = \frac{dx}{dt} =v_{0} \to x = v_{0}t + x_{0}
$$
$$
x(t) = v_{0}t+ x_{0}
$$
For y axis: 
$$
\frac{d}{dt} \frac{ \partial (\frac{1}{2}m\dot{y}^{2} - mgy\sin\alpha) }{ \partial \dot{y} } -\frac{ \partial (\frac{1}{2}m\dot{y}^{2} - mgy\sin\alpha) }{ \partial y } =0
$$
$$
\frac{d}{dt} \left( m\dot{y} \right) - (-mg\sin\alpha) =0
$$
$$
m\ddot{y} + mg\sin\alpha = 0
$$
$$
\ddot{y} = -\frac{mg\sin\alpha}{m}
$$
$$
\ddot{y} = -g\sin\alpha
$$
$$
\dot{y} = -g\sin(\alpha)t  + v_{0}
$$
$$
y(t) = -g \sin(\alpha)t^{2} + v_{0}t +y_{0} 
$$
#### c. Redo the problem with Newtonian Mech.
In y direction
$$
F = ma
$$
$$
\frac{F}{m} = \ddot{y}
$$
$$
\frac{mg\sin\alpha}{m} = \ddot{y}
$$
$$
g\sin\alpha = \ddot{y}
$$
$$
\dot{y} = g\sin(\alpha) t + v_{0}
$$
$$
y = g\sin(\alpha)t^{2} + v_{0}t +  y_{0}
$$
In x direction 
$$
F = ma
$$
$$
0 = ma
$$
$$
a = 0
$$
$$
x(t) = v_{0}t + x_{0}
$$
###  Question 2
Calculate the kinetic energy 
$$
T = \frac{1}{2}m(x^{2}+y^{2}+z^{2})
$$
of a free particle of mass m
a.  cylindrical coordinates and find Lagrange’s equations of motion in cylindrical coordinates
$$
x=r \cos(\theta)
$$
$$
\dot{x} = \dot{r} \cos(\theta) -r\sin(\theta)\dot{\theta}
$$
$$
y = r\sin(\theta)
$$
$$
\dot{y} = \dot{r} \sin(\theta) + r\cos(\theta)\dot{\theta}
$$
$$
z=\dot{z}
$$
$$
T = \frac{m}{2}((\dot{r} \cos(\theta) -r\sin(\theta)\dot{\theta})^{2}+(\dot{r} \sin(\theta) + r\cos(\theta)\dot{\theta})^{2}+\dot{z}^{2})
$$
$$
\dot{x}^{2} = (\dot{r}\cos(\theta)-r\sin(\theta)\dot{\theta})(\dot{r}\cos(\theta)-r\sin(\theta)\dot{\theta})
$$
$$
\dot{x}^{2} = (\dot{r}\cos(\theta))^{2} -2(r\sin(\theta)\dot{\theta})(\dot{r}\cos(\theta)) + (r\sin(\theta)\dot{\theta})^{2}
$$
$$
\dot{x}^{2}=\dot{r}^{2}\cos ^{2}(\theta)-2r\sin(\theta)\dot{\theta}\dot{r}\cos(\theta) + r^{2}\sin ^{2}(\theta)\dot{\theta}^{2}
$$
$$
\dot{y}^{2} = (\dot{r}\sin(\theta)+r\cos(\theta)\dot{\theta})^{2}
$$
$$
\dot{y}^{2} = (\dot{r}\sin(\theta)+r\cos(\theta)\dot{\theta})(\dot{r}\sin(\theta)+r\cos(\theta)\dot{\theta})
$$
$$
\dot{y}^{2} = ((\dot{r}\sin(\theta))^{2}+ 2(\dot{r}\sin(\theta)r\cos(\theta)\dot{\theta})+(r\cos(\theta)\dot{\theta})^{2})
$$
$$
\dot{y}^{2} = (\dot{r}^{2}\sin ^{2}(\theta)+2\dot{r}\sin(\theta)r\cos(\theta)\dot{\theta} + r^{2}\cos ^{2}(\theta)\dot{\theta}^{2})
$$
$$
\dot{z}^{2} = \dot{z}^{2}
$$
$$
(\dot{r}^{2}\sin ^{2}(\theta)+2\dot{r}\sin(\theta)r\cos(\theta)\dot{\theta} + r^{2}\cos ^{2}(\theta)\dot{\theta}^{2}) + (\dot{r}^{2}\cos ^{2}(\theta)-2r\sin(\theta)\dot{\theta}\dot{r}\cos(\theta) + r^{2}\sin ^{2}(\theta)\dot{\theta}^{2})
$$
$$
(\dot{r}^{2}\sin ^{2}(\theta)+2\dot{r}\sin(\theta)r\cos(\theta)\dot{\theta} + r^{2}\cos ^{2}(\theta)\dot{\theta}^{2}) + (\dot{r}^{2}\cos ^{2}(\theta)-2r\sin(\theta)\dot{\theta}\dot{r}\cos(\theta) + r^{2}\sin ^{2}(\theta)\dot{\theta}^{2})
$$
$$
\dot{r}^{2}\sin ^{2}(\theta)+r^{2}\cos ^{2}(\theta)\dot{\theta}^{2} + \dot{r}^{2}\cos ^{2}(\theta)+r^{2}\sin ^{2}(\theta)\dot{\theta}^{2}
$$
$$
\dot{r}^{2}(\sin ^{2}(\theta)+\cos ^{2}(\theta)) + r^{2}\dot{\theta}^{2}(\cos ^{2}(\theta)+\sin ^{2}\theta)
$$
$$
\dot{x}^{2} + \dot{y}^{2} =r^{2}+r^{2}\dot{\theta^{2}}
$$
$$
T = \frac{m}{2}(\dot{r}^{2}+r^{2}\dot{\theta}^{2}+\dot{z}^{2})
$$
$$
L= T - U = \frac{m}{2}(\dot{r}^{2}+r^{2}\dot{\theta}^{2}+\dot{z}^{2}) - 0
$$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial  \dot{r} } -\frac{ \partial L }{ \partial r } = 0 
$$
$$
\frac{d}{dt} \left( {m}\dot{r} \right) - \left( m\dot{\theta}^{2}r\right) =0
$$
$$
m \ddot{r} - m\dot{\theta}^{2}r=0
$$
$$
\ddot{r} = \dot{\theta} ^{2}r
$$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{\theta} }-\frac{ \partial L }{ \partial \theta } = 0 
$$
$$
\frac{d}{dt} (mr^{2}\dot{\theta}) - 0  = 0 
$$
$$
m\dot{r}^{2}\ddot{\theta} = 0
$$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{z} } -\frac{ \partial L }{ \partial z }  = 0
$$
$$
\frac{d}{dt} (m\dot{z}) -0 = 0
$$
$$
m\ddot{z}=0
$$
Set of equations for Cylindrical Coordinates: 
$$
m\ddot{z} = 0
$$
$$
m\dot{r}^{2}\ddot{\theta} = 0
$$
$$
\ddot{r} = \dot{\theta}^{2}r
$$
b. spherical coordinates and find Lagrange’s equations of motion in spherical coordinates
$$
x = r(t)\cos (\phi(t)) \sin (\theta(t))
$$
$$
\dot{x} = \dot{r}(\cos \phi \sin \theta) + r\left( \frac{d}{dt} (\cos \phi \sin \theta) \right)
$$
$$
\dot{x} = \dot{r}\cos \phi \sin\theta + r (-\dot{\phi}\sin \phi \sin \theta+\cos \phi \cos (\theta)  \dot{\theta})
$$
$$
\dot{x} = \dot{r} \cos \phi \sin \theta - r \dot{\phi} \sin \phi \sin \theta + r \dot{\theta}\cos \phi \cos \theta
$$
$$
y = r\sin \phi \sin \theta
$$
$$
\dot{y} = \dot{r}\sin \phi \sin \theta + r\left( \frac{d}{dt} (\sin \phi \sin \theta) \right)
$$
$$
\dot{y} = \dot{r}\sin \phi \sin\theta + r(\dot{\theta}\sin \phi \cos \theta + \dot{\phi}\cos \phi \sin \theta)
$$
$$
\dot{y} = \dot{r}\sin \phi \sin \theta + r\dot{\theta}\sin \phi \cos\theta + r\dot{\phi}\cos \phi \sin \theta
$$
$$
z= r\cos \theta
$$
$$
\dot{z} = \dot{r}\cos\theta - r\dot{\theta}\sin\theta 
$$
$$
T = \frac{1}{2}mv^{2}
$$
$$
v^{2}=(\dot{x}^{2}+\dot{y}^{2}+\dot{z}^{2})
$$
Finding x
$$
x^{2} = (\dot{r} \cos \phi \sin \theta - r \dot{\phi} \sin \phi \sin \theta + r \dot{\theta}\cos \phi \cos \theta)^{2} 
$$
$$
a^{2}+ 2ab + 2ac + b^{2} + 2bc + c^{2}
$$
$$
\dot{x}^{2}=(\dot{r}\cos \phi \sin \theta)^{2}+ 2(\dot{r}\cos \phi \sin \theta)(-r \dot{\phi} \sin \phi \sin \theta) + 2(\dot{r}\cos \phi \sin \theta)(r\dot{\theta}\sin \phi \cos\theta)
$$
$$
 + (-r\dot{\phi}\sin \phi \sin \theta)^{2} + 2(-r\dot{\phi}\sin \phi \sin \theta)(r\dot{\theta}\sin \phi \cos\theta) + (r\dot{\theta}\sin \phi \cos\theta)^{2}
$$
$$
\dot{x}^{2} = \dot{r}^{2}\cos ^{2}\phi \sin^{2}\theta-2\dot{r}r\dot{\phi}\cos \phi \sin \theta \sin \phi \sin \theta + 2\dot{r}r\dot{\theta}\cos \phi \sin \theta \sin \phi \cos \theta \dots
$$
$$
+ r^{2} \dot{\phi}^{2}\sin ^{2}\phi \sin ^{2}\theta-2r^{2}\dot{\phi}\dot{\theta}\sin \phi \sin \theta \sin \phi \cos \theta + r^{2}\dot{\theta}^{2}\sin ^{2}\phi \cos ^{2}\theta
$$
Finding y
$$
\dot{y}^{2}=(\dot{r}\sin \phi \sin \theta + r\dot{\theta}\sin \phi \cos\theta + r\dot{\phi}\cos \phi \sin \theta)^{2}
$$
$$
=(\dot{r}\sin \phi \sin \theta)^{2}+2(\dot{r}\sin \phi \sin \theta )( r\dot{\theta}\sin \phi \cos\theta) + 2(\dot{r}\sin \phi \sin \theta )(r\dot{\phi}\cos \phi \sin \theta) \dots
$$
$$
 + ( r\dot{\theta}\sin \phi \cos\theta)^{2} + 2( r\dot{\theta}\sin \phi \cos\theta)(r\dot{\phi}\cos \phi \sin \theta) + (r\dot{\phi}\cos \phi \sin \theta)^{2} 
$$
$$
=\dot{r}^{2}\sin ^{2}\phi \sin ^{2}\theta + 2\dot{r}r\dot{\theta}\sin ^{2}\phi \sin\theta \cos\theta + 2\dot{r}r\dot{\phi}\sin \phi \sin ^{2}\theta\dots
$$
$$
+r^{2}\theta^{2}\sin ^{2} \phi \cos ^{2}\theta + 2r^{2}\dot{\theta}\dot{\phi}\cos\theta \sin\theta \cos \phi \sin \phi + r^{2}\dot{\phi}^{2}\cos ^{2}\phi \sin ^{2}\theta
$$
Finding z
$$
\dot{z}^{2} = (\dot{r}\cos \theta-r\dot{\theta}\sin\theta)^{2}
$$
$$
\dot{z}^{2} = \dot{r}^{2}\cos ^{2}\theta -2\dot{r}\cos \theta r\dot{\theta}\sin \theta + r^{2}\dot{\theta}^{2}\sin ^{2}\theta
$$
Now put it all together
$$
v^{2}= \dot{r}^{2}\cos ^{2}\phi \sin^{2}\theta-2\dot{r}r\dot{\phi}\cos \phi \sin ^{2} \theta \sin \phi  + 2\dot{r}r\dot{\theta}\cos \phi \sin \theta \sin \phi \cos \theta \dots
$$
$$
+ r^{2} \dot{\phi}^{2}\sin ^{2}\phi \sin ^{2}\theta-2r^{2}\dot{\phi}\dot{\theta}\sin ^{2} \phi \sin \theta  \cos \theta + r^{2}\dot{\theta}^{2}\sin ^{2}\phi \cos ^{2}\theta \dots
$$
$$
+\dot{r}^{2}\sin ^{2}\phi \sin ^{2}\theta + 2\dot{r}r\dot{\theta}\sin ^{2}\phi \sin\theta \cos\theta + 2\dot{r}r\dot{\phi}\sin \phi \sin ^{2}\theta\dots
$$
$$
+r^{2}\theta^{2}\sin ^{2} \phi \cos ^{2}\theta + 2r^{2}\dot{\theta}\dot{\phi}\cos\theta \sin\theta \cos \phi \sin \phi + r^{2}\dot{\phi}^{2}\cos ^{2}\phi \sin ^{2}\theta\dots
$$
$$
+ \dot{r}^{2}\cos ^{2}\theta -2\dot{r}\cos \theta r\dot{\theta}\sin \theta + r^{2}\dot{\theta}^{2}\sin ^{2}\theta
$$
$$
=\frac{1}{2}m(\dot{r}^{2}(\sin ^{2}\theta + \cos ^{2}\theta)+r^{2}\dot{\theta}^{2}(\cos ^{2}\theta+\sin ^{2}\theta)+r^{2}\sin ^{2}\phi(\dot{\phi}^{2}))
$$
$$
v^{2} = \dot{r}^{2}+r^{2}\dot{\theta}^{2}+r^{2}\dot{\phi}^{2}\sin ^{2}\phi
$$
$$
L = T - U = T 
$$
$$
L = \frac{1}{2}m(\dot{r}^{2}+r^{2}\dot{\theta}^{2}+r^{2}\dot{\phi}^{2}\sin ^{2}\phi)
$$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{\phi} } - \frac{ \partial L }{ \partial \phi } =0
$$
$$
\frac{ \partial L }{ \partial \dot{\phi} } = 2r^{2}\dot{\phi}\sin ^{2}\phi
$$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{\phi} } = 2r^{2}\sin(\phi)(\ddot{\phi}\sin \phi+2\dot{\phi}^{2}\cos \phi)
$$
$$
\frac{ \partial L }{ \partial \phi } = 2\dot{\phi}^{2}r^{2}\sin \phi \cos \phi
$$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{\phi} } -\frac{ \partial L }{ \partial \phi } =0
$$
$$
2r^{2}\sin(\phi)(\ddot{\phi}\sin \phi+2\dot{\phi}^{2}\cos \phi) - 2\dot{\phi}^{2}r^{2}\sin \phi \cos \phi=0
$$
$$
\ddot{\phi} = -\dot{\phi}^{2}\cot(\phi)
$$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{\theta} } -\frac{ \partial L }{ \partial \theta }  = 0
$$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{\theta} } = 2r^{2}\ddot{\theta}
$$
$$
\frac{ \partial L }{ \partial \theta }  = 0
$$
$$
2r^{2}\ddot{\theta} - 0  =0 
$$
$$
\ddot{\theta} = 0
$$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{r} } = 2\ddot{r} 
$$
$$
\frac{ \partial L }{ \partial r }  = 2r\dot{\theta}^{2} + 2r\dot{\phi}^{2}\sin ^{2}\phi
$$
$$
2\ddot{r} - 2r\dot{\theta}^{2}-2r\phi^{2}\sin ^{2}\phi = 0
$$
$$
\ddot{r} = r\dot{\theta}^{2}+r\phi^{2}\sin ^{2}\phi
$$
$$
\ddot{r} = r(\dot{\theta}^{2}+\phi^{2}\sin ^{2}\phi)
$$
Equations for spherical motion: 
$$
\ddot{r} = r(\dot{\theta}^{2}+\phi^{2}\sin ^{2}\phi)
$$
$$
\ddot{\theta} = 0
$$
$$
\ddot{\phi} = -\dot{\phi}^{2}\cot(\phi)
$$
### Problem 3. 
The Figure is a top down view of a smooth wire hoop on a horizontal surface that is forced to rotate at a fixed angular velocity ω about a vertical axis through the point A. A bead of mass m is threaded on the hoop and is free to move around it, with its position specified by the angle ϕ that it makes at the center with the diameter AB.
a. Find the Lagrangian for this system using ϕ as your generalized coordinate.
$$
r = \frac{1}{2} AB
$$
$$
R(\phi,t) = \sqrt{ (r+r\cos \phi)^{2}+(r\sin \phi)^{2} } = r\sqrt{ 2+2\cos \phi } =2r\cos \frac{\phi}{2}
$$
$$
\dot{R}(\phi,t) = -r\dot{\phi} \sin \frac{\phi}{2}
$$
$$
\theta(\phi,t) = \frac{\phi}{2} + \omega t
$$
$$
\dot{\theta} = \frac{\dot{\phi}}{2}+ \omega 
$$

$$
\dot{\theta}^{2} = \left( \frac{\dot{\phi}}{2} + \omega \right)^{2} \to \left( \frac{\dot{\phi}}{2} \right)^{2} + \frac{2\dot{\phi}}{2}\omega + \omega^{2}
$$
$$
\dot{\theta}^{2}=\frac{\dot{\phi}^{2}}{4}+\frac{2\dot{\phi}}{2}\omega+\omega^{2}
$$
$$
\dot{R}^{2}=r^{2}\dot{\phi}^{2}\sin ^{2} \frac{\phi}{2}
$$
$$
R^{2}=4r^{2}\cos ^{2} \frac{\phi}{2}
$$
From above
$$
T = \frac{m}{2}(\dot{r}^{2}+r^{2}\dot{\theta}^{2}+\dot{z}^{2})
$$
We can ignore z term because it is in 2-d space
$$
T = \frac{m}{2}(\dot{r}^{2}+r^{2}\dot{\theta}^{2})
$$
$$
T = \frac{m}{2}(-r^{2}\dot{\phi}^{2}\sin ^{2} \frac{\phi}{2} + 4r^{2}\cos ^{2} \frac{\phi}{2}(\frac{\dot{\phi}^{2}}{4}+\frac{2\dot{\phi}}{2}\omega+\omega^{2}))
$$
$$
T = \frac{m}{2}(r^{2}\dot{\phi}^{2}\sin ^{2} \frac{\phi}{2}+(\frac{\dot{\phi}^{2}4r^{2}\cos ^{2} \frac{\phi}{2}}{4}+\frac{2\dot{\phi}4r^{2}\cos ^{2} \frac{\phi}{2}\omega}{2}+4r^{2}\cos ^{2} \frac{\phi}{2}\omega^{2}))
$$
$$
T=\frac{m}{2}\left(r^{2}\dot{\phi}^{2}\sin ^{2}\left( \frac{\phi}{2} \right)+\dot{\phi}^{2}r^{2}\cos ^{2} \frac{\phi}{2} + \dot{\phi}4r^{2}\cos ^{2} \frac{\phi}{2}\omega + 4r^{2}\cos ^{2} \frac{\phi}{2} \omega^{2} \right)
$$
$$
T = \frac{m}{2}\left( r^{2}\dot{\phi}^{2}+ 4\dot{\phi}r^{2}\cos ^{2} \frac{\phi}{2}\omega + 4r^{2}\cos ^{2} \frac{\phi}{2}\omega^{2}\right)
$$
$$
L = T - U
$$
$$
L =T = \frac{m}{2}\left( r^{2}\dot{\phi}^{2}+ 4\dot{\phi}r^{2}\cos ^{2} \frac{\phi}{2}\omega + 4r^{2}\cos ^{2} \frac{\phi}{2}\omega^{2}\right)
$$
(b) Use the Lagrange equation of motion to show that the bead oscillates about point B exactly like a simple pendulum.
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{\phi} }-\frac{ \partial L }{ \partial \phi }  = 0
$$
$$
\frac{ \partial L }{ \partial \dot{\phi} } =\frac{m}{2}\left( 2r^{2}\dot{\phi}+4r^{2}\cos ^{2} \frac{\phi}{2}\omega \right)
$$
$$
\frac{d}{dt} \frac{ \partial L }{ \partial \dot{\phi} } = {mr^{2}}\left( \ddot{\phi}-\omega\dot{\phi}\sin(\phi )\right)
$$
$$
\frac{ \partial L }{ \partial \phi } = \frac{m}{2}\left( {-2\dot{\phi}r^{2}\sin(\phi)} -2r^{2}\omega^{2} \sin (\phi)\right)
$$
$$
=-mr^{2}\sin \phi(\dot{\phi}+\omega^{2})
$$
$$
mr^{2}\left( \ddot{\phi}-\omega\dot{\phi}\sin \phi \right) +mr^{2}\sin \phi(\dot{\phi}+\omega^{2})=0
$$
$$
mr^{2}(\ddot{\phi}-\omega \dot{\phi}\sin \phi) = -mr^{2}\sin \phi(\dot{\phi}+\omega^{2})
$$
$$
\ddot{\phi}-\omega \dot{\phi}\sin \phi +\sin \phi(\dot{\phi}+\omega^{2})=0
$$
$$
\ddot{\phi} -\omega \dot{\phi} \sin \phi + \dot{\phi}\sin \phi +\omega^{2}\sin \phi = 0
$$
$$
\ddot{\phi} +\dot{\phi}\sin \phi+\omega^{2}\sin \phi = \omega \dot{\phi}\sin \phi
$$
Multiply both sides by $\omega$
$$
\omega \ddot{\phi}+\omega \dot{\phi}\sin \phi+\omega^{3}\sin \phi = \omega \dot{\phi}\sin \phi
$$
Cancel terms
$$
\omega \ddot{\phi} + \omega^{3}\sin \phi = 0
$$
$$
 \ddot{\phi} =- \omega^{2} \sin \phi
$$

This is the simple pendulum second order nonlinear differential equation

(c) What is the frequency of these oscillations if their amplitude is small?
We can use the small angle approximation
$$
\sin(\theta) \approx \theta
$$
$$
\ddot{\phi} \approx -\omega^{2}\phi
$$
$$
\text{Frequency } \approx \omega
$$




