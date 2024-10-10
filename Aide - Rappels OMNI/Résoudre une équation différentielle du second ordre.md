---
dg-publish: true
---
Soit **l'équation différentielle homogène** du second ordre :
$$y'' \ + \ a_1 \ y' \ + a_0 \ y = 0$$

## Polynôme caractéristique

En reprenant les **coefficients** de **l'équation différentielle homogène** du second ordre :
$$P(X) = X^2 + a_1X+a_0$$

*Remarque : En physique, on préférera noter l'équation différentielle du second ordre sous une forme plus appropriée, voir* [[Résoudre une équation différentielle du second ordre#Notation en Physique]]
## Discriminant du polynôme caractéristique

En calculant le **discriminant** *(delta)* du polynôme caractéristique, 3 cas de figure sont possibles

### Si ∆>0

P admet **deux racines réelles** :

$$\text{Les racines réelles sont } X_1 \text{ et } X_2$$
On écrit alors la solution :
$$y(t) = \lambda e^{X_1t} \ + \ \mu e^{X_2 t}, \ \ \ ( \lambda, \mu) \in \mathcal{R}^2$$
*Plus d'infos dans le cas de la mécanique :*
[[Résoudre une équation différentielle du second ordre#Lorsque ∆ > 0]]
### Si ∆=0

P admet **une racine double** :
$$\text{La racine double se note : } X_0$$
On écrit alors la solution :
$$y(t) = ( \lambda + \mu) e^{X_0 t}, \ \ \ ( \lambda, \mu) \in \mathcal{R}^2$$
*Plus d'infos dans le cas de la mécanique :*
[[Résoudre une équation différentielle du second ordre#Lorsque ∆ = 0]]
### Si ∆<0

P admet **deux racines complexes conjuguées** : 
$$X_1 = X_0 + i \omega \text{ et } X_2 = X_0 -i \omega$$
On peut écrire les solutions sous les formes suivantes :
$$y(t) = e^{X_0 t} [ \ \lambda \ \mathrm{cos}( \omega t) \ + \mu \ \mathrm{sin}( \omega t) \ ], \ \ \ ( \lambda, \mu) \in \mathcal{R}^2$$
$$y(t) = \lambda e ^{X_0 t} [ \ \mathrm{sin}( \omega t + \phi) \ ], \ \ \ ( \lambda, \mu ) \in \mathcal{R}^2$$
*Plus d'infos dans le cas de la mécanique :*
[[Résoudre une équation différentielle du second ordre#Lorsque ∆ < 0]]
## Notation en Physique

### Ecriture de l'équation différentielle du second ordre

> [!NOTE] Ecriture d'une équa diff du second ordre en Physique
> $$y'' \ + \ 2 \gamma \ y' \ + \omega_0^2 \ y = 0$$
> $$\gamma \text{ correspond à l'amortissement (radians/s)}$$
> $$\omega_{0} \text{ correspond à la pulsation propre (radian/s)}$$

> [!NOTE] Ecriture du discriminant en Physique 
> $$\Delta = 4(\gamma^2 - \omega_0^2)$$


### Identification des systèmes

#### Lorsque ∆ > 0
$$\text{Les coefficients } \gamma \text{ et } \omega_0 \text{ sont positifs}$$
On obtiendra une solution de la forme : 
$$y(t) = \lambda e^{X_1t} \ + \ \mu e^{X_2 t}$$
On dit que ce sont des **solutions amorties ou surcritiques**
Le régime est dit **apériodique**
Il n'y a **pas d'oscillation autour de l'axe des abscisses**

#### Lorsque ∆ = 0
$$\text{Les coefficients } \gamma \text{ et } \omega_0 \text{ sont positifs}$$
On obtient une solution de la forme :
$$y(t) = ( \lambda + \mu) e^{X_0 t}, \ \ \ ( \lambda, \mu) \in \mathcal{R}^2$$
On dit que ce sont des **solutions amorties critiques**
Le régime est dit **apériodique critique**
Il n'y a **pas d'oscillation autour de l'axe des abscisses**

#### Lorsque gamma est nul
$$\text{Si } \gamma = 0, \text{ on a alors } \Delta = - \omega_0^2. \text{ Les racines sont donc } ± i \omega_0$$
On obtient alors des solutions purement sinusoïdales :
$$y(t) = \lambda \ \mathrm{cos}( \omega_0 t) \ + \mu \ \mathrm{sin}( \omega_0 t)$$
$$y(t) = A \ \mathrm{sin}( \omega_0 t + \phi)$$
Le régime est dit **harmonique** *(c'est une régime théorique)*

#### Lorsque ∆ < 0

On a 2 racines complexes conjuguées. 

$$\text{On pose alors } \omega_p = \sqrt{\omega_0^2 - \gamma^2}$$
$$\text{Les racines sont alors } - \gamma \ ± i \omega_p$$
Les solutions sont alors de la forme :

$$y(t) = [ \lambda \ \mathrm{cos}( \omega_p t) \ + \mu \ \mathrm{sin} ( \omega_p t) ] \ e^{- \gamma t}$$
ou
$$y(t) = A \ \mathrm{sin} ( \omega_p t + \phi) \ e^{- \gamma t}$$
Le régime est dit **pseudo-périodique** ou **pseudo-critique**

#### Résumé graphique des cas possibles :
![[Pasted image 20241010174319.png]]