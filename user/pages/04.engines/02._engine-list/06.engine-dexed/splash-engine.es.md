---
title: Dexed
id: dexed
image: dexed.jpg
description: Sintetizador FM por software inspirado en los clásicos Yamaha DX7 y TX7
  de los años 80
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - ucase-kb
  - ucase-pr
  - synth-emu
  - synth-fm
  homepage:
  - 'yes'
date: 17:38 24-04-2020
subtitle: FM Synthesizer
splash:
  bg_image_landscape: dexed-hero.png
  bg_image: dexed-hero_small.png
media_thumb: dexed.jpg
sitemap:
  lastmod: 07-05-2026 14:15
urls:
- urlLink: https://asb2m10.github.io/dexed
  urlLabel: Project's Website
- urlLink: http://www.linuxsynths.com/DexedPatchesDemos/dexed.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/asb2m10/dexed
  urlLabel: Source Code
- urlLink: https://yamahablackboxes.com/collection/yamaha-dx7-synthesizer/
  urlLabel: Yamaha DX7 Info
audio:
- audioLink: https://soundcloud.com/starling-studios/mmoncur-hexed-osc74
  audioLabel: mmoncur - Hexed (OSC74)
  audioType: soundcloud
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=wSs1-020nNY
---
Dexed es un sintetizador software de tipo FM desarrollado por Pascal Gauthier, de Digital Suburban. Es una aplicación ideal para importar, reproducir y editar/gestionar patches sysex tanto del clásico sintetizador Yamaha DX7 como del TX7..

Dexed incluye seis operadores, fieles a la estructura DX. Cada operador tiene un indicador de nivel. Los operadores se pueden organizar en varios algoritmos, indicados por los cuadros verdes. Los bancos de patches se llaman "cartuchos" y hay muchos (unos 32) incluidos en el paquete de instalación. Al seleccionar un cartucho se cargan los patches del banco correspondiente..

Dexed se puede configurar para utilizar algunas de las limitaciones matemáticas originales de un sintetizador DX. Esto no solo se aplica al DAC, también afecta a la resolución en bits de las ondas sinusoidales y a la forma en que se aplica la amplitud a cada operador. Como todo esto es experimental, habrá varios motores disponibles para poder compararlos fácilmente..

Dexed incluye 3 tipos de motor:
+ **Moderno:** esta es la implementación original de sintetizador de música de 24 bits para android.
+ **Marca I:** Basado en la serie OPL, pero con una resolución más alta (las LUT son de 10 bits). El objetivo de este motor es acercarse lo máximo posible al DX7 real..
+ **Serie OPL:** esta es una implementación experimental de los chips de la familia OPL obtenidos mediante ingeniería inversa. 8-bit. Ten en cuenta que las envolventes aún necesitan ajustes.

## Funciones:
+ Multiplataforma (OS X, Windows o Linux) y multiformato (VST, AU, LV2)
+ El motor de sonido music-synthesizer-for-android está muy inspirado en las características del DX7 original.
+ 144 parámetros del DX7 automatizables por DAW disponibles desde un único panel
+ Admite completamente mensajes sysex de entrada y salida del DX7; incluido el cambio de controlador. Esto significa que puedes usarlo con un DX7/TX7 nativo como editor de patches y gestor de sysex
+ Cada operador tiene un vúmetro en tiempo real para saber cuál está activo.
+ Puede cargar/guardar cualquier programa sysex de DX7/TX7. También es posible guardar un único programa en un archivo sysex diferente.
