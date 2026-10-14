---
title: Arpeggiator
media_order: arpeggiator.jpg
description: Un sencillo arpegiador MIDI y plugin de patrones MIDI
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - effect
  - fx-midi
date: 17:38 24-04-2020
subtitle: Un plugin sencillo de arpegiador y patrones MIDI
splash:
  bg_image_landscape: arpeggiator-hero.jpg
  bg_image: arpeggiator-hero_small.jpg
media_thumb: arpeggiator.jpg
urls:
- urlLink: https://github.com/BramGiesen/arpeggiator_LV2
  urlLabel: Source Code
---
Arpeggiator y un plugin de patrones MIDI desarrollado para la plataforma MOD por Bram Giesen.

####Arpeggiator
El arpegiador tiene las siguientes opciones:

**Opciones de tempo:**
También hay varias opciones para ajustar el tempo del plugin. La primera es el modo Free Running. En este modo, el tempo se controla mediante el control de BPM del plugin. Encima del control de BPM hay un control de Divisions. El plugin también se puede sincronizar con el host.

**Modos del Arpeggiator:**
El arpegiador tiene los siguientes modos:
+ Arriba
+ Abajo
+ Arriba-Abajo
+ Arriba-Abajo(alternativa)
+ Reproducido
+ Aleatorio

**Modos de octava:**
El arpegiador tiene un control de extensión de octavas. El arpegiador puede recorrer las notas entrantes a lo largo de varias octavas. Este control establece el rango de octavas que se recorrerán por encima del tono original. El control de modo de octava determina cómo se añadirán estas octavas a las notas originales..

####MIDI-patrón
El plugin de patrón MIDI se puede usar para crear patrones rítmicos. El plugin toma la nota entrante y sustituye la velocity de la nota por un valor establecido por uno de los faders del plugin. Como el plugin itera por los faders, genera una especie de secuencia rítmica. El control CV del plugin se puede usar para volver a disparar la secuencia..
