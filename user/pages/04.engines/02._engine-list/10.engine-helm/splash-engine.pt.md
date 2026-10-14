---
title: Helm
id: helm
image: helm.jpg
description: Monophonic/polyphonic soft-synth based on subtractive synthesis
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-pr
  homepage:
  - 'yes'
date: 17:38 24-04-2020
subtitle: Sintetizador Analógico Virtual
splash:
  bg_image_landscape: helm-hero.png
  bg_image: helm-hero_small.png
media_thumb: helm.png
sitemap:
  lastmod: 07-05-2026 16:53
urls:
- urlLink: https://tytel.org/helm
  urlLabel: Website
- urlLink: http://linuxsynths.com/HelmPatchesDemos/helm.html
  urlLabel: LinuxSynths's page
- urlLink: https://github.com/mtytel/helm
  urlLabel: Source Code
audio:
- audioType: local
  audioFile: bitofbrush.ogg
  audioLabel: Bit of Brush
- audioType: local
  audioFile: cassiopeiaone.ogg
  audioLabel: Cassiopeia One
- audioType: local
  audioFile: girandoone.ogg
  audioLabel: Girando One
- audioType: local
  audioFile: supersawmodified.ogg
  audioLabel: Super Saw Modified
- audioType: local
  audioFile: dripping.ogg
  audioLabel: Dripping
- audioType: local
  audioFile: cassiopeiatwo.ogg
  audioLabel: Cassiopeia Two
- audioType: local
  audioFile: expresstwo.ogg
  audioLabel: Express Two
- audioType: local
  audioFile: pensivealientwo.ogg
  audioLabel: Pensive Alien Two
---
Helm é um sintetizador virtual monofônico/polifônico de código aberto e em tempo real, desenvolvido por Matthew Tytel em Tytel.org. Está disponível nas versões de 32 e 64 bits e pode ser executado como um plugin LV2 ou como um instrumento independente. Também inclui capacidade multiplataforma de carregar e salvar patches..

O que distingue o Helm de muitos outros sintetizadores de software é a grande flexibilidade no roteamento de modulação. Clicar em qualquer uma das fontes de modulação destacará todos os parâmetros que podem ser modulados. A quantidade de profundidade de modulação pode ser ajustada clicando e arrastando na área do parâmetro..

## Recursos:
O Helm consiste em dois osciladores de som rico, cada um oferecendo 11 formas de onda diferentes (com antialiasing). Uma função exclusiva de cross-modulation permite modular o timbre do oscilador esquerdo ou a fase do oscilador direito. Cada onda inclui ajustes finos e grosseiros (transposição) de detuning. O modo Unison está disponível para cada oscilador, assim como o controle da quantidade de spread de cada um (com base na quantidade de detuning). O botão 'h' adiciona um harmônico para cada voz desse oscilador. Além dos osciladores, há um suboscilador com modelagem de onda shuffle e uma fonte de ruído. As quatro fontes sonoras têm controles discretos de nível do sinal de amplitude.

A seção de filtro permite alternar entre os tipos de filtro lowpass, highpass, bandpass, high-shelf, low-shelf, band-shelf e allpass. Os controles deslizantes de cutoff e resonance são fornecidos ao longo dos eixos x e y do gráfico do filtro, respectivamente. Também está disponível um filtro formant muito útil com controle dos eixos X-Y, e estão incluídos dois LFOs monofônicos e um LFO polifônico..

O Helm também inclui uma função de arpejador muito versátil, com controles de gate, faixa de oitavas e padrão, além de uma seção de step-sequencer. Também oferece vários efeitos úteis, incluindo Reverb, stutter (reaplica parte do sinal de áudio e a repete), Delay, distorção e feedback. Os controles globais incluem pitchbend, quantidade de polifonia (até 32 vozes), portamento com opção de legato e rastreamento de Velocity. Um osciloscópio está localizado na área central superior, à direita do controle deslizante de volume principal..

O gerenciamento de presets é bastante simples. O botão 'Browse', próximo ao nome do preset atual, abrirá a janela de gerenciamento de presets, onde estão localizados os diretórios de presets. É possível procurar presets selecionando qualquer pasta ou digitando uma palavra-chave para pesquisar nessa mesma pasta. Os presets podem ser exportados separadamente ou diretamente para a pasta de presets desejada clicando em 'save.' Certifique-se de que o nome dado ao seu preset seja diferente dos nomes existentes no diretório ativo, pois o Helm não solicitará confirmação para substituir um preset existente com o mesmo nome.
