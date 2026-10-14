---
title: ZAM Plugins
media_order: redwave.jpg
description: Eine Plugin-Sammlung zur Klangverarbeitung
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
  - fx-eq
  - fx-filter
  - fx-dynamics
  - fx-distortion
date: 17:38 24-04-2020
subtitle: Plugin-Sammlung
splash:
  bg_image_landscape: redwave-hero.jpg
  bg_image: redwave-hero_small.jpg
media_thumb: redwave.jpg
audio:
- audioType: local
  audioFile: angie-20141010_follow.ogg
  audioLabel: Follow, by Angie Hudson (2013)
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=MGErjKRu_dQ
urls:
- urlLink: http://www.zamaudio.com/
  urlLabel: ZamAudio's Website
- urlLink: http://github.com/zamaudio/zam-plugins
  urlLabel: Source Code
---
Zam-plugins ist eine Sammlung von LV2/LADSPA/VST/JACK-Audio-Plugins zur Klangbearbeitung, die intern bei ZamAudio entwickelt wurden. Die Standardeinstellungen und fast jeder Schieberegler sind auf Standardbereiche kalibriert..

Ein großes Dankeschön an falktx für das Schreiben des Distrho Plugin Framework. Dadurch konnte ich diese GUIs für zam-plugins schnell und ordentlich erstellen. Danke auch an mira, nphilipp, adi, edogawa und Haskellfant, die dabei geholfen haben, die Software für verschiedene Distributionen zu paketieren!

## Übersicht

#### ZaMaximX2
Eines der besten Plugins der Serie. In seinem Standardzustand fungiert es als Brickwall-Limiter fürs Mastering, lässt sich aber auch so einstellen, dass es den durchschnittlichen Pegel als Stereo-Maximizer anhebt, ohne jemals zu clippen. Klingt selbst bei grober Behandlung musikalisch. (Basiert auf DSP aus einem DAFX’02-Paper).

#### ZamAutoSat
Ein automatisches Sättigungs-Plugin, das dafür bekannt ist, Live-Mikrofonkanäle gleichmäßig auszusteuern.
Du kannst dieses Plugin großzügig einsetzen, ohne den Klang zu beeinflussen..

#### ZamComp
Ein leistungsstarker Mono-Kompressor-Kanalzug. Verleiht einer Kick- oder Snare-Drum mit den richtigen Einstellungen ordentlich Druck..

#### ZamCompX2
Stereo-Version von ZamComp mit Knee-Slew-Steuerung.

#### ZamEQ2
Zweibandiger parametrischer Equalizer mit Hoch- und Tiefen-Shelving-Schaltungen.

#### ZamGEQ31
31-Band-Grafik-Equalizer, gut zum EQing von Live-Räumen, zum Entfernen unerwünschter Geräusche aus einer Spur usw..

#### ZamHeadX2
HRTF-Akustikfilter-Plugin für gerichteten Klang.

#### ZamPhono
Eine Sammlung von Phono-Filtern zur Restaurierung von Schallplatten oder zur Vorbereitung des Schneidens neuer Platten.

#### ZamGate
Gate plugin zum Ducking von Sounds mit niedrigem Gain.

#### ZamGateX2
Gate-Plugin zum Ducking von Sounds mit niedrigem Gain, Stereo-Version.

#### ZamTube
Wicked-Verzerrungseffekt. Wave digital filter physikalisches Modell einer Trioden-Röhrenverstärkerstufe, mit modellierten Tone Stacks von echten Gitarrenverstärkern (danke D. Yeh et al.).

#### ZamDelay
Ein einfaches Feedback-Delay-Gerät mit Sync-to-Host-BPM-Funktion und Filter.

#### ZamDynamicEQ
Ein dynamischer Equalizer, der seinen Gain basierend auf der Erkennung eines schmalen Frequenzbands ändert. Kann so abgestimmt werden, dass andere Frequenzbereiche spontan verändert werden..

#### ZaMultiComp
Mono-Multiband-Kompressor mit 3 einstellbaren Bändern.

#### ZaMultiCompX2
Aushängeschild der zam-plugins: Stereo-Version von ZaMultiComp, mit individuellen Threshold-Reglern für jedes Band und Echtzeit-Visualisierung der Kompressionskurven.
