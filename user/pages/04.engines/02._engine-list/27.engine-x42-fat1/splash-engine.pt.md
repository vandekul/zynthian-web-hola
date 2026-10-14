---
title: X42 Autotune
media_order: x42-fat1.png
description: Auto-tuner plugin
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - fx-other
  - ucase-fx
date: 17:38 24-04-2020
subtitle: Autoafinador baseado no zita-at1 de Fons Adriaensens
splash:
  bg_image_landscape: x42-fat1-hero_small.png
  bg_image: x42-fat1-hero_small.png
media_thumb: x42-fat1.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-autotune
  urlLabel: X42 Autotune's Website
- urlLink: https://github.com/x42/fat1.lv2
  urlLabel: Source Code
---
x42-autotune (também conhecido como fat1.lv2) é um afinador automático baseado no zita-at1 de Fons Adriaensen.

O AT1 foi desenvolvido para corrigir a afinação de uma voz que está cantando (ligeiramente) desafinada. Ele funciona reamostrando e repetindo o sinal em loop e não inclui correção de formantes, portanto deve ser usado apenas para corrigir pequenos erros, e não para transpor uma música de fato. O AT1 provavelmente também pode ser usado em alguns instrumentos, mas foi projetado principalmente para cobrir a extensão vocal..

A afinação 'esperada' pode ser controlada por MIDI ou ser um conjunto fixo de notas.

As principais diferenças em relação ao zita-at1 são que a versão do plugin LV2 informa sua Latency ao host, salva o estado com a sessão e a entrada MIDI tem semântica de sidechain.. 

#### Modos de operação
AT1 retuna o sinal de entrada para a nota mais próxima na escala configurada. A escala consiste em até 12 notas (1 oitava), que são definidas e indicadas no teclado à esquerda. Por padrão, as 12 estão ativadas..

Clique com o botão esquerdo para ativar/desativar notas individuais, e clique com o botão direito no teclado para abrir uma caixa de diálogo e selecionar escalas maiores/menores comuns. O teclado também indica a nota atual selecionada pelo estimador de pitch..

Os seguintes modos de operação são compatíveis:

**Manual:** Use um conjunto fixo de notas (ignore MIDI). Clique com o botão esquerdo para alternar as notas..

**MIDI:** Responda às mensagens MIDI note on/off. Use a(s) nota(s) MIDI atualmente ativa(s). Se nenhuma estiver ativa, use qualquer nota da escala cromática..

**Automático (padrão):** Se nenhuma nota MIDI estiver ativa, use o conjunto estático e fixo de notas (clique com o botão esquerdo para alternar). As notas MIDI têm prioridade..

#### Parâmetros

**Seleção de canal MIDI:** Selecione o canal MIDI ao qual responder. Pode ser 'Omni' ou 1..16.

**Pânico MIDI:** Redefinir quaisquer notas MIDI 'presas.

**Afinação:** Define a frequência correspondente à altura de 'A', ou seja, a afinação desejada. Na maioria dos casos, o valor padrão será 440 Hz. O valor exato é exibido sempre que este controle é tocado e pode ser ajustado em incrementos de 0,2 Hz..

**Bias:** Normalmente, o estimador de pitch seleciona a nota ativada mais próxima do pitch medido. O controle Bias adiciona uma preferência pela nota atual - isso permite que ela fique mais desafinada do que ficaria de outra forma..

**Filtro:** Isso define a quantidade de suavização na correção de pitch enquanto a nota atual não muda. Se ela mudar, o filtro é ignorado e a correção salta imediatamente para o novo valor..

**Correção:** Determina quanto do erro de afinação estimado é corrigido. A correção total pode remover a expressão ou o vibrato..

**Offset:** Adiciona um deslocamento na faixa de +/- dois semitons à correção de afinação. Com o controle Correction definido como zero, o resultado é uma alteração constante da afinação..

**Medidor de erro de Pitch:** A barra abaixo do teclado indica o erro de afinação do sinal de entrada em relação à nota atual. O intervalo é de +/- um semitom..
