---
title: Ratatouille - Dual Neural Modeler
media_order: ratatouille.jpg
description: Modelador de redes neurais duplas. Combine 2 modelos neurais + IRs
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - ucase-fx
  - fx-distortion
date: 17:38 24-04-2020
subtitle: Combine 2 modelos neurais e 2 IRs
splash:
  bg_image: ratatouille-hero.jpg
  bg_image_landscape: ratatouille-hero.jpg
media_thumb: ratatouille.jpg
urls:
- urlLink: https://github.com/brummer10/Ratatouille.lv2
  urlLabel: Source Code
- urlLink: https://tone3000.com
  urlLabel: Ratatouille's Models in Tone3000
---
Ratatouille é um carregador e mixer de modelos neurais para Linux/Windows.
Pode carregar dois modelos, que podem ser arquivos *.nam (Neural Amp Modeler) ou *.json / .aidax (RTNeural) e usar
o controle "Blend" para combinar os dois modelos e misturá-los para simular o timbre específico que você está buscando.
Claro, você também pode carregar apenas um único arquivo de modelo e o controle "Blend" não fará nada.

Ratatouille usa processamento paralelo para os modelos neurais, então, carregar um segundo modelo neural não seria
notável na carga de DSP. Opcionalmente, Ratatouille poderia executar o processo completo em modo bufferizado.
Isso reduz ainda mais a carga de DSP. A latência resultante será informada ao host para que ele possa ser
compensada. Para sua informação, a Latency resultante será exibida na GUI.

O controle "Delay" poderia adicionar um pequeno atraso para superar problemas de faseamento, ou adicionar um pouco de cor/reverb ao som.
A tecla 'ctrl' ativa o ajuste fino para definir um delay com precisão de sample. Ratatouille também pode detectar a fase.
offset e compensá-lo internamente.

Para completar seu som, você pode carregar dois Impulse Response Files e mixá-los conforme suas necessidades. Arquivos IR podem ser
normalizados ao carregar, para que não influenciassem o loudness.

Ratatouille.lv2 oferece suporte à reamostragem quando necessário para corresponder à taxa de amostragem esperada dos modelos carregados. Ambos
os modelos e os IR Files podem ter expectativas diferentes em relação à taxa de amostragem.
#### Obtenha modelos de uma grande comunidade

[Tone3000.com](https://tone3000.com) tornou-se o lugar para obter os melhores modelos para Neural Amp Modeler, Aida-X e Proteus, enquanto se expande para oferecer suporte a mais plataformas no futuro. Não só modelos, mas nossa coleção de IRs também está crescendo e se tornando muito popular na plataforma.

#### Carregando arquivos

Na zynthian-ui, você pode carregar arquivos de modelo facilmente. Basta girar o knob atribuído ao controle de modelo e o seletor de arquivos será exibido..

