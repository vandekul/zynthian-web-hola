---
title: setBfree
id: setbfree
description: Emulador Hammond B3 e Leslie altamente personalizável
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-add
  - ucase-kb
  - synth-emu
  - synth-phy
  homepage:
  - 'yes'
date: 17:38 10-03-2020
subtitle: Tonewheel Organ Emulator
splash:
  bg_image: setbfree-hero_small.jpg
  bg_image_landscape: setbfree-hero.jpg
media_thumb: setbfree.jpg
sitemap:
  lastmod: 07-05-2026 14:23
urls:
- urlLink: http://setbfree.org
  urlLabel: Project's Website
- urlLink: http://www.linuxsynths.com/SetBfreePatchesDemos/setbfree.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/pantherb/setBfree
  urlLabel: Source Code
video:
- videoType: vimeo
  videoLink: https://vimeo.com/130633814
  videoLabel: A rendition of Jimmy Smith's The Cat
audio:
- audioType: local
  audioFile: georgia_on_my_waltzin_mind.ogg
  audioLabel: Georgia on my waltzin mind, by TKC (MDA EPiano + setBfree)
- audioType: local
  audioFile: setBfreeDrawbarsManipulationByBaggypants.mp3
  audioLabel: Hammond Drawbars Manipulations, by Baggypants (setBfree)
- audioType: local
  audioFile: RhodesHammondByHumi.mp3
  audioLabel: Rhodes & Hammond, by Humi
---
setBfree é um sintetizador de software controlado por MIDI, projetado para imitar o som e as características dos órgãos eletromecânicos e dos dispositivos de modificação de som que trouxeram fama mundial aos nomes e produtos de Laurens Hammond e Don Leslie.

## Recursos:
setBfree é um *Kit de Construção de Órgão Tonewheel*, um modelo físico com mais de 1000 parâmetros configuráveis. Como em um B3 real, é possível 'abri-lo' e ajustar os parâmetros desde o estado impecável de '53 (padrão) até um estado desgastado, com tubos empoeirados dos anos 80.

Ao ser executado no zynthian, o setBfree oferece 7 configurações de teclado predefinidas que combinam manuais e pedaleira.:
+ **Superior:** 1 teclado (1 x MIDI channel)
+ **Superior + Inferior:** 2 teclados (2 x canais MIDI)
+ **Superior + Pedais:** 2 teclados (2 x canais MIDI)
+ **Superior + Inferior + Pedais:** 3 teclados (3 x canais MIDI)
+ **Dividir inferior/superior:** 1 teclado (1 x canal MIDI)
+ **Pedais divididos/Superior:** 1 teclado (1 x canal MIDI)
+ **Dividir Pedais/Inferior/Superior:** 1 teclado (1 x canal MIDI)

No zynthian, o setBfree também oferece 4 tipos de forma de onda para o gerador de tone-wheel.:
+ **Seno:** Som Hammond
+ **Quadrado:** Som de órgão combo
+ **Triângulo:** Som de órgão combo
+ **Dente de serra:** Som de órgão combo

Todos os controles podem ser atribuídos a MIDI-CC conforme necessário por meio do mecanismo MIDI-learn..

