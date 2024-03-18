---
{"dg-publish":true,"permalink":"/physics/theoretical-mechanics-1/class-notes/2024-02-27-collisions/"}
---


*** missed the first half of class ***


Total potential energy

$$
u = \sum^{n}_{i=1}u_{i} + \sum_{i<j} u_{ij}
$$
The first term is the potential from external forces, the second term is known as [[Physics/Theoretical Mechanics 1/Class Notes/Concepts/interaction potential\|interaction potential]]. 

## 2 particle collision 
Recall there is [[Physics/Theoretical Mechanics 1/Class Notes/Concepts/Elastic collisions\|Elastic collisions]] and [[Physics/Theoretical Mechanics 1/Class Notes/Concepts/Inelastic collisions\|Inelastic collisions]]

Consider a collisions in the lab frame: 

$$
\frac{1}{2}m_{1} \vec{v}_{1}^{2}+ \frac{1}{2}m_{2} \vec{v}_{2}^{2} = \frac{1}{2}m_{1} \vec{v}_{1}'^{2} + \frac{1}{2} m_{2} \vec{v}_{2}'^{2}
$$
 Where $v_{i}'$ is post collision velocity

Similarly:

$$
m_{1}\vec{v}_{1} + m_{2}\vec{v}_{2} = m_{1} \vec{v}_{1}' + m_{2}\vec{v}_{2}' = m_\text{tot}\vec{V}_\text{tot}
$$
$$
\therefore  \sum \vec{p}_{i} = \vec{P}_\text{tot}
$$
Same collision viewed from thze center of mass frame
$$

$$
Since center of mass frame and center of mass at rest in the center of mass at rest in the center of mass frame are the same 

$$
\vec{v}_{2}^{*} = \frac{m_{1}}{m_{2}} \vec{v}_{1}^{*}, \ \ \vec{v}_{2}^{*} = -\frac{m_{1}}{m_{2}}\vec{v}_{1}'^{*}
$$
Vectors are anti-parallel, means the two particles approach head on in the center of mass frame. 

> figure 1 hree 


Scattering angle is the same, not generally true in the lab frame. 

Consider now kinetic energy in the center of mass frame: 
$$
\frac{1}{2}m_{1}\vec{v}_{1} ^{2} + \frac{1}{2} m_{2}\vec{v}_{2}^{*^{2}}= \frac{1}{2} m_{1} \vec{v}_{1}{^{*^{2}}} + \frac{1}{2} m_{2} \vec{v}_{2}'^{*^{2}}
$$This can be rewritten as 
$$
\frac{1}{2} m_{1}\vec{v}^{*^{2}}_{1}+\frac{1}{2}m_{2} \frac{m_{1}^{2}}{m_{2}^{2}} \vec{v}_{1}^{*^{2}}=\frac{1}{2}m_{1}\vec{v}_{1}^{*^{2}} + \frac{1}{2} m_{2}\frac{m_{1}^{2}}{m_{2}^{2}} \vec{v}_{1}'^{*^{2}}
$$
or $$
\frac{1}{2}\left( m_{1}+\frac{m_{1}^{2}}{m_{2}} \right) \vec{v}_{1}^{*^{2}} = \frac{1}{2} \left( m_{1} + \frac{m_{1}^{2}}{m_{2}} \right)\vec{v}_{1}' ^{*^{2}}
$$
Since elastic 
$$
T^{*} = T'^{*}
$$
Meaning 
$$
|\vec{v}_{1}^{*}| = |\vec{v}_{1}'^{*}|
$$
and 
$$
|\vec{v}_{2}^{*}| = |\vec{v}_{2}'^{*}|
$$
Laboratory system: 

> insert figure 2 here 

m2 is at rest 
$$
\vec{R} = \frac{m_{1}\vec{r}_{1}+m_{2}\vec{r}_{2}}{m_{1}+m_{2}}
$$
$$
\dot{\vec{R}} = \frac{m_{1}}{m_{1}+m_{2}}\vec{v}_{1}
$$
Center of mass system: 

$$
\vec{r}_{1}^{*} = \vec{r}_{1}-\vec{R}
$$
$$
\vec{r}_{2}^{*}  = \vec{r}_{2}-\vec{R}
$$

