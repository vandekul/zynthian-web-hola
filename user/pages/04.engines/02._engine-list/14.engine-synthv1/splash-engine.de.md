---
title: SynthV1
id: synthv1
description: Klassischer subtraktiver 4-Oszillator-Polysynthesizer mit Stereo-FX
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-pr
date: 17:38 24-04-2020
subtitle: Virtual Analog Synthesizer
splash:
  bg_image_landscape: synthv1-hero.png
  bg_image: synthv1-hero_small.png
media_thumb: synthv1.png
audio:
- audioType: local
  audioFile: woodpecker.ogg
  audioLabel: Woodpecker
- audioType: local
  audioFile: undeniable.ogg
  audioLabel: Undeniable
- audioType: local
  audioFile: noizeexportdemo.ogg
  audioLabel: Noize Export Demo
- audioType: local
  audioFile: saturnone.ogg
  audioLabel: Saturn One
- audioType: local
  audioFile: spaceorgan.ogg
  audioLabel: Space Organ
- audioType: local
  audioFile: clavone.ogg
  audioLabel: Clav One
- audioType: local
  audioFile: bubbler.ogg
  audioLabel: Bubbler
- audioType: local
  audioFile: isitterrific.ogg
  audioLabel: Is it terrific?
- audioType: local
  audioFile: phasedout.ogg
  audioLabel: Phased Out
- audioType: local
  audioFile: solohornone.ogg
  audioLabel: Solo Horn One
- audioType: local
  audioFile: synthkeysfour.ogg
  audioLabel: Synth Keys Four
- audioType: local
  audioFile: eightmm.ogg
  audioLabel: Eight MM
- audioType: local
  audioFile: solohornthree.ogg
  audioLabel: Solohornthree
urls:
- urlLink: https://synthv1.sourceforge.io
  urlLabel: Project's Website
- urlLink: http://www.linuxsynths.com/Synthv1PatchesDemos/synthv1.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/rncbc/synthv1
  urlLabel: Source Code
---
SynthV1 ist ein altmodischer, vollständig digitaler subtraktiver polyphoner 4-Oszillator-Synthesizer mit Stereo-FX. Er wurde von Rui Nuno Capela entworfen und entwickelt und ist Teil der Vee One Suite (zu der Padthv1, Samplv1 und Drumkv1 gehören). Er kann als eigenständiger Synth oder als LV2-Plugin innerhalb eines DAW-Setups wie Ardour oder QTractor laufen. Er kann in einer Jack- oder Non Session Management (NSM)-Sitzung laufen und unterstützt Jack Midi und Alsa Midi..

## Funktionen:
Synthv1 bietet sowohl polyphone (32 Noten) als auch monophone Spielbarkeit sowie Regler für Velocity- und Aftertouch-Empfindlichkeit. Das Layout besteht aus zwei identischen Seiten mit den Bezeichnungen Synth 1 und Synth 2 sowie einer dritten (Effekt-)Seite. Beide Synth-Seiten umfassen einen DCO-Bereich, einen Filter-Bereich, einen Amplituden-Bereich, einen LFO-Bereich, einen Controller-Bereich und einen allgemeinen Output-Bereich. Der Output-Bereich steuert den Audio-Pegel im Verhältnis zum Output des anderen Synths sowie den Anteil des Effektsignals.

Der Oszillatorbereich jeder Seite umfasst zwei Wellenform-Wahlschalter mit den klassischen Wellenformen und ihren bandbegrenzten Gegenstücken: Puls-zu-Rechteck, Dreieck-zu-Sägezahn, Sinus, Zufall und Rauschen. Eine Einstellung von null (bei Auswahl von Puls) deaktiviert den Oszillator. Eine Sync-Funktion ist ebenfalls enthalten. Die Width-Knobs modulieren sowohl die Wellenformen als auch die Zufalls- und Rauschsignale..

Verstimmung um plus und minus vier Oktaven sowie Feinverstimmung. Portamento (glide) und eine globale Anpassung der ADSR-Hüllkurvengeschwindigkeit befinden sich im oberen rechten Bereich der GUI..

Der Filterbereich bietet 12-dB- (Zustandsvariablen-), 24-dB- (Stilson/Smith Moog) und Biquad-Filtertypen: Tiefpass, Hochpass, Bandpass und Bandsperre. Außerdem gibt es einen Formantfilter. Sowohl für Filter als auch für Amplitude stehen herkömmliche ADSR-Hüllkurven zur Verfügung, ebenso eine weitere ADSR-Hüllkurve für den LFO-Bereich. Der LFO verfügt über eine BPM-Steuerung, die mit dem Transport oder der Host-Rate synchronisiert werden kann.

Die „DEF“-Sektion enthält Regler zum Einstellen von pitchbend, modulation und velocity. Die Effektseite (im obigen Screenshot nicht zu sehen) bietet verschiedene Effekttypen: chorus, flanger, phaser, reverb und delay sowie einen Kompressor und einen Limiter..
