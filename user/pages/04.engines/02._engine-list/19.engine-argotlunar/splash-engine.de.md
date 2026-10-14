---
title: Argotlunar
media_order: argotlunar.png
description: Ein Echtzeit-Delay-Line-Granulator für surreale Transformationen
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
Argotlunar ist ein Tool zum Erzeugen surrealer Transformationen von Audiostreams. Genauer gesagt handelt es sich um einen Echtzeit-Delay-Line-Granulator. Er zerlegt einen Audiostream in kurze Samples (Grains). Für jedes Grain können Amplitude, Panning, Dauer, Delay, Pitch, Glissando, Filter und Hüllkurve zufällig eingestellt werden. Die Ausgabe aller Grains wird zu einem Stream zusammengemischt, der in den Haupteingang zurückgeführt werden kann..

Zeitbezogene Parameter können mit dem Host-Tempo synchronisiert werden, um rhythmische und pulsierende Texturen zu erzeugen. Tonhöhenbezogene Parameter können für harmonische und melodische Effekte quantisiert werden. Feedback kann chaotische, dicht geschichtete und verzerrte Klänge erzeugen..

Die meisten Parameter können zugeordnet werden. Beispiele:

+ Filter-Cutoff mit der Tonhöhe korreliert: Höherer Filter-Cutoff für Grains mit höherer Tonhöhe und umgekehrt.
+ Grain-Dauer korreliert mit Panning: Grains mit kürzerer Dauer im Zentrum des Stereofelds platziert und Grains mit längerer Dauer breit im Stereofeld verteilt.

Argotlunar ist freie Software. Lizenziert unter der GPL v2.

#### Details:

+ Zeitbezogene Parameter können mit dem Host-Tempo synchronisiert werden.
+ Pitch-bezogene Parameter können auf verschiedene Akkorde/Skalen quantisiert werden.
+ Bis zu drei Parameterpaare können miteinander korreliert werden..
+ Raised-cosine-bell-, parabolische und dreieckige Grain-Hüllkurven mit einstellbarer Form.
+ Die Transposition wird spline-interpoliert, um Aliasing zu reduzieren..
+ 12dB zustandsvariabler Filter (HP/BP/LP/Notch).
+ Comb filter.
