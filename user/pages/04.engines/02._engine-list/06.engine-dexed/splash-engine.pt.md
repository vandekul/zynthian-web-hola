---
title: Dexed
id: dexed
image: dexed.jpg
description: Sintetizador FM virtual inspirado nos clássicos Yamaha DX7 e TX7 dos
  anos 1980
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
Dexed é um sintetizador FM desenvolvido por Pascal Gauthier, da Digital Suburban. É um aplicativo ideal para importar, tocar e editar/gerenciar patches sysex tanto do clássico sintetizador Yamaha DX7 quanto do TX7..

O Dexed inclui seis operadores, fiéis à estrutura DX. Cada operador tem um indicador de nível. Os operadores podem ser organizados em vários algoritmos, indicados pelas caixas verdes. Os bancos de patches são chamados de "cartuchos" e há muitos (cerca de 32) incluídos no pacote de instalação. Selecionar um cartucho carrega os patches do banco correspondente.

O Dexed pode ser configurado para usar algumas das limitações matemáticas originais de um sintetizador DX. Isso não se aplica apenas ao DAC, mas também envolve a resolução em bits das ondas senoidais e a forma como a amplitude é aplicada a cada operador. Como tudo isso é experimental, haverá vários engines disponíveis para que seja possível compará-los facilmente..

O Dexed vem com 3 tipos de mecanismo:
+ **Moderno:** esta é a implementação original de 24-bit music-synthesizer-for-android.
+ **Marcar I:** Baseado na OPL Series, mas com uma resolução mais alta (as LUT são de 10 bits). O objetivo deste engine é ser o mais próximo possível do DX7 real..
+ **Série OPL:** esta é uma implementação experimental dos chips da família OPL submetidos a engenharia reversa. 8-bit. Tenha em mente que os envelopes ainda precisam de ajustes.

## Funcionalidades:
+ Multiplataforma (OS X, Windows ou Linux) e multiformato (VST, AU, LV2)
+ O motor de som music-synthesizer-for-android é estreitamente baseado nas características do DX7 original
+ 144 parâmetros do DX7 automatizáveis na DAW disponíveis em um único painel
+ Suporta totalmente mensagens sysex de entrada e saída do DX7; incluindo mudanças de controlador. Isso significa que você pode usar isto com um DX7/TX7 nativo como editor de patches e gerenciador de sysex
+ Cada operador tem um VU meter em tempo real para saber qual está ativo
+ Pode carregar/salvar quaisquer programas sysex do DX7/TX7. Também é possível salvar um único programa em um arquivo sysex diferente..
