---
title: AMSynth
id: amsynth
description: Sintetizador de modelado analógico que utiliza un enfoque tradicional
  de síntesis sustractiva para el diseño de sonido
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-pr
date: 17:38 24-04-2020
subtitle: Sintetizador analógico virtual
splash:
  bg_image_landscape: amsynth-hero.png
  bg_image: amsynth-hero_small.png
media_thumb: amsynth.png
audio:
- audioType: local
  audioLabel: Particularly Two
  audioFile: particularlytwo.ogg
- audioType: local
  audioLabel: Corg Two Six
  audioFile: corgtwosix.ogg
- audioType: local
  audioLabel: Glass Bay
  audioFile: glassbay.ogg
- audioType: local
  audioLabel: Partenza
  audioFile: partenza.ogg
- audioType: local
  audioLabel: Simple Life
  audioFile: simplelife.ogg
- audioType: local
  audioLabel: End Game
  audioFile: endgame.ogg
- audioType: local
  audioLabel: First Pew
  audioFile: firstpew.ogg
- audioType: local
  audioLabel: Overpass
  audioFile: overpass.ogg
- audioType: local
  audioLabel: Soft Warning
  audioFile: softwarning.ogg
- audioType: local
  audioLabel: Soft Warning
  audioFile: softwarning.ogg
urls:
- urlLink: https://amsynth.github.io
  urlLabel: Project's Website
- urlLink: http://www.linuxsynths.com/amSynthdemos/amsynth.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/amsynth/amsynth
  urlLabel: Source Code
---
AmSynth, o Analog Modelling Synthesizer, desarrollado y mantenido por Nick Dowell, utiliza un enfoque tradicional de síntesis sustractiva para el diseño de sonido y puede ejecutarse como instrumento independiente o como plug-in DSSI o LV2 dentro de una estación de trabajo de audio digital como Ardour o Qtractor.

AmSynth es un sintetizador virtual polifónico/monofónico en tiempo real, sensible al tacto y con capacidad de control MIDI completa. Incluye dos osciladores, cada uno capaz de generar las formas de onda clásicas: de cuadrada a pulso, de triangular a diente de sierra, sinusoidal, ruido y sample-and-hold. El oscilador 2 se puede sincronizar con el oscilador 1 y también se puede desafinar: ajuste fino (más o menos 4 semitonos), desafinación gruesa (más o menos 12 semitonos) y desafinación de octava (menos tres o más cuatro). Sincronizar los osciladores y ajustar la desafinación en semitonos produce algunos timbres interesantes similares a FM. Un Knob de mezcla de osciladores permite controlar el equilibrio entre ambos; al girarlo del todo a la izquierda o a la derecha, se aísla uno u otro. También incluye un Knob de nivel de modulación en anillo..

Se proporciona una envolvente ADSR estándar para las secciones de amplitud y filtro. Los Knobs de sensibilidad a la Velocity del filtro y la amplitud están situados en la esquina inferior derecha de la GUI..

La sección de filtro incluye 9 tipos de filtro: low-pass, high-pass, bandpass y notch (cada uno con ajustes de 12dB y 24dB), y una opción para omitir el filtro. Un knob de intensidad de envolvente controla la profundidad del efecto de filtro, tanto en positivo como en negativo. Esta sección incluye el seguimiento de teclado del filtro, la resonancia y el cutoff..

AmSynth tiene un LFO. Este LFO puede estar completamente desactivado o configurarse para afectar al pitch, al filtro y a la amplitud, o a cualquier combinación de los tres. El parámetro pitch puede dirigirse a cualquiera de los osciladores, o a ambos. Las formas de onda incluyen: cuadrada, triangular, sinusoidal, sample-and-hold, saw-up, saw-down y ruido.

Junto con los controles principales de volumen y drive (distorsión), amSynth incluye una Reverb de tipo plate, un Knob de tamaño para ajustar la amplitud, y Knobs de stereo y damping. Entre las funciones adicionales de la versión más reciente se incluyen el control mono/legato/poly y una capacidad de portamento muy amplia, que ahora se puede configurar en modo "always" o "legato". También se incluye un control de panorama, y las teclas de acceso rápido "ctrl+r" aleatorizarán los ajustes..

Los ajustes precisos de los Knobs se pueden realizar manteniendo pulsada la tecla Shift mientras se mueven los Knobs..

AmSynth tiene capacidad de polifonía ilimitada, aunque normalmente 16 notas de polifonía son suficientes. La función Pitchbend se puede seleccionar en semitonos, hasta 2 octavas. Ahora también se pueden cargar escalas microtonales..

## Características:
+ Osciladores duales (seno / diente de sierra / cuadrada / ruido) con sincronización rígida
+ Filtro resonante de 12/24 dB/oct (low-pass / high-pass / band-pass / notch)
+ Modos de teclado mono / poly / legato
+ Generadores de envolvente ADSR dobles (filtro y amplitud)
+ LFO que puede modular los osciladores, el filtro y la amplitud
+ Distorsión y reverb
