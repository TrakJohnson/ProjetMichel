---
title: L'Anaglyphe
permalink: chap1.html
layout: default
---

<div class="title-box">Chapitre 1 - L'Anaglyphe</div>

  Après cette courte introduction, Michel décide de s'intéresser à ce qui lui paraît être la façon la plus simple de créer une illusion en 3D: l’anaglyphe. C’est une technique peu avancée mais toujours d’actualité, car c'est une solution facile à implémenter.

![Lunettes anaglyphes](assets/img/lunettes-anaglyphes.jpg)

<div class="caption">Lorsqu'on pense 3D, on pense souvent d'abord aux lunettes anaglyphes comme celles-ci</div>

  Les lunettes bleues et rouges, aussi appelées lunettes **anaglyphes**, sont simplement composées de deux filtres, de couleur cyan et rouge. Chacun des filtres va bloquer une certaine partie de l'image, pour ainsi pouvoir montrer une image différente à chaque oeil.
  
  L'image anaglyphe qui est projetée est constituée de _deux images superposées_ (appelées homologues) sur lesquelles on a appliqué un filtre, rouge pour l'une, bleu pour l'autre. On utilise ces couleurs car elles sont "opposées": si on les décompose en RVB (Rouge Vert Bleu), le rouge est composé de 100% R 0% V 0% B, tandis que le cyan est composé de 0% R 100% V 100% B. Ainsi, il est plus facile de les séparer. Ces images homologues ne sont pas identiques: en fait, elles sont prises de façon à ce que les deux caméras soient sur la même scène, mais positionnées à une distance équivalente à un écart pupillaire moyen (aux alentours de 6.3cm).
  
![Anaglyphe Fonctionnement](assets/img/anaglyphe-miseenplace.jpg)

<div class="caption">L'image affichée sur l'écran est décomposée par les lunettes anaglyphes (qui sont représentées par les deux filtres) et créént ainsi l'illusion de voir une image différente avec chaque oeil, et donc une scène en 3D, alors que l'image est pourtant en 2D.</div>

Puisqu’il peut, Michel essaye donc de reproduire cet effet. Ne sachant pas comment le faire digitalement, il utilise deux projecteurs, qui projette chacun un film légèrement différent, et sur lesquels il va positionner ses filtres bleus et rouges. Malgré un résultat initial impressionant, Michel se rend compte que certaines images se dédoublent, c'est-à-dire que le cerveau n'arrive pas à les assimiler en une seule image ! C'est en fait car un de ses projecteurs est inclinés, ce qui donne une image comme ça:

![Anaglyphe problème](assets/img/anaglyphe-decale.png)

<div class="caption">On remarque que l'image bleue et l'image rouge au premier plan sont non seulement décalées latéralement, mais aussi qu'elles ont une rotation différente - cela est bien sûr un effet non désiré et qui nuit au rendu de cette 3D anaglyphe</div>

Curieux, Michel décide de jouer avec ses projecteurs et de voir à quel point est-ce que le cerveau ne parvient plus à faire le lien entre ces deux images, c'est-à-dire quand est-ce qu'on ne voit plus une image 3D mais deux images superposées. Il invite quelques voisins pour avoir un échantillon de réponses varié.

<div class="experience">
<h1>Expérience #1 - Anaglyphe et rotations</h1>
<h2>Mise en place</h2>

Michel prépare plusieurs cas, où il incline un de ses projecteurs de 1°, 5° et 10°, puis fait la même chose avec l'autre.

<table>
  <tr>
    <td></td>
    <td>Inclinaison de l'image de gauche</td>
    <td>Inclinaison de l'image de droite</td>
  </tr>
  <tr>
    <td>Inclinaison de 1°</td>
    <td><img src="assets/img/3D_left1.png"></td>
    <td><img src="assets/img/3D_right1.png"></td>
  </tr>
  <tr>
    <td>Inclinaison de 5°</td>
    <td><img src="assets/img/3D_left5.png"></td>
    <td><img src="assets/img/3D_right5.png"></td>
  </tr>
  <tr>
    <td>Inclinaison de 10°</td>
    <td><img src="assets/img/3D_left10.png"></td>
    <td><img src="assets/img/3D_right10.png"></td>
  </tr>
