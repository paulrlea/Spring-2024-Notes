---
{"dg-publish":true,"permalink":"/physics/theoretical-mechanics-1/hw/hw-2-paul-lea/"}
---

1. A meter stick is at rest in reference frame $S_{0}$, which is traveling relative to reference frame $S$ with speed $v=0.75c$ in the positive x-direction of $S$. (This is the setup for both parts (a) and (b)).
	a. The stick lies in the $x_{0}$, $y_{0}$ plane and makes an angle $\theta_{0} = 45 \text{degrees}$with the $x_{0}$ axis (as measured in $S_{0}$.) What is the length l of the meter stick as measured in S, and what is its angle $\theta$ with the x-axis?
Length Contraction in x-axis
$$
x' = \frac{x}{\gamma}
$$
$$
x'=1\cos(45)\left( \sqrt{ 1- (\frac{0.75}{1})^{2} } \right)
$$
$$
x' = \frac{1}{\sqrt{ 2 }} (0.66143782776614766702)
$$
Total length (use Pythagorean theorem)
$$
L' = \sqrt{\left( \frac{1}{\sqrt{ 2 }} (0.66143782776614766702) \right)^{2} + \left( \frac{1}{\sqrt{ 2 }} \right)^{2} }
$$
$$
L' \approx 0.84779
$$
Angle between $x'$ axis and meter stick using trigonometry
$$
\tan(\theta) = \frac{\frac{1}{\sqrt{ 2 }}}{\frac{1}{\sqrt{ 2 }} (0.66143782776614766702)}
$$
$$
\tan(\theta) = \frac{1}{0.66143782776614766702}
$$
$$
\theta = \arctan\left( \frac{1}{0.66143782776614766702} \right)
$$
$$
\theta = 56.51784205297067947°
$$

