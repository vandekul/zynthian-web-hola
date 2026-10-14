---
title: setBfree
id: setbfree
description: Emulador Hammond B3 y Leslie altamente personalizable
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-add
  - ucase-kb
  - synth-emu
  - synth-phy
  homepage:
  - 'yes'
date: 17:38 10-03-2020
subtitle: Tonewheel Organ Emulator
splash:
  bg_image: setbfree-hero_small.jpg
  bg_image_landscape: setbfree-hero.jpg
media_thumb: setbfree.jpg
sitemap:
  lastmod: 07-05-2026 14:23
urls:
- urlLink: http://setbfree.org
  urlLabel: Project's Website
- urlLink: http://www.linuxsynths.com/SetBfreePatchesDemos/setbfree.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/pantherb/setBfree
  urlLabel: Source Code
video:
- videoType: vimeo
  videoLink: https://vimeo.com/130633814
  videoLabel: A rendition of Jimmy Smith's The Cat
audio:
- audioType: local
  audioFile: georgia_on_my_waltzin_mind.ogg
  audioLabel: Georgia on my waltzin mind, by TKC (MDA EPiano + setBfree)
- audioType: local
  audioFile: setBfreeDrawbarsManipulationByBaggypants.mp3
  audioLabel: Hammond Drawbars Manipulations, by Baggypants (setBfree)
- audioType: local
  audioFile: RhodesHammondByHumi.mp3
  audioLabel: Rhodes & Hammond, by Humi
---
setBfree es un sintetizador de software controlado por MIDI diseñado para imitar el sonido y las propiedades de los órganos electromecánicos y los dispositivos de modificación del sonido que dieron fama mundial a los nombres y productos de Laurens Hammond y Don Leslie..

## Características:
setBfree es un *Kit de construcción de órgano Tonewheel*, un modelo físico con más de 1000 parámetros configurables. Como un B3 real, se puede 'abrir' y ajustar los parámetros desde el estado impecable del 53 (por defecto) hasta el estado desgastado de válvulas polvorientas de los 80s.

Al ejecutarse en zynthian, setBfree ofrece 7 configuraciones de teclado predefinidas que combinan teclados y pedales:
+ **Superior:** 1 teclado (1 x canal MIDI)
+ **Superior + Inferior:** 2 teclados (2 x canales MIDI)
+ **Superior + Pedales:** 2 teclados (2 x canales MIDI)
+ **Superior + Inferior + Pedales:** 3 teclados (3 x canales MIDI)
+ **Dividir inferior/superior:** 1 teclado (1 x canal MIDI)
+ **Dividir pedales/parte superior:** 1 teclado (1 x canal MIDI)
+ **Dividir Pedales/Inferior/Superior:** 1 teclado (1 x canal MIDI)

En zynthian, setBfree también ofrece 4 tipos de forma de onda para el generador tone-wheel.:
+ **Seno:** Sonido Hammond
+ **Cuadrado:** Sonido de órgano combo
+ **Triángulo:** Sonido de órgano combo
+ **Sawtooth:** Sonido de órgano combo

Todos los controles se pueden asignar a MIDI-CC según sea necesario mediante el mecanismo MIDI-learn..

