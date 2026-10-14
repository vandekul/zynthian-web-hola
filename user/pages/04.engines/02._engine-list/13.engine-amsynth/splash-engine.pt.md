---
title: AMSynth
id: amsynth
description: Sintetizador de modelagem analógica que usa síntese subtrativa tradicional
  para criar sons
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-pr
date: 17:38 24-04-2020
subtitle: Sintetizador Analógico Virtual
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
O AmSynth, ou sintetizador de modelagem analógica, desenvolvido e mantido por Nick Dowell, usa uma abordagem tradicional de síntese subtrativa para criação de som e pode ser executado como instrumento independente ou como plug-in DSSI ou LV2 em uma estação de trabalho de áudio digital, como Ardour ou Qtractor..

AmSynth é um sintetizador virtual polifônico/monofônico em tempo real, com sensibilidade ao toque e capacidade de controle MIDI completa. Inclui dois osciladores, cada um capaz de gerar as formas de onda clássicas: de quadrada a pulso, de triangular a dente de serra, senoidal, ruído e sample-and-hold. O oscilador 2 pode ser sincronizado com o oscilador 1 e também pode ser desafinado: ajuste fino (mais ou menos 4 semitons), desafinação grossa (mais ou menos 12 semitons) e desafinação de oitava (menos três ou mais quatro). Sincronizar os osciladores e ajustar a desafinação em semitons produz alguns timbres interessantes, semelhantes a FM. Um knob de mixagem dos osciladores permite controlar o equilíbrio entre os dois, e girá-lo totalmente para a esquerda ou para a direita isola um ou outro. Também há um knob de nível de Ring modulation..

Um envelope ADSR padrão é fornecido para as seções de amplitude e filtro. Os knobs de sensibilidade à Velocity do filtro e da amplitude estão localizados no canto inferior direito da GUI..

A seção de filtro inclui 9 tipos de filtro: passa-baixa, passa-alta, passa-banda e notch (cada um com configurações de 12dB e 24dB), além de uma opção para ignorar o filtro. Um knob de intensidade do envelope controla a profundidade do efeito do filtro, em valores positivos e negativos. Keyfollow, ressonância e cutoff do filtro estão incluídos nesta seção..

O AmSynth tem um LFO. Esse LFO pode ficar completamente desligado ou ser configurado para afetar o pitch, o filtro e a amplitude, ou qualquer combinação dos três. O parâmetro de pitch pode ser roteado para qualquer um dos osciladores ou para ambos. As formas de onda incluem: quadrada, triangular, senoide, sample-and-hold, saw-up, saw-down e ruído.

Junto com os controles principais de volume e drive (distorção), o amSynth inclui um reverb do tipo plate, um knob de tamanho para ajustar a largura, knobs de estéreo e damping. Os recursos adicionais da versão mais recente incluem controle mono/legato/poly e uma ampla capacidade de portamento, que agora pode ser definida para o modo "always" ou "legato". Também há controle de panning, e as teclas de atalho "ctrl+r" randomizam as configurações..

Ajustes finos do knob podem ser feitos mantendo pressionada a tecla shift enquanto os knobs são movidos..

O AmSynth tem capacidade de polifonia ilimitada, embora 16 notas de polifonia sejam geralmente suficientes. A função Pitchbend pode ser selecionada em semitons, até 2 oitavas. Escalas microtonais também podem ser carregadas agora..

## Recursos:
+ Osciladores duplos (senoidal / serra / quadrada / ruído) com hard sync
+ filtro ressonante de 12/24 dB/oct (passa-baixas / passa-altas / passa-banda / notch)
+ Modos de teclado mono / poly / legato
+ Geradores de envelope ADSR duplos (filtro e amplitude)
+ LFO que pode modular os osciladores, o filtro e a amplitude
+ Distorção e reverb
