---
title: Argotlunar
media_order: argotlunar.png
description: Un granulador de línea de retardo en tiempo real para crear transformaciones
  surrealistas
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
Argotlunar es una herramienta para crear transformaciones surrealistas de flujos de audio. En concreto, es un granulador de línea de delay en tiempo real. Desintegra un flujo de audio en muestras cortas (granos). Cada grano puede tener ajustes aleatorios de amplitud, panoramización, duración, delay, pitch, glissando, filtro y envolvente. La salida de todos los granos se mezcla en un flujo que puede realimentarse a la entrada principal.

Los parámetros relacionados con el tiempo pueden sincronizarse con el tempo del host, para crear texturas rítmicas y pulsantes. Los parámetros relacionados con el tono pueden cuantizarse para lograr efectos armónicos y melódicos. La realimentación puede crear sonidos caóticos, densamente superpuestos y distorsionados..

La mayoría de los parámetros se pueden correlacionar. Ejemplos:

+ Filter cut-off correlacionado con pitch: mayor Filter cut-off para granos con mayor pitch, y viceversa.
+ Duración del grano correlacionada con el paneo: Granos de menor duración paneados al centro del campo estéreo, y granos de mayor duración paneados ampliamente en el campo estéreo.

Argotlunar es software libre. Con licencia bajo la GPL v2..

#### Detalles:

+ Los parámetros relacionados con el tiempo se pueden sincronizar con el tempo del host..
+ Los parámetros relacionados con el Pitch se pueden cuantizar a varios acordes/escalas.
+ Se pueden correlacionar hasta tres pares de parámetros.
+ Envolventes de grano de campana de coseno elevado, parabólicas y triangulares, con forma ajustable.
+ La transposición se interpola mediante splines para reducir el aliasing.
+ Filtro de estado variable de 12dB (HP/BP/LP/Notch).
+ Comb filter.
