---
title: x42 MIDI-filters
media_order: x42-midifilter.jpg
description: Uma poderosa coleção de filtros e ferramentas MIDI simples
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - ucase-pr
  - effect
  - fx-midi
date: 17:38 24-04-2020
subtitle: Uma coleção poderosa de filtros e ferramentas MIDI simples
splash:
  bg_image_landscape: x42-midifilter-hero.jpg
  bg_image: x42-midifilter-hero_small.jpg
media_thumb: x42-midifilter.jpg
urls:
- urlLink: http://x42-plugins.com/x42/x42-midifilter
  urlLabel: x42 MIDI-filter's Website
- urlLink: https://github.com/x42/x42-plugins
  urlLabel: Source Code
---
Uma coleção de mais de 25 filtros de dados MIDI no formato de plugin LV2, desenvolvida e mantida por [Robin Gareus](http://x42-plugins.com). Os filtros seguem estas regras básicas:
+ Uma entrada MIDI, uma saída MIDI (sem geradores, sem sintetizadores)
+ Sem interface gráfica personalizada, apenas entradas de controle
+ Todos os controles podem ser automatizados, os plugins lidam com alterações dinâmicas de parâmetros.
+ Todos os plugins reportam sua latency ao host (para a maioria deles é zero)
+ DRY (princípio de Não Se Repetir) - filtros simples que podem ser combinados em uma rede
+ Autodocumentado: descrição integrada e documentação da porta de controle

##Visão geral
**CC2Note:** Converta mensagens MIDI control change em mensagens note-on/off. Note off é enfileirado 10 msec depois..

**Filtro de Canal MIDI:** Filtro simples de canal MIDI. Apenas os dados dos canais selecionados podem passar. Este filtro afeta apenas midi-data relevantes para o canal (ou seja, note-on/off, control e program changes, key e channel pressure e pitchbend). MIDI-SYSEX e Realtime message são sempre encaminhadas. Este plugin destina-se ao uso ao vivo, com controle por botão. Consulte também o filtro 'MIDI Channel Map.

**Mapa de Canais:** Reescrever número do canal MIDI. Este filtro afeta apenas dados MIDI relevantes para o canal (ie note-on/off, control and program changes, key and channel pressure and pitchbend). MIDI-SYSEX e mensagens Realtime são sempre transmitidas sem modificações..

**MIDI Aplicar escala:** Filtra eventos note-on/off dependendo da escala musical. Se a tonalidade for alterada, eventos note-off são enviados para todas as notas ativas fora da tonalidade..

**Filtro de eventos MIDI:** Filtro de mensagens estilo Notch. Suprime mensagens específicas. Para uma faixa flexível de note-on/off, consulte também 'keyrange' e 'velocityrange'.

**Filtro de faixa de teclas MIDI:** Este filtro permite definir um intervalo de notas MIDI permitidas. Eventos note-on/off fora do intervalo permitido são descartados. Se o intervalo mudar, eventos note-off são enviados para as notas atualmente ativas que acabarem ficando fora do intervalo válido..

**Divisão de teclado MIDI:** Altere o número do canal MIDI dependendo da nota. O plugin mantém o controle das notas MIDI transpostas e envia os eventos note-off correspondentes caso o intervalo seja alterado enquanto uma nota estiver ativa. No entanto, o split-point e as atribuições de canal de cada manual só devem ser alterados quando nenhuma nota estiver sendo tocada..

**MapCC:** Altere uma mensagem de controle para outra -- combine com scalecc para modificar/escalar o valor real.

**Transposição das teclas MIDI:** Mapa flexível de 12 tons. Permite mapear uma nota dentro de uma oitava para outra nota na mesma faixa de oitava +- 12 semitones. Como alternativa, as notas também podem ser mascaradas (desativadas). Se duas teclas forem mapeadas para a mesma nota, os eventos correspondentes de Note-on/off serão mantidos ativos: somente o primeiro Note-on e o último Note-off serão enviados. As configurações podem ser alteradas dinamicamente: os eventos Note-on/off serão enviados de acordo..

**Acorde MIDI:** Harmonizer - cria acordes a partir de uma única nota (fundamental) em uma determinada escala musical. A escala, assim como os intervalos, pode ser automatizada livremente (os acordes atualmente mantidos serão alterados). Os Note-ons são travados; para acordes múltiplos/combinados, apenas um único note-on/off será acionado durante a duração dos acordes combinados. Se for recebida uma nota fora da escala, ela será transmitida sem alterações - nenhum acorde será atribuído. Nota: Combine este efeito com o 'MIDI
Use o filtro Enforce Scale' para eliminá-los.

**MIDI Delayline:** Linha de delay MIDI. Atrase todos os eventos MIDI por um tempo definido em BPM e batidas. Se o delay incluir um fator aleatório, este efeito garante que os eventos note on/off permaneçam sempre em sequência, independentemente da aleatorização..

**Uníssono de canal MIDI:** Duplicar eventos MIDI de um canal para outro.

**MIDI Strum:** Um efeito de arpejo MIDI destinado a simular o dedilhado de um instrumento de cordas (por exemplo, guitarra). Um acorde é 'coletado' e as notas individuais do acorde são reproduzidas espaçadas ao longo do tempo. O 'Note Collect Timeout' permite que o efeito seja tocado ao vivo com um teclado MIDI; ele compensa o fato de uma pessoa não pressionar as teclas exatamente ao mesmo tempo. Se o efeito for usado com um sequenciador que pode enviar acordes com todas as notas note-on exatamente ao mesmo tempo, ele deve ser definido como zero.

**MIDI Transposição cromática:** Transposição cromática de notas MIDI e key-pressure. Se um ponto de inversão for definido, a escala é espelhada em torno desse ponto antes da transposição. As notas que ficarem fora do intervalo válido 0..127 são descartadas.
MIDI Monophonic Legato	Segure uma nota até que a próxima chegue. -- Toque a mesma nota novamente para desligá-la..

**MIDI Remover Active Sensing:** Filtro para bloquear todos os eventos de active sensing. As mensagens de active sensing são mensagens MIDI opcionais e destinam-se a ser enviadas repetidamente para informar um receptor de que uma conexão está ativa; no entanto, elas podem sobrecarregar o canal MIDI ou ser gravadas inadvertidamente ao despejar dados MIDI brutos em disco..

**MIDI Bloqueador de duplicatas:** Bloqueador de duplicatas MIDI. Filtra mensagens de note on/off sobrepostas e duplicadas.

**Note2CC:** Converta mensagens MIDI note-on em mensagens de control change.

**Alternar nota MIDI:** Alternar notas: toque uma nota para ativá-la, toque-a novamente para desativá-la.

**MIDI N-Tap Delay:** Este efeito repete as notas N vezes. Onde N é um número fixo ou ilimitado enquanto uma determinada tecla estiver pressionada. As variáveis BPM e delay-time permitem ramps de tempo. A cada repetição, o ajuste de Velocity especificado é somado ou subtraído, e o resultado é limitado entre 1 e 127..

**MIDI Thru:** MIDI All pass. Este plugin não tem efeito e destina-se a servir de exemplo..

**MIDI Quantização:** Quantização de eventos ao vivo. Este filtro alinha os eventos MIDI recebidos a uma grade de tempo fixa. Como o efeito opera em um fluxo ao vivo, ele introduzirá latência: os eventos serão atrasados até o próximo 'tick'. Se o host do plugin fornecer informações BBT, os eventos serão alinhados ao relógio do host; caso contrário, o efeito funcionará com seu próprio tempo.

**Randomização de Velocity MIDI:** Aleatorizar a Velocity das notas MIDI (tanto note on quanto note off).

**Escalar valor de CC:** Modificar o valor (byte de dados) de uma mensagem de control change MIDI.

**MIDI Sostenuto:** Este filtro atrasa mensagens note-off por um determinado período, emulando um pedal sostenuto de piano. Quando o pedal é solto, as mensagens note-off que estão na fila são enviadas imediatamente. O tempo de atraso pode ser alterado dinamicamente; as alterações também afetam as mensagens note-off que ainda estão na fila..

**Filtro de intervalo de Velocity MIDI:** Filtra eventos MIDI note-on de acordo com Velocity. Eventos note-on fora do intervalo permitido são descartados. Se um Note-off for recebido para uma nota que foi filtrada anteriormente, ele também não é encaminhado. Se o intervalo permitido mudar, eventos note-off são enviados às notas atualmente ativas que passam a ficar fora do intervalo válido..

**Ajuste de MIDI Velocity:** Altere a Velocity dos eventos de nota com controles separados para Note-on e Note-off. O intervalo de entrada 1 - 127 é mapeado para o intervalo entre Min e Max. Se Min for maior que Max, o intervalo é invertido. O valor de offsets é adicionado ao evento de Velocity após o mapeamento do intervalo Min/Max.
