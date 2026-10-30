---
title: OBX-D
id: obxd
description: Synthétiseur logiciel inspiré de certains appareils classiques fabriqués
  par Oberheim dans les années 1980
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-kb
  - ucase-pr
  - synth-emu
  homepage:
  - 'yes'
date: 17:38 24-04-2020
subtitle: Oberheim Emulator
splash:
  bg_image: obxd-hero_small.png
  bg_image_landscape: obxd-hero.png
media_thumb: obxd.jpg
sitemap:
  lastmod: 07-05-2026 16:19
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=NdfcgiLsp88
audio:
- audioType: local
  audioFile: OBXdLoveByHumi.mp3
  audioLabel: Oberheim Love, by Humi
- audioType: local
  audioFile: chirpybellstwo.ogg
  audioLabel: Chirpy Bells 2
- audioType: local
  audioFile: lotshappenin.ogg
  audioLabel: Lots Happenin
- audioType: local
  audioFile: madderthan.ogg
  audioLabel: Madderthan
- audioType: local
  audioFile: saladdressing.ogg
  audioLabel: Salad Dressing
- audioType: local
  audioFile: withair.ogg
  audioLabel: Withair
urls:
- urlLink: http://www.linuxsynths.com/ObxdPatchesDemos/obxd.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/2DaT/Obxd
  urlLabel: Source Code
---
OBXD est un synthétiseur monophonique/polyphonique à 8 voix en temps réel développé par 2DaT, Layzer et Breeze (sur KVR) et récemment porté sous Linux. OBXD est disponible aux formats LV2 et VST, et peut fonctionner dans la plupart des hôtes, comme Ardour, Carla, Jalv et Qtractor..

OBXD inclut de nombreuses fonctionnalités du célèbre synthétiseur matériel OB-X des années 1980, ainsi que quelques modifications (voir les liens vers le manuel ci-dessous). Il dispose de deux oscillateurs avec des commandes de niveau discrètes et d’un bouton de niveau de bruit, de formes d’onde en dents de scie et carrées indépendantes avec commande de modulation de largeur d’impulsion ; d’un bouton de cross-modulation, d’un bouton Sync et d’un bouton Step (pour régler l’accordage de l’oscillateur par demi-tons plutôt que de manière continue). Un bouton du mode Unison (toutes les notes polyphoniques sont empilées en une seule voix monophonique plus épaisse), ainsi que les commandes Spread, Glide (portamento), accordage et transposition d’octave sont inclus. Le bouton « Bright » contrôle la précision du spectre sonore dans les hautes fréquences, et le bouton « P Env » fournit une enveloppe de hauteur, câblée directement à la section d’enveloppe du filtre..

## Fonctionnalités:
La section de filtre de l’OBXD comporte un filtre multimode à 12 dB. Outre les commandes traditionnelles de fréquence de coupure, de résonance et de profondeur de l’enveloppe, cette section permet de contrôler le suivi du clavier, l’interpolation de haute qualité (qui augmente légèrement la consommation CPU) et le contrôle multimode..

Le Knob « Multi » permet de passer entre les options de filtre suivantes : passe-bas (Knob à gauche), notch (position intermédiaire) et passe-haut (Knob à droite). L’activation du bouton « BP » fournit un filtre passe-bande à la place du notch (Knob en position intermédiaire). Le bouton « 24dB » fournit un filtre passe-bas de 24 dB qui varie de 24 dB (Knob à gauche) à 6 dB (Knob à droite).

Il y a un bouton VAM (voice allocation mode) qui donne la priorité à la dernière note au lieu de la priorité à la note la plus basse. La section de contrôle comprend une plage de bend de 12 demi-tons (2 notes lorsqu'elle est désactivée) et un bouton de bend uniquement pour l'oscillateur 2. Le Vibrato Rate est relié en dur à la molette de modulation, mais interagit également de manière intéressante avec le potentiomètre LFO rate. La section de contrôle dispose également d'un réglage de la sensibilité à la vélocité pour le filtre et l'amplitude..

La section LFO comprend des formes d’onde sinusoïdales, carrées et sample-and-hold, qui peuvent être mélangées. La section Voice Variation offre un contrôle supplémentaire du filtre, du glide et de l’amplitude, et Voice Pan permet de contrôler indépendamment la direction du panoramique de chacune des 8 voix..

