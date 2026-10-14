---
title: SynthV1
id: synthv1
description: Sintetizador polifônico subtrativo vintage de 4 osciladores com efeitos
  estéreo
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
SynthV1 é um sintetizador polifônico subtrativo totalmente digital, à moda antiga, com 4 osciladores e FX estéreo. Foi projetado e desenvolvido por Rui Nuno Capela e faz parte da Vee One Suite (que inclui Padthv1, Samplv1 e Drumkv1). Pode funcionar como sintetizador independente ou como plugin LV2 em uma configuração de DAW, como Ardour ou QTractor. Pode funcionar em uma sessão Jack ou Non Session Management (NSM) e oferece suporte a Jack Midi e Alsa Midi..

## Recursos:
O Synthv1 tem capacidade polifônica (32 notas) e monofônica, além de controles de sensibilidade a Velocity e Aftertouch. O layout consiste em duas páginas idênticas, denominadas Synth 1 e Synth 2, além de uma terceira página (de efeitos). Ambas as páginas de synth incluem uma seção DCO, uma seção de filtro, uma seção de amplitude, uma seção LFO, uma seção de controlador e uma seção de saída geral. A seção de saída controla o nível de áudio em relação à saída do outro synth, bem como a quantidade de sinal de efeitos.

A seção de oscilador de cada página inclui dois seletores de forma de onda, com as formas de onda clássicas e suas contrapartes com limitação de banda: pulso para quadrada, triangular para dente de serra, seno, aleatória e ruído. Uma configuração de zero (quando definida como pulso) desativa o oscilador. Também está incluída uma função de sync. Os Knobs de width modulam as formas de onda, assim como os sinais aleatórios e de ruído..

Desafinação de mais e menos quatro oitavas, além de ajuste fino de afinação. Portamento (glide) e um ajuste global para a taxa do envelope ADSR estão localizados na área superior direita da GUI..

A seção Filter oferece tipos de filtro de 12 dB (variável de estado), 24 dB (Stilson/Smith Moog) e biquad: lowpass, highpass, bandpass e band-reject. Há também um filtro de formantes. Há envelopes ADSR tradicionais para o filtro e a amplitude, além de outro envelope ADSR para a seção LFO. O LFO tem um controle BPM que pode ser sincronizado ao transporte ou à taxa do host..

A seção "DEF" contém controles para configurar pitchbend, modulation e velocity. A página de efeitos (não mostrada na captura de tela acima) oferece vários tipos de efeitos: chorus, flanger, phaser, reverb e delay, além de um compressor e um limiter..
