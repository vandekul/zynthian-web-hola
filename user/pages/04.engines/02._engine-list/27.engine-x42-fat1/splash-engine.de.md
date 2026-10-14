---
title: X42 Autotune
media_order: x42-fat1.png
description: Auto-tuner plugin
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - fx-other
  - ucase-fx
date: 17:38 24-04-2020
subtitle: Auto-Stimmgerät basierend auf zita-at1 von Fons Adriaensens
splash:
  bg_image_landscape: x42-fat1-hero_small.png
  bg_image: x42-fat1-hero_small.png
media_thumb: x42-fat1.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-autotune
  urlLabel: X42 Autotune's Website
- urlLink: https://github.com/x42/fat1.lv2
  urlLabel: Source Code
---
x42-autotune (auch bekannt als fat1.lv2) ist ein Auto-Tuner, der auf Fons Adriaensens zita-at1 basiert.

AT1 ist dafür gedacht, die Tonhöhe einer Stimme zu korrigieren, die (leicht) schief singt. Es funktioniert durch Resampling und Looping des Signals und beinhaltet keine formant correction, daher sollte es nur zur Korrektur kleiner Fehler und nicht zum tatsächlichen Transponieren eines Songs verwendet werden. AT1 kann wahrscheinlich auch bei einigen Instrumenten verwendet werden, ist aber hauptsächlich für den Stimmumfang ausgelegt..

Die 'expected'-Tonhöhe kann durch MIDI gesteuert werden oder eine feste Auswahl von Noten sein.

Die wichtigsten Unterschiede zu zita-at1 bestehen darin, dass die LV2-Plugin-Version ihre Latency an den Host meldet, den Zustand mit der Session speichert und der MIDI-Eingang Sidechain-Semantik hat.. 

#### Betriebsmodi
AT1 stimmt das Eingangssignal auf die Note um, die der konfigurierten Skala am nächsten liegt. Die Skala besteht aus bis zu 12 Noten (1 Oktave), die auf der Tastatur auf der linken Seite eingestellt und angezeigt werden. Standardmäßig sind alle 12 aktiviert..

Mit der linken Maustaste kannst du einzelne Noten aktivieren/deaktivieren, und mit der rechten Maustaste auf der Tastatur öffnest du einen Dialog, um gängige Dur-/Moll-Tonleitern auszuwählen. Die Tastatur zeigt außerdem die aktuelle Note an, die vom Pitch Estimator ausgewählt wurde..

Die folgenden Betriebsmodi werden unterstützt:

**Handbuch:** Verwende einen festen Satz von Noten (MIDI ignorieren). Mit der linken Maustaste Noten umschalten.

**MIDI:** Reagiere auf MIDI-Note-On/Off-Nachrichten. Verwende aktuell aktive MIDI-Note(n). Falls keine vorhanden sind, verwende eine beliebige Note der chromatischen Tonleiter.

**Automatisch (Standard):** Wenn keine MIDI-Noten aktiviert sind, verwende den statischen, festen Notensatz (zum Umschalten links klicken). MIDI-Noten haben Vorrang..

#### Parameter

**MIDI-Kanalauswahl:** Wähle den MIDI-Kanal aus, auf den reagiert werden soll. Das kann „Omni“ oder 1..16 sein..

**MIDI Panic:** Alle 'hängenden' MIDI-Noten zurücksetzen.

**Stimmung:** Hiermit wird die Frequenz festgelegt, die dem Ton „A“ entspricht, also die gewünschte Stimmung. In den meisten Fällen ist der Standardwert 440 Hz. Der genaue Wert wird angezeigt, sobald dieser Regler berührt wird, und kann in Schritten von 0.2 Hz eingestellt werden..

**Bias:** Normalerweise wählt der Tonhöhenschätzer die aktivierte Note aus, die der gemessenen Tonhöhe am nächsten liegt. Der Bias-Regler bevorzugt die aktuelle Note etwas stärker - dadurch kann sie stärker verstimmt sein, als es andernfalls der Fall wäre..

**Filter:** Damit wird die Stärke der Glättung der Tonhöhenkorrektur festgelegt, solange sich die aktuelle Note nicht ändert. Ändert sie sich, wird der Filter umgangen und die Korrektur springt sofort auf den neuen Wert..

**Korrektur:** Legt fest, wie viel der geschätzten Tonhöhenabweichung korrigiert wird. Eine vollständige Korrektur kann Ausdruck oder Vibrato entfernen..

**Versatz:** Fügt einen Versatz im Bereich von +/- zwei Halbtönen zur Pitch Correction hinzu. Wenn der Correction-Regler auf null eingestellt ist, ergibt sich eine konstante Tonhöhenänderung.

**Tonhöhenfehleranzeige:** Der Balken unter der Tastatur zeigt die Tonhöhenabweichung des Eingangssignals in Bezug auf die aktuelle Note an. Der Bereich beträgt +/- einen Halbton..
