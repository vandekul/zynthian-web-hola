---
title: AMSynth
id: amsynth
description: Analog-Modellierungssynthesizer, der einen traditionellen subtraktiven
  Syntheseansatz zur Klanggestaltung verwendet
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-pr
date: 17:38 24-04-2020
subtitle: Virtueller Analog-Synthesizer
splash:
  bg_image_landscape: amsynth-hero.png
  bg_image: amsynth-hero_small.png
media_thumb: amsynth.png
audio:
- audioType: local
  audioLabel: Particularly Two
  audioFile: particularlytwo.ogg
- audioType: local
  audioLabel: Corg Two Six
  audioFile: corgtwosix.ogg
- audioType: local
  audioLabel: Glass Bay
  audioFile: glassbay.ogg
- audioType: local
  audioLabel: Partenza
  audioFile: partenza.ogg
- audioType: local
  audioLabel: Simple Life
  audioFile: simplelife.ogg
- audioType: local
  audioLabel: End Game
  audioFile: endgame.ogg
- audioType: local
  audioLabel: First Pew
  audioFile: firstpew.ogg
- audioType: local
  audioLabel: Overpass
  audioFile: overpass.ogg
- audioType: local
  audioLabel: Soft Warning
  audioFile: softwarning.ogg
- audioType: local
  audioLabel: Soft Warning
  audioFile: softwarning.ogg
urls:
- urlLink: https://amsynth.github.io
  urlLabel: Project's Website
- urlLink: http://www.linuxsynths.com/amSynthdemos/amsynth.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/amsynth/amsynth
  urlLabel: Source Code
---
AmSynth, or Analog Modelling Synthesizer, entwickelt und betreut von Nick Dowell, verwendet einen traditionellen Ansatz der subtractive synthesis für das Sounddesign und kann entweder als eigenständiges Instrument oder als DSSI- oder LV2-Plug-in in einer Digital Audio Workstation wie Ardour oder Qtractor ausgeführt werden..

AmSynth ist ein Echtzeit-Polyphon/Monophon-Virtual-Synthesizer mit Anschlagdynamik und umfassender MIDI-Steuerungsmöglichkeit. Er umfasst zwei Oszillatoren, die jeweils die klassischen Wellenformen erzeugen können: Rechteck- bis Pulswelle, Dreieck- bis Sägezahnwelle, Sinus, Rauschen und Sample-and-Hold. Oszillator 2 kann mit Oszillator 1 synchronisiert und auch verstimmt werden: Feinabstimmung (plus oder minus 4 Halbtöne), Grobverstimmung (plus oder minus 12 Halbtöne) und Oktavverstimmung (minus drei oder plus vier). Das Synchronisieren der Oszillatoren und das Anpassen der Halbtonverstimmung erzeugt einige interessante FM-ähnliche Klangfarben. Ein Oszillator-Mix-Knob ermöglicht die Steuerung der Balance zwischen den beiden, und wenn man ihn ganz nach links oder rechts dreht, wird jeweils einer der beiden isoliert. Ein Ringmodulationspegel-Knob ist ebenfalls vorhanden.

Eine standardmäßige ADSR-Hüllkurve wird sowohl für den Amplituden- als auch für den Filterbereich bereitgestellt. Die Filter- und Amplituden-Velocity-Empfindlichkeits-Knobs befinden sich in der unteren rechten Ecke der GUI.

Der Filterbereich umfasst 9 Filtertypen: low-pass, high-pass, bandpass und notch (jeweils mit 12dB- und 24dB-Einstellungen) sowie eine Filter-Bypass-Option. Ein Envelope-Strength-Knob steuert die Tiefe des Filtereffekts, sowohl im positiven als auch im negativen Bereich. Filter-Keyfollow, Resonance und Cutoff sind in diesem Bereich enthalten..

AmSynth hat einen Low Frequency Oscillator. Dieser LFO kann vollständig ausgeschaltet oder so eingestellt werden, dass er die Tonhöhe, den Filter und die Amplitude oder eine beliebige Kombination aus diesen drei Parametern beeinflusst. Der Tonhöhenparameter kann zu einem der Oszillatoren oder zu beiden geleitet werden. Zu den Wellenformen gehören: Square, Triangle, Sine, Sample-and-Hold, Saw-up, Saw-down und Noise.

Zusammen mit den Reglern für Hauptlautstärke und Drive (Verzerrung) bietet amSynth ein Plate-Type Reverb, einen Size-Knob zum Anpassen der Weite sowie Stereo- und Damping-Knobs. Zu den zusätzlichen Funktionen der neueren Version gehören eine Mono/Legato/Poly-Steuerung und eine sehr weitreichende Portamento-Funktion, die jetzt auf den Modus „always“ oder „legato“ eingestellt werden kann. Außerdem gibt es eine Panning-Steuerung, und mit dem Hotkey „ctrl+r“ werden die Einstellungen randomisiert..

Feinabstimmungen der Knob-Einstellungen können vorgenommen werden, indem Sie die Umschalttaste gedrückt halten, während Sie die Knobs bewegen..

AmSynth bietet unbegrenzte Polyphonie, obwohl eine 16-stimmige Polyphonie normalerweise ausreicht. Die Pitchbend-Funktion kann in Halbtonschritten bis zu 2 Oktaven eingestellt werden. Mikrotonale Skalen können jetzt ebenfalls geladen werden..

## Funktionen:
+ Duale Oszillatoren (Sinus / Sägezahn / Rechteck / Rauschen) mit Hard Sync
+ 12/24 dB/oct resonanter Filter (Tiefpass / Hochpass / Bandpass / Kerbfilter)
+ Mono / poly / Legato-Keyboard-Modi
+ Duale ADSR-Hüllkurvengeneratoren (Filter & Amplitude)
+ LFO, der die Oszillatoren, den Filter und die Amplitude modulieren kann
+ Distortion und Reverb
