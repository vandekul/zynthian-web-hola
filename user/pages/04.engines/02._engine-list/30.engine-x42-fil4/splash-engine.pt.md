---
title: X42 Equalizer
media_order: x42-fil4.png
description: 4 band parametric equalizer
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - fx-filter
content:
  items: '@self.modular'
date: 17:38 24-04-2020
subtitle: 4 band Parametric Equalizer
splash:
  bg_image_landscape: x42-fil4-hero_small.png
  bg_image: x42-fil4-hero_small.png
media_thumb: x42-fil4.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-eq
  urlLabel: X42 Equalizer's Website
- urlLink: https://github.com/x42/fil4.lv2
  urlLabel: Source Code
---
x42-eq (também conhecido como fil4.lv2) é um equalizador paramétrico de 4 bandas com shelving adicional de graves e agudos, além de filtros passa-altas e passa-baixas. O equalizador foi projetado para corresponder ao Gain analógico equivalente, com Latency zero e sem deslocamento de fase ao se aproximar da frequência de Nyquist. Ele não tem uma resposta comprimida, frequentemente chamada de som digital. O x42-eq apresenta displays integrados de espectro e espectrograma (cascata) em tempo real, um display de peak-hold que pode ser redefinido pelo usuário e um controle de Gain de saída..

fil4.lv2 é baseado nos fil-plugins LADSPA de Fons Adriaensen.

#### Controles de espectro
Os controles do espectrograma ficam no lado inferior direito,

**Desligado:** Não exiba o espectro<br>
**Especificação:** Exibir um espectro ponderado de ruído rosa (1/oitava.<br>
**Hist:** Exibição do espectrograma; visualização do histórico (linhas brancas tracejadas indicam alteração das configurações)<br>
**Pre:** Analise a entrada<br>
**Publicação:** Analise a Saída Processada<br>

A Stereo Variant tem uma opção para analisar a soma (All) ou apenas o canal Left ou Right. O knob de Gain permite alinhar o espectro, veja a escala no lado direito do visor.

**Alto:** Distorção de altas frequências, resolução aumentada nas frequências mais baixas.<br>
**Med:** Medium Frequency Warping<br>
**Latido:** Sem Frequency Warping, enfatize as frequências altas<br>

**Rpd:** Decaimento rápido (~~20ms)<br>
**Rápido:** Decaimento rápido (~~80ms)<br>
**Mod:** Tempo de decaimento moderado (~~200ms)<br>
**Lento:** Decaimento lento (~~2seg)<br>
**Ns.:** Medição de ruído (~20sec)<br>

#### Especificações do filtro
Fil4 consiste em quatro filtros ressonantes de segunda ordem que usam um filtro lattice no estilo Regalia-Mitra, que tem a ótima propriedade de ser estável mesmo enquanto os parâmetros estão sendo alterados..

Os filtros high/low-shelf são filtros biquad/IIR padrão de 2ª ordem.

Passa-altas e passa-baixas são filtros ressonantes de 2ª ordem (-12dB/oitava):

+ Qualidade 0.0: -6dB na frequência de corte (sem feedback)
+ Qualidade 0.7: -3dB at cutoff-freq
+ Qualidade 1.0: 0dB em cutoff (ressonante)

Todos os filtros têm zero latency com ganho analógico equivalente correto em Nyquist (o deslocamento de fase do sinal na frequência de Nyquist é zero).

