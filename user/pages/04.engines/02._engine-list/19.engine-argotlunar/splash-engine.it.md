---
title: Argotlunar
media_order: argotlunar.png
description: Un granulatore delay-line in tempo reale per creare trasformazioni surreali
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
  homepage:
  - 'yes'
date: 17:38 24-04-2020
subtitle: Granulator
splash:
  bg_image_landscape: argotlunar-hero.png
  bg_image: argotlunar-hero_small.png
media_thumb: argotlunar.png
audio:
- audioType: soundcloud
  audioLink: https://soundcloud.com/t800infiltrator/argotlunar
  audioLabel: Argotlunar, by t800infiltrator
- audioType: soundcloud
  audioLink: https://soundcloud.com/ioflow/20110912a
  audioLabel: 20110912, by ioflow
- audioType: soundcloud
  audioLink: https://soundcloud.com/pneuman/rpm-2012-lagrange
  audioLabel: 'RPM 2012: lagrange, by pneuman'
urls:
- urlLink: http://mourednik.github.io/argotlunar/)
  urlLabel: Argotlunar's Website
- urlLink: https://www.kvraudio.com/product/argotlunar-by-michael-ourednik
  urlLabel: KVRAudio's Page
- urlLink: https://github.com/mourednik/argotlunar
  urlLabel: Source Code
---
Argotlunar è uno strumento per creare trasformazioni surreali di flussi audio. Nello specifico, è un granulator a linea di delay in tempo reale. Disintegra un flusso audio in brevi samples (grani). Ogni grano può avere impostazioni casuali di ampiezza, panning, durata, delay, pitch, glissando, filtro e inviluppo. L'output di tutti i grani viene mixato in un flusso che può essere reinviato all'input principale..

I parametri relativi al tempo possono essere sincronizzati al tempo dell’host, per texture ritmiche e pulsanti. I parametri relativi al pitch possono essere quantizzati per effetti armonici e melodici. Il Feedback può creare suoni caotici, stratificati e distorti..

La maggior parte dei parametri può essere correlata. Esempi:

+ Frequenza di taglio del filtro correlata all'intonazione: frequenza di taglio più alta per i grains con intonazione più alta e viceversa.
+ Durata dei granuli correlata al panning: granuli di durata più breve posizionati al centro del campo stereo e granuli di durata maggiore distribuiti ampiamente nel campo stereo.

Argotlunar è un software libero. Concesso in licenza GPL v2.

#### Dettagli:

+ I parametri relativi al tempo possono essere sincronizzati al tempo dell’host.
+ I parametri relativi all'intonazione possono essere quantizzati su vari accordi/scale.
+ È possibile correlare fino a tre coppie di parametri..
+ Inviluppi dei grani a campana con coseno rialzato, parabolici e triangolari, con forma regolabile.
+ La trasposizione è interpolata con spline per ridurre l’aliasing.
+ filtro a variabile di stato 12dB (HP/BP/LP/Notch).
+ Comb filter.
