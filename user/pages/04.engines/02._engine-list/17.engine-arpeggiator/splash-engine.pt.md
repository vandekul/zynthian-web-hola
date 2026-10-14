---
title: Arpeggiator
media_order: arpeggiator.jpg
description: Um simples plugin de arpejador e padrões MIDI
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - effect
  - fx-midi
date: 17:38 24-04-2020
subtitle: Um plugin simples de arpejador e padrão MIDI
splash:
  bg_image_landscape: arpeggiator-hero.jpg
  bg_image: arpeggiator-hero_small.jpg
media_thumb: arpeggiator.jpg
urls:
- urlLink: https://github.com/BramGiesen/arpeggiator_LV2
  urlLabel: Source Code
---
Arpeggiator e um plugin de padrão MIDI desenvolvido para a plataforma MOD por Bram Giesen.

####Arpeggiator
O arpejador tem as seguintes opções:

**Opções de andamento:**
Também há algumas opções para definir o tempo do plugin. A primeira é o modo Free Running. Nesse modo, o tempo é controlado pelo controle BPM do plugin. Acima do controle BPM, há um controle Divisions. O plugin também pode ser sincronizado com o host.

**Modos do Arpeggiator:**
O arpejador tem os seguintes modos:
+ Acima
+ Baixo
+ Cima-Baixo
+ Cima-Baixo(alternativa)
+ Reproduzido
+ Aleatório

**Modos de Oitava:**
O arpejador tem um controle de extensão de oitavas. O arpejador pode iterar as notas recebidas por várias oitavas. Esse controle define o intervalo de oitavas que será percorrido em relação à altura original. A forma como essas oitavas serão adicionadas às notas originais é determinada pelo controle de modo de oitava..

####MIDI-padrão
O plugin MIDI-pattern pode ser usado para criar padrões rítmicos. O plugin recebe a nota de entrada e substitui a velocity da nota por um valor definido por um dos Faders do plugin. Como o plugin percorre os Faders, ele gera uma espécie de sequência rítmica. O controle CV do plugin pode ser usado para reiniciar a sequência.
