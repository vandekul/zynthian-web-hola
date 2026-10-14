---
title: Ratatouille - Dual Neural Modeler
media_order: ratatouille.jpg
description: Dualer Neuralnetz-Modeller. Mische 2 neuronale Modelle + IRs
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - ucase-fx
  - fx-distortion
date: 17:38 24-04-2020
subtitle: Mische 2 neuronale Modelle und 2 IRs
splash:
  bg_image: ratatouille-hero.jpg
  bg_image_landscape: ratatouille-hero.jpg
media_thumb: ratatouille.jpg
urls:
- urlLink: https://github.com/brummer10/Ratatouille.lv2
  urlLabel: Source Code
- urlLink: https://tone3000.com
  urlLabel: Ratatouille's Models in Tone3000
---
Ratatouille ist ein Neural-Model-Lader und -Mixer für Linux/Windows.
Es kann zwei Modelle laden, die *.nam-Dateien (Neural Amp Modeler) oder *.json / .aidax-Dateien (RTNeural) sein können, und verwenden
die „Blend“-Steuerung, um zwischen den beiden Modellen zu überblenden und sie zu mischen, um den spezifischen Klang zu simulieren, den Sie suchen.
Natürlich können Sie auch nur eine einzelne Modelldatei laden, und die "Blend"-Steuerung bewirkt nichts.

Ratatouille verwendet parallele Verarbeitung für die neuronalen Modelle, daher wäre das Laden eines zweiten neuronalen Modells nicht
bemerkenswert in Bezug auf die DSP-Auslastung. Optional könnte Ratatouille den gesamten Prozess im gepufferten Modus ausführen.
Das reduziert die dsp-Last noch weiter. Die resultierende latency wird dem Host gemeldet, damit sie ...ರುತ್ತ
kompensiert. Zur Information wird die resultierende Latency auf der GUI angezeigt.

Der "Delay"-Regler könnte eine kleine Verzögerung hinzufügen, um Phasenprobleme zu überwinden oder dem Klang etwas Farbe/Reverb hinzuzufügen.
Die 'ctrl'-Taste aktiviert die Feinabstimmung, um ein sample-genaues Delay einzustellen. Ratatouille kann auch die Phase erkennen
offset und intern kompensieren.

Um deinen Sound abzurunden, kannst du zwei Impulse Response Files laden und sie nach deinen Bedürfnissen mischen. IR-files könnten sein.
beim Laden normalisiert, sodass sie die Lautheit nicht beeinflussten.

Ratatouille.lv2 unterstützt Resampling, wenn dies erforderlich ist, um die erwartete Sample-Rate der geladenen Modelle zu erreichen. Beide
modelle und die IR-Dateien haben möglicherweise unterschiedliche Erwartungen hinsichtlich der Samplerate.
#### Modelle aus einer großen Community beziehen

[Tone3000.com](https://tone3000.com) ist zum Anlaufpunkt für die besten Modelle für Neural Amp Modeler, Aida-X und Proteus geworden und wird künftig weitere Plattformen unterstützen. Nicht nur die Modellauswahl, sondern auch unsere Sammlung von IRs wächst und wird innerhalb der Plattform immer beliebter..

#### Dateien werden geladen

Über die zynthian-ui kannst du Modelldateien einfach laden. Bewege einfach den dem Modell-Steuerelement zugewiesenen Knob, und der Dateiauswahldialog erscheint..

