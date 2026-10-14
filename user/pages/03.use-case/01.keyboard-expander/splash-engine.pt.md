---
title: Keyboard Expander
media_order: ui_screenshots_kb.png,SalamanderGrandPianoDemoByHumi.mp3,PatMathenyByMauroBorgadelloRhodesStrings.mp3,IfIAintGotYou.mp3,LovelornManFracescoNutiByMauroBorgadello.mp3,PianoteqMidiDemoSteinweyD.mp3,baggypants_on_stage.jpeg,setBfreeDrawbarsManipulationByBaggypants.mp3,georgia_on_my_waltzin_mind.ogg,SmoothPillowByDhrupadiya.mp3,BodySoulByJoostRhodes.mp3,RhodesHammondByHumi.mp3,MorningSunshineByJTunes.mp3,RadioheadByTkc-SalamanderGrandPianoV3.mp3,night_track.ogg,CosmicSynthGuitarByJTunes.mp3,SpaceChoir1ByJTunes.mp3,keyexpander_combined.png,RelaxingThemeByDhrupadiya.mp3,use-cases-1-new.jpg,_DSC4481_02_web_use_case_production.jpg
content_position: center
date: 09:57 09-03-2020
margin_top: half
padding_top: none
padding_bottom: none
margin_bottom: none
role: default
body_classes: use-case custom-list
limit_reveal: '0'
background: _DSC4481_02_web_use_case_production.jpg
subtitle: Deixe seus dedos tocar o som que deseja
splash:
  bg_image_landscape: _DSC4481_02_web_use_case_production.jpg
media_thumb: _DSC4481_02_web_use_case_production.jpg
tag: ucase-kb
audio:
- audioType: local
  audioFile: autumn_leaves_low.ogg
  audioLabel: Autum Leaves, by TKC (Accurate Salamander Grand Piano)
