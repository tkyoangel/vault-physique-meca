---
dg-publish: true
---

## Vecteur vitesse intantanée

**On définit le vecteur vitesse instantanée par la relation suivante :**
$$\vec{v} = \lim_{ \delta t \rightarrow 0} \frac{\vec{MM'}}{\delta t} = \lim_{ \delta t \rightarrow 0} \frac{\delta\vec{OM}}{\delta t} = \frac{\mathrm{d} \vec{OM}}{\mathrm{d}t}$$
*La vitesse est donc le taux de variation du vecteur position par unité de temps, en Physique, la vitesse désigne donc le vecteur vitesse instantanée*

## Expression dans les différents repères
[[Repérer la position de P#Les 3 principaux types de coordonnées]]
### Dans le repère cartésien

On sait déjà que : 
$$\vec{OM}(t) = x(t) \vec{e_x} + y(t) \vec{e_y} + z(t) \vec{e_z}$$
Alors, tout simplement, 
$$\vec{v}(t) = \overset{.}{x}(t) \vec{e_x} + \overset{.}{y}(t) \vec{e_y} + \overset{.}{z}(t) \vec{e_z}$$
*(le "." au dessus d'une lettre symbolise la dérivée première de cette fonction par rapport au temps)*

### Dans le repère cylindrique

On sait déjà que : 
$$\vec{OM}(t) = r(t) \vec{e_r} + z(t) \vec{e_z}$$
Alors, on peut écrire, 

$$\vec{v}(t) = \frac{\mathrm{d}r(t)}{\mathrm{d}t} \vec{e_r}(t) \ + \ r(t) \frac{\mathrm{d} \theta (t)}{\mathrm{d}t} \vec{e_ \theta}(t) \ + \ \frac{\mathrm{d}z(t)}{\mathrm{d}t} \vec{e_z}$$

Et donc, de manière physique :
$$\vec{v}(t) = \overset{.}{r} \vec{e_r} \ + \ r \overset{.}{\theta} \vec{e_ \theta} \ + \ \overset{.}{z} \vec{e_z}$$
*(si besoin, voir [[Dérivation des vecteurs unitaires (par rapport au temps)]])*


## Composantes en fonction de l'abscisse curviligne

$$\vec{v} = \frac{\mathrm{d}\vec{OM}}{\mathrm{d}t} = \frac{\mathrm{d}\vec{OM}}{\mathrm{d}l} \frac{\mathrm{d}l}{\mathrm{d}t} = \frac{\mathrm{d}l}{\mathrm{d}t} \vec{u_T}$$
Cette relation traduit le fait que **le vecteur vitesse** est toujours **tangent à la trajectoire**, dans le sens du mouvement et que sa norme est :
$$|| \vec{v} || = \frac{\mathrm{d}l}{\mathrm{d}t}$$
A partir de cette même relation, nous pouvons même trouver l'expression du vecteur unitaire tangent :
$$\vec{u_T} = \frac{\vec{v}}{|| \vec{v} ||}$$
voir [[Base de Frenet]]
## Norme du vecteur vitesse instantanée

$$|| \vec{v} || = \frac{\mathrm{d}l}{\mathrm{d}t} = \sqrt{(\frac{\mathrm{d}x}{\mathrm{d}t})^2+(\frac{\mathrm{d}y}{\mathrm{d}t})^2+(\frac{\mathrm{d}z}{\mathrm{d}t})^2} = \sqrt{(\frac{\mathrm{d}r}{\mathrm{d}t})^2 + (r\frac{\mathrm{d} \theta}{\mathrm{d}t})^2 + (\frac{\mathrm{d}z}{\mathrm{d}t})^2}$$
