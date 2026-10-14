---
title: MDA JX-10
id: mda-jx10
description: Sintetizador sustractivo inspirado en algunas máquinas Roland de los
  años 80
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-kb
  - synth-emu
date: 17:38 24-04-2020
subtitle: JX-8p/JX-10 Emulator
splash:
  bg_image_landscape: djx10-hero.jpg
  bg_image: djx10-hero_small.jpg
media_thumb: djx10.jpg
urls:
- urlLink: http://mda.smartelectronix.com
  urlLabel: MDA's Website
- urlLink: https://github.com/moddevices/mda-lv2
  urlLabel: MDA-LV2 Source Code
audio:
- audioType: local
  audioFile: fifthsweeppad.ogg
  audioLabel: Fifth Sweep Pad
- audioType: local
  audioFile: hardlead.ogg
  audioLabel: Hard Lead
- audioType: local
  audioFile: solidbacking.ogg
  audioLabel: Solid Backing
- audioType: local
  audioFile: detunedsynbrass.ogg
  audioLabel: Detuned Syn-Brass
- audioType: local
  audioFile: sawbass.ogg
  audioLabel: Saw Bass
- audioType: local
  audioFile: touchyfellow.ogg
  audioLabel: Touchy Fellow
- audioType: local
  audioFile: helicopter.ogg
  audioLabel: Helicopter
- audioType: local
  audioFile: wobblebass.ogg
  audioLabel: Wobble Bass
- audioType: local
  audioFile: filterdemo.ogg
  audioLabel: Filter Demo
---
MDA JX-10 es un sintetizador sustractivo por software inspirado en algunas máquinas Roland de los 80. Consume muy pocos recursos y la calidad del sonido es excelente..

Proporciona dos osciladores (saw y pulsewidth) que se pueden aislar o combinar. La polifonía se obtiene mediante el ajuste del control glide: cero para control polifónico, máximo para monofónico. Incluye envolventes ADSR estándar para el timbre (filtro) y la amplitud. Pitchbend está ajustado a un tono entero. La profundidad del LFO está conectada directamente a la rueda de modulación. He añadido una demo para dar una idea del filtro LP, muy rico (última demo de arriba).

En el siglo XX, los plugins de Maxim Digital Audio (mda) se encontraban entre los primeros plugins VST disponibles para Windows. Tienen fama de ser de gran calidad y consumir poca CPU. Hace varios años se publicó el código fuente de estos plugins y David Robillard portó los plugins mda al formato LV2. La mayoría de los plugins mda son efectos, pero también hay cuatro instrumentos: DX10, JX10, Piano y ePiano..

## Características:
+ 2 osciladores fijos (Mix seleccionable entre 100:0 y 50:50) & Noise
+ Afinación del oscilador +-24 semitonos
+ Filtro resonante (Controlable por Env/LFO/Velocity)
+ ADSR para VCF & Amp/Env
+ Glide - 6 modos (Poly, P-Legato, P-Glide, Mono, M-Legato, M-Glide)
+ LFO
+ Vibrato
+ Afinación del sintetizador +-2 octavas
+ Bajo uso de CPU
+ Banco predeterminado de 52 patches
+ Sin GUI
