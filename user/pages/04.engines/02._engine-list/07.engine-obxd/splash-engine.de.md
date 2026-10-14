---
title: OBX-D
id: obxd
description: Von klassischen Oberheim-Geräten der 80er inspirierter Soft-Synth
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
OBXD ist ein monophoner/8-stimmig polyphoner Echtzeit-Synthesizer, entwickelt von 2DaT, Layzer und Breeze (bei KVR) und kürzlich auf Linux portiert. OBXD ist in den Formaten LV2 und VST verfügbar und kann in den meisten Hosts wie Ardour, Carla, Jalv und Qtractor ausgeführt werden..

OBXD umfasst viele Funktionen des berühmten OB-X-Hardwaresynthesizers aus den 1980er-Jahren sowie einige Modifikationen (siehe Links zum Handbuch unten). Es gibt zwei Oszillatoren mit diskreten Pegelreglern und einem Noise-Pegel-Knob, unabhängigen Sägezahn- und Rechteckwellenformen mit Pulsbreitenmodulation; einen Cross-Modulation-Knob, einen Sync-Button und einen Step-Button (um die Oszillatorstimmung in Halbtönen statt stufenlos anzupassen). Eine Unison-Mode-Taste (alle polyphonen Noten werden zu einer volleren monophonen Stimme gestapelt), Spread, Glide (Portamento), Tuning und Oktavtransponierung sind ebenfalls enthalten. Der „Bright“-Knob steuert die Präzision höherer Klangspektren, und der „P Env“-Knob bietet eine Pitch-Envelope, die fest mit dem Filter-Envelope-Bereich verdrahtet ist..

## Funktionen:
Die OBXD-Filtersektion verfügt über ein 12-dB-Multi-Mode-Filter. Neben den traditionellen Cutoff-, Resonance- und Envelope-Depth-Reglern ermöglicht diese Sektion die Steuerung von Key Follow, hochwertiger Interpolation (erhöht leicht den CPU-Verbrauch) und Multi-Mode-Steuerung.

Der "Multi"-Knob ermöglicht den Übergang zwischen den folgenden Filteroptionen: low-pass (Knob nach links), notch (mittlere Position) und high-pass (Knob nach rechts). Durch Aktivieren der "BP"-Taste wird anstelle von notch ein bandpass-Filter verwendet (Knob in mittlerer Position). Die "24dB"-Taste bietet einen 24-dB-lowpass-Filter, der sich von 24dB (Knob nach links) bis 6dB (Knob nach rechts einstellen lässt.).

Es gibt eine VAM-Taste (Voice Allocation Mode), die der zuletzt gespielten Note Vorrang gibt statt der tiefsten Note. Die Bediensektion umfasst einen Pitchbend-Bereich von 12 Halbtönen (2 Noten, wenn ausgeschaltet) und eine Taste, mit der nur Oszillator 2 auf Pitchbend reagiert. Die Vibrato-Rate ist fest mit dem Modwheel verdrahtet, interagiert aber auch auf interessante Weise mit dem LFO-Rate-Knob. Die Bediensektion bietet außerdem eine Steuerung für die Velocity-Empfindlichkeit von Filter und Amplitude..

Der LFO-Bereich umfasst Sinus-, Rechteck- und Sample-and-hold-Wellenformen, die miteinander gemischt werden können. Der Voice Variation-Bereich bietet weitere Kontrolle über Filter, Glide und Amplitude, und mit Voice Pan lässt sich die Pan-Richtung jeder der 8 Stimmen unabhängig steuern..

