---
{"dg-publish":true,"permalink":"/theoretical-mechanics/hw/hw-1-paul-lea/"}
---

# Homework 1
1. Consider a projectile fired from the origin of a three-dimensional coordinate system on Earth (+z is the “up” direction). Assume that the projectile is fired with an initial velocity $v_{0}$ at an angle α above the horizontal in the direction of the +x axis. 

a. Calculate the angular momentum of the projectile. Momentum and position and are measured with respect to the origin of the coordinate system.
 ![Pasted image 20240109205626.png](/img/user/Theoretical%20Mechanics/Images/Pasted%20image%2020240109205626.png)
$$
\vec{L} = \vec{r} \times \vec{p} 
$$
$$
x_{v} = v_{0}\cos(\alpha) \ ; \ x_{t} = v_{0}\cos(\alpha)t
$$
$$
z_{v} = v_{0}\sin(\alpha) - gt \ ; \ z_{t} = v_{0}\sin(\alpha)t - \frac{1}{2}gt^{2}
$$
$$
\vec{r} = (x_{t}\hat{i} + z_{t}\hat{k})
$$
$$
\vec{p} = m(x_{v}\hat{i} + z_{v}\hat{k})
$$
$$
\vec{L} = \det\begin{bmatrix}
\hat{i} \ \ \ ,\hat{j} \ ,\ \ \hat{k} \\
x_{t} \ \ ,0, \ \  \ z_{t} \\
mx_{v} \ ,0, \ mz_{v}
\end{bmatrix}
$$
$$
\vec{L} = -(mx_{t}z_{v} - mz_{t}x_{v})\hat{j}
$$
$$
\vec{L} =- m\left( (v_{0}\cos(\alpha)t(v_{0}\sin(\alpha)-gt))-\left( \left( v_{0}\sin(\alpha)t-\frac{1}{2}gt^{2} \right)v_{0}\cos(\alpha) \right) \right)
$$
$$
\vec{L} = -m\left( -gt^{2} v_{0}\cos(\alpha) +  \frac{1}{2}gt^{2}v_{0}\cos(\alpha) \right)
$$
$$
\vec{L} = \frac{1}{2} mgt^{2}v_{0} \cos(\alpha) \hat{j}
$$
b. Calculate the torque
$$
\vec{N} = \vec{r} \times \vec{F}_{g}
$$
$$
\vec{r} = (x_{t}\hat{i} + z_{t}\vec{k})
$$
$$
\vec{F}_{g} = -gm\hat{k}
$$
$$
\vec{N} = \begin{bmatrix}
\hat{i}\  , \  \hat{j} \ , \ \hat{k} \\
x_{t}  ,\ 0 , \ z_{t} \\
0,0,-gm
\end{bmatrix}
$$
$$
\vec{N} = mgv_{0}\cos(\alpha)t
$$
c. Prove that $\vec{N} = \dot{\vec{L}}$

$$
mgtv_{0}\cos(\alpha)\vec{j} = \frac{d}{dt}\left( \frac{1}{2}mgt^{2} v_{0}\cos(\alpha)\vec{j} \right)
$$
$$ 
mgtv_{0}\cos(\alpha)\vec{j} = mgtv_{0}\cos(\alpha)\hat{j}
$$
They match!

2 . A block of mass m slides down a friction-less incline (Figure 2). The block is released at height h. The bottom of the loop should be treated as a circular segment with radius R. 

(a) What is the force of the inclined track on the block at the bottom (point A)? 
$$
U = mgh ; \  T = \frac{1}{2}mv^{2}
$$
$$
2gh = v^{2}  \to \sqrt{ 2gh } = v_{a}
$$
$$
F_{centripetal} = \frac{mv^{2}}{r} = \frac{m(2gh)}{r}
$$
$$
F_{a} = \frac{2mgh}{r} + mg
$$
(b) At what speed does the block leave the track? 
$$
B_{height} = R - (R\cos(45^{\degree})) = R - \frac{R}{\sqrt{2}}

$$
$$
T_{b} = mg(h-(R - \frac{R}{\sqrt{2}}))
$$
$$
\sqrt{\frac{2mg(h - (R - \frac{R}{\sqrt{2}}))}{m}} = v
$$
$$
\sqrt{2gh + (\sqrt{2} - 2)gR} = v
$$
(c) How far away from point A does the block land on level ground? Give your answer in terms of R, h, m, and g. (Hint: Set Point A to be the origin of your coordinate system) 
 Take the velocity $v_{b}$ as the exit velocity from the track. Divide it into vertical and horizontal components. 
