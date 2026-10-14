---
title: Arpeggiator
media_order: arpeggiator.jpg
description: Ein einfaches MIDI-Arpeggiator- und MIDI-Pattern-Plugin
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - effect
  - fx-midi
date: 17:38 24-04-2020
subtitle: Ein einfaches Plugin für Arpeggios & MIDI-Muster
splash:
  bg_image_landscape: arpeggiator-hero.jpg
  bg_image: arpeggiator-hero_small.jpg
media_thumb: arpeggiator.jpg
urls:
- urlLink: https://github.com/BramGiesen/arpeggiator_LV2
  urlLabel: Source Code
---
Arpeggiator und ein MIDI-Pattern-Plugin, das für die MOD-Plattform von Bram Giesen entwickelt wurde.

####Arpeggiator
Der Arpeggiator verfügt über folgende Optionen:

**Tempooptionen:**
Es gibt auch einige Optionen, um das Tempo des Plugins einzustellen. Die erste ist der Free Running-Modus. In diesem Modus wird das Tempo über den BPM-Regler des Plugins gesteuert. Über dem BPM-Regler befindet sich ein Divisions-Regler. Das Plugin kann auch mit dem Host synchronisiert werden.

**Arpeggiator-Modi:**
Der Arpeggiator verfügt über die folgenden Modi:
+ Nach oben
+ Nach unten
+ Hoch-Runter
+ Auf-Ab(Alternative)
+ Gespielt
+ Zufällig

**Oktavmodi:**
Der Arpeggiator verfügt über eine Steuerung für die Oktavspreizung. Der Arpeggiator kann die eingehenden Noten über mehrere Oktaven hinweg durchlaufen. Mit dieser Steuerung wird der Bereich der Oktaven festgelegt, die über der ursprünglichen Tonhöhe durchlaufen werden. Wie diese Oktaven zu den ursprünglichen Noten hinzugefügt werden, wird durch die Steuerung für den Oktavmodus bestimmt..

####MIDI-Muster
Das MIDI-pattern-Plugin kann zum Erstellen rhythmischer Muster verwendet werden. Das Plugin nimmt die eingehende Note und ersetzt die Velocity der Note durch einen Wert, der über einen der Fader des Plugins eingestellt wird. Da das Plugin die Fader durchläuft, erzeugt es eine Art rhythmische Sequenz. Die CV-Steuerung des Plugins kann verwendet werden, um die Sequenz erneut auszulösen..
