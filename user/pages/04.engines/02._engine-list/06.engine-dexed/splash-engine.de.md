---
title: Dexed
id: dexed
image: dexed.jpg
description: FM-Softsynth, inspiriert von den klassischen Yamaha-DX7- und TX7-Synthesizern
  der 1980er-Jahre
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
Dexed ist ein Softsynth vom FM-Typ, entwickelt von Pascal Gauthier von Digital Suburban. Es ist eine ideale Anwendung zum Importieren, Spielen und Bearbeiten/Verwalten von sysex-Patches sowohl des klassischen Yamaha DX7-Synthesizers als auch des TX7..

Dexed umfasst sechs Operatoren, getreu der DX-Struktur. Jeder Operator hat eine Pegelanzeige. Die Operatoren können in verschiedenen Algorithmen angeordnet werden, die durch die grünen Kästchen angezeigt werden. Patch-Bänke werden „cartridges“ genannt, und im Installationspaket sind viele (etwa 32) enthalten. Bei Auswahl einer cartridge werden die Patches in der entsprechenden Bank geladen..

Dexed kann so konfiguriert werden, dass einige der ursprünglichen mathematischen Einschränkungen eines DX-Synthesizers verwendet werden. Das betrifft nicht nur den DAC, sondern auch die Bit-Auflösung der Sinuswellen und die Art und Weise, wie die Amplitude auf jeden Operator angewendet wird. Da all dies experimentell ist, werden mehrere Engines verfügbar sein, damit sie einfach miteinander verglichen werden können..

Dexed wird mit 3 Engine-Typen geliefert:
+ **Modern:** dies ist die ursprüngliche Implementierung von music-synthesizer-for-android in 24 Bit.
+ **Mark I:** Basierend auf der OPL-Serie, jedoch mit höherer Auflösung (LUT sind 10-Bit). Ziel dieser Engine ist es, dem echten DX7 möglichst nahe zu kommen..
+ **OPL-Serie:** dies ist eine experimentelle Implementierung der reverse-engineerten Chips der OPL-Familie. 8-Bit. Beachte, dass die Hüllkurven noch abgestimmt werden müssen.

## Funktionen:
+ Plattformübergreifend (OS X, Windows oder Linux) und formatübergreifend (VST, AU, LV2)
+ Die Sound-Engine music-synthesizer-for-android orientiert sich eng an den Eigenschaften des ursprünglichen DX7.
+ 144 DAW-automatisierbare DX7-Parameter auf einem einzigen Bedienfeld verfügbar
+ Unterstützt vollständig DX7-Eingabe- und -Ausgabe-sysex-Nachrichten; einschließlich Controller-Änderungen. Das bedeutet, dass du dies mit einem nativen DX7/TX7 als Patch-Editor und sysex-Manager verwenden kannst
+ Jeder Operator verfügt über ein Echtzeit-VU-Meter, damit du weißt, welcher aktiv ist.
+ Kann beliebige DX7/TX7-Sysex-Programme laden/speichern. Es ist auch möglich, ein einzelnes Programm in einer anderen Sysex-Datei zu speichern..