</table>

Il est intéressant de noter que l'image de l'oeil gauche est à droite de l'image de l'oeil droit - cela paraît contre-intuitif, mais en fermant un oeil, puis l'autre, on se rend compte que c'est normal.

Après avoir montré ces images à ses voisins (avec des lunettes anaglyphes bien sûr) il leur demande de noter sur 10 la qualité de la 3D, et de prendre en compte notemment si ils voient des dédoublements. Voici ce qu'il obtient:

<h2>Résultats</h2>

<table>
  <tr>
    <td rowspan="2">Oeil directeur</td>
    <td colspan="3" style="text-align:center;">Rotation de l'image de droite (degrés)</td>
    <td colspan="3" style="text-align:center;">Rotation de l'image de gauche (degrés)</td>
  </tr>
  <tr>
    <td>1</td>
    <td>5</td>
    <td>10</td>
    <td>1</td>
    <td>5</td>
    <td>10</td>
  </tr>
  <tr>
    <td rowspan="8" style="text-align:center;">Notes des participants</td>
    <td>10</td>
    <td>7.5</td>
    <td>5</td>
    <td>10</td>
    <td>5</td>
    <td>2.5</td>
  </tr>
  <tr>
    <td>10</td>
    <td>8</td>
    <td>5</td>
    <td>10</td>
    <td>7</td>
    <td>2</td>
  </tr>
  <tr>
    <td>10</td>
    <td>8</td>
    <td>7</td>
    <td>10</td>
    <td>9</td>
    <td>6</td>
  </tr>
  <tr>
    <td>10</td>
    <td>8</td>
    <td>7</td>
    <td>10</td>
    <td>8</td>
    <td>6</td>
  </tr>
  <tr>
    <td>10</td>
    <td>8</td>
    <td>5</td>
    <td>9</td>
    <td>7</td>
    <td>3</td>
  </tr>
  <tr>
    <td>9</td>
    <td>7</td>
    <td>6</td>
    <td>9</td>
    <td>8</td>
    <td>8</td>
  </tr>
  <tr>
    <td>7</td>
    <td>7</td>
    <td>5</td>
    <td>8</td>
    <td>6.5</td>
    <td>5</td>
  </tr>
  <tr>
    <td>10</td>
    <td>10</td>
    <td>7</td>
    <td>10</td>
    <td>9</td>
    <td>6</td>
  </tr>
  <tr>
    <td>Moyennes</td>
    <td>9.5</td>
    <td>7.9</td>
    <td>5.9</td>
    <td>9.5</td>
    <td>7.4</td>
    <td>4.8</td>
  </tr>
</table>

<h2>Conclusion</h2>

  - On observe que les notes sont inversement proportionelles à l'angle, ce qui est attendu car plus le décalage est important, moins le cerveau comprend-il ce qu'il se passe
  - Cependant, Michel est surpris par deux choses:
	- Tout d'abord, certaines personnes ne semblent pas très dérangées par certains décalages, comme celui de 5°: cela montre la capacité du cerveau à "deviner" ce qu'il se passe, et de corriger lui-même le décalage. Beaucoup de ses voisins n'on pas noté de dédoublement particulier à 5°, mais seulement que cela causait des maux de têtes ou requièrait plus de concentration: cela est peut-être un indice montrant que le cerveau travaille pour corriger cela, tout comme il corrige l'image inversée qui est sur notre rétine
	- Ensuite, il y a une légère différence entre l'oeil gauche et l'oeil droit: l'impact sur la vision 3D est plus important lorsque l'image rouge est décalée, que quand l'image bleue l'est. Cela pourrait s'expliquer simplement parce que on distingue plus le rouge sur le fond blan que le cyan, mais cela reste à vérifier.
	
</div>

Cela fut intéressant, et la technique d'anaglyphe marche assez bien; cependant Michel se dit qu'il doit y avoir des moyens plus performants et faisant moins mal à la tête. 

<a href="{{ '/chap2' | prepend: site.baseurl | prepend: site.url }}">Sa quête continue ...</a>