$$
v_{bx} = v_{b}\cos (45{\degree}) \ ; \ v_{by} = v_{b}\sin (45{\degree})
$$
This gives us horizontal and vertical components of motion as it leaves the track. We can velocity at any time t by adding a gravity term to the y component. Motion in the x direction is constant
$$
v_{by}(t) = v_{b}\sin (45{\degree}) - gt
$$
Now we have our velocity equations we need to find position equations. Integrate and plug in initial conditions
$$
x(t) = \int v_{bx}(t) dt = \int v_{b}\cos (45{\degree}) dt
$$
$$
x(t) = v_{b}\cos(45{\degree})t + x_{0}
$$
$$
x(t) = \frac{v_{b}}{\sqrt{ 2 }} t + x_{0}
$$
$$
y(t) = \int v_{by}(t) \, dt = \int v_{b}\sin (45{\degree}) - gt  \,dt
$$
$$
y(t) = v_{b}\sin (45{\degree})t - \frac{1}{2}gt^{2} + y_{0} 
$$
$$
y(t) = \frac{v_{b}t}{\sqrt{ 2 }} - \frac{1}{2}gt^{2} + y_{0} 
$$
We have our equations of motion, but we need to find the $y_{0}$ and $x_{0}$ values. We can accomplish this by looking at the triangle formed between points a and b, outlined (poorly) in red in the figure below
![Pasted image 20240112132814 1.png](/img/user/Theoretical%20Mechanics/Images/Pasted%20image%2020240112132814%201.png)


From the previous part, we have the y component of the triangle

$$
B_{y} = R - (R\cos(45^{\degree})) = R-\frac{R}{\sqrt{ 2 }}
$$
Now we just need the x component

![Pasted image 20240112142738 1.png](/img/user/Theoretical%20Mechanics/Images/Pasted%20image%2020240112142738%201.png)
$$
B_{x} = \frac{R}{\sqrt{ 2 }}
$$
Now we have both initial conditions for position.
Next, we can calculate the time of flight above the height of B
$$
tof = \frac{2(v_{b}\sin 45)}{g}
$$
Add to this the time of flight between height of B and the ground. $v_{b}$ is the same due to conservation of energy. This utilizes the principle that the time of flight is equal to the distance over the average velocity, which is initial velocity + final velocity over 2. 
$$
tof_{2}=\frac{R-\frac{R}{\sqrt{ 2 }}}{\frac{v_{b}+v_{max}}{2}}
$$
Now we have the total time of flight between point B and the ground, where $v_{max}$ is $\sqrt{ 2gh }$ . 
$$
tof_{total}= \frac{2v_{b}\sin 45}{g} + \frac{2(R-\frac{R}{\sqrt{ 2 }})}{v_{b} + v_{max}}
$$
Plug this into the position formula for x
$$
x(tof) = \frac{v_{b}}{\sqrt{ 2 }} (\frac{2v_{b}\sin 45}{g} + \frac{2(R-\frac{R}{\sqrt{ 2 }})}{v_{b} + \sqrt{ 2gh }}) + \frac{R}{\sqrt{ 2 }}
$$
Simplify a little
$$
\frac{2v_{b}^{2}}{2g} + \frac{2v_{b}R\left( 1-\frac{1}{\sqrt{ 2 }} \right)}{v_{b}+\sqrt{ 2gh }}+\frac{R}{\sqrt{ 2 }}
$$
Finally, plug in $v_{b}$
$$
\sqrt{2gh + (\sqrt{2} - 2)gR} = v
$$
$$
\frac{2(2gh + (\sqrt{2} - 2)gR)}{2g} + \frac{2\sqrt{2gh + (\sqrt{2} - 2)gR}R\left( 1-\frac{1}{\sqrt{ 2 }} \right)}{\sqrt{2gh + (\sqrt{2} - 2)gR}+\sqrt{ 2gh }}+\frac{R}{\sqrt{ 2 }}
$$
Simplify
$$
2h + (\sqrt{2} - 2)R + \frac{\sqrt{g(2h + (\sqrt{2} - 2)R)}(\sqrt{2}\sqrt{gh} - \sqrt{g(2h + (\sqrt{2} - 2)R)})}{g} + \frac{R}{\sqrt{ 2 }}
$$
$$
2h + \frac{3R}{\sqrt{2}} - 2R +\frac{\sqrt{g(2h + (\sqrt{2} - 2)R)}(\sqrt{2}\sqrt{gh} - \sqrt{g(2h + (\sqrt{2} - 2)R)})}{g}
$$
(d) Sketch the potential energy U(x) of the block. Indicate the total energy on the sketch

![Pasted image 20240110150145.png](/img/user/Theoretical%20Mechanics/Images/Pasted%20image%2020240110150145.png)


