---
title: Argotlunar
media_order: argotlunar.png
description: Un granulateur à ligne de retard en temps réel pour créer des transformations
  surréalistes
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - fx-delay
  - fx-mod
  - fx-other
  - ucase-fx
  homepage:
  - 'yes'
date: 17:38 24-04-2020
subtitle: Granulator
splash:
  bg_image_landscape: argotlunar-hero.png
  bg_image: argotlunar-hero_small.png
media_thumb: argotlunar.png
audio:
- audioType: soundcloud
  audioLink: https://soundcloud.com/t800infiltrator/argotlunar
  audioLabel: Argotlunar, by t800infiltrator
- audioType: soundcloud
  audioLink: https://soundcloud.com/ioflow/20110912a
  audioLabel: 20110912, by ioflow
- audioType: soundcloud
  audioLink: https://soundcloud.com/pneuman/rpm-2012-lagrange
  audioLabel: 'RPM 2012: lagrange, by pneuman'
urls:
- urlLink: http://mourednik.github.io/argotlunar/)
  urlLabel: Argotlunar's Website
- urlLink: https://www.kvraudio.com/product/argotlunar-by-michael-ourednik
  urlLabel: KVRAudio's Page
- urlLink: https://github.com/mourednik/argotlunar
  urlLabel: Source Code
---
Argotlunar est un outil permettant de créer des transformations surréalistes de flux audio. Plus précisément, il s'agit d'un granulateur à ligne de Delay en temps réel. Il désintègre un flux audio en courts échantillons (grains). Chaque grain peut avoir des réglages aléatoires d'amplitude, de panoramique, de durée, de Delay, de hauteur, de glissando, de filtre et d'enveloppe. La sortie de tous les grains est mélangée en un flux qui peut être réinjecté dans l'entrée principale.

Les paramètres liés au temps peuvent être synchronisés au tempo de l’hôte, pour des textures rythmiques et pulsées. Les paramètres liés au Pitch peuvent être quantifiés pour des effets harmoniques et mélodiques. Le Feedback peut créer des sons chaotiques, densément superposés et distordus..

La plupart des paramètres peuvent être mis en corrélation. Exemples:

+ Fréquence de coupure du filtre corrélée à la hauteur : fréquence de coupure plus élevée pour les grains de hauteur plus élevée, et vice versa.
+ Durée des grains corrélée au panoramique : les grains de plus courte durée sont placés au centre du champ stéréo, et ceux de plus longue durée sont largement répartis dans le champ stéréo..

Argotlunar est un logiciel libre. Sous licence GPL v2.

#### Détails:

+ Les paramètres liés au temps peuvent être synchronisés au tempo de l’hôte..
+ Les paramètres liés à la hauteur peuvent être quantifiés sur différents accords/gammes.
+ Jusqu'à trois paires de paramètres peuvent être corrélées..
+ Enveloppes de grain en cosinus surélevé, paraboliques et triangulaires, avec forme réglable.
+ La transposition est interpolée par spline afin de réduire l’aliasing..
+ filtre à variable d’état 12dB (HP/BP/LP/Notch).
+ Comb filter.
