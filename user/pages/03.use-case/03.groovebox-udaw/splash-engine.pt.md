---
title: Groovebox / Micro-DAW
content_position: center
date: 09:57 09-03-2020
margin_top: half
padding_top: none
padding_bottom: none
margin_bottom: none
role: default
body_classes: use-case custom-list
limit_reveal: '0'
subtitle: Uma ferramenta de produção robusta
background: _DSC4578_02_web_use_case_production.jpg
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=fVEJqswo_1s
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=4wJpog5Z5qQ
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=vpkRrzg_h-Q
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=3arcgoKu9T4
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=-4YbrNM4zRo
audio:
- audioType: local
  audioFile: zcontest23-01-Zynesthesia_by_kosro.ogg
  audioLabel: Zynesthesia, by Kosro
- audioType: local
  audioFile: zcontest23-02-Origin_by_danielwine.ogg
  audioLabel: Origin, by Daniel Wine
- audioType: local
  audioFile: xcontest23-01-The_seas_of_Mars_by_Nicolaz.ogg
  audioLabel: The Seas of Mars, by Nicolaz
- audioType: local
  audioFile: zcontest23-03-Everything_must_flow_by_Nicolaz.ogg
  audioLabel: Everything must flow, by Nicolaz
- audioType: local
  audioFile: xcontest23-03-westernbrassband_by_ivaneo.ogg
  audioLabel: Western Brass Band, by Ivaneo
- audioType: local
  audioFile: ZynthianicTranceByJtunes.ogg
  audioLabel: Zynthianic Trance, by JTunes
- audioType: local
  audioFile: PPG13ByCanTrell.ogg
  audioLabel: PPG13, by Can Trell
- audioType: local
  audioFile: TheWeightByBaggyPants.ogg
  audioLabel: The Weight, by BaggyPants
- audioType: local
  audioFile: MonsieurTheActorByRomanGeneralov.ogg
  audioLabel: Monsieur The Actor, by R.Generalov
- audioType: local
  audioFile: VasculabCOMPDByCanTrell.ogg
  audioLabel: Vasculab COMPD, by Can Trell
media_thumb: ''
splash:
  bg_image_landscape: _DSC4578_02_web_use_case_production.jpg
engines: true
tag: ucase-pr
---
O Zynthian é também uma ferramenta poderosa para produção. Inclui mais de 100 synth-engines com milhares de presets e mais de 1000 efeitos de áudio & MIDI.

![zui_vangelis_add_chain](zui_vangelis_add_chain.png)

É totalmente multitimbral, sendo capaz de gerir até 16 cadeias de instrumentos e qualquer número de efeitos de áudio, processadores midi e mixbuses. Suporta o padrão LV2-plugin, pelo que a lista de processadores disponíveis é enorme e está sempre a crescer.

![01-zui_vangelis_mixerer](01-zui_vangelis_mixer.png)
![05-zui_vangelis_chainman](05-zui_vangelis_chainman.png)

Inclui um poderoso step-sequencer com funcionalidades para atuação ao vivo e composição de músicas:

+ alta resolução (1920 ppqn)
+ editor de padrões (eventos & blocos)
+ copiar/colar & transpor blocos
+ copiar/colar padrões
+ captura ao vivo
+ desfazer/refazer
+ opções avançadas de stutter:  speed, duration, volume-fade, speed-ramp
+ opções de repetição & aleatorização: probabilidade de reproduzir/saltar, frequência de reproduzir/saltar, etc. 
+ automação de parâmetros
+ muito mais!

![zui_vangelis_pated_stuter](zui_vangelis_pated_stuter.png)

Também inclui um leitor avançado de clips de áudio capaz de carregar qualquer formato de ficheiro de áudio, aplicar time-stretch e sincronizar Samples de áudio, etc.

![zui_clippy_wave](zui_clippy_wave.png)

A vista do launcher permite combinar padrões do step sequencer e clips de áudio, iniciando-os e parando-os de forma sincronizada, permitindo diferentes modos  para reprodução única, loops, etc. As frases permitem estruturar as suas músicas, automatizando alterações de tempo & compasso, definindo loops e secções CODA, etc.

![02-zui_vangelis_launcher](02-zui_vangelis_launcher.png)

Uma lista crescente de controladores midi suportados pode ser usada para controlar o zynthian sem configuração prévia, totalmente plug & play:

+ **Novation:** LaunchPad Mini / Pro / X. LaunchKey Mini, etc.
+ **Akai:** APC Key-25, APC 40, MPK mini, MIDI Mix
+ **Korg:** nanoKONTROL
+ **Behringer:** Motör 61 / 49
+ **Arturia:** Keylab 61
+ **Teenage Engeneering:** OP1
+ **Worlde:** Mini
+ **Foxtex:** Mixtab
+ **Mackie (MCU)**

[Clique aqui](https://wiki.zynthian.org/index.php/Supported_MIDI_controllers) para consultar a lista completa de controladores MIDI suportados.

O Zynthian também pode ser controlado a partir de DAWs e sequenciadores externos. Tem muitas opções de ligação:

+ conectores MIDI DIN-5 legados (IN / OUT / THRU)
+ 4 x portas USB-A (host)
+ 1 x portas USB-B (dispositivo)
+ Conectividade de rede Ethernet e WIFI

e também suporta os protocolos de rede MIDI mais amplamente utilizados, como:

+ NetUMP (MIDI 2.0)
+ RTP (Apple MIDI)
+ QMidiNet (IP-multicast)
+ TouchOSC (tablet como controlador MIDI)

E há muito mais:

+ midi-learning fácil com intervalo de valores e escala
+ encaminhamento flexível de áudio & midi
+ mixbuses
+ gravador de áudio multipista
+ gravador e reprodutor midi
+ midi-filter baseado em regras
+ PureData & Organelle patches
+ Integração MOD-UI

Em relação à Latency e ao Jitter, a configuração padrão (<10ms) é suficiente para a maioria dos músicos, mas se procura uma Latency extremamente baixa, a configuração de áudio pode ser ajustada.

<!--
<small>Trip Jazz Demo, by Humi</small>
![TripJazzdemoByHumi.mp3](TripJazzdemoByHumi.mp3?preload=metadata)
<small>BlueBox is Roughly Great, by Nicolaz</small>
![BlueBoxIsRoughlyGreatByNicolaz.mp3](BlueBoxIsRoughlyGreatByNicolaz.mp3?preload=metadata)
<small>RTPMidi Celebration, by JTunes</small>
![RTPMidiCelebrationByJTunes.mp3](RTPMidiCelebrationByJTunes.mp3)
<small>Epic EnteR, by R.Generalov</small>
![EpicEnteRByRomanGeneralov.mp3](EpicEnteRByRomanGeneralov.mp3)
<small>Electro, by Humi</small>
![ElectroByHumi.mp3](ElectroByHumi.mp3)
<small>Mr Tchaikovsky, by sm7x7</small>
![MrTchaikovskyBySm7x7.mp3](MrTchaikovskyBySm7x7.mp3)
<small>Of Course My Lord, by R.Generalov</small>
![OfCourseMyLordByRomanGeneralov.mp3](OfCourseMyLordByRomanGeneralov.mp3)
<small>First Real Synth, by Can Trell</small>
![FirstRealSynthByCanTrell.mp3](FirstRealSynthByCanTrell.mp3)
<small>For Wyleu, by Humi</small>
![ForWyleuByHumi.mp3](ForWyleuByHumi.mp3)
-->


