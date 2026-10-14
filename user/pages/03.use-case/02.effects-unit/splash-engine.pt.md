---
title: Effects Unit
content_position: center
date: 09:57 09-03-2020
margin_top: half
padding_top: none
padding_bottom: none
margin_bottom: none
role: default
body_classes: use-case custom-list
limit_reveal: '0'
media_order: always-with-me-always-with-you.wav,CleanGuitarByRodrigoAmaral.mp3,CrunchGuitarByRodrigoAmaral.mp3,ElectroKalimbaMisteryForestDreamByJofemodo.mp3,LeadGuitarByRodrigoAmaral.mp3,ui_screenshots_sl.png,use-cases-2-new.jpg,_DSC4534_01_web_use_case_fx_unit.jpg
subtitle: A melhor biblioteca de FXs grátis
background: _DSC4534_01_web_use_case_fx_unit.jpg
audio:
- audioType: local
  audioFile: portland_nights.ogg
  audioLabel: Portland Nights, by TKC (SooperLooper)
- audioType: local
  audioFile: always-with-me-always-with-you.ogg
  audioLabel: Always with me, always with you (Joe Satriani, played by Stojos)
- audioType: local
  audioFile: CleanGuitarByRodrigoAmaral.ogg
  audioLabel: Clean Guitar, by Rodrigo Amaral
- audioType: local
  audioFile: CrunchGuitarByRodrigoAmaral.ogg
  audioLabel: Crunch Guitar, by Rodrigo Amaral
- audioType: local
  audioFile: LeadGuitarByRodrigoAmaral.ogg
  audioLabel: Lead Guitar, by Rodrigo Amaral
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=QPQT5gviZbo
  videoLabel: ''
media_thumb: _DSC4534_01_web_use_case_fx_unit.jpg
splash:
  bg_image_landscape: _DSC4534_01_web_use_case_fx_unit.jpg
engines: true
tag: ucase-fx
---
O Zynthian pode ser usado como uma poderosa unidade de Efeitos de Áudio que permite criar uma cadeia de efeitos personalizada para cada entrada de áudio disponível.

O Kit oficial Zynthian V5 tem 2 entradas de áudio balanceadas com controlo de Gain independente que varia de -12db a +32dB. Leia as especificações completas [aqui](/technical-specifications). Pode ligar diretamente uma vasta gama de dispositivos de entrada, como microfones dinâmicos, guitarras elétricas & acústicas, piezos, line-in, etc. Se precisar de mais entradas de áudio, basta ligar a sua interface de áudio USB favorita e obter todos os canais adicionais de entrada/saída de áudio de que precisa.

O Zynthian suporta o padrão de plugins LV2 e inclui centenas de plugins de processamento de áudio. Pode combiná-los como quiser para esculpir o som, recriar paisagens vintage ou explorar novas texturas. Pode ter qualquer número de FX-chains com encaminhamento flexível, permitindo uma configuração tão simples ou complexa quanto desejar.

Se você é guitarrista, vai gostar dos neural modelers incluídos no zynthian:

+ [NAM](/engines/_engine-list/engine-nam)
+ [Ratatouille](/engines/_engine-list/engine-ratatouille)
+ [Aida-X](/engines/_engine-list/engine-aidax)
+ [Neural Rack](/engines/_engine-list/engine-neuralrack)

Eles oferecem emulação de última geração e precisa de equipamentos analógicos como amplificadores, distorção, fuzz, pedais de overdrive, etc. Literalmente milhares de modelos estão disponíveis gratuitamente em [Tone3000](https://tone3000.com), que está totalmente integrado com zynthian. Escolha um modelo para o seu equipamento favorito e obtenha o timbre que adora com alguns cliques.

Se gosta de looping, o SooperLooper está totalmente integrado, permitindo controlar até 6 loops independentes com gravação instantânea, overdub, reverse, multiply, replace, time-stretch, pitch-shift, e muito mais.

![Zynthian_UI_SooperLooper](ui_screenshots_sl.png)

O fluxo de trabalho de MIDI-learning é rápido e fácil. Pode ajustar os parâmetros que quiser a partir do seu controlador MIDI favorito. Os botões podem ser atribuídos a presets (program-change), e knobs e faders a parâmetros (CC).

Em relação à latency e ao jitter, a configuração padrão (<10ms) é suficiente para a maioria dos músicos, mas se procura uma latency extremamente baixa, a configuração de áudio pode ser ajustada.
