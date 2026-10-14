---
title: Surge
media_order: surge.png
description: Surge ist ein digitaler Synthesizer und macht keinen Hehl daraus. In
  seinem Kern schlägt eine hybride subtraktive Engine mit einem leistungsstarken FX-Stack.
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-kb
  - ucase-pr
  homepage:
  - 'yes'
date: 17:38 20-10-2020
subtitle: Hybrid Synthesizer
splash:
  bg_image_landscape: surge-hero.png
  bg_image: surge-hero_small.png
media_thumb: surge.png
audio:
- audioType: soundcloud
  audioLink: https://soundcloud.com/user-589036812-258992427/surge-2237-ad
  audioLabel: 2237 AD
- audioType: soundcloud
  audioLink: https://soundcloud.com/user-589036812-258992427/surge-demo-001-microtonal-soundscape-1-x-surge
  audioLabel: Microtonal Soundscape
- audioType: soundcloud
  audioLink: https://soundcloud.com/theexponent/resurgence
  audioLabel: Resurgence
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=2GLp6FD6oVE
urls:
- urlLink: https://surge-synthesizer.github.io/
  urlLabel: Surge's Website
- urlLink: https://surge-synthesizer.github.io/manual/
  urlLabel: Surge's Manual
- urlLink: https://github.com/surge-synthesizer/surge
  urlLabel: Source Code
---
Surge verwendet einen subtraktiven hybriden Synthesealgorithmus. Jeder Patch enthält zwei 'Szenen', bei denen es sich um separate Instanzen der gesamten Synthese-Engine (mit Ausnahme der Effekte) handelt, die für Layering oder Split-Patches verwendet werden können..

Es enthält eine umfangreiche Bibliothek mit Factory-Sounds.:

+ 1725 Patches
+ 523 wavetables

##Funktionen
**Oscillators:**
+ 3 Oszillatoren pro Szene.
+ 8 vielseitige Oszillator-Algorithmen: Classic, Sine, Wavetable, Window, FM2, FM3, S&H Noise und Audio Input.
+ Der klassische Oszillator ist ein morphbarer Puls-/Sägezahn-/Dual-Sägezahn-Oszillator mit einem Sub-Oszillator und Hard Sync.
+ FM2/FM3-Oszillatoren bestehen aus einem Träger und 2 oder 3 Modulatoren sowie verschiedenen Optionen.
+ Die meisten Algorithmen (außer FM2, FM3 und Audio input) bieten Unisono mit bis zu 16 Stimmen auf Oszillatorebene an..
+ Oszillator-FM und Ringmodulation zwischen Oszillatoren 1-2 und 2-3.
+ Die meisten Oszillator-Algorithmen (außer FM2, FM3 und Sine) sind strikt band-limited, decken aber dennoch das gesamte hörbare Spektrum ab und liefern einen klaren, druckvollen und dennoch sauberen Klang..
+ Rauschgenerator mit variablem Spektrum.

**Filter-Block:**
+ Zwei Filtereinheiten in 8 verschiedenen Konfigurationen.
+ Rückkopplungsschleife in 7 dieser Konfigurationen verfügbar.
+ Verfügbare Filteralgorithmen: Lowpass (12 und 24 dB/oct, jeweils mit 3 Variationen), Lowpass 24 dB/oct (3 Variationen), Ladder Lowpass (6-24 dB/oct), Highpass (12 und 24 dB/oct, jeweils mit 3 Variationen), Bandpass (12 und 24 dB/oct, jeweils mit 3 Variationen), Notch (12 und 24 dB/oct, jeweils mit 2 Variationen), Comb (4 Variationen), S&H.
+ Filter können sich selbst oszillieren (mit Anregung) und reagieren erstaunlich schnell auf Änderungen der Cutoff-Frequenz.
+ Waveshaper (5 Formen).

**Modulation:**
+ 12 LFO-Einheiten verfügbar, 6 davon pro Stimme und 6 global für die gesamte Szene.
+ DAHDSR-Hüllkurvengeneratoren auf jedem LFO.
+ 7 verformbare LFO-Wellenformen und Step-Sequencer-Modus.
+ Voice-LFOs ermöglichen ein erneutes Triggern der Hüllkurve, wenn sie als Step-Sequencer verwendet werden..
+ Extrem schnelles und flexibles Modulations-Routing. Fast jeder kontinuierliche Parameter kann moduliert werden.!

**Effekte:**
+ 8 Effekteinheiten, angeordnet als 2 Inserts pro Szene, 2 Sends und 2 Master-Effekte.
+ 13 Effektalgorithmen: EQ, Distortion, Conditioner (EQ, Stereobildkontrolle und Limiter), Frequency Shifter, Rotary Speaker, Ring Modulator, Vocoder, Chorus, Phaser, Flanger, Delay, Reverb 1, Reverb 2
