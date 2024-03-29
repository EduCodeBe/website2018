
# Cours de mathématique 

[![hackmd-github-sync-badge](https://hackmd.io/XVhDcOKcQkWvZ-7k7TTAOQ/badge)](https://hackmd.io/XVhDcOKcQkWvZ-7k7TTAOQ)


## Auteurs et contributeurs 

* [Nicolas Pettiaux](mailto:manueldemath@pettiaux.be) ( [CV](https://nicolas.pettiaux.be) ) @npettiaux 
* les élèves de 5e math-sciences et latin-math de l'[Athénée Robert Catteau](https://robertcatteau.be)
    * @IlyassAchour
    * et encore plusieurs
* Lila Galland qui a prêté ses notes de cours


Ce document collaboratif est sous licence CC-BY-SA, la licence utilisée aussi par [Wikipedia](https://fr.wikipedia.org).

Merci de ne pas inclure de contenu privatisé sous droit d'auteur. Par contre, vous pouvez inclure ce que vous rédigez ou du contenu copier-coller depuis wikipedia puisque la licence est la même.

Ce contenu est un des projets de [cours-libres.org](https://cours-libres.org)

View the book with "<i class="fa fa-book fa-fw"></i> Book Mode".

Examples
---
- [Book example](/s/book-example)
- [Slide example](/s/slide-example)
- [YAML metadata](/s/yaml-metadata)
- [Features](/s/features)

Themes
---
- [Dark theme](/theme-dark?both)
- [Vertical alignment](/theme-vertical-writing?both)

###### tags: `Book`

# Formulaire (à connaître par cœur)

## Trigonométrie

 | $\alpha$ en rad (°)      | 0 | $\pi/6$ (30)   | $\pi/4$ (45) | $\pi/3$ (60)     | $\pi/2$ (90) |
 |----------------|----|-------|--------------|--------------|-----|
 | $\sin(\alpha)$ | $0$  | $1/2$ | $\sqrt{2}/2$ | $\sqrt{3}/2$ | $1$   |
 | $\cos(\alpha)$ | $1$  |  $\sqrt{3}/2$ | $\sqrt{2}/2$ |$1/2$ | $0$   |
 | $\tan(\alpha)$ | $0$ |  $\sqrt{3}/3$ | $1$ | $\sqrt{3}$ | $\nexists$   |
 | $\cot(\alpha)$ | $\nexists$ |  $\sqrt{3}$ | $1$ | $\sqrt{3}/3$ | $0$   |
 
  * $\cos(a\pm b)=\cos(a)\cos(b)\mp\sin(a)\sin(b)$
  * $\sin(a\pm b)=\sin(a)\cos(b)\pm\sin(b)\cos(a)$
  * $\tan(a\pm b)=\dfrac{\tan(a)\pm\tan(b)}{1\mp\tan(a)\tan(b)}$
  * $\cos(2a) = \cos^2(a)-\sin^2(a) =  2 \cos^2(a)- 1 = 1- 2 \sin^2(a)$ 
  * $\sin(2a)= 2 \sin(a)\cos(a)$
  * $\tan(2a)=\dfrac{2\tan(a)}{1-\tan^2(a)}$
  * $\cos^2(a)=\dfrac{1+\cos(2a)}{2}$
  * $\sin^2(a)=\dfrac{1-\cos(2a)}{2}$
  * $\cos(a)=\dfrac{1-\tan^2(a/2)}{1+\tan^2(a/2)}$
  * $\sin(a)=\dfrac{2\tan(a/2)}{1+\tan^2(a/2)}$
  * $\sin(x)\pm\sin(y)= 2 \sin{\dfrac{x\pm y}{2}}\cos{\dfrac{x\mp y}{2}}$
  * $\cos(x)+\cos(y)= 2 \cos{\dfrac{x+y}{2}}\cos{\dfrac{x-y}{2}}$
  * $\cos(x)-\cos(y)= 2 \sin{\dfrac{x+y}{2}}\sin{\dfrac{x-y}{2}}$
  * $\sin(x)\cos(y)=\frac{1}{2}\left(\sin(x+y) + \sin(x-y) \right)$
  * $\cos(x)\cos(y)=\frac{1}{2}\left(\cos(x+y) + \cos(x-y) \right)$
  * $\sin(x)\sin(y)=\frac{1}{2}\left(\cos(x-y) - \cos(x+y) \right)$
  
  
## Dérivées 
  * $(a \cdot x)' = a$ avec $a,b \in \mathbb{R}$ et $f,g$ des fonctions
  * $(ax+b)' = a$
  * $(f+g)' = f' + g'$
  * $(fg)' = f'g + fg'$
  * $\left(\dfrac{f}{g}\right)' = \frac{f'g - fg'}{g^2}$
  * $(x^a)' = a x^{a-1}$
  * $\left[g(f(x))\right]'= g'(f(x)) \cdot f'(x)$
  * $\sin(x)'=\cos(x)$
  * $\cos(x)'=-\sin(x)$
  * $\tan(x)'=\dfrac{1}{\cos^2(x)}=1+\tan^2(x)$
  * $(a^x)'$=$\ln(a)$ $\cdot$ $(a^x)$

#### Tableau des dérivées 

| $f(x)$  |  $f'(x)$ |
|------|-------|
|constante| 	0|
|$x$ | 	1|
|$x^2$| $2x$|
|$x^3$| $3x^2$|
|$x^n$ | $n \cdot x^{n-1}$|
|$\frac{1}{x} = x^{-1}$|$-\dfrac{1}{x^2} = -x^{-2}$|
|$\sqrt{x}=x^{1/2}$|$\dfrac{1}{2\sqrt{x}}=\dfrac{1}{2}x^{-1/2}$|
|$\sin(x)$|$\cos(x)$|
|$\cos(x)$|$-\sin(x)$|
|$\tan(x)$|$\dfrac{1}{\cos^2(x)}$|

Et à partir de la $6^e$, il faudra aussi connaître les formules suivantes 

| $f(x)$  |  $f'(x)$ |
|------|-------|
|$e^x$|$e^x$|
|$a^x$|$\ln(a) \cdot a^x$|
|$\ln(x)$|$\dfrac{1}{x}$|
|$\log_a(x)$|$\dfrac{1}{\ln(a)} \cdot \frac{1}{x}$|
##   Tableau des dérivées composées $f,u,v$ :
| $f(x)$  |  $f'(x)$ |
|------|-------|
| $a \cdot u$ | $a \cdot u'$|
|$u^2$ |$2 \, u \times u'$
|$u^3$ 	|$3 \, u^2 \times u'$|
|$u^n$ 	|$n\cdot u^{n-1} \times u'$|
|$\dfrac{1}{u}$ |	$-\dfrac{1}{u^2} \times u'$
|$\sqrt{u}$ 	|$\dfrac{1}{2\sqrt{u}} \times u'$|
|$\sin(u)$ |	$\cos(u) \times u'$|
|$\cos(u)$ |	$-\sin(u) \times u'$|
|$\tan(u)$ |	$\dfrac{1}{\cos^2(u)} \times u'$|
|$u(v(x)) = u(v)$ |    $u'(v(x)) \cdot v'(x) = u'(v) \cdot v'$| 


# Table des matières

# Contenus des cours des années 3 et 4

## Figures isométriques et figures semblables

###   Angle inscrit, angle au centre dans un cercle

###   Figures isométriques

###   Cas d’isométrie des triangles

###   Théorème de Thalès (sans démonstration) et sa réciproque

###   Configurations de Thalès

###   Figures semblables

###   des triangles à côtés parallèles

###   Logique ( implication, réciproque, contraposée, ...)

###   Autre :
  
## Triangle rectangle

###   Théorème de Pythagore et sa réciproque

###   Médiane relative à l’hypoténuse

###   Inscriptibilité d’un triangle rectangle dans un demi-cercle

###   Propriétés métriques dans un triangle rectangle

###   Nombres irrationnels

###   Trigonométrie

###   Définition du sinus, cosinus et tangente d’un angle  dans le triangle rectangle

###   Nombres trigonométriques de 30°, 45° et 60°

## Approche graphique d'une fonction

###   Relation, fonction

###   Graphique d’une fonction

###   Variable dépendante, variable indépendante

###   Parties de $\mathbb{R}$

###   Éléments caractéristiques d’une fonction exclusivement à partir de son graphique

###   Domaine et ensemble-image

###   Image d'un réel

###   Zéro(s)

###   Signe
 
## Premier degré

###   Fonction constante $y \equiv f(x) = b$

###   Représentation graphique de la fonction du premier degré et de la fonction constante

###   Rôle des paramètres $m$ et $p$ dans l'équation $y = mx+p$
  * $m$ est la pente de la droite $d$ dont l'équation est $y=mx + p$. On l'appelle aussi le coefficient angulaire de la droite $d$.
  * $p$ est l'ordonné à l'origine de la droite. En effet, en x=0 l'équation de la droite devient $y=m\cdot 0+p$, soit $y=p$ qui correspond donc bien à l'ordonné à l'origine.

###   Caractéristiques de la fonction du premier (zéro, signe, croissance-décroissance)

###   Inéquation du premier degré 

###   Intersection de deux fonctions du premier degré et/ou constantes
Pour calculer une intersection de deux fonctions du premier degré, il suffit d'égaliser les deux fonctions en question et résoudre en x. 

Exemple:

$f(x)= 6x+3$ et $g(x)=2x-1$; l'intersection entre $f$ et $g$ s'écrit comme $f(x)=g(x)$

Résolvons:
$f(x)=g(x)$
$\iff 6x+3 = 2x-1$ $\iff4x=-4$ $\iff x=-1$
Nous savons dès à présent où se trouve l'intersection (ici en x=-1). Pour finir, injectons ce x trouvé dans $f$ ou $g$, cela n'a pas d'importance puisqu'ils auront la même valeur en y en leur intersection. En effet,
$f(-1)=g(-1)=-3$. L'intersection se trouve donc au point $(-1,-3)$.

 
 ## Outils algébriques

###   Principes d’équivalence des inégalités

###   Équations impossible et indéterminée

###   Règle du produit nul

Cette règle est très souvent utilisée, notamment dans les résolutions d'équations du second degré (et +).

$a\cdot b=0 \Leftrightarrow a = 0 \vee b=0$

###   Équation produit

###   Système d’équations linéaires

###   Puissances à exposant entier

###   Racines (carrée – cubique)

###   Polynômes à une variable (degré , coefficients, opérations)

###   Loi du reste

###   Factorisation

###   Fractions rationnelles
 
 ## Géométrie descriptive

###   Représentation plane d’un objet de l’espace

###   Comparaison entre perspectives cavalière et centrale

###   Caractérisation d’une droite et d’un plan

###   Positions relatives de deux droites, de deux plans, d’une droite et d’un plan

###   Propriétés utiles aux constructions des points de percée et des sections planes

###   Vocabulaire ensembliste (utilisation en contexte) : appartenance, inclusion, intersection
 
 ## Statistique descriptive

###   Population et échantillon

###   Caractères qualitatif et quantitatif

###   Caractères discret et continu

###   Classes de données, centre de classe

###   Effectifs et fréquences cumulés

###   Indicateurs de position : mode, moyenne arithmétique, médiane, quartiles

###   Indicateurs de dispersion : étendue, variance, écart-type, intervalle interquartile

###   Graphiques statistiques : boite à moustaches, histogramme et diagrammes cumulatifs

###   Fonctions statistiques et graphiques d’un logiciel (ordinateur, tablette ou calculatrice)
 
 ## Trigonométrie

###   Définition du sinus, cosinus et tangente d’un angle dans le cercle trigonométrique
Dans un triangle rectangle, 
  * le sinus d'un angle $\alpha$ est le rapport de la longueur du côté opposé à celle de l'hypothénuse $\sin(\alpha) = \frac{\mbox{côté opposé}}{\mbox{hypothénuse}}$
  * le cosinus d'un angle  $\alpha$ est le rapport du côté adjacent à l'hypothénuse $\cos(\alpha) = \frac{\mbox{côté adjacent}}{\mbox{hypothénuse}}$
  * la tangente d'un angle  $\alpha$ est le rapport du côté opposé au côté adjacent $\tan(\alpha) = \frac{\mbox{côté opposé}}{\mbox{côté adjacent}}$

On résume ceci par le moyen mnémotechnique SOHCAHTOA.

Dans le cercle trigonométrique (centré à l'origine, de rayon 1, dans lequel les angles sont lus positivement depuis l'axe X dans le sens anti-horlogique),
  * le sinus d'un angle $\alpha$ est la projection verticale (sur l'axe Y) de l'intersection de la demi-droite qui fait un angle $\alpha$ avec l'axe X et le cercle ;
  * le cosinus d'un angle $\alpha$ est la projection horizontale (sur l'axe X) de l'intersection de la demi-droite qui fait un angle $\alpha$ avec l'axe X et le cercle ;
  * la tangente d'un angle $\alpha$ est la projection verticale de l'intersection de la demi-droite qui fait un angle $\alpha$ avec l'axe X et de la droite verticale passant par $(1,0)$ ;
  * la cotangente d'un angle $\alpha$ est la projection horizontale de l'intersection de la demi-droite qui fait un angle $\alpha$ avec l'axe X et de la droite horizontale passant par $(0,1)$ ;


###   Relations principales ( $\sin^2(x) + \cos^2(x) = 1$ ), ( $\tan(x) = \sin(x)/\cos(x)$ )

###   Formule de l’aire d’un triangle quelconque

###   Relation des sinus

###   Théorème d’Al Kashi
 
 ## Fonctions de références

###   Représentations graphiques des fonctions de référence ($1/x$, $x^2$, $x^3$, valeur absolue, racine, racine cubique)

###   Croissance, décroissance, extremums sur un intervalle

###   Parité

###   Caractéristiques graphiques des fonctions de référence (asymptote, point d'inflexion, relation de réciprocité)

###   Transformées de fonctions par (symétrie orthogonale, translation, affinité)
  
## Deuxième degré

###   Fonction du $2^e$ degré

###   Caractéristiques de la fonction du $2^e$ degré (Zéro, Signe, Croissance, décroissance, Extremum)

###   Caractéristiques de la parabole d’axe vertical (Sommet, Axe de symétrie, Concavité)

###   Équations et inéquations du $2e$ degré

###   Somme et produit des solutions de l’équation du $2^e$ degré

###   Forme factorisée du trinôme du $2^e$ degré

## Géométrie analytique plane

###   Vecteurs

###   Addition de deux vecteurs

###   Multiplication d’un vecteur par un réel

###   Vecteurs colinéaires

###   Repère orthonormé

###   Composantes d’un vecteur

###   Vecteur directeur d’une droite

###   Équations vectorielle, paramétriques et cartésienne d’une droite

###   Droite d’équation $y = ax + b$

###   Coefficient angulaire d’une droite

###   Condition de parallélisme et de perpendicularité de deux droites
  * 2 droites sont parallèles si et seulement si elles ont même pente (même coefficient directeur) ;
  * 2 droites sont perpendiculaires si et seulement si leurs pentes sont opposées et inverses l'une de l'autre (autrement dit, si le produit de leurs pentes vaut $-1$).


###   Distance entre un point et une droite

###   Milieu d’un segment
Soit le segment $AB$ défini par les points $A=(x_A,y_A)$ et $B=(x_B,y_B)$, le point $M$, milieur de $AB$ a comme coordonnées $(x_M,y_M)=(\frac{x_A+x_B}{2},\frac{y_A+y_B}{2})$

###   Définition de la parabole en tant que lieu géométrique

  * Lieu des points équidistants à une droite appelée directrice et à un point appelé foyer

###   Équation cartésienne d’une parabole d’axe vertical
$y=a (x-\alpha)^2+\beta$
$y=a x^2 + b x + c$ et $\Delta = b^2 - 4 ac$ et $x_{1,2} = \frac{-b\pm\sqrt\Delta}{2a}$
$\alpha = \frac{-b}{2a}$ et $\beta=\frac{-\Delta}{2a}$ 

###   Équation cartésienne d’un cercle 
$(x-a)^2 + (y-b)^2 = r^2$

 $x = x_c + r \cos(\theta)$ et  $y = y_c + r \sin(\theta)$

# Matière de $5^e$

## Statistique à deux variables

## Suites

## Limites, asymptotes et continuité

### Limites

### Quelques limites particulières

#### Sin(x)/x quand x tend vers 0

$$ \lim_{x \to 0} \dfrac{\sin(x)}{x} = 1$$

##### Démonstration

Géométriquement, dans le cercle trigonométrique, prenons un petit angle positif $x$. Il délimite sur le cercle les points $P, Q, R$ et $T$ qui représente la tangente de $x$.

#### 

### Continuité

### Asymptotes

## Dérivée

### Introduction 

La dérivée est très importante car permet de comprendre comment change une fonction, donc un phénomène. On s’en sert très souvent au cours de mathématique dans les études de fonction.

L’avantage c’est qu’il n’y a pratiquement que des formules à apprendre, et une fois que tu les connais, c’est extrêmement simple !! 

### La dérivée, qu’est-ce-que c’est ?

Quand on a une fonction $f$ assez régulière, on peut calculer une autre fonction que l’on note $f'$ (prononcée « f prime ») et qu’on appelle la dérivée de $f$. 

Nous verrons plus tard l’utilité de $f'$.

L’objectif est tout d’abord de savoir comment calculer cette dérivée $f'$ à partir de la fonction $f$.

Par définition, la dérivée par rapport à $x$ de $f(x)$ est écrite $f'(x)$ et vaut $$ f'(x) := \lim_{h \to 0} \dfrac{f(x+h)-f(x)}{h} = \lim_{\Delta x \to 0} \dfrac{f(x+\Delta x)-f(x)}{\Delta x} = \lim_{x_1 \to x} \dfrac{f(x_1)-f(x)}{x_1 - x} $$


Notez qu'il existe une autre notation pour la dérivée de $f$, à savoir $$f'(x)=\frac{\mathrm{d}f}{\mathrm{d}x}(x)$$

### Formules de dérivées

Le tableau à 2 colonnes suivant contient à gauche la fonction $f$ et sa dérivée $f'$ à droite.

Ce tableau est à connaître par coeur dès le début ce tableau. Avec l’habitude et beaucoup d’exercices, ça semblera logique et évident.

#### Tableau des dérivées 

| $f(x)$  |  $f'(x)$ |
|------|-------|
|constante| 	0|
|$x$ | 	1|
|$x^2$| $2x$|
|$x^3$| $3x^2$|
|$x^n$ | $n \cdot x^{n-1}$|
|$\frac{1}{x} = x^{-1}$|$-\dfrac{1}{x^2} = -x^{-2}$|
|$\sqrt{x}=x^{1/2}$|$\dfrac{1}{2\sqrt{x}}=\dfrac{1}{2}x^{-1/2}$|
|$\sin(x)$|$\cos(x)$|
|$\cos(x)$|$-\sin(x)$|
|$\tan(x)$|$\dfrac{1}{\cos^2(x)}$|

Et à partir de la $6^e$, il faudra aussi connaître les formules suivantes 

| $f(x)$  |  $f'(x)$ |
|------|-------|
|$e^x$|$e^x$|
|$a^x$|$\ln(a) \cdot a^x$|
|$\ln(x)$|$\dfrac{1}{x}$|
|$\log_a(x)$|$\dfrac{1}{\ln(a)} \cdot \frac{1}{x}$|



Dans le tableau, ce qu’on appelle constante, c’est un réel, qui ne dépend pas de $x$, comme $27, ⅔, 36,7$ ou $\pi$.

Prenons un exemple :

Si $f(x) = x^2$, alors d’après la formule du tableau, on a $f'(x) = 2x$, tout simplement !

La seule formule qui peut poser problème est celle de $x^n$.

En fait c’est la formule valable pour toutes les puissances de $x$ : $x^5$, $x^9$, $x^{965}$, et même les puissances négatives comme $x^{-5}$ ou $x^{-12}$. Pour les valeurs entières de $n$ (autrement dit $n\in\mathbb{Z}$), ceci est valable pour tout $x$ réel ($x\in\mathbb{R}$).

Si le domaine de la fonction est restreint aux réels positifs ($x\in\mathbb{R^+}$), alors la formule est aussi valable pour toute valeur réelle de $n$. Les valeurs rationnelles de $n$ ($x\in\mathbb{Q}$) correspondent à des puissances de racines. En effet, pour tout rationnel $n$, on peut l'écrire $n=\frac{p}{q}$ où $p, q \in\mathbb{N}$, et $x^n=x^\frac{p}{q} = \sqrt[q]{x^p}$.

Voici une vidéo sur les dérivées de base et une astuce pour retenir cette formule, ainsi que la démonstration de 2 formules du tableau à partir de celle de $x^n$.

### Somme de fonctions et constantes multiplicatives

Et si on a une somme de fonctions ? C’est facile, on dérive les uns après les autres.

**La dérivée d'une somme est la somme des dérivées.**

#### Démonstration de la dérivée d'une somme de fonctions

Soit $f,g$, 2 fonctions dérivables sur l'intervalle $I = \left[ a,b \right]$. Démontrons que $(f+g)' = f'+g'$

##### Démonstration 

Par définition de la dérivée, la dérivée par rapport à $x$ de $(f+g)(x)$  $$ (f+g)'(x) := \lim_{h \to 0} \dfrac{(f+g)(x+h)-(f+g)(x)}{h} = \lim_{\Delta x \to 0} \dfrac{f(x+\Delta x)-f(x)}{\Delta x} = \lim_{x_1 \to x} \dfrac{f(x_1)-f(x)}{x_1 - x} $$


Exemple : $f(x) = x^5 - x^2 + 12$

La dérivée de $x^5$ est $5x^4$, la dérivée de $x^2$ est $2x$, la dérivée de $12$ est $0$ car $12$ est une constante. On a alors :

$f'(x) = 5x^4 - 2x + 0$

C’est très simple, on dérive tranquillement chaque terme, il faut juste faire attention à mettre le bon signe à chaque fois ($+$ ou $-$).

Et les constantes multiplicatives ?

Ce qu’on appelle constante multiplicative, ce sont les réels qui sont facteurs des puissances de $x$.

Par exemple dans $f(x) = 7x^9 - 8x^3 + 5$, le $7$ et le $8$ sont des constantes multiplicatives, car elles sont des facteurs de  $x$, tandis que le 5 est une constante tout court, il n’y a pas de $x$ avec lui.

Alors comment fait-on ?

Là aussi c’est très simple, dans la dérivée, on conserve la constante multiplicative et on dérive tranquillement le reste.

Exemple : $f(x) = 9x^5$. La dérivée de $x^5$ est $5x^4$, on a donc
$f'(x) = 9\times 5x^4$ et $f'(x) = 45x^4$. On copie le $9$ et on a ensuite dérivé le terme $x^5$. Evidemment après on calcule $9\times5$, on ne laisse surtout pas le $9 \times 5x^4$ comme ça.

Bien sûr on peut avoir des sommes de fonctions avec des constantes multiplicatives : $f(x) = 7x^9 - 8x^3 + 5$

Et tout naturellement, on dérive chaque terme en recopiant le constante multiplicative à chaque fois : 

$f'(x) = 7\times 9x^8 - 8\times 3x^2 + 0 = f'(x) = 63x^8 - 24x^2$

Il n’y a aucune difficulté à ce niveau-là, tout semble très logique.

#### Produits et quotients de fonctions

Par contre quand on a des produits ou des quotients de fonctions, ça devient un peu différent.

Soit les 2 fonctions $u$ et $v$, les formules sont alors les suivantes :
$(u\times v)'= u' \times v + u \times v'$ ou plus simplement, 
$(u v)'= u'  v + u v'$ . Et $\dfrac{u}{v} = \dfrac{u'v-uv'}{v^2}$.

Prenons $f(x) = (2x + 1) \times (x^2 - 9)$

On a bien $u \times v$ avec $u = 2x + 1$ et $v = x^2 – 9$. 

Il est alors recommandé d’écrire u, v, u’ et v’ de la manière suivante :

$u = 2x + 1$ et $u’ = 2$

$v = x2 – 9$ et $v’ = 2x$

Il ne reste plus alors qu’à appliquer la formule en remplaçant $u$, $v$, $u’$ et $v’$.

$f'(x) = u'v + uv' = (2) \times (x^2 - 9) + (2x + 1) \times (2x)$ ou
$f'(x) = 2x^2 - 18 + 4x^2 + 2x$ ou encore, $f'(x) = 6x^2 + 2x - 18$

Il n’y a aucune difficulté du moment que l'on connaît et peut appliquer  la formule !

L’intérêt d’écrire $u, u’, v$ et $v’$ sous la forme d’un petit tableau comme au-dessus permet d’avoir les différentes parties regroupées.
Ainsi, après avoir écrit la formule $u’v + uv’$, ce sera beaucoup plus facile lors du remplacement.

Pour se souvenir de la formule, voici un moyen simple : dites-vous « je dérive le 1er et je laisse le 2ème (ce qui te donne $u’v$), puis je fais l’inverse, je laisse le 1er et jé dérive le 2ème (ce qui donne $uv’$) ».

**ATTENTION**: Il ne faut surtout pas dire que $(u × v)’ = u’ × v’$.
En gros il ne faut pas dériver bêtement chaque terme, il faut bien appliquer la formule.

Pour les quotients c’est exactement la même chose, on applique la formule après avoir fait le petit tableau. Soit à dériver $\dfrac{5x+1}{x^6+5x-2}$.

On écrit

$u = 5x + 1$ et $u’ = 5$

$v = x^6 + 5x – 2$ et $v’ = 6x^5 + 5$

Et on applique la formule $\dfrac{u}{v} = \dfrac{u'v-uv'}{v^2}$.

Et là il faut retenir quelque chose de très important : **on ne développe jamais le dénominateur.**

La raison principale c’est : à quoi ça sert de développer ? 
En effet, rien ne va se simplifier… 

Au numérateur en revanche, on va avoir des termes qui vont se simplifier.
Une fois de plus, une fois que les formules connues, il n’y a aucun souci.

Évidemment un peu d’entraînement avec ces exercices sur les dérivées de produits et de quotients ne feront pas de mal.

**Les dérivées de fonctions composées**

Déjà, une fonction composée, c’est quoi ? Et bien ce sont tout simplement 2 fonctions qui sont regroupées ensemble.

Exemple : au lieu d’avoir seulement $g(x)$ = $\sqrt{x}$ on a
$f(x)$ = $\sqrt{8x^2 - 5x + 4}$

Cette $2^e$ fonction est une fonction composée, puisqu’il y a 2 fonctions « imbriquées », à savoir : $\sqrt{x}$ \, et $\, 8x^2 - 5x + 4$

Deux autres exemples : au lieu d’avoir $g(x)$ =$\frac{1}{x}$
on a $f(x)$ =$\frac{1}{8x^6 + 4x^7 - 6x}$
et au lieu d’avoir
$g(x)$ = $x^2$, on a
$f(x)$ = $(5x^9 - 2x + 6)^2$

Généralement, la fonction « à l’intérieur » de l’autre (dans le 1er exemple, $8x^2 – 5x + 4$, dans le $2^e$ exemple $8x^6 +4x^7 – 6x$, dans le $3^e$ exemple $5x^9 – 2x + 6$ est notée $u$.

Ainsi, la formule générale des fonctions composées est entre autres :
$u^2$, $\sqrt{u}$, $\frac{1}{u}$ etc…

Pour dériver ce type de fonctions, c’est extrêmement simple. 

On dérive comme si c’était un $x$ et non un $u$, et on multiplie toujours par $u’$.

Regardons ce que cela donne dans le tableau :


  Tableau des dérivées composées $f,u,v$ :
| $f(x)$  |  $f'(x)$ |
|------|-------|
| $a \cdot u$ | $a \cdot u'$|
|$u^2$ |$2 \, u \times u'$
|$u^3$ 	|$3 \, u^2 \times u'$|
|$u^n$ 	|$n\cdot u^{n-1} \times u'$|
|$\dfrac{1}{u}$ |	$-\dfrac{1}{u^2} \times u'$
|$\sqrt{u}$ 	|$\dfrac{1}{2\sqrt{u}} \times u'$|
|$\sin(u)$ |	$\cos(u) \times u'$|
|$\cos(u)$ |	$-\sin(u) \times u'$|
|$\tan(u)$ |	$\dfrac{1}{\cos^2(u)} \times u'$|
|$u(v(x)) = u(v)$ |    $u'(v(x)) \cdot v'(x) = u'(v) \cdot v'$| 


C’est **exactement** le même tableau que précédemment mais on a remplacé $x$ par $u$, et on a multiplié à chaque fois la dérivée par $u’$.

## Application principale : variations d’une fonction


Bon la dérivée c’est bien joli mais à quoi ça sert dans le cours de mathématique ?

Et bien c’est très simple :

Si $f' ≥ 0$, alors $f$ est croissante et si $f' ≤ 0$, alors $f$ est décroissante.

Un exemple tout simple : soit la fonction $f(x) = x^2 - 6x + 4$

On cherche à faire le tableau de variation de $f$.

Pour cela, on calcule d’abord $f'$ : $f'(x) = 2x - 6$

Le but est de savoir le **signe** de $f'$. Ici, $f’$ est de la forme $ax + b$, il suffit donc de savoir quand $f'$ s’annule car on sait construire le tableau de signe d’une fonction de type $ax + b$.

On calcule $ 2x – 6 = 0$ ou $ 2x = 6$ ou $ x = 3$. 

On peut alors faire le *tableau de signe* de $f’$:

| $x$ | $- \infty$ | 3 | $\infty$ |
|---|------------|---|----------|
|$f'(x)$| $-$ | $0$ | $+$ |


En effet, cela correspond au tableau de signe d’une fonction $ax + b$ avec $a > 0$.

Et maintenant on applique la propriété qu’on a vu juste au-dessus : si $f' ≤ 0$, la fonction est décroissante, sinon elle est croissante !

Il faut bien voir qu’on fait le *tableau de **signes*** de $f'$, mais le *tableau de **variations*** de $f$, il ne faut pas mélanger les 2.

Évidemment, si $f'$ change plusieurs fois de signe, $f$ change plusieurs fois de sens de variation. On peut donc imaginer le tableau suivant :

Il y a une chose qu'il faut retenir : pour faire un tableau de signe de $f'$, il faut factoriser au maximum $f'$.

En effet, quand on fait le tableau de signe d’une fonction, il faut toujours la factoriser …

### Lien avec la limite et dérivabilité
(pas vu encore en 5 LM-MS au 6 décembre 2022)

La dérivabilité, c’est le fait qu’une fonction soit dérivable ou non sur un certain intervalle. Pour cela, on utilise les limites vues au chapitre précédent.

Le lien entre limite et dérivée est simple : si on a un point d’abscisse $a$, on a la relation suivante :

Il y a une autre formule équivalente mais qui est moins pratique à utiliser, nous te la donnons juste à titre indicatif pour que tu saches ce que c’est au cas où tu la rencontres :

Bon ok, et ça sert à quoi cette formule ??
Cette formule sert justement à savoir si une fonction est dérivable en un point ou non.

—
En effet, la fonction f est dérivable en a SI

avec k REEL !!
—

Autrement dit il faut que la limite existe et que cette limite soit finie.
On rappelle que +∞ et -∞ ce n’est pas fini, donc si on obtient ce résultat, ce ne sera pas dérivable…

Attention : la limite ci-dessus n’existe pas forcément, si elle n’existe pas la fonction ne sera pas dérivable en a…

Mais si la limite existe et qu’elle est finie, on peut poser :

f'(a) = k

Avec un petit exemple ce sera plus simple :
Prenons la fonction racine :

f(x) = \sqrt{x}

On cherche à savoir si cette fonction est dérivable en a = 0 ou non.
On calcule alors :

car f(0) = √0 = 0

On multiplie alors en haut et en bas par √x pour pouvoir simplifier :

La limite vaut donc +∞, donc la limite n’est pas finie !!
Donc la fonction racine n’est pas dérivable en 0.

Cette partie peut peut-être te sembler un peu dure, mais rassure-toi, ce n’est pas ce qu’il faut retenir en priorité, loin de là !!
D’ailleurs on fait rarement ce genre de calculs, il est beaucoup plus important de savoir calculer la dérivée d’une fonction comme on l’a fait auparavant.

Mais tu peux toujours t’entraîner avec ces exercices sur la dérivabilité d’une fonction, on y trouve notamment une propriété intéressante à connaître, démontrée avec ce qu’on vient de voir.


## Équation de la tangente

Cette histoire de limite et de dérivabilité n’est sûrement pas ce qui est le plus utilisé le plus dans les cours.

En revanche, il y a une autre application plus importante de la dérivée : **l’équation de la tangente** !

Une tangente à une fonction qu’est-ce-que c’est ?

C’est une droite, elle est donc de la forme $y = ax + b$

Ensuite, cette droite « longe » la courbe de la fonction sans la traverser… bon avec un schéma ce sera plus simple :

*** IMAGE À RAJOUTER ***

Et si on fait un gros zoom, la tangente ne coupe la courbe qu’en un seul point :

Bien sûr si on dézoome, il est possible que la tangente recoupe la courbe mais ce sera assez loin et ça ne nous intéresse pas.

La tangente que tu connais peut-être déjà c’est la tangente à un cercle, qui est perpendiculaire au rayon :


Les 3 droites sont tangentes au cercle (et donc perpendiculaires à un rayon)

Il y a évidemment une infinité de tangentes, en fait il y en a en tout point où la fonction est dérivable.
Pourquoi ?
Et bien tout simplement parce que dans la formule de l’équation de la tangente, il y a la dérivée !

L’équation de la tangente AU POINT D’ABSCISSE « a » est la suivante :

Cette formule est à apprendre PAR COEUR !!!

Néanmoins nous allons te l’expliquer un peu.
En fait, la dérivée de f en a, c’est-à-dire f ‘(a), a une signification graphique :

—
f ‘(a) est le coefficient directeur de la tangente au point d’abscisse a
—

Or on a vu que la tangente était une droite, et comme son coefficient directeur est f ‘(a), son équation est de la forme :

y = f'(a)x + b

Par ailleurs, quand x = a, y = f(a) puisque la tangente coupe la courbe en a !
On a donc en remplaçant x par a et y par f(a) :

f(a) = f'(a)\times a + b
donc

b = f(a) - f'(a)\times a

Et donc en remplaçant le b dans l’équation ci-dessus, on a :

y = f'(a)x + f(a) - f'(a)\times a
ce qui donne

y = f'(a)(x-a) + f(a)

Et voilà, on a retrouvé l’équation de la formule !! a

—
Attention à ne pas confondre f(a) et f ‘(a) !!
Pour ne pas inverser, dis-toi que le f ‘(a) est avec le x puisque f ‘(a) est le coefficient directeur.
Utilise cela pour te souvenir facilement de la formule.
—

Dernière chose à noter : si on te demande de donner l’équation d’une tangente en a, il faut donc connaître f ‘(a) et f(a) pour remplacer dans la formule.
Il est alors conseillé de calculer séparemment f ‘, puis f ‘(a) et f(a) également séparemment au lieu d’écrire directement la formule, sinon il y a trop de chose à calculer d’un coup et il y a alors plus de chances que tu fasses des erreurs a

Avec ces quelques exemples sur les tangentes, tu verras la méthode complète pour calculer une équation de tangente.

Intérêt de la dérivée

La dérivée est fondamentale car on la retrouve presque tout le temps avec les fonctions !!

Comme on l’a vu, elle permet de connaître l’équation de la tangente, de pouvoir calculer quelques limites de formes indéterminées, et surtout de connaître le sens de variation d’une fonction !!
C’est pour cette dernière application qu’elle est la plus utilisée.

La dérivée est également utile dans les équations différentielles, que l’on voit en Terminale, qui sont des équations reliant une fonction et sa dérivée.
L’intérêt est que de nombreux phénomènes physiques sont régis par des équations différentielles, et il faut donc savoir les résoudre pour pouvoir étudier les grandeurs mises en jeu.

## Fonctions trigonométriques

## Géométrie vectorielle du plan et de  l’espace

## Géométrique analytique et synthétique de  l’espace

# Matière de $6^e$

## Fonctions réciproques

## Fonctions exponentielles

### Définitions
La fonction exponentielle est celle
  *  dont la dérivée est proportionnelle à elle-même $f'(x) = \frac{d}{dx} f(x) =  k f(x)$ où $k \in \mathbb{R}$
  *  qui transforme une somme en produit : $f(a+b) = f(a) f(b)$
  *  qui est définie par $f:\mathbb{R} \rightarrow \mathbb{R}: x \rightarrow a^x$ où $a \ne 1 \wedge a>0$
### Propriétés
* $e^{x+y}=e^xe^y$
* Le rayon de convergeance de la fonction $e^x$ vaut $\infty$
* $\text{dom}\ f = \mathbb{R}$  et  $\text{Im}\ f = \mathbb{R_0^+}$ ($f(x)>0$ ,  $\forall x\in\mathbb{R}$)
* Continue, soit $\forall \tilde{x}\in\mathbb{R},\lim_{x\to\tilde{x}, x<\tilde{x}} x =\lim_{x\to\tilde{x}, x>\tilde{x}} x$
* Partout dérivable
* Strictement croissante si $a>1$ et strictement décroissante si $0<a<1$
* $G_f\ni (0,1), \forall a\in\mathbb{R}$
* $a^x$ grimpe plus vite que n'importe quel polynôme si $a>1$
* ... ?

### Représentation graphique

## Fonctions logarithmes

Définitions : la fonction logarithme est celle

  *  dont la dérivée est inversément à son argument $f'(x) = \frac{d}{dx} f(x) =  k \frac{1}{x}$ où $k \in \mathbb{R}$
  *  qui transforme un produit en somme : $f(ab) = f(a) + f(b)$
  
## Intégrales et primitives

## Nombres complexes

## Fonctions réciproques 

## Fonctions cyclométriques

## Lieux géométriques

## Probabilité

## Lois de probabilités

# Compléments - PES (préparation aux études supérieures)

## Éléments de logique

Note aux rédacteurs : les symboles latex logiques sont dans [ici](http://ybouchard.espaceweb.usherbrooke.ca/cours/symboles_logiques_latex.pdf)

#### Disjonction exclusive

$p \veebar q$ se lit « soit $p$, soit $q$ ». 

$p \veebar q$ n'est vrai que si un seul des ses opérandes est vrai. 

L'opérateur $\veebar$ est également appelé « ou exclusif ».

##### Table de vérité

| $p$  | $q$ | $p \veebar q$ | 
| ---- | --- | -----------|
| $V$  | $V$ |   $F$      |
| $V$  | $F$ |   $V$      |
| $F$  | $V$ |   $V$      |
| $F$  | $F$ |   $F$      |

### Propositions

#### Définition

Une *proposition* est une *affirmation* qui est soit vraie, soit fausse.

##### Exemples

  * «  La carotte est un légume »  est une proposition.
  * «  La carotte est un moyen de locomotion »  est une proposition.
  * «  La carotte a bon goût »  n'est pas une proposition. Sa valeur de vérité dépend du goût du lecteur.
  * «  Arrache cette carotte ! »  n'est pas une proposition. C'est un ordre
  * «  Je mens »  n'est pas une proposition. C'est un paradoxe.

#### Formalisme

En logique propositionnelle (comme en arithmétique,  en algèbre, etc.), on raisonne la plupart du temps sur des propositions quelconques que l'on note $p$, $q$, $r$, $\ldots$ Comme on ne connaît pas à priori la valeur de vérité de la proposition, on doit envisager tous les cas  possibles, ce qui nécessite l'utilisation de  *tables de vérité* (voir la section suivante).


### Opérateurs logiques

Soient $p$ et $q$ deux propositions quelconques. On peut  les connecter. La  *valeur de vérité* de la  *formule* ainsi  obtenue est exprimée par une  *table de vérité*. Le symbole  $V$ vaut pour  *vrai*, tandis que $F$ vaut pour  *faux*.

#### Négation

La négation transforme le vrai en faux et vice-versa.

| $p$  | $\neg p$| 
| ---- | --------|
| $V$  | $F$     |
| $F$  | $V$     |

###### Exemple

Avec $p$ = « il pleut », on a:
  * $\neg p$ :  «  *il est faux qu'* il pleut » 
ou, plus simplement~:
  * $\neg p$ :  « il  *ne* pleut  *pas* »


#### Conjonction

$p \wedge q$ se lit « $p$ et $q$ ». 

$p \wedge q$ n'est vrai que si $p$ et $q$ sont tous les deux vrais.

##### Table de vérité

| $p$  | $q$ | $p \wedge q$ | 
| ---- | --- | -------------|
| $V$  | $V$ |     $V$      |
| $V$  | $F$ |     $F$      |
| $F$  | $V$ |     $F$      |
| $F$  | $F$ |     $F$      |


#### Disjonction

$p \vee q$ se lit « $p$ ou $q$ ». 

$p \vee q$ est vrai dès que l'un de ses opérandes est vrai.

L'opérateur $\vee$ est également appelé « ou inclusif ».

| $p$  | $q$ | $p \vee q$ | 
| ---- | --- | -----------|
| $V$  | $V$ |   $V$      |
| $V$  | $F$ |   $V$      |
| $F$  | $V$ |   $V$      |
| $F$  | $F$ |   $F$      |

###### Exemple
L'affirmation « il pleut  *ou* l'orage éclate »  est  *fausse* s'il n'y a  *ni* pluie  *ni* orage.


#### Disjonction exclusive

$p \veebar q$ se lit « soit $p$, soit $q$ ». 

$p \veebar q$ n'est vrai que si un seul des ses opérandes est vrai. 

L'opérateur $\veebar$ est également appelé « ou exclusif ».

##### Table de vérité

| $p$  | $q$ | $p \veebar q$ | 
| ---- | --- | -----------|
| $V$  | $V$ |   $F$      |
| $V$  | $F$ |   $V$      |
| $F$  | $V$ |   $V$      |
| $F$  | $F$ |   $F$      |

#### Implication

$p \implies q$ se lit « si $p$, alors $q$ »  ou encore « $p$ implique $q$ ». 

Dans l'expression $p \implies q$, $p$ est l' *antécédent*, la  *prémisse* ou l' *hypothèse* tandis que $q$ est le  *conséquent* ou la  *conclusion*.

$p \implies q$ est toujours vrai,  *sauf* quand $p$ est vrai et $q$ faux. En particulier $p \implies q$ est toujours vrai:
  *  lorsque $p$ est faux, quelle que soit la valeur de vérité de $q$ ;
  * lorsque $q$ est vrai, quelle que soit la valeur de vérité de $p$.


##### Table de vérité

| $p$  | $q$ | $p \implies q$ | 
| ---- | --- | -----------|
| $V$  | $V$ |   $V$      |
| $V$  | $F$ |   $F$      |
| $F$  | $V$ |   $V$      |
| $F$  | $F$ |   $V$      |

##### Interprétation de la table de vérité

Pour comprendre la table de vérité de l'implication, prenons un exemple. 

Soient les propositions $p$ et $q$, $p$ « il pleut » et $q$ « j'utilise mon parapluie », alors l'implication $p \implies q$ se traduit par l'expression propositionnelle :  «   *Si* il pleut  *alors* j'utilise mon parapluie »

La table de vérité de l'implication exprime le fait que lorsque j'affirme :  «  Si il pleut alors j'utilise mon parapluie »

La table de vérité de l'implication exprime le fait que lorsque j'affirme :  «  Si il pleut alors j'utilise mon parapluie » le seul cas où je mens, c'est lorsqu'il pleut  *mais* que je n'utilise  *pas* mon parapluie, c'est-à-dire quand $p$ est vrai et $q$ faux. S'il pleut et que j'utilise mon parapluie, je n'ai pas menti. S'il ne pleut pas, que j'utilise ou non mon parapluie ne constitue pas un mensonge non plus car : «  Si il pleut alors j'utilise mon parapluie » ne représente un engagement  *que* s'il pleut. 

#### Équivalence

$p \equiv q$ se lit « $p$ si et seulement si $q$ ».

$p \equiv q$ est vrai lorsque $p$ et $q$ ont même valeur de vérité.

On dit donc, de manières équivalentes, pour $p \equiv q$ 
  * $p$ si et seulement si $q$, ou 
  * une condition nécessaire et suffisante (CNS) pour $p$ est $q$, ou
  * $p$ est équivalent à $q$, ou
  * $p$ équivaut $q$.


##### Table de vérité


| $p$  | $q$ | $p \equiv q$ | 
| ---- | --- | -----------|
| $V$  | $V$ |   $V$      |
| $V$  | $F$ |   $F$      |
| $F$  | $V$ |   $F$      |
| $F$  | $F$ |   $V$      |

### Calcul propositionnel et priorités des opérateurs logiques

On peut construire des formules en connectant des propositions,  mais aussi en connectant d'autres formules. La valeur de vérité  de la formule obtenue dépend des valeurs de vérité des propositions  qui y figurent.
 
Dans ce cours, les règles de priorités adoptées pour les opérateurs logiques sont  celles définies par les fondateurs de la logique mathématique moderne. Elles sont en outre celles toujours  en vigueur pour les connecteurs propositionnels. À savoir que tous les connecteurs ont la  *même priorité* à l'exception de  la négation qui est prioritaire. Pour indiquer l'ordre d'évaluation des opérateurs et donc bien former les  expressions propositionnelles, on utilise les  *parenthèses*.

 
###### Exemple

On peut construire la formule $(p \veebar q) \vee (\neg p \vee \neg q)$ en  connectant les propositions $p$ et $q$.


