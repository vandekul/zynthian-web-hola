---
title: OBX-D
id: obxd
description: Sintetizador virtual inspirado en algunos dispositivos clásicos fabricados
  por Oberheim en los años 80
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-kb
  - ucase-pr
  - synth-emu
  homepage:
  - 'yes'
date: 17:38 24-04-2020
subtitle: Oberheim Emulator
splash:
  bg_image: obxd-hero_small.png
  bg_image_landscape: obxd-hero.png
media_thumb: obxd.jpg
sitemap:
  lastmod: 07-05-2026 16:19
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=NdfcgiLsp88
audio:
- audioType: local
  audioFile: OBXdLoveByHumi.mp3
  audioLabel: Oberheim Love, by Humi
- audioType: local
  audioFile: chirpybellstwo.ogg
  audioLabel: Chirpy Bells 2
- audioType: local
  audioFile: lotshappenin.ogg
  audioLabel: Lots Happenin
- audioType: local
  audioFile: madderthan.ogg
  audioLabel: Madderthan
- audioType: local
  audioFile: saladdressing.ogg
  audioLabel: Salad Dressing
- audioType: local
  audioFile: withair.ogg
  audioLabel: Withair
urls:
- urlLink: http://www.linuxsynths.com/ObxdPatchesDemos/obxd.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/2DaT/Obxd
  urlLabel: Source Code
---
OBXD es un sintetizador monofónico/polifónico de 8 voces en tiempo real desarrollado por 2DaT, Layzer y Breeze (en KVR) y portado recientemente a Linux. OBXD está disponible en formatos LV2 y VST, y puede ejecutarse en la mayoría de los hosts, como Ardour, Carla, Jalv y Qtractor..

OBXD incluye muchas de las características del famoso sintetizador hardware OB-X de los años 80, así como algunas modificaciones (consulta los enlaces al manual más abajo). Tiene dos osciladores con controles de nivel discretos y un knob de nivel de ruido, formas de onda de sierra y cuadrada independientes con control de modulación de anchura de pulso; un knob de cross-modulation, botón sync y botón step (para ajustar la afinación del oscilador en semitonos en lugar de hacerlo de forma continua). Incluye botón de modo Unison (todas las notas de polifonía se apilan en una sola voz monofónica más gruesa), controles de spread, glide (portamento), afinación y transposición de octava. El knob "Bright" controla una mayor precisión en las frecuencias altas del espectro sonoro, y el knob "P Env" proporciona una envolvente de tono, conectada directamente a la sección de envolvente del filtro..

## Características:
La sección de filtro OBXD cuenta con un filtro multimodo de 12 dB. Además de los controles tradicionales de cutoff, resonance y envelope depth, esta sección permite controlar key follow, la interpolación de alta calidad (aumenta ligeramente el consumo de CPU) y el control multimodo.

El Knob "Multi" permite alternar entre las siguientes opciones de filtro: low-pass (Knob a la izquierda), notch (posición intermedia) y high-pass (Knob a la derecha). Al activar el botón "BP", se obtiene un filtro bandpass en lugar de notch (Knob en posición intermedia). El botón "24dB" proporciona un filtro lowpass de 24 dB que se ajusta de 24 dB (Knob a la izquierda) a 6 dB (Knob a la derecha).

Hay un botón VAM (voice allocation mode) que da prioridad a la última nota en lugar de a la nota más grave. La sección de control incluye un rango de bend de 12 semitonos (de 2 notas cuando está desactivado) y un botón para que el bend afecte solo al oscilador 2. Vibrato Rate está conectado directamente al modwheel, pero también interactúa de formas interesantes con el knob de frecuencia del LFO. La sección de control también incluye controles de sensibilidad a la velocidad para el filtro y la amplitud..

La sección LFO incluye formas de onda sinusoidales, cuadradas y de sample-and-hold, que se pueden mezclar. La sección Voice Variation ofrece un control adicional del filtro, el glide y la amplitud, y Voice Pan permite controlar de forma independiente la dirección del pan de cada una de las 8 voces..

