---
title: OBX-D
id: obxd
description: Sintetizador virtual inspirado em alguns aparelhos clássicos da Oberheim
  nos anos 80
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
OBXD é um sintetizador monofônico/polifônico de 8 vozes em tempo real desenvolvido por 2DaT, Layzer e Breeze (no KVR) e recentemente portado para Linux. OBXD está disponível nos formatos LV2 e VST e pode ser executado na maioria dos hosts, como Ardour, Carla, Jalv e Qtractor..

O OBXD inclui muitos recursos do famoso sintetizador de hardware OB-X dos anos 1980, além de algumas modificações (consulte os links para o manual abaixo). Há dois osciladores com controles de nível discretos e um Knob de nível de ruído, formas de onda saw e square independentes com controle de pulsewidth modulation; um Knob de cross-modulation, botão de sync e botão de step (para ajustar a afinação do oscilador em semitons, em vez de gradualmente). Estão incluídos botão de modo Unison (todas as notas da polifonia são empilhadas em uma única voz monofônica mais encorpada), spread, glide (portamento), afinação e controle de transposição de oitava. O Knob "Bright" controla a precisão das frequências mais altas do espectro sonoro, e o Knob "P Env" fornece envelope de afinação, conectado diretamente à seção de envelope do filtro.

## Recursos:
A seção de filtro do OBXD tem um filtro multimodo de 12 dB. Além dos controles tradicionais de cutoff, ressonância e profundidade do envelope, esta seção permite controlar o key follow, a interpolação de alta qualidade (aumenta ligeiramente o consumo de CPU) e o controle multimodo.

O knob "Multi" permite alternar entre as seguintes opções de filtro: low-pass (knob à esquerda), notch (posição intermediária) e high-pass (knob à direita). Ativar o botão "BP" fornece um filtro bandpass em vez de notch (knob na posição intermediária). O botão "24dB" oferece um filtro lowpass de 24 dB que se ajusta de 24 dB (knob à esquerda) a 6 dB (knob à direita).

Há um botão VAM (modo de alocação de vozes) que dá prioridade à última nota em vez da nota mais grave. A Seção de Controle inclui uma faixa de bend de 12 semitons (2 notas quando desligada) e um botão de bend apenas do oscilador 2. A taxa de Vibrato está conectada diretamente ao modwheel, mas também interage com o knob de taxa do LFO de maneiras interessantes. A Seção de Controle também inclui controles de sensibilidade à Velocity do filtro e da amplitude..

A seção LFO inclui formas de onda senoidal, quadrada e sample-and-hold, que podem ser combinadas. A seção de variação de voz oferece mais controle sobre o filtro, o glide e a amplitude, e o Voice Pan permite controlar a direção do pan de cada uma das 8 vozes de forma independente..

