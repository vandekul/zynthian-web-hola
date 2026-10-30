---
title: Arpeggiator
media_order: arpeggiator.jpg
description: Un arpégiateur MIDI simple et un plugin de motifs MIDI
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - effect
  - fx-midi
date: 17:38 24-04-2020
subtitle: Un plugin simple d’arpégiateur et de motifs MIDI
splash:
  bg_image_landscape: arpeggiator-hero.jpg
  bg_image: arpeggiator-hero_small.jpg
media_thumb: arpeggiator.jpg
urls:
- urlLink: https://github.com/BramGiesen/arpeggiator_LV2
  urlLabel: Source Code
---
Arpeggiator et un plugin de séquence MIDI développé pour la plateforme MOD par Bram Giesen.

####Arpeggiator
L’arpégiateur dispose des options suivantes:

**Options de tempo:**
Il existe également plusieurs options pour définir le tempo du plugin. La première est le mode Free Running. Dans ce mode, le tempo est contrôlé par la commande BPM du plugin. Au-dessus de la commande BPM se trouve une commande Divisions. Le plugin peut également être synchronisé avec l’hôte.

**Modes de l’arpégiateur:**
L’arpégiateur dispose des modes suivants:
+ Haut
+ Bas
+ Haut-Bas
+ Haut-Bas(alternative)
+ Joué
+ Aléatoire

**Modes d’octave:**
L’arpeggiator dispose d’un contrôle de plage d’octaves. L’arpeggiator peut faire défiler les notes entrantes sur plusieurs octaves. Ce contrôle définit la plage d’octaves parcourue au-dessus de la hauteur d’origine. La manière dont ces octaves sont ajoutées aux notes d’origine est déterminée par le contrôle du mode d’octave..

####MIDI-motif
Le plugin de motif MIDI peut être utilisé pour créer des motifs rythmiques. Le plugin prend la note entrante et remplace la velocity de la note par une valeur définie par l’un des Faders du plugin. Comme le plugin parcourt les Faders, il génère une sorte de séquence rythmique. Le contrôle CV du plugin peut être utilisé pour redéclencher la séquence..