> figure 3 here 


### Trajectories in lab frame 

$$
m_{1}\vec{v}_{1} + m_{2}\vec{v}_{2} = m_{1}\vec{v}_{1}' + m_{2}\vec{v}_{2}' = m \dot{\vec{R}}
$$
Seperating in 2d
X component
$$
m_{1}v_{1} = m_{1}v_{1}'\cos \psi + m_{2}v_{2}' +\cos \xi
$$
Y component
$$
0=m_{1}v_{1}' \sin \psi + m_{2}v_{2}' \sin \xi 
$$
- This is because the momentum upwards is the same as the momentum downwards

### Trajectories in COM frame

> figure 4

$$
\dot{\vec{R}}=0 \ \ \ \ \ \ m_{1}\vec{v}_{1}^{*} +m_{2}\vec{v}_{2}^{*} = m_{1}\vec{v}_{1}'^{*} + m_{2}\vec{v}_{2}'^{*}=0
$$
Relationship between $\psi, \xi$ in lab frame with angle $\theta$ in lab frame

$$
\vec{r}_{i} ^{*} = \vec{r}_{i} - \vec{R} \tag{1}
$$
$$
\vec{v}_{i}^{*} = \vec{v}_{i}- \dot{\vec{R}} \tag{2}
$$
$$
\vec{v}_{i}'^{*} = \vec{v}'_{i} - \dot{\vec{R}} \tag{3}
$$
$$
\vec{R} = \frac{m_{1}\vec{r}_{1}+ m_{2}\vec{r}_{2}}{m_{1}+m_{2}}
$$
$$
\dot{\vec{R}} = \frac{m_{1}}{m_{1}+m_{2}} \dot{\vec{v}_{1}}
$$
Break eq. 3 into components
x: 
$$
v_{1}'^{*} \cos\theta = v_{1}'\cos \psi  - \frac{m_{1}}{m_{1}+m_{2}}v_{1} \tag{1a}
$$
$$
v_{1}'^{*} \cos\theta +\frac{m_{1}}{m_{1}-m_{2}}v_{1} = v_{1}\cos \psi \tag{2a}
$$
y:
$$
v_{1}'^{*} \sin\theta = v_{1}'\sin \psi \tag{3a}-0
$$
$v_{1}$ is only in the x direction 
$$
v_{1}'^{*} \sin\theta = v_{1}' \sin \psi \tag{4a}
$$
$$
\frac{(4a)}{(2a)}= \frac{v_{1}'^{*}\sin\theta}{v_{1}'^{*}\cos\theta   \frac{m_{1}}{m_{1}+m_{2}}v_{1}} = \tan \psi
$$
$$
v_{1}'^{*} = v_{1}^{*}
$$
$$
v_{1}'^{*} = v_{1}-\dot{\vec{R}}
$$
$$
v_{1}^{*} = v_{1} - \frac{m_{1}}{m_{1}+m_{2}}v_{1} = v_{1}\left[ \frac{m_{1}+m_{2}}{m_{1}+m_{2}} - \frac{m_{1}}{m_{1}+m_{2}} \right]
$$
$$
v_{1}^{*}=\frac{m_{2}}{m_{1}+m_{2}} v_{1} = v_{1}^{*'}
$$
$$
\tan \psi = \frac{\sin\theta}{\cos\theta + \frac{m_{1}}{m_{1}+m_{2}}v_{1} \frac{1}{v_{1}'^{*}}}
$$
$$
\tan \psi = \frac{\sin\theta}{\cos\theta +\frac{m_{1}}{m_{2}}}
$$
Testing this for edge cases 
$$
m_{1} \ll m_{2} \to \tan \psi \approx \tan\theta \therefore \psi \approx\theta
$$
$$
m_{1}=m_{2} \tan \psi = \frac{\sin\theta}{\cos\theta+1} = \tan \frac{\theta}{2}
$$
Similar correct method for product 2
$$
\tan \xi = \tan\left( \frac{\pi}{2} - \frac{\theta}{2} \right)
$$
$$
m_{1}=m_{2} \xi + \psi =\frac{\pi}{2}
$$



