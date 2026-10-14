---
title: X42 Compressor
media_order: x42-darc.png
description: Compressor de faixa dinâmica de áudio de uso geral
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - ucase-fx
  - fx-dynamics
content:
  items: '@self.modular'
date: 17:38 24-04-2020
subtitle: General Purpose Dynamic Audio Range Compressor
splash:
  bg_image_landscape: x42-darc-hero_small.png
  bg_image: x42-darc-hero_small.png
media_thumb: x42-darc.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-compressor
  urlLabel: X42 Compressor's Website
- urlLink: https://github.com/x42/darc.lv2
  urlLabel: Source Code
---
x42-compressor (também conhecido como darc.lv2) é um Compressor de Faixa Dinâmica de Áudio inspirado no zita-dc1 de Adriaensen. É um compressor descendente com um som muito agradável, que prioriza o fluxo de trabalho, expondo apenas um conjunto mínimo de controles. A compressão responde à potência do sinal (RMS), à sonoridade percebida pelos humanos, não ao pico digital relacionado ao meio-.

O compressor conta com auto makeup-gain, fixado em -10 dBFS/RMS. Isso mantém a sonoridade percebida em uma ampla faixa de thresholds e configurações de ratio..

Um recurso «Hold» distinto altera o tempo de release, que só é aplicado enquanto o sinal exceder o threshold. Em outras palavras: quando «Hold» está ativado, o ganho atual (ou a atenuação) é congelado quando o sinal cai abaixo do threshold.
Isto impede que o compressor adicione gain excessivo (por exemplo, module o noise-floor) e pode neutralizar o 'pumping' excessivo ao usar tempos de release curtos.

O plugin está disponível nas variantes mono e stereo. No caso desta última, ambas as entradas são somadas e a potência do sinal é calculada pela média para determinar o fator de Gain..

darc.lv2 é inspirado no algoritmo e na interface de usuário do zita-dc1 de Fons Adriaensen.

#### Parâmetros
**Input Gain:** Gain aplicado antes da detecção de nível ou de qualquer outro processamento. Observe que isso não é visualizado como deslocamento no eixo x na exibição da curva. O intervalo vai de -10 a +30dB em incrementos de 1dB (ajuste fino de 0.2dB).

**Threshold:** Nível do sinal (RMS) no qual o efeito de compressão é ativado. O intervalo é de -50 a -10dB em incrementos de 0.5dB (granularidade fina de 0.1dB).

**Proporção:** A quantidade de Gain ou atenuação a ser aplicada (dB/dB acima do threshold). Unity é mantido em -10dBFS/RMS (auto makeup-gain).

**Attack time:** Tempo que o sinal leva para ficar totalmente comprimido após ultrapassar o threshold.

**Release time:** Tempo mínimo de recuperação até o nível de sinal não comprimido após cair abaixo do limiar.

**Manter (botão de seleção):** Mantenha a atenuação atual quando o sinal ficar abaixo do limiar. Isso evita a modulação do piso de ruído e pode combater o 'pumping'.

#### Exibição
O medidor horizontal na parte inferior mostra o Gain aplicado ao sinal. O visor mostra o intervalo mínimo/máximo nos últimos 50ms. Valores à esquerda &lt; 0 significam que o sinal é atenuado (a entrada está mais alta que -10 dBFS/RMS).

O gráfico na parte superior visualiza o mapeamento de gain da entrada para a saída em dB. Quando «Hold» está ativado, a área onde o gain não é liberado fica sombreada em azul. A exibição também mostra o nível do sinal de entrada como uma área branca sombreada sob a curva, assim como o nível de saída atual (média de 50 ms) como um ponto..
