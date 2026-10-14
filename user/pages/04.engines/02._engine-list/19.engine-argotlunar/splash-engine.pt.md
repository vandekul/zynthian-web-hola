---
title: Argotlunar
media_order: argotlunar.png
description: Um granulador de linha de atraso em tempo real para criar transformações
  surreais.
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
  homepage:
  - 'yes'
date: 17:38 24-04-2020
subtitle: Granulator
splash:
  bg_image_landscape: argotlunar-hero.png
  bg_image: argotlunar-hero_small.png
media_thumb: argotlunar.png
audio:
- audioType: soundcloud
  audioLink: https://soundcloud.com/t800infiltrator/argotlunar
  audioLabel: Argotlunar, by t800infiltrator
- audioType: soundcloud
  audioLink: https://soundcloud.com/ioflow/20110912a
  audioLabel: 20110912, by ioflow
- audioType: soundcloud
  audioLink: https://soundcloud.com/pneuman/rpm-2012-lagrange
  audioLabel: 'RPM 2012: lagrange, by pneuman'
urls:
- urlLink: http://mourednik.github.io/argotlunar/)
  urlLabel: Argotlunar's Website
- urlLink: https://www.kvraudio.com/product/argotlunar-by-michael-ourednik
  urlLabel: KVRAudio's Page
- urlLink: https://github.com/mourednik/argotlunar
  urlLabel: Source Code
---
Argotlunar é uma ferramenta para criar transformações surreais de fluxos de áudio. Especificamente, é um granulator de linha de atraso em tempo real. Ele desintegra um fluxo de áudio em Samples curtos (grãos). Cada grão pode ter configurações aleatórias de amplitude, panning, duração, delay, pitch, glissando, filtro e envelope. A saída de todos os grãos é mixada em um fluxo que pode ser realimentado na entrada principal.

Os parâmetros relacionados ao tempo podem ser sincronizados ao tempo do host, para criar texturas rítmicas e pulsantes. Os parâmetros relacionados à altura podem ser quantizados para criar efeitos harmônicos e melódicos. Feedback pode criar sons caóticos, densamente sobrepostos e distorcidos..

A maioria dos parâmetros pode ser correlacionada. Exemplos:

+ Frequência de corte do filtro correlacionada com o pitch: frequência de corte mais alta para grãos com pitch mais alto, e vice-versa.
+ Duração dos grãos correlacionada com panning: Grãos com duração mais curta posicionados no centro do campo estéreo, e grãos com duração mais longa posicionados amplamente no campo estéreo.

Argotlunar é um software gratuito. Licenciado sob a GPL v2.

#### Detalhes:

+ Os parâmetros relacionados ao tempo podem ser sincronizados com o andamento do host.
+ Os parâmetros relacionados ao Pitch podem ser quantizados para vários acordes/escalas.
+ Até três pares de parâmetros podem ser correlacionados.
+ Envelopes de grão raised-cosine-bell, parabólica e triangular, com formato ajustável.
+ A transposição é interpolada por spline para reduzir o aliasing.
+ 12dB state variable filter (HP/BP/LP/Notch).
+ Comb filter.
