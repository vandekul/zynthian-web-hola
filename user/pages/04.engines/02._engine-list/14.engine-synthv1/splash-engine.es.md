---
title: SynthV1
id: synthv1
description: Sintetizador polifónico sustractivo clásico de 4 osciladores con efectos
  estéreo
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-pr
date: 17:38 24-04-2020
subtitle: Virtual Analog Synthesizer
splash:
  bg_image_landscape: synthv1-hero.png
  bg_image: synthv1-hero_small.png
media_thumb: synthv1.png
audio:
- audioType: local
  audioFile: woodpecker.ogg
  audioLabel: Woodpecker
- audioType: local
  audioFile: undeniable.ogg
  audioLabel: Undeniable
- audioType: local
  audioFile: noizeexportdemo.ogg
  audioLabel: Noize Export Demo
- audioType: local
  audioFile: saturnone.ogg
  audioLabel: Saturn One
- audioType: local
  audioFile: spaceorgan.ogg
  audioLabel: Space Organ
- audioType: local
  audioFile: clavone.ogg
  audioLabel: Clav One
- audioType: local
  audioFile: bubbler.ogg
  audioLabel: Bubbler
- audioType: local
  audioFile: isitterrific.ogg
  audioLabel: Is it terrific?
- audioType: local
  audioFile: phasedout.ogg
  audioLabel: Phased Out
- audioType: local
  audioFile: solohornone.ogg
  audioLabel: Solo Horn One
- audioType: local
  audioFile: synthkeysfour.ogg
  audioLabel: Synth Keys Four
- audioType: local
  audioFile: eightmm.ogg
  audioLabel: Eight MM
- audioType: local
  audioFile: solohornthree.ogg
  audioLabel: Solohornthree
urls:
- urlLink: https://synthv1.sourceforge.io
  urlLabel: Project's Website
- urlLink: http://www.linuxsynths.com/Synthv1PatchesDemos/synthv1.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/rncbc/synthv1
  urlLabel: Source Code
---
SynthV1 es un sintetizador polifónico sustractivo totalmente digital y de estilo clásico, con 4 osciladores y FX estéreo. Está diseñado y desarrollado por Rui Nuno Capela, y forma parte de Vee One Suite (que incluye Padthv1, Samplv1 y Drumkv1). Puede funcionar como sintetizador independiente o como plugin LV2 dentro de una configuración de DAW, como Ardour o QTractor. Puede funcionar en una sesión de Jack o Non Session Management (NSM), y ofrece compatibilidad con Jack Midi y Alsa Midi.

## Características:
Synthv1 tiene capacidad tanto polifónica (32 notas) como monofónica, además de controles de sensibilidad a Velocity y Aftertouch. La disposición consta de dos páginas idénticas, denominadas Synth 1 y Synth 2, además de una tercera página (de efectos). Ambas páginas de sintetizador incluyen una sección DCO, una sección Filter, una sección Amplitude, una sección LFO, una sección Controller y una sección General Output. La sección Output controla el nivel de audio con respecto a la salida del otro sintetizador, así como la cantidad de señal de efectos.

La sección de oscilador de cada página incluye dos selectores de forma de onda, con las formas de onda clásicas y sus equivalentes limitados en banda: de pulso a cuadrada, triangular a diente de sierra, sinusoidal, aleatoria y ruido. Un ajuste de cero (cuando está configurado como pulso) desactivará el oscilador. También se incluye una función de sincronización. Los Knobs de anchura modulan las formas de onda, así como las señales aleatorias y de ruido..

Desafinación de más y menos cuatro octavas, más desafinación fina. Portamento (glide) y un ajuste global para la velocidad de la envolvente ADSR se encuentran en la zona superior derecha de la GUI..

La sección Filter proporciona tipos de filtro de 12-dB (state variable), 24-dB (Stilson/Smith Moog) y bi-quad: lowpass, highpass, bandpass y band-reject. También hay un formant filter. Se incluyen envolventes ADSR tradicionales tanto para el filtro como para la amplitud, además de otra envolvente ADSR para la sección LFO. El LFO tiene un control BPM que se puede sincronizar con el transporte o con la frecuencia del host..

El apartado "DEF" tiene controles para configurar pitchbend, modulation y velocity. La página Effects (no se muestra en la captura de pantalla anterior) ofrece varios tipos de efectos: chorus, flanger, phaser, reverb y delay, así como un compressor y un limiter..
