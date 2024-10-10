---
dg-publish: true
---
## Vecteur accélération instantanée

On écrit le vecteur accélération instantanée :
$$\vec{a} = \frac{\mathrm{d}\vec{v}}{\mathrm{d}t} = \frac{\mathrm{d}^2\vec{OM}}{\mathrm{d}t^2}$$
*il représente le taux de variation du vecteur vitesse par unité de temps*


## Composantes dans différents repères

### Coordonnées cartésiennes

$$\vec{a} = \frac{\mathrm{d^2}x}{\mathrm{d}t^2} \vec{e_x} + \frac{\mathrm{d^2}y}{\mathrm{d}t^2} \vec{e_y} + \frac{\mathrm{d^2}z}{\mathrm{d}t^2} \vec{e_z}$$
### Coordonnées cylindriques
*voir [[Dérivation des vecteurs unitaires (par rapport au temps)#Dérivée du vecteur e theta]]*

$$\vec{a} = (\overset{..}{r} - r \overset{.}{\theta^2})\vec{e_r} \ + \ (2\overset{.}{r}\overset{.}{\theta} \ + \ r \overset{..}{\theta})\vec{e_\theta} + \overset{..}{z}\vec{e_z}$$
(démonstration : [[Poly Meca.pdf#page=65]])

### Dans la base de Frenet

*pour rappel, on avait défini dans [[Vitesse d'un point matériel]] :*
$$\vec{v} = \frac{\mathrm{d}l}{\mathrm{d}t} \vec{u_T}$$
Ainsi, 

$$\vec{a} = \frac{\mathrm{d}\vec{v}}{\mathrm{d}t} = \frac{\mathrm{d^2}l}{\mathrm{d}t^2} \vec{u_T} + \frac{\mathrm{d}l}{\mathrm{d}t}\frac{\mathrm{d}\vec{u_T}}{\mathrm{d}t}$$

$$\text{On peut y réécrire sous la forme : } \frac{\mathrm{d^2}l}{\mathrm{d}t^2} \vec{u_T} + \frac{\mathrm{d}l}{\mathrm{d}t} \frac{\mathrm{d}\vec{u_T}}{\mathrm{d}l} \frac{\mathrm{d}l}{\mathrm{d}t} = \frac{\mathrm{d^2}l}{\mathrm{d}t^2}\vec{u_T} + (\frac{\mathrm{d}l}{\mathrm{d}t})^2 \frac{\mathrm{d}\vec{u_T}}{\mathrm{d}l}$$

*On identifie ensuite l'expression du vecteur uN, voir [[Base de Frenet]]*

$$\vec{a} = \frac{\mathrm{d^2}l}{\mathrm{d}t^2} \vec{u_T} \ + \ (\frac{\mathrm{d}l}{\mathrm{d}t})^2 \frac{\vec{u_N}}{R_C}$$


Ainsi, on peut exprimer l'accélération sous la forme : 
$$\vec{a} = a_T \ \vec{u_T} \ + a_N \ \vec{u_N}$$
où :
$$a_T\text{ représente l'accélération tangentielle : } a_T = \frac{\mathrm{d^2}l}{\mathrm{d}t^2} = \frac{\mathrm{d}||\vec{v}||}{\mathrm{d}t}$$
$$a_N \text{ représente l'accélération normale : } a_N = (\frac{\mathrm{d}l}{dt})^2 = \frac{1}{R_C} = \frac{v^2}{R_C}$$
*Remarque : si un point parcourt une trajectoire curviligne à vitesse ||v|| constante, alors l'accélération tangentielle est nulle, donc son vecteur accélération est toujours normal à la trajectoire, dirigé vers l'intérieur, et d'autant plus grand que le rayon de courbure Rc est petit.*


