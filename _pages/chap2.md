---
title: Introduction
permalink: chap2.html
layout: default
---

<div class="title-box">Chapitre 2 - La Polarisation</div>

Michel n’est pas satisfait - les films en anaglyphe sont peu nombreux et voir tout avec un mélange de bleu et de rouge n’est franchement pas attrayant. Il va donc voir comment la 3D est produite dans un cinéma. Contre toute attente, ses lunettes n’ont aucune couleur - elles ne sont pas anaglyphes, mais polarisées.
  
  ![RealD](assets/img/reald.jpeg)
  
<div class="caption">Les lunettes que Michel a habilement rapporté chez lui</div>
  
Avant de se lancer dans des expériences, Michel se lance dans une petite recherche internet pour s’instruire sur la polarisation.
  
Il existe plusieurs types de polarisation: la polarisation linéaire et la polarisation elliptique (la polarisation circulaire étant un cas particulier de la polarisation elliptique). La lumière **non-polarisée** est composée de plein d'ondes electromagnétiques, ayant toutes des orientations différentes. La lumière **polarisée linéairement** est elle composée d'une seule de ces ondes électromagnétiques, et elle a donc une seule orientation.
  
![Polarisation linéaire](assets/img/polarisation-lineaire.png)
  
<div class="caption">De la lumière non-polarisée (gauche) passe à travers un polariseur linéaire et en sort polarisée linéairement (droite)</div>


Les lunettes de cinéma **polarisées linéairement** fonctionnent comme les lunettes anaglyphes, sauf qu'au lieu de filtrer certaine longueurs d'onde, elles filtrent certaines polarisations. Par exemple, l'oeil gauche va accepter seulement la lumière 
polarisée linéairement à 0°, et l'oeil droit la lumière polarisée linéairement à 90°.

Ainsi, au lieu de projeter une image rouge sur une image bleue, on projette une image polarisée d'une façon sur une image polarisée d'une autre façon. Et tout comme l'anaglyphe, les lunettes ont pour fonction de tromper nos yeux en leur offrant chacun une image légèrement différente, pour que le cerveau l'assimile comme une scène en 3D.

![Polarisation Linéaire Cinéma](assets/img/polarisation-linéaire.jpeg)

<div class="caption">Fonctionnement d'un cinéma utilisant des lunettes polarisées linéairement</div>

Michel se dit qu'il est maintenant le temps de vérifier cela !

