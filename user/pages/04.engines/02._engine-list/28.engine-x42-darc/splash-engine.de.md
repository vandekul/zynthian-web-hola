---
title: X42 Compressor
media_order: x42-darc.png
description: Allzweck-Audiodynamikbereichskompressor
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - ucase-fx
  - fx-dynamics
content:
  items: '@self.modular'
date: 17:38 24-04-2020
subtitle: General Purpose Dynamic Audio Range Compressor
splash:
  bg_image_landscape: x42-darc-hero_small.png
  bg_image: x42-darc-hero_small.png
media_thumb: x42-darc.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-compressor
  urlLabel: X42 Compressor's Website
- urlLink: https://github.com/x42/darc.lv2
  urlLabel: Source Code
---
x42-compressor (auch bekannt als darc.lv2) ist ein Dynamic Audio Range Compressor, inspiriert von Adriaensens zita-dc1. Es ist ein sehr gut klingender Downward Compressor, der den Workflow in den Fokus stellt und nur eine minimale Anzahl an Bedienelementen bietet. Die Kompression reagiert auf die Signalleistung (RMS), also auf die vom Menschen wahrgenommene Lautheit, nicht auf den medienbezogenen Digital-Peak-.

Der Kompressor verfügt über auto makeup-gain, fest eingestellt auf -10 dBFS/RMS. Dies erhält die wahrgenommene Lautheit über einen weiten Bereich von Schwellenwerten und Ratio-Einstellungen..

Eine spezielle «Hold»-Funktion ändert die release-time, sodass sie nur angewendet wird, solange das Signal den threshold überschreitet. Mit anderen Worten: Wenn «Hold» aktiviert ist, wird der aktuelle Gain (oder die Dämpfung) eingefroren, wenn das Signal unter den threshold fällt.
Dies verhindert, dass der Kompressor übermäßigen Gain hinzufügt (z. B. den Noise-Floor moduliert), und kann übermäßigem 'Pumping' bei kurzen Release-Zeiten entgegenwirken..

Das Plugin ist als Mono- und Stereo-Variante verfügbar. Bei Letzterer werden beide Eingänge summiert und die Signalleistung gemittelt, um den Gain-Faktor zu bestimmen..

darc.lv2 ist vom Algorithmus und der Benutzeroberfläche von Fons Adriaensens zita-dc1 inspiriert..

#### Parameter
**Input Gain:** Gain, der vor der Pegelerkennung oder einer anderen Verarbeitung angewendet wird. Beachte, dass dies in der Kurvenanzeige nicht als Versatz auf der x-Achse dargestellt wird. Der Bereich reicht von -10 bis +30dB in Schritten von 1dB (0,2dB fein abgestuft).

**Schwellenwert:** Signalpegel (RMS), bei dem der Kompressionseffekt aktiviert wird. Der Bereich reicht von -50 bis -10dB in Schritten von 0.5dB (0.1dB fein abgestuft).

**Ratio:** Die Menge an Gain oder Dämpfung, die angewendet werden soll (dB/dB oberhalb des Thresholds). Unity bleibt bei -10dBFS/RMS erhalten (automatische Makeup-Gain).

**Attack time:** Zeit, die das Signal benötigt, um nach Überschreiten des Schwellenwerts vollständig komprimiert zu werden.

**Release time:** Minimale Erholungszeit bis zum unkomprimierten Signalpegel nach Unterschreiten des Schwellenwerts.

**Halten (check-button):** Behalte die aktuelle Dämpfung bei, wenn das Signal den Schwellenwert unterschreitet. Dies verhindert eine Modulation des Grundrauschens und kann dem 'Pumpen entgegenwirken.'.

#### Anzeige
Die horizontale Anzeige am unteren Rand zeigt den Gain, der auf das Signal angewendet wird. Die Anzeige zeigt den Min-/Max-Bereich der letzten 50 ms. Werte links &lt; 0 bedeuten, dass das Signal abgeschwächt wird (der Eingang ist lauter als -10 dBFS/RMS).

Das Diagramm oben visualisiert das Input-zu-Output-Gain-Mapping in dB. Wenn «Hold» aktiviert ist, wird der Bereich, in dem das Gain nicht freigegeben wird, blau schattiert. Die Anzeige zeigt außerdem den Input-Signalpegel als ebenfalls unter der Kurve weiß schattierten Bereich sowie den aktuellen Output-Pegel (50-ms-Durchschnitt) als Punkt.
