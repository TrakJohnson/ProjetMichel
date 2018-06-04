---
title: Introduction
permalink: chap2.html
layout: default
---

<div class="title-box">Chapitre 2 - La Polarisation</div>

  Cependant, Michel n’est pas satisfait - les films en anaglyphe sont peu nombreux et voir tout avec un mélange de bleu et de rouge n’est franchement pas attrayant. Il va donc voir comment la 3D est produite dans un cinéma. Contre toute attente, ses lunettes n’ont aucune couleur - elles ne sont pas anaglyphes, mais polarisées.
  
  ![RealD](assets/img/reald.jpeg)
  
<div class="caption">Les lunettes que Michel a habilement rapporté chez lui</div>
  
  Avant de se lancer dans des expériences, Michel se lance dans une petite recherche internet pour s’instruire sur la polarisation.
  
  Il existe plusieurs types de polarisation: la polarisation linéaire et la polarisation elliptique (la polarisation circulaire étant un cas particulier de la polarisation elliptique). La lumière **non-polarisée** est composée de plein d'ondes electromagnétiques, ayant toutes des orientations différentes. La lumière **polarisée linéairement** est elle composée d'une seule de ces ondes électromagnétiques.
  
![Polarisation linéaire](assets/img/polarisation-lineaire.png)
  
<div class="caption">De la lumière non-polarisée (gauche) passe à travers un polariseur linéaire et en sort polarisée linéairement (droite)</div>


Les lunettes de cinéma **polarisées linéairement** fonctionnent comme les lunettes anaglyphes, sauf qu'au lieu de filtrer certaine longueurs d'onde, elles filtres certaines polarisations. Par exemple, l'oeil gauche va accepter seulement la lumière polarisée linéairement à 0°, et l'oeil gauche la lumière polarisée linéairement à 90°. Ainsi, au lieu de projeter une image rouge sur une image bleue, on projette une image polarisée d'une façon sur une image polarisée d'une autre façon. Et tout comme l'anaglyphe, les lunettes ont pour fonction de tromper nos yeux en leur offrant chacun une image légèrement différente, pour que le cerveau l'assimile comme une scène en 3D.

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
  - On observe ensuite que dans un sens, les lunettes se comportent comme si elles étaient un polariseur linéaire
  - Cependant elle n'ont pas cette propriété dans l'autre sens ... ?! 
</div>

Et pourtant, Michel n'est pas au bout de ses suprises. Comprenant qu'il n'a pas affaire à un simple polariseur linéaire, il décide de faire plus de tests. Il se balade chez lui avec ses lunettes, quand tout à coup, il remarque qu'il voit des couleurs bizarres lorsqu'il regarde son écran. C'est reparti pour une série de tests !

<div class="experience">

<h1>Expérience #3 - Lunettes et écrans</h1>
<h2>Mise en place</h2>

Plusieurs tests sont effectués:
  - Lunettes en face de l'écran
	- Orientées à 0° et 90°
  - Lunettes dos à l'écran
    - Orientées à 0° et 90°
  - Test sur un autre écran
  
Les écrans utilisés sont:
  * Ecrans 

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

La lumière polarisée circulairement, c'est simplement un **déphasage** de une de ces ondes, c'est-à-dire qu'on "décale" un des composants.

![Déphasage](assets/img/polarisation-circulaire.png)

<div class="caption">Par exemple, ici, on remarque que les ondes bleues et vertes ne sont plus synchronisées (bas) mais sont maintenant décalées (haut) ce qui donne lieu à ce qu'on appelle la polarisation circulaire</div>

Et le plus intéressant, c'est qu'on fonction de ce déphasage, on peut obtenir de la lumière polarisée circulairement dans le sens des aiguilles d'une montre, et dans le sens inverse. Et on peut filtrer l'une des deux: c'est ainsi que marchent les lunettes polarisées circulairement.

![Lunettes polarisées circulairement](assets/img/polarisation-circulaire-lunettes.png)

<div class="caption"></div>





