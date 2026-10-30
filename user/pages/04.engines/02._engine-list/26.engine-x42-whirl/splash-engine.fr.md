---
title: X42 Whirl Speaker
media_order: x42-whirl.png
description: Rotary Speaker Simulator
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - effect
  - fx-mod
  - ucase-fx
date: 17:38 24-04-2020
subtitle: Collection de plugins
splash:
  bg_image_landscape: x42-whirl-hero.png
  bg_image: x42-whirl-hero_small.png
media_thumb: x42-whirl.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-whirl
  urlLabel: Whirl Speaker's Website
- urlLink: https://github.com/pantherb/setBfree
  urlLabel: Source Code
---
x42-whirl est conçu pour imiter le son et les caractéristiques du haut-parleur rotatif électromécanique qui a rendu célèbres dans le monde entier le nom et les produits de Don Leslie..

Il s’agit d’une version autonome de l’effet apparu avec le synthétiseur setBfree. Au lieu de simuler l’effet global du dispositif électromécanique, x42-whirl en modélise physiquement les propriétés, ce qui permet de reproduire très fidèlement le son du dispositif réel..

Comme toutes les pièces individuelles sont modélisées, x42-whirl offre non seulement un contrôle avancé, mais facilite également les personnalisations, dont certaines ne sont pas réalisables sur l'appareil mécanique.

#### Détails
Le flux du signal correspond à celui du matériel d’origine. Pour plus de commodité, il est représenté dans l’interface du plugin. Deux filtres sont utilisés pour séparer les basses et les aigus, qui sont envoyés aux haut-parleurs à pavillon et à tambour. Un EQ supplémentaire permet de personnaliser le son du haut-parleur haute fréquence..

Le cœur de l’effet est un haut-parleur à pavillon rotatif. Deux pavillons sont visibles, mais l’un d’eux (le sombre dans l’interface graphique) est factice et sert principalement à compenser la force centrifuge de l’autre pendant la rotation. Le plugin utilise une combinaison de décalage Doppler et de réponses impulsionnelles à décalage nul dépendant de l’angle pour un pavillon Model 600 (le pavillon Model 44W est identique à celui du Model 600 et est apparemment standard sur tous les modèles Leslie [1]). La mesure du pavillon a été réalisée par J.O. Smith III et al([2]). Le son du woofer est dominé par une modulation d’amplitude causée par la rotation du tambour à écope.

x42-whirl calcule six réflexions en fonction des angles du pavillon et du tambour, ainsi que de la distance et de la position des microphones, afin d’émuler la diffusion réverbérante correspondant aux dimensions et aux caractéristiques de diffusion de l’enceinte. De plus, le modèle tient compte d’artefacts tels que la fuite du signal provenant du tweeter, qui ne passe pas par le pavillon..

La commande moteur permet de définir deux vitesses cibles (lente/chorale et rapide/trémolo) pour chacun des rotors du pavillon et du tambour, en RPM, ainsi que les constantes de temps d’accélération et de décélération en secondes (pour atteindre la moitié de la vitesse). Bien que cela ne tienne pas compte du frottement, cela se rapproche d’un système d’origine correctement lubrifié..

Parfois, le pavillon ou le tambour est dirigé vers l’arrière du caisson lorsqu’il s’arrête, ce qui produit un son peu satisfaisant. Un paramètre facultatif supplémentaire permet de définir une position d’arrêt..

Pour plus de commodité, l’étage de sortie comprend deux mélangeurs matriciels stéréo qui permettent de réduire le champ stéréo et d’améliorer la compatibilité mono..

#### Remarque sur les paramètres
Par défaut, le plugin utilise des paramètres correspondant à un Model 44 (vitesses de rotation, rayon du tambour et du pavillon) et une technique caractéristique de prise de son avec micros gauche/droite à 180deg. Cependant, les différents aspects peuvent être personnalisés.

La position décentrée du pavillon est prise en compte dans le calcul des réflexions de l’enceinte, cependant les microphones sont positionnés symétriquement à égale distance du centre du rotor. L’augmentation des rayons accroît la modulation de fréquence Doppler, tandis que l’augmentation de la distance des microphones modifie subtilement le spectre en raison de la durée de propagation différente du signal pour chacune des positions de réflexion et du haut-parleur.

Toutes les distances sont mesurées à partir du centre de chaque rotor. Le plugin permet certaines configurations impossibles dans le monde réel (par exemple, déplacer le micro à l’intérieur de l’appareil en rotation). Ces cas n’influent que sur les calculs de distance et d’angle et ne correspondront pas à ce que vous pourriez entendre s’il était mécaniquement possible de les réaliser. Bien que l’objectif soit de modéliser l’appareil aussi fidèlement que possible, ces configurations sont conservées dans le plugin car elles peuvent produire des sons intéressants, et c’est finalement tout l’intérêt..
