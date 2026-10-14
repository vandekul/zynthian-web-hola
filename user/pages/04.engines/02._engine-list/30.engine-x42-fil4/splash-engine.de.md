---
title: X42 Equalizer
media_order: x42-fil4.png
description: 4 band parametric equalizer
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - fx-filter
content:
  items: '@self.modular'
date: 17:38 24-04-2020
subtitle: 4 band Parametric Equalizer
splash:
  bg_image_landscape: x42-fil4-hero_small.png
  bg_image: x42-fil4-hero_small.png
media_thumb: x42-fil4.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-eq
  urlLabel: X42 Equalizer's Website
- urlLink: https://github.com/x42/fil4.lv2
  urlLabel: Source Code
---
x42-eq (auch bekannt als fil4.lv2) ist ein parametrischer 4-Band-Equalizer mit zusätzlichen Low- und High-Shelving- sowie Hoch- und Tiefpassfiltern. Der Equalizer ist so ausgelegt, dass er eine äquivalente analoge Gain-Kurve mit zero Latency und ohne Phase-Shift bei Annäherung an die Nyquist-Frequenz erreicht. Er hat keinen beengten Frequenzgang, der oft als digitaler Klang bezeichnet wird. x42-eq verfügt über integrierte Echtzeit-Spektrum- und Spektrogramm-Anzeigen (Waterfall), eine vom Benutzer zurücksetzbare Peak-Hold-Anzeige und eine Ausgangs-Gain-Regelung.

fil4.lv2 basiert auf Fons Adriaensens LADSPA fil-plugins.

#### Spektrum-Steuerungen
Die Steuerelemente des Spektrogramms befinden sich unten rechts.,

**Aus:** Das Spektrum nicht anzeigen<br>
**Spezifikation:** Ein rosa Rauschen (1/Oktave)-gewichtetes Spektrum anzeigen.<br>
**Gesch.:** Spektrogrammanzeige; Verlaufsansicht (weiße gestrichelte Linien zeigen Änderungen der Einstellungen)<br>
**Vorherige:** Analysiere die Eingabe<br>
**Beitrag:** Analysiere den verarbeiteten Output<br>

Die Stereo-Variante bietet die Möglichkeit, nur die Summe (All), den linken oder den rechten Kanal zu analysieren. Der Gain Knob ermöglicht es, das Spektrum auszurichten; siehe die Skala auf der rechten Seite des Displays..

**Hoch:** Hochfrequenz-Warping, erhöhte Auflösung in den tiefen Frequenzen.<br>
**Med:** Verzerrung mittlerer Frequenzen<br>
**Bark:** Kein Frequency Warping, hohe Frequenzen betonen<br>

**Rpd:** Schneller Abfall (~~20ms)<br>
**Schnell:** Schnelles Abklingen (~~80ms)<br>
**Mod:** Moderate Abklingzeit (~~200ms)<br>
**Langsam:** Langsames Abklingen (~~2 Sek.)<br>
**Ns.:** Rauschmessung (~20 Sek)<br>

#### Filter-Spezifikationen
Fil4 besteht aus vier resonanten Filtern 2. Ordnung, die ein Lattice-Filter im Stil von Regalia-Mitra verwenden, das den schönen Vorteil hat, auch bei Parameteränderungen stabil zu bleiben..

Die High-/Low-Shelf-Filter sind standardmäßige Biquad-/IIR-Filter 2. Ordnung..

Hoch- und Tiefpass sind resonante Filter 2. Ordnung (-12 dB/Oktave):

+ Qualität 0.0: -6dB bei cutoff-freq (kein Feedback)
+ Qualität 0.7: -3dB bei cutoff-freq
+ Qualität 1.0: 0dB bei cutoff (resonant)

Alle Filter haben null Latency bei korrektem äquivalentem analogem Gain bei Nyquist (Signal-Phasenverschiebung bei der Nyquist-Frequenz ist null).

