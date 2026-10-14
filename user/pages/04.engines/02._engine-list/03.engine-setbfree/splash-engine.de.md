---
title: setBfree
id: setbfree
description: Hochgradig anpassbarer Hammond-B3- und Leslie-Emulator
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-add
  - ucase-kb
  - synth-emu
  - synth-phy
  homepage:
  - 'yes'
date: 17:38 10-03-2020
subtitle: Tonewheel Organ Emulator
splash:
  bg_image: setbfree-hero_small.jpg
  bg_image_landscape: setbfree-hero.jpg
media_thumb: setbfree.jpg
sitemap:
  lastmod: 07-05-2026 14:23
urls:
- urlLink: http://setbfree.org
  urlLabel: Project's Website
- urlLink: http://www.linuxsynths.com/SetBfreePatchesDemos/setbfree.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/pantherb/setBfree
  urlLabel: Source Code
video:
- videoType: vimeo
  videoLink: https://vimeo.com/130633814
  videoLabel: A rendition of Jimmy Smith's The Cat
audio:
- audioType: local
  audioFile: georgia_on_my_waltzin_mind.ogg
  audioLabel: Georgia on my waltzin mind, by TKC (MDA EPiano + setBfree)
- audioType: local
  audioFile: setBfreeDrawbarsManipulationByBaggypants.mp3
  audioLabel: Hammond Drawbars Manipulations, by Baggypants (setBfree)
- audioType: local
  audioFile: RhodesHammondByHumi.mp3
  audioLabel: Rhodes & Hammond, by Humi
---
setBfree ist ein MIDI-gesteuerter Software-Synthesizer, der den Klang und die Eigenschaften der elektromechanischen Orgeln und Klangbearbeitungsgeräte nachahmen soll, die den Namen und Produkten von Laurens Hammond und Don Leslie weltweiten Ruhm eingebracht haben..

## Funktionen:
setBfree ist ein *Tonewheel-Organ-Bausatz*, ein physikalisches Modell mit über 1000 konfigurierbaren Parametern. Wie bei einer echten B3 kann man sie 'öffnen' und Parameter vom Zustand mint'53 (Standard) bis hin zu heruntergekommenem dusty tube 80's anpassen.

Auf Zynthian bietet setBfree 7 vordefinierte Tastaturkonfigurationen, die Manuale und Pedale kombinieren.:
+ **Oberer:** 1 Keyboard (1 x MIDI-Kanal)
+ **Oben + Unten:** 2 Keyboards (2 x MIDI-Kanäle)
+ **Obermanual + Pedale:** 2 Keyboards (2 x MIDI-Kanäle)
+ **Oberes + Unteres + Pedale:** 3 Keyboards (3 x MIDI-Kanäle)
+ **Untere/obere Bereiche aufteilen:** 1 Keyboard (1 x MIDI-Kanal)
+ **Geteilte Pedale/Oberer:** 1 Tastatur (1 x MIDI-Kanal)
+ **Split-Pedale/Untere/Obere:** 1 Tastatur (1 x MIDI-Kanal)

Auf zynthian bietet setBfree außerdem 4 Wellenformtypen für den tone-wheel generator.:
+ **Sinus- 񟿿:** Hammond-Sound
+ **Quadrat:** Combo-Orgel-Sound
+ **Dreieck:** Combo-Orgel-Sound
+ **Sägezahn:** Combo-Orgel-Sound

Alle Bedienelemente können bei Bedarf über den MIDI-learn-Mechanismus einem MIDI-CC zugewiesen werden..

