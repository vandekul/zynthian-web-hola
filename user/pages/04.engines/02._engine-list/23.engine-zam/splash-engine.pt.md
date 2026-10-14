---
title: ZAM Plugins
media_order: redwave.jpg
description: Uma coleção de plugins para processamento de som
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - fx-delay
  - fx-mod
  - fx-other
  - ucase-fx
  - fx-eq
  - fx-filter
  - fx-dynamics
  - fx-distortion
date: 17:38 24-04-2020
subtitle: Coleção de plugins
splash:
  bg_image_landscape: redwave-hero.jpg
  bg_image: redwave-hero_small.jpg
media_thumb: redwave.jpg
audio:
- audioType: local
  audioFile: angie-20141010_follow.ogg
  audioLabel: Follow, by Angie Hudson (2013)
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=MGErjKRu_dQ
urls:
- urlLink: http://www.zamaudio.com/
  urlLabel: ZamAudio's Website
- urlLink: http://github.com/zamaudio/zam-plugins
  urlLabel: Source Code
---
Zam-plugins é uma coleção de plug-ins de áudio LV2/LADSPA/VST/JACK para processamento de som, desenvolvidos internamente na ZamAudio. As configurações padrão e quase todos os controles deslizantes são calibrados para os intervalos padrão.

Um enorme agradecimento a falktx por escrever o Distrho Plugin Framework. Isso me permitiu criar estas GUIs para zam-plugins de forma rápida e organizada. Agradeço também a mira, nphilipp, adi, edogawa e Haskellfant, que ajudaram a empacotar o software para diferentes distribuições.!

## Visão geral

#### ZaMaximX2
Um dos melhores plugins da série, funciona como um limitador brickwall para masterização em seu estado padrão, mas também pode ser ajustado para elevar o nível médio como um maximizador estéreo sem nunca clipar. Soa musical mesmo com um tratamento agressivo. (Baseado no DSP encontrado em um artigo da DAFX’02).

#### ZamAutoSat
Um plugin de saturação automática, conhecido por proporcionar um nivelamento suave aos canais de microfone ao vivo.
Você pode aplicar este plugin generosamente sem afetar o timbre..

#### ZamComp
Um poderoso canal de compressor mono. Adiciona bastante corpo a um bumbo ou caixa com as configurações certas.

#### ZamCompX2
Versão estéreo do ZamComp com controle de knee slew.

#### ZamEQ2
Equalizador paramétrico de duas bandas com circuitos shelving de agudos e graves.

#### ZamGEQ31
Equalizador gráfico de 31 bandas, bom para fazer EQ de espaços ao vivo, remover ruídos indesejados de uma faixa etc..

#### ZamHeadX2
Plugin de filtragem acústica HRTF para som direcional.

#### ZamPhono
Uma coleção de filtros phono para restaurar discos de vinil, ou preparar para cortar novos deles.

#### ZamGate
Plugin Gate para ducking de sons de baixo ganho.

#### ZamGateX2
Plugin Gate para ducking de sons com baixo Gain, versão estéreo.

#### ZamTube
Efeito de distorção brutal. Filtro digital de ondas com modelo físico de um estágio amplificador de válvula triodo, com tone stacks modelados a partir de amplificadores de guitarra reais (agradecimentos a D. Yeh et al).

#### ZamDelay
Uma unidade simples de delay com feedback, recurso de sincronização ao BPM do host e filtro.

#### ZamDynamicEQ
Um equalizador dinâmico que altera seu Gain com base na detecção de uma faixa estreita de frequências. Pode ser ajustado para alterar outras faixas de frequência em tempo real..

#### ZaMultiComp
Compressor multibanda mono, com 3 bandas ajustáveis.

#### ZaMultiCompX2
Carro-chefe dos zam-plugins: versão estéreo do ZaMultiComp, com controles de threshold individuais para cada banda e visualização em tempo real das curvas de compressão.
