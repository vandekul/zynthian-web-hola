---
title: Dexed
id: dexed
image: dexed.jpg
description: Synthétiseur logiciel FM inspiré des synthétiseurs classiques Yamaha
  DX7 et TX7 des années 1980
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - ucase-kb
  - ucase-pr
  - synth-emu
  - synth-fm
  homepage:
  - 'yes'
date: 17:38 24-04-2020
subtitle: FM Synthesizer
splash:
  bg_image_landscape: dexed-hero.png
  bg_image: dexed-hero_small.png
media_thumb: dexed.jpg
sitemap:
  lastmod: 07-05-2026 14:15
urls:
- urlLink: https://asb2m10.github.io/dexed
  urlLabel: Project's Website
- urlLink: http://www.linuxsynths.com/DexedPatchesDemos/dexed.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/asb2m10/dexed
  urlLabel: Source Code
- urlLink: https://yamahablackboxes.com/collection/yamaha-dx7-synthesizer/
  urlLabel: Yamaha DX7 Info
audio:
- audioLink: https://soundcloud.com/starling-studios/mmoncur-hexed-osc74
  audioLabel: mmoncur - Hexed (OSC74)
  audioType: soundcloud
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=wSs1-020nNY
---
Dexed est un synthétiseur logiciel de type FM développé par Pascal Gauthier de Digital Suburban. C’est une application idéale pour importer, jouer et modifier/gérer des patches Sysex provenant des synthétiseurs classiques Yamaha DX7 et TX7..

Dexed comprend six opérateurs, fidèles à la structure DX. Chaque opérateur dispose d’un indicateur de niveau. Les opérateurs peuvent être organisés selon différents algorithmes, indiqués par les cases vertes. Les banques de patches sont appelées « cartouches » et il y en a beaucoup (environ 32) incluses dans le package d’installation. Sélectionner une cartouche charge les patches de la banque correspondante.

Dexed peut être configuré pour utiliser certaines des limitations mathématiques d’origine d’un synthétiseur DX. Cela ne s’applique pas uniquement au DAC, cela concerne également la résolution en bits des ondes sinusoïdales et la manière dont l’amplitude est appliquée à chaque opérateur. Comme tout cela est expérimental, plusieurs moteurs seront disponibles afin de pouvoir les comparer facilement..

Dexed est fourni avec 3 types de moteur:
+ **Moderne:** il s’agit de l’implémentation originale de music-synthesizer-for-android en 24 bits.
+ **Mark I:** Basé sur la série OPL, mais avec une résolution plus élevée (les LUT sont sur 10 bits). L’objectif de ce moteur est de se rapprocher au plus près du vrai DX7..
+ **Série OPL:** il s'agit d'une implémentation expérimentale des puces de la famille OPL rétroconçues. 8-bit. Gardez à l'esprit que les enveloppes nécessitent encore des ajustements..

## Fonctionnalités:
+ Multiplateforme (OS X, Windows ou Linux) et multiformat (VST, AU, LV2)
+ Le moteur sonore music-synthesizer-for-android est étroitement inspiré des caractéristiques du DX7 original
+ 144 paramètres DX7 automatisables dans la DAW, accessibles depuis un seul panneau
+ Prend entièrement en charge les messages sysex d’entrée et de sortie du DX7, y compris les changements de contrôleur. Cela signifie que vous pouvez l’utiliser avec un DX7/TX7 natif comme éditeur de patchs et gestionnaire sysex.
+ Chaque opérateur dispose d’un VU-mètre en temps réel pour savoir lequel est actif.
+ Peut charger/enregistrer n’importe quel programme sysex DX7/TX7. Il est également possible d’enregistrer un seul programme dans un fichier sysex différent..
