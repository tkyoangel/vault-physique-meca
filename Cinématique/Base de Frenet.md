---
dg-publish: true
---


Le vecteur vitesse a permis d'introduire le premier vecteur ut, tangent à la trajectoire 

*(voir [[Vitesse d'un point matériel#Composantes en fonction de l'abscisse curviligne]])*

Nous allons montrer comment trouver un le deuxième vecteur composant la base de frenet

$$\text{On sait que } \vec{u_T} \text{ est un vecteur unitaire} \Leftrightarrow \frac{\mathrm{d} ||\vec{u_T}||^2}{\mathrm{d}l} = \frac{\mathrm{d} (1)}{\mathrm{d}l} = 0$$
*(l représente l'abscisse curviligne)*

Ainsi, en utilisant cette relation, du vecteur unitaire ut (mis au carré pour la démonstration, pas de raison particulière). On peut écrire :

$$\frac{\mathrm{d}}{\mathrm{d}l}(\vec{u_T}.\vec{u_T}) = 0 \Leftrightarrow \frac{\mathrm{d}\vec{u_T}}{\mathrm{d}l} .\vec{u_T} + \vec{u_T} \ . \frac{\mathrm{d}\vec{u_T}}{\mathrm{d}l} = 0 \Leftrightarrow 2(\frac{\mathrm{d}\vec{u_T}}{\mathrm{d}l} .\vec{u_T}) = 0$$

$$\text{On peut donc écrire } \frac{\mathrm{d}\vec{u_T}}{\mathrm{d}l}. \vec{u_T} = 0 \Leftrightarrow \text{ ce qui équivaut à dire...}$$

Que le vecteur uN est orthogonal à uT (car uN est colinéaire à la dérivée du vecteur uT par rapport au rayon de courbure)

On définit uN comme le vecteur unitaire normal à la courbe, dirigé vers l'intérieur

$$\text{Et on admet que : } \frac{\mathrm{d} \vec{u_T}}{\mathrm{d}l} = \frac{\vec{u_N}}{R_C} \text{ où } R_C \text{ est appelé rayon de courbure au point M.}$$
Rc représente le rayon du cercle par lequel on peut approximer la courbe localement en M.