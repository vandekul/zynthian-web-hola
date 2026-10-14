---
title: Surge
media_order: surge.png
description: Surge es un sintetizador digital y no se anda con rodeos. En su núcleo
  late un potente motor sustractivo híbrido con una potente cadena de efectos.
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-kb
  - ucase-pr
  homepage:
  - 'yes'
date: 17:38 20-10-2020
subtitle: Sintetizador híbrido
splash:
  bg_image_landscape: surge-hero.png
  bg_image: surge-hero_small.png
media_thumb: surge.png
audio:
- audioType: soundcloud
  audioLink: https://soundcloud.com/user-589036812-258992427/surge-2237-ad
  audioLabel: 2237 AD
- audioType: soundcloud
  audioLink: https://soundcloud.com/user-589036812-258992427/surge-demo-001-microtonal-soundscape-1-x-surge
  audioLabel: Microtonal Soundscape
- audioType: soundcloud
  audioLink: https://soundcloud.com/theexponent/resurgence
  audioLabel: Resurgence
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=2GLp6FD6oVE
urls:
- urlLink: https://surge-synthesizer.github.io/
  urlLabel: Surge's Website
- urlLink: https://surge-synthesizer.github.io/manual/
  urlLabel: Surge's Manual
- urlLink: https://github.com/surge-synthesizer/surge
  urlLabel: Source Code
---
Surge utiliza un algoritmo de síntesis híbrida sustractiva. Cada preset contiene dos «escenas» que son instancias independientes de todo el motor de síntesis (excepto los efectos) y que pueden utilizarse para crear presets por capas o divididos..

Incluye una amplia biblioteca de sonidos de fábrica:

+ 1725 patches
+ 523 wavetables

##Características
**Osciladores:**
+ 3 osciladores por escena.
+ 8 algoritmos de oscilador versátiles: Classic, Sine, Wavetable, Window, FM2, FM3, S&H Noise y Audio Input.
+ El oscilador clásico es un oscilador de pulso/diente de sierra/doble diente de sierra con modulación de forma, un suboscilador y sincronización dura.
+ Los osciladores FM2/FM3 constan de una portadora y 2 o 3 moduladores, y ofrecen varias opciones.
+ La mayoría de los algoritmos (excepto FM2, FM3 y la entrada de audio) ofrecen un unísono de hasta 16 voces a nivel de oscilador..
+ FM del oscilador y ring modulation entre los osciladores 1-2 y 2-3.
+ La mayoría de los algoritmos de oscilador (excepto FM2, FM3 y Sine) están estrictamente limitados en banda, pero aun así cubren todo el espectro audible y ofrecen un sonido contundente y limpio..
+ Generador de ruido con espectro variable.

**Bloque de filtro:**
+ Dos unidades de filtro en 8 configuraciones diferentes.
+ Bucle de realimentación disponible en 7 de esas configuraciones.
+ Algoritmos de filtro disponibles: Lowpass (12 y 24 dB/oct, cada uno con 3 variaciones), Lowpass 24 dB/oct (3 variaciones), Ladder Lowpass (6-24 dB/oct), Highpass (12 y 24 dB/oct, cada uno con 3 variaciones), Bandpass (12 y 24 dB/oct, cada uno con 3 variaciones), Notch (12 y 24 dB/oct, cada uno con 2 variaciones), Comb (4 variaciones), S&H.
+ Los filtros pueden autooscilar (con excitación) y responder increíblemente rápido a los cambios en la frecuencia de corte.
+ Waveshaper (5 formas).

**Modulación:**
+ 12 unidades LFO disponibles, 6 son por voz y 6 son globales para toda la escena.
+ Generadores de envolvente DAHDSR en cada LFO.
+ 7 formas de onda LFO deformables y modo secuenciador por pasos.
+ Los Voice LFOs permiten volver a disparar la envolvente cuando se usan como secuenciador por pasos.
+ Enrutamiento de modulación extremadamente rápido y flexible. Casi todos los parámetros continuos pueden modularse.!

**Efectos:**
+ 8 unidades de efectos organizadas como 2 inserts por escena, 2 sends y 2 efectos master.
+ 13 algoritmos de efectos: EQ, Distortion, Conditioner (EQ, control de imagen estéreo y limiter), Frequency Shifter, Rotary Speaker, Ring Modulator, Vocoder, Chorus, Phaser, Flanger, Delay, Reverb 1, Reverb 2