<div class="experience">
  <h1>Expérience #2 - Lunettes de cinéma</h1>
  <h2>Mise en place</h2>
  <img src="assets/img/experience-polarisation.png">
  
  La fente et la lentille convergente sont utilisées pour obtenir une image nette.
  Les lunettes de cinéma utilisées sont des lunettes [RealD 3D](https://en.wikipedia.org/wiki/RealD_3D)
  
  <h2>Résultats</h2>
  <table>
	<tr>
		<th rowspan="2"></th>
		<th colspan="2">Lunettes face à la lampe</th>
		<th colspan="2">Lunettes face au mur</th>
	</tr>
	<tr>
		<td>Intensité</td>
		<td>Couleur</td>
		<td>Intensité</td>
		<td>Couleur</td>
	</tr>
	<tr>
		<td>Analyzeur à 0°</td>
		<td>100%</td>
		<td>Légèrement jaune</td>
		<td>100%</td>
		<td>Blanche</td>
	</tr>
	<tr>
		<td>Analyzeur à 90°</td>
		<td>100% </td>
		<td>Légèrement bleue</td>
		<td>0%</td>
		<td>N/A</td>
	</tr>
  </table>
  
  <h2>Conclusions</h2>
  
  
  - On observe tout d'abord que le sens des lunettes influe sur le résultat
    - On peut donc en déduire que le matériau utilisé ne se comporte pas comme un filtre normal, ou alors que celui-ci est en fait composé de deux couches de matériaux différents
  - On observe ensuite que dans un sens, les lunettes se comportent comme si elles étaient un polariseur linéaire - mais que les deux verres sont polarisés dans le même sens, ce qui contredit le concept des lunettes polarisées linéairement
  - Cependant elle n'ont pas cette propriété dans l'autre sens, et de plus, les couleurs changent !
</div>

Et pourtant, Michel n'est pas au bout de ses suprises. Comprenant qu'il n'a pas affaire à un simple polariseur linéaire, il décide de faire plus de tests. Il se balade chez lui avec ses lunettes, quand tout à coup, il remarque qu'il voit des couleurs bizarres lorsqu'il regarde son écran. C'est reparti pour une expérience !

<div class="experience">

<h1>Expérience #3 - Lunettes et écrans</h1>
<h2>Mise en place</h2>

Plusieurs tests sont effectués:
  - Lunettes en face de l'écran
	- Orientées à 0° et 90°
  - Lunettes dos à l'écran
    - Orientées à 0° et 90°
  - Test sur un autre écran
  
<h2>Résultats</h2>
<! --- TODO rotate table --!>
<table>
  <tr>
    <th></th>
    <th>Face à l'écran</th>
    <th>Dos à l'écran</th>
  </tr>
  <tr>
    <td>Angle 0°</td>
    <td><img src="assets/img/ecran-back-horizontal.jpg"></td>
    <td><img src="assets/img/ecran-front-horizontal.jpg"></td>
  </tr>
  <tr>
    <td>Angle 90°</td>
    <td><img src="assets/img/ecran-back-vertical.jpg"></td>
    <td><img src="assets/img/ecran-front-vertical.jpg"></td>
  </tr>
</table>

Et sur un autre écran:

<img src="assets/img/ecran-mac.jpg">

<h2>Conclusions</h2>

  - Le comportement est le même qu'avec de la lumière polarisée linéairement (cf. Expérience #2)
	- Cela voudrait dire que la lumière de cette écran est polarisée linéairement
  - Cependant, lorsqu'on essaie avec un autre type d'écran, les lunettes deviennent ... anaglyphes ?!

</div>

C'en est trop pour Michel - il est temps d'arrêter d'essayer toutes les configurations et de comprendre ce qu'il a observé. 

Tout d'abord, après un peu d'investigation, il découvre que ses lunettes ne sont pas linéairement polarisées, mais **circulairement polarisées**. La polarisation circulaire repose sur le fait qu'on peut décomposer une onde electromagnétique en deux ondes: le projeté de cette onde sur le plan horizontal et le plan vertical.

![Décomposition](assets/img/polarisation-decomposition.png)

<div class="caption">La lumière polarisée linéairement, ici représentée comme l'onde rouge, peut-être décomposée en l'onde bleue et l'onde verte</div>

La lumière polarisée circulairement, est simplement le résultat d' un **déphasage** d'une de ces deux ondes, c'est-à-dire qu'on "décale" un des composants.

![Déphasage](assets/img/polarisation-circulaire.png)

<div class="caption">Par exemple, ici, on remarque que les ondes bleues et vertes ne sont plus synchronisées en haut alors qu'elles le sont en bas: c'est ici la différence entre la lumière polarisée linéairement et circulairement</div>

![Animation](assets/img/polarisation-circulaire-mouvement.gif)

<div class="caption">Ici, la "coupe" (à droite) des composants nous donne deux vecteurs: le bleu et le vert, qui en s'additionnant, donnent le vecteur noir; cela illustre la raison pour laquelle on nomme cela la polarisation circulaire</div>

Et le plus intéressant, c'est qu'en fonction de ce déphasage, on peut obtenir de la lumière polarisée circulairement dans le sens des aiguilles d'une montre, ou dans le sens inverse. Et on peut filtrer l'une des deux: c'est ainsi que marchent les lunettes polarisées circulairement.

Ainsi, c'est toujours sur le même concept que reposent ces lunettes 3D: la séparation d'une image en deux. Cependant, c'est la technique de séparation qui diffère. Et l'avantage qu'offre la polarisation circulaire, c'est que contrairement à la polarisation linéaire, lorsqu'on tourne la tête au cinéma, l'image reste nette - si l'on fait cela avec des lunettes polarisées linéairement, les images se mélangeront, car les filtres des lunettes ne seront plus alignés avec l'image polarisée de l'écran.

Cela est bien intéressant, se dit Michel, mais ça n'explique pas mon expérience. Il s'intéresse donc à la composition d'un polariseur circulaire.


Comme on peut le voir dans l'image précédente, un polariseur circulaire contient 2 composants: cela vérifie l'hypothèse émise lors de l'expérience #2. Le premier composant est un simple **polariseur linéaire**, est le deuxième est une **lame un-quart**, ou lame à quart d'onde. La fonction de cette lame est justement de déphaser la lumière polarisée, comme son nom l'indique, d'un quart d'une longeur d'onde (pi/2) - ce convertit de la lumière polarisée linéairement en lumière polarisée circulairement, et vice-versa.

![Lame quart-d'onde](assets/img/polarisation-circulaire-static.gif)

<div class="caption">Fonctionnement d'une lame quart-d'onde</div>

Lorsque la lame quart d'onde reçoit de la lumière polarisée circulairement, elle la reconvertit en lumière polarisée linéairement. Et en fonction du sens de rotation de la lumière polarisée circulairement d'origine, le résultat va être polarisé linéairement avec un angle différent.

![Lunettes polarisées circulairement](assets/img/polarisation-circulaire-lunettes.png)

<div class="caption">Le premier composant est une lame quart-d'onde, le deuxième un polariseur linéaire. Ici, on observe que la lumière polarisée circulairement dans un sens passe dans l'oeil gauche, mais pas dans l'oeil droit, et vice-versa</div>

Michel peut maintenant, grâce à ces explications, expliquer ses résultats. Tout d'abord, lorsqu'il regarde des objets, ou juste le ciel, il ne voit pas de différent car cette lumière est non-polarisée. Lorsque cependant on fait passer de la lumière polarisée, tout change. Si on fait passer la lumière dans le polariseur linéaire d'abord, alors la lame quart d'onde n'aura pas d'effet: c'est donc le comportement que l'on observe lorsque les lunettes sont face au mur dans l'expérience #2. Et dans l'autre sens, c'est de la lumière polarisée circulairement que l'on voit sur le mur - pour le vérifier, Michel aurait pu utiliser une lame quart d'onde.

Pour les écrans, une partie de l'explication est dans le fonctionnement des écrans LCD. L'expliquer serait tout un autre sujet, mais il faut retenir que la polarisation entre en jeu, et que la lumière que l'on reçoit d'un écran est polarisée linéairement. C'est pour cela qu'on observe le même comportement dans les expériences #2 et #3.

Mais alors, comment expliquer les couleurs ? C'est en fait à cause de la lame quart d'onde, qui a comme effet secondaire de laisser passer un peu plus de certaines longueurs d'ondes. Cet effet est grandement accentué dans l'expérience #3, car en plus de cela, les écrans LCD polarisent certaines couleurs plus que d'autres. La dernière photo de cette expérience suppose que l'écran de ce Mac polarise la lumière jaune circulairement dans un sens, et la lumière bleue dans l'autre. Pour comprendre cela, il faudrait s'intéresser au fonctionnement de ces écrans, mais c'est toute une autre histoire ... Michel s'arrête donc là en terme de polarisation.

<a href="{{ '/chap3' | prepend: site.baseurl | prepend: site.url }}">Suite ...</a>




