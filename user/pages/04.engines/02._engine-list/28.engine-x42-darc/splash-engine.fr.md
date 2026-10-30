---
title: X42 Compressor
media_order: x42-darc.png
description: Compresseur audio de plage dynamique polyvalent
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - ucase-fx
  - fx-dynamics
content:
  items: '@self.modular'
date: 17:38 24-04-2020
subtitle: Compresseur de dynamique audio polyvalent
splash:
  bg_image_landscape: x42-darc-hero_small.png
  bg_image: x42-darc-hero_small.png
media_thumb: x42-darc.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-compressor
  urlLabel: X42 Compressor's Website
- urlLink: https://github.com/x42/darc.lv2
  urlLabel: Source Code
---
x42-compressor (alias darc.lv2) est un compresseur de plage dynamique audio inspiré du zita-dc1 d’Adriaensen. C’est un compresseur descendant au son très agréable, qui privilégie la simplicité d’utilisation et ne propose qu’un ensemble minimal de commandes. La compression réagit à la puissance du signal (RMS), à l’intensité sonore telle qu’elle est perçue par l’oreille humaine, et non aux crêtes numériques liées au support..

Le compresseur dispose d’un auto makeup-gain, fixé à -10 dBFS/RMS. Cela maintient le volume perçu sur une large plage de réglages de threshold et de ratio..

Une fonction distincte «Hold» modifie le temps de relâchement, qui ne s’applique que tant que le signal dépasse le seuil. En d’autres termes : lorsque «Hold» est activé, le gain actuel (ou l’atténuation) est figé lorsque le signal passe sous le seuil..
Cela empêche le compresseur d’ajouter un gain excessif (par exemple, de moduler le noise-floor) et peut contrer le « pumping » excessif lors de l’utilisation de temps de release courts..

Le plug-in est disponible en version mono et stéréo. Dans le cas de cette dernière, les deux entrées sont additionnées et la puissance du signal est moyennée afin de déterminer le facteur de Gain..

darc.lv2 s'inspire de l'algorithme et de l'interface de zita-dc1 de Fons Adriaensen.

#### Paramètres
**Gain d’entrée:** Gain appliqué avant la détection du niveau ou tout autre traitement. Notez que cela n’est pas représenté comme un décalage sur l’axe x dans l’affichage de la courbe. La plage va de -10 à +30dB par pas de 1dB (gain fin de 0.2dBav 无码).

**Seuil:** Niveau du signal (RMS) auquel l'effet de compression est activé. La plage est de -50 à -10dB par pas de 0,5dB (0,1dB à réglage fin).

**Ratio:** La quantité de gain ou d’atténuation à appliquer (dB/dB au-dessus du seuil). L’unité est conservée à -10dBFS/RMS (auto makeup-gain).

**Temps d’attaque:** Temps nécessaire pour que le signal soit entièrement compressé après avoir dépassé le seuil.

**Temps de relâchement:** Temps minimum de retour au niveau de signal non compressé après être passé sous le seuil.

**Maintenir (case à cocher):** Conserver l'atténuation actuelle lorsque le signal passe sous le seuil. Cela empêche la modulation du noise-floor et peut contrer le 'pumping'.

#### Afficher
L’indicateur horizontal en bas affiche le Gain appliqué au signal. L’affichage indique la plage min/max sur les 50 dernières ms. Les valeurs à gauche &lt; 0 signifient que le signal est atténué (l’entrée est plus forte que -10 dBFS/RMS).

Le graphique en haut visualise le mappage du gain d’entrée vers le gain de sortie en dB. Lorsque « Hold » est activé, la zone où le Gain n’est pas relâché est ombrée en bleu. L’affichage montre également le niveau du signal d’entrée sous forme de zone blanche ombrée sous la courbe, ainsi que le niveau de sortie actuel (moyenne sur 50 ms) sous forme de point..
