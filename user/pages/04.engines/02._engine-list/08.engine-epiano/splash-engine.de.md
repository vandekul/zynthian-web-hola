---
title: MDA ePiano
id: mda-epiano
description: Ein einfaches, aber gutes virtuelles E-Piano auf Basis von Fender-Rhodes-Samples
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - ucase-kb
  - synth-sample
  - synth-emu
  homepage:
  - 'yes'
date: 17:38 24-04-2020
subtitle: Elektropiano-Emulator
splash:
  bg_image_landscape: rhodes-hero.jpg
  bg_image: rhodes-hero_small.jpg
media_thumb: rhodes.jpg
sitemap:
  lastmod: 07-05-2026 16:22
audio:
- audioType: local
  audioFile: georgia_on_my_waltzin_mind.ogg
  audioLabel: Georgia on my waltzin mind, by TKC (MDA EPiano + setBfree)
- audioType: local
  audioFile: night_track.ogg
  audioLabel: Night Track, by TKC (MDA EPiano + ZASFX + SooperLooper)
- audioType: local
  audioFile: DemoEPianoByBaggyPants.ogg
  audioLabel: Demo MDA-ePiano, by Baggypants
urls:
- urlLink: https://gitlab.com/drobilla/mda-lv2
  urlLabel: MDA-LV2 Source Code
---
MDA ePiano ist ein einfaches, aber gutes virtuelles Electric Piano. Es emuliert den warmen Klang eines Fender Rhodes ziemlich gut und verbraucht dabei nur sehr wenige Ressourcen. Es hat nur wenige Optionen, aber das ist alles, was du brauchst. Einfachheit ist schön..

Im 20. Jahrhundert gehörten Plugins von Maxim Digital Audio (MDA, alias Paul Kellett) zu den ersten VST-Plugins, die für Windows verfügbar waren. Sie erlangten den Ruf, hohe Qualität bei geringer CPU-Auslastung zu bieten. Vor einigen Jahren wurde der Quellcode dieser Plugins veröffentlicht (GPL-/MIT-Lizenz, danke Paul!) und David Robillard portierte die MDA-Plugins ins LV2-Format. Die meisten MDA-Plugins sind Audioeffekte, aber es gibt auch vier virtuelle Instrumente: DX10, JX10, Piano und das bemerkenswerte **ePiano**. 

## Funktionen:
+ Basierend auf 12 sorgfältig gesampelten und gemasterten Rhodes-Piano-Samples.
+ 32-stimmige Polyphonie
+ Individuelle Breitensteuerung
+ Decay, release
+ Stereo-Breite
+ Velocity-Empfindlichkeit
+ Anpassbare Dämpfungs- und Härtestärke
+ Sanfter Dämpfungsfilter
