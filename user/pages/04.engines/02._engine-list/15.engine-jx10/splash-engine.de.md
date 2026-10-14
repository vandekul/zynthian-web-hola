---
title: MDA JX-10
id: mda-jx10
description: Subtraktiver Softsynth nach Vorbild einiger Roland-Geräte der 1980er-
  Jahre
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-kb
  - synth-emu
date: 17:38 24-04-2020
subtitle: JX-8p/JX-10 Emulator
splash:
  bg_image_landscape: djx10-hero.jpg
  bg_image: djx10-hero_small.jpg
media_thumb: djx10.jpg
urls:
- urlLink: http://mda.smartelectronix.com
  urlLabel: MDA's Website
- urlLink: https://github.com/moddevices/mda-lv2
  urlLabel: MDA-LV2 Source Code
audio:
- audioType: local
  audioFile: fifthsweeppad.ogg
  audioLabel: Fifth Sweep Pad
- audioType: local
  audioFile: hardlead.ogg
  audioLabel: Hard Lead
- audioType: local
  audioFile: solidbacking.ogg
  audioLabel: Solid Backing
- audioType: local
  audioFile: detunedsynbrass.ogg
  audioLabel: Detuned Syn-Brass
- audioType: local
  audioFile: sawbass.ogg
  audioLabel: Saw Bass
- audioType: local
  audioFile: touchyfellow.ogg
  audioLabel: Touchy Fellow
- audioType: local
  audioFile: helicopter.ogg
  audioLabel: Helicopter
- audioType: local
  audioFile: wobblebass.ogg
  audioLabel: Wobble Bass
- audioType: local
  audioFile: filterdemo.ogg
  audioLabel: Filter Demo
---
MDA JX-10 ist ein subtraktiver Soft-Synth, inspiriert von einigen Roland-Geräten aus den 80ern. Er verbraucht sehr wenige Ressourcen und die Klangqualität ist großartig..

Es bietet zwei Oszillatoren (Sägezahn und Pulsbreite), die einzeln verwendet oder gemischt werden können. Die Polyphonie wird über die Glide-Steuerung eingestellt: null für polyphon, Maximum für monophone Steuerung. Standard-ADSR-Hüllkurven sind für Timbre (Filter) und Amplitude vorhanden. Pitchbend ist auf einen Ganzton eingestellt. Die LFO-Tiefe ist fest mit dem Modulationsrad verdrahtet. Ich habe eine Demo hinzugefügt, um eine Vorstellung vom sehr satten LP-Filter zu vermitteln (letzte Demo oben).

Zurück im 20. Jahrhundert gehörten die Plugins von Maxim Digital Audio (mda) zu den ersten für Windows verfügbaren VST-Plugins. Sie sind für ihre hohe Qualität bei geringer CPU-Auslastung bekannt. Vor einigen Jahren wurde der Quellcode dieser Plugins veröffentlicht, und David Robillard portierte die mda-Plugins ins LV2-Format. Die meisten mda-Plugins sind Effekte, aber es gibt auch vier Instrumente: DX10, JX10, Piano und ePiano.

## Funktionen:
+ 2 feste Oszillatoren (Mix zwischen 100:0 und 50:50 wählbar) & Rauschen
+ Oscillator-Stimmung +-24 Halbtöne
+ Resonanzfilter (Steuerbar durch Env/LFO/Velocity)
+ ADSR für VCF & Amp/Env
+ Glide - 6 Modi (Poly, P-Legato, P-Glide, Mono, M-Legato, M-Glide)
+ LFO
+ Vibrato
+ Synth-Stimmung +-2 Oktaven
+ Geringe CPU-Auslastung
+ Standardbank mit 52 Patches
+ Keine GUI
