---
title: MDA JX-10
id: mda-jx10
description: Sintetizador virtual subtrativo inspirado em algumas máquinas Roland
  dos anos 1980
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
MDA JX-10 é um soft-synth subtrativo inspirado em algumas máquinas Roland dos anos 80. Consome pouquíssimos recursos e a qualidade do som é ótima..

Ele oferece dois osciladores (dente de serra e largura de pulso) que podem ser isolados ou combinados. A polifonia é obtida usando o ajuste do controle glide: zero para controle polifônico, máximo para controle monofônico. São fornecidos envelopes ADSR padrão para timbre (filtro) e amplitude. O Pitchbend está ajustado para um tom inteiro. A intensidade do LFO está ligada diretamente à roda de modulação. Adicionei uma demonstração para dar uma ideia do filtro LP muito rico (última demonstração acima).

No século XX, os plugins da Maxim Digital Audio (mda) estavam entre os primeiros plugins VST disponíveis para Windows. Eles têm fama de alta qualidade e baixo uso de CPU. Há vários anos, o código-fonte desses plugins foi lançado, e David Robillard portou os plugins mda para o formato LV2. A maioria dos plugins mda são efeitos, mas também há quatro instrumentos: DX10, JX10, Piano e ePiano.

## Recursos:
+ 2 osciladores fixos (Mix selecionável entre 100:0 e 50:50) & Ruído
+ Afinação do oscilador +-24 semitons
+ Filtro ressonante (Controlável por Env/LFO/Velocity)
+ ADSR para VCF & Amp/Env
+ Glide - 6 modos (Poly, P-Legato, P-Glide, Mono, M-Legato, M-Glide)
+ LFO
+ Vibrato
+ Afinação do sintetizador +-2 oitavas
+ Baixo uso da CPU
+ Banco padrão de 52 patches
+ Sem GUI