- audioType: local
  audioFile: night_track.ogg
  audioLabel: Night Track, by TKC (MDA EPiano + ZASFX + SooperLooper
- audioType: local
  audioFile: georgia_on_my_waltzin_mind.ogg
  audioLabel: Georgia on my waltzin mind, by TKC (MDA EPiano + setBfree)
- audioType: local
  audioFile: RadioheadByTkc-SalamanderGrandPianoV3.ogg
  audioLabel: Everything In Its Right Place, by Radiohead. Solo rendition by tkc.(Salamander
    Grand Piano V3 + Zynreverb Room)
- audioType: local
  audioFile: BodySoulByJoostRhodes.ogg
  audioLabel: Body & Soul, by Joost (Pianoteq Fender Rhodes)
- audioType: local
  audioFile: IfIAintGotYou.ogg
  audioLabel: If I Aint Got You, by Alicia Keys. Solo rendition by TKC (Salamander
    Grand Piano V3 + Dragonfly Hall Reverb
- audioType: local
  audioFile: PianoteqMidiDemoSteinweyD.ogg
  audioLabel: Pianoteq MIDI demo (Steinwey D)
- audioType: local
  audioFile: SalamanderGrandPianoDemoByHumi.ogg
  audioLabel: Salamander Grand Piano demo, by Humi
- audioType: local
  audioFile: setBfreeDrawbarsManipulationByBaggypants.ogg
  audioLabel: Hammond Drawbars Manipulations, by Baggypants (setBfree)
- audioType: local
  audioFile: RhodesHammondByHumi.ogg
  audioLabel: Rhodes & Hammond, by Humi
- audioType: local
  audioFile: MorningSunshineByJTunes.ogg
  audioLabel: Morning Sunshine, by JTunes
- audioType: local
  audioFile: SpaceChoir1ByJTunes.ogg
  audioLabel: Space Choir1, by JTunes
- audioType: local
  audioFile: CosmicSynthGuitarByJTunes.ogg
  audioLabel: Cosmic Synth Guitar, by JTunes
- audioType: local
  audioFile: PatMathenyByMauroBorgadelloRhodesStrings.ogg
  audioLabel: Pat Metheny, by Mauro Borgadello (Rhodes+Strings)
- audioType: local
  audioFile: LovelornManFracescoNutiByMauroBorgadello.ogg
  audioLabel: Lovelorn Man (Francesco Nuti), by Mauro Bordello
- audioType: local
  audioFile: RelaxingThemeByDhrupadiya.ogg
  audioLabel: Relaxing Theme, by Dhrupadiya
noHeader: true
engines: true
---
Zynthian é uma ótima ferramenta para teclistas que desejam expandir as suas possibilidades de tocar sem ter de transportar hardware pesado e caro.

O Zynthian inclui mais de 30 motores de síntese, centenas de efeitos e milhares de presets. Pode tocar o estilo de música que quiser, recriando instrumentos vintage ou explorando novos sons e texturas. Pode combinar vários motores e presets, ajustar parâmetros de síntese e adicionar efeitos e filtros.

![zui_vangelis_chain_control_obxd_filter](zui_vangelis_chain_control_obxd_filter.png)

O Zynthian suporta o formato de plugins LV2, por isso a lista de motores de síntese & efeitos está sempre a crescer. A maioria dos plugins disponíveis é software livre, mas alguns plugins comerciais estão disponíveis, como o incrível [Pianoteq](https://www.modartt.com/pianoteq?target=_blank) physical modeller ou TAL-U-NO-LX, um emulador preciso do JUNO-60. Estão incluídas versões de demonstração de ambos.

Pode facilmente combinar várias chains (instrumentos) para criar sons em camadas, mantendo o controlo independente sobre os parâmetros que desejar. Pode transpor cada uma de forma independente e dividir o teclado como quiser. 

![zui_vangelis_chain_control_keyrange](zui_vangelis_chain_control_keyrange.png)

Cada controlador MIDI (teclado, etc.) que ligar ao zynthian pode ser encaminhado para qualquer número de cadeias e configurado para funcionar em *ativo* ou *multi* modo. *Ativo* é o modo padrão. Em *ativo* modo, a cadeia selecionada recebe as notas que você toca, **não importa o canal MIDI**. Por outro lado, o *multi* modo permite que você **tire partido dos canais MIDI**, permitindo que diferentes cadeias recebam diferentes canais MIDI.

Sub-snapshots (ZS3s) permitem mudanças rápidas de preset e transições suaves entre instrumentos. Sem interrupção do som ao mudar de instrumento. Você começa a tocar um novo preset enquanto as últimas notas do anterior ainda estão na fase de release. Mantenha algumas notas pressionadas ou sustentadas ao mudar para um novo preset e as notas continuarão a soar até você soltar a tecla/pedal. 

O fluxo de trabalho de MIDI-learning é rápido e fácil, permitindo-lhe gerir tudo a partir dos seus teclados/controladores.  Os botões podem ser atribuídos a presets (program-change), knobs e faders, a parâmetros do motor (CC).

![Baggypants no Palco](baggypants_on_stage.jpeg)

O Zynthian tem conectores MIDI-IN/THRU/OUT padrão e 4 portas USB ([especificações completas](/technical-specifications)). Você pode configurar cada teclado para tocar uma cadeia diferente. Ou dividir seu teclado e mapear vários instrumentos nele. Ou talvez queira que o step-sequencer controle a linha de Drum & Bass enquanto você toca um lead. As possibilidades são quase infinitas ...

A ferramenta de configuração web permite instalar coleções, gerir os seus presets, soundfonts e snapshots, descarregar as suas gravações e muito mais! Também pode configurar o seu zynthian para ser totalmente controlado a partir do seu teclado. Cada ação da UI pode ser mapeada para eventos MIDI.

Em relação à Latency e ao Jitter, a configuração padrão (<10ms) é suficiente para a maioria dos músicos, mas se procura uma Latency extremamente baixa, a configuração de áudio pode ser ajustada.