b. Now assume that you measure an angle of $\theta = 45 \text{degrees}$ in $S$. What is $\theta_{0}$ for this to happen? What is the value of l, as measured in S now?
$$
\tan(\theta_{0}) = 1 = \frac{y_{0}}{x_{0}} = \frac{y'}{x'\sqrt{ 1 - \left( \frac{v}{c} \right)^{2} }}
$$
$$
\tan(\theta_{0}) = \frac{\tan\left( \theta \right)}{\gamma}
$$
$$
\tan (\theta_{0}) = \frac{\tan(45 \text{ degrees})}{\gamma} =1\left( \sqrt{ 1- (\frac{0.75}{1})^{2} } \right)
$$
$$
\tan(\theta_{0})=0.661438 \to \arctan(0.661438) = \theta
$$
$$
\theta_{0} = 33.48 \text{ degrees}
$$
$$
x'=1\cos(33.48 \text{ degrees})\left( \sqrt{ 1- (\frac{0.75}{1})^{2} } \right) = 0.551691
$$
$$
y' = 1\sin(33.48 \text{ degrees}) = 0.551646
$$
$$
l' = \sqrt{ 0.551646^{2}+  0.551691^{2}} = 0.780177
$$
$$
l' = 0.780177
$$
2. A rocket is traveling at speed $V=0.95c$ along the x-axis of frame S. It shoots a bullet whose velocity $v'$ (measured in the rocket’s rest frame S’) is $vy'=0.95c$ along the y’ axis of S’. (Assume that the x and x’ axes are aligned as are the y and y’ axes.)
a. Derive the equation for x and y velocities in the S’ reference frame ($vx'$ and $vy'$) in in terms of the velocity in the S frame and V.
$$
v_{x}' = \frac{dx'}{dt'}
$$
$$
dx'=\frac{\partial x'}{\partial x}dx - \frac{\partial x'}{\partial t}dt
$$
$$
dt'=\frac{\partial t'}{\partial x}dx + \frac{\partial t'}{\partial t}dt
$$
$$
\frac{dx'}{dx} = \gamma , \ \ \frac{\partial x'}{\partial t} = -\gamma v_{x}, \ \ \frac{\partial t'}{dx} = -\frac{\gamma v_{x}}{c^{2}}
$$
$$
\frac{dt'}{dt} = \gamma
$$
Plugging this all into the equation for $dx'$ and $dt'$
$$
dx' = \gamma dx + (-\gamma V)dt
$$
$$
dt' = -\frac{\gamma V}{c^{2}}dx+\gamma dt
$$
$$
v'_{x} = \frac{\gamma dx + (-\gamma V)dt}{-\frac{\gamma v_{x}}{c^{2}}dx+\gamma dt}
$$
Factor out gamma
$$
v'_{x} = \frac{ dx + (- V)dt}{-\frac{ v_{x}}{c^{2}}dx+ dt}
$$
Multiply by 1 ($\frac{1}{dt}$)
$$
v'_{x} = \frac{\frac{dx}{dt}-V}{1-\frac{vdx}{c^{2}dt}}
$$
$$
v'_{x} = \frac{v_{x}-V}{1-\frac{Vv_{x}}{c^{2}}}
$$
Now to find $v_{y}'$
$$
v_{y}' = \frac{dy'}{dt'}
$$
$$
dy' = \frac{dy'}{dy} dy
$$
$$
v_{y}' = \frac{dy'}{dt'} = \frac{dy}{-\frac{\gamma V}{c^{2}}dx+\gamma dt}
$$
Multiply both top and bottom by ($\frac{1}{dt}$)
$$
v'_{y} =  \frac{\frac{dy}{dt}}{-\frac{\frac{V\gamma}{c^{2}}dx}{dt}+\frac{\gamma dt}{dt}}
$$
$$
v'_{y} = \frac{v_{y}}{-\frac{Vv_{x}\gamma}{c^{2}}+\gamma}
$$
b. Calculate the individual velocity components in the S frame and report the bullet’s total velocity (magnitude and direction) as measured in S?
$$
\gamma = \frac{1}{\sqrt{ 1-\left( \frac{v}{c} \right)^{2} }}
$$
$$
\gamma = 3.20256
$$
We have $v'_y$ and $v'_{x}$  and $V$
$$
v_{y}' = 0.9c, \ v_{x}' = 0.95c, \ V = 0.95c
$$
$$
0.9c = \frac{v_{y}'}{-\frac{(0.95c)(0.95c)(3.20256)}{c^{2}}+3.20256}
$$
$$
0.9c({-\frac{(0.95c)(0.95c)(3.20256)}{c^{2}}+3.20256})= {v_{y}'}
$$
$$
v'_{y}=0.28102464c
$$
$$
v_{x} = v_{x}'
$$
$$
|v|=\sqrt{v_{x}^{2}+v_{y}'^{2}}
$$
$$
|v| = 0.99069c
$$
Direction: 
$$
\tan\theta =\frac{0.28102464c}{0.95c}
$$
$$
\arctan \frac{0.28102464c}{0.95c} = \theta
$$

$$
\theta = 16.479 \degree
$$
16.479 degrees above x axis

3. Cosmic rays create muons in the Earth’s upper atmosphere. These muons rain down more-or-less uniformly on the Earth’s surface, although some of them decay on the way to the surface, with a half-life of ~1.5 μs (measured in their rest frame). A muon detector is carried in a balloon to an altitude of 2000 m, and in the course of an hour detects 650 muons traveling at 0.99c toward the Earth

a). What is the muon’s half-life as measured by an observer on the surface of the Earth?
$$
\Delta t'  = \Delta t \gamma 
$$
$$
\gamma = \frac{1}{\sqrt{ 1-\left( \frac{0.99c}{c} \right)^{2} }}
$$
$$
\gamma = 7.08881
$$
$$
t' = (1.5\mu s)7.08881
$$
$$
10.633215  \ \mu s
$$
b). If an identical detector remains at sea level, how many muons should it register in one hour?
Time between top detector and bottom detector in Muon frame: 
Time from top detector to bottom detector in earth frame:
$$
t=\frac{2000m}{0.99\left( 3E8 \frac{m}{s} \right)}=0.000006734 \ s = 6.734 \ \mu s
$$
Half life formula: 
$$
N = N_{0}\left( \frac{1}{2} \right)^{t/h}
$$
Where $h = 10.633\mu s$, $N_{0}=650$ and $t=6.734\mu s$ 
$$
N = 650\left( \frac{1}{2} \right)^{6.734/10.633215}
$$
$$
N \approx 419 \text{ muons}
$$
c. What would the answer be if you ignore the effects of time dilation?
Time from top detector to bottom detector in earth frame:
$$
t=\frac{2000m}{0.99\left( 3E8 \frac{m}{s} \right)}=0.000006734 \ s = 6.734 \ \mu s
$$
Half life formula: 
$$
N = N_{0}\left( \frac{1}{2} \right)^{t/h}
$$
Where $h = 1.5 \mu s$, $N_{0}=650$ and $t=6.734\mu s$ 
$$
N = 650\left( \frac{1}{2} \right)^{6.734/1.5}
$$

$$
N \approx 29 \text{ muons}
$$