3. Consider a projectile of mass m fired vertically upward in a constant gravitational field g. The direction of the gravitational field is downward. The initial velocity of the projectile is v(0) = v0. Calculate the time, tm , required for the projectile to reach maximum height for the case of 
(a) zero resisting force: $F_{r}= 0$
Max height when $v=0$
$$
v(t) = v_{0} - gt
$$
Set $v(t) = 0$ and solve for t
$$
0 = v_{0} - gt \to gt = v_{0} \to \frac{v_{0}}{g} = t
$$
$$
t_{max} = \frac{v_{0}}{g}
$$
(b) a resisting force proportional to the square of the velocity of the projectile: $F_{r} = -cv^{2}$, with c being a positive constant.
This is a velocity dependent force
$$
F_{net}(v)=-mg - cv^{2}
$$
$$
F(v) =ma=m \frac{dv}{dt}
$$
$$
-mg-cv^{2} = m \frac{dv}{dt}
$$
$$
\int dt = m \int \frac{1}{-mg-cv^{2}} \, dv
$$
$$
\int_{v_{0}}^{0} \frac{1}{-(mg) - (cv)^2} \,dv = -\frac{\tan^{-1}\left(\frac{cv}{\sqrt{g} \sqrt{m}}\right)}{c \sqrt{g} \sqrt{m}} + c_{1}
$$
$$
t= (-\frac{\tan^{-1}\left(\frac{\sqrt{ c }v}{\sqrt{g} \sqrt{m}}\right)}{ \sqrt{ c } \sqrt{g} \sqrt{m}} + c_{1}) |^{0}_{v_{0}}
$$
$$
t_{m} = 0 +m \tan ^{-1}\left( \frac{\sqrt{ c }v_{0}}{\sqrt{ gm }} \right) \frac{1}{\sqrt{ cgm }} 
$$
$$
t_{m} = m \tan ^{-1}\left( \frac{\sqrt{ c }v_{0}}{\sqrt{ gm }} \right) \frac{1}{\sqrt{ cgm }}
$$
 4.A particle of mass m has speed $v(x) = \frac{\alpha}{x}$
 (a) Calculate the force F(x) responsible. 
 $$
F=ma =m \frac{dv}{dt}
$$
$$
v(x(t)) \  ; \ \frac{dv}{dt}=m\frac{dv}{dx} \frac{dx}{dt}
$$
$$
F(x) = mv \frac{dv}{dx}
$$
$$
\frac{dv}{dx} = -\frac{\alpha}{x^{2}}
$$
$$
F(x) = -m \frac{\alpha}{x} \frac{\alpha}{x^{2}}
$$
 (b) Calculate the displacement x(t) of the particle. 
$$
\frac{dx}{dt} = v
$$
$$
\frac{\alpha}{x} = \frac{dx}{dt} \to \alpha dt = xdx
$$
integrate both sides
$$
\int x \, dx =\int \alpha \, dt 
$$
$$
\frac{1}{2}x^{2} = \alpha t
$$
solve for x
$$
x^{2}=2\alpha t
$$
$$
x(t)=\sqrt{2\alpha t }
$$
 (c) Calculate the speed of the particle v(t) as a function of time.
 $$
\dot{x} = v= \frac{2\alpha}{2\sqrt{2\alpha t}}
$$
$$
v(t)=\frac{\alpha}{\sqrt{ 2\alpha t }}
$$
 (d) After having calculated x(t) and v(t) check whether the solutions reproduce the given v(x). 
$$
x=\sqrt{ 2\alpha t }
$$
$$
x^{2} = 2\alpha t \to \frac{x^{2}}{2\alpha} = t
$$
Plug back into $v(t)$
$$
v(x) = \frac{\alpha}{\sqrt{ 2\alpha  \frac{x^{2}}{2\alpha}}}
$$
$$
v(x)=\frac{\alpha}{\sqrt{ x^{2} }}
$$
$$
v(x) = \frac{\alpha}{x}
$$
 (e) Calculate the force $F(t) =m (\frac{dv}{dt})$ as a function of time t. Is the result in agreement with the solutions to (a) and (b)?
 $$
F(t) = m  \frac{dv}{dt}
$$
$$
\dot{v}(t)= -\dfrac{{\alpha}^2}{2^\frac{3}{2}\left({\alpha}t\right)^\frac{3}{2}}
$$
$$
F(t) = -\dfrac{{m\alpha}^2}{2^\frac{3}{2}\left({\alpha}t\right)^\frac{3}{2}}
$$
Second method using (a) and (b)

$$
F(x) = -m \frac{\alpha}{x} \frac{\alpha}{x^{2}} = -m \frac{\alpha^{2}}{x^{3}}
$$
$$
F(t)=-m \frac{\alpha^{2}}{(x(t)=\sqrt{2\alpha t })^{3}}
$$
$$
F(t) = \frac{ma^{2}}{(2\alpha t)^{3/2}}
$$
They agree!






