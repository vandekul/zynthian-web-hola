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
subtitle: Deja que tus dedos toquen el sonido que quieres
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
Zynthian es una gran herramienta para teclistas que quieren ampliar sus posibilidades musicales sin tener que cargar con hardware pesado y caro.

Zynthian incluye más de 30 motores de síntesis, cientos de efectos y miles de presets. Puedes tocar el estilo musical que quieras, recreando instrumentos vintage o explorando nuevos sonidos y texturas. Puedes combinar varios motores y presets, ajustar los parámetros del sintetizador y añadir efectos y filtros.

![zui_vangelis_chain_control_obxd_filter](zui_vangelis_chain_control_obxd_filter.png)

Zynthian admite el formato de plugins LV2, por lo que la lista de motores de síntesis & efectos no deja de crecer. La mayoría de los plugins disponibles son software libre, pero también hay algunos plugins comerciales disponibles, como el increíble [Pianoteq](https://www.modartt.com/pianoteq?target=_blank) modelador físico o TAL-U-NO-LX, un emulador preciso del JUNO-60. Se incluyen versiones de demostración de ambos.

Puedes combinar fácilmente varias cadenas (instrumentos) para crear sonidos en capas manteniendo el control independiente de los parámetros que quieras. Puedes transponer cada una de forma independiente y dividir el teclado como quieras. 

![zui_vangelis_chain_control_keyrange](zui_vangelis_chain_control_keyrange.png)

Cada controlador MIDI (teclado, etc.) que conectes a zynthian se puede enrutar a cualquier número de cadenas y configurar para funcionar en *activo* o *multi* modo. *Activo* es el modo predeterminado. En *activo* modo, la cadena seleccionada recibe las notas que tocas, **no importa el canal MIDI**. Por otro lado, el *multi* modo te permite **aprovecha los canales MIDI**, permitiendo que diferentes cadenas reciban diferentes canales MIDI.

Sub-snapshots (ZS3s) permiten cambios rápidos de preset y transiciones suaves entre instrumentos. Sin cortes de sonido al cambiar de instrumento. Empiezas a tocar un nuevo preset mientras las últimas notas del anterior aún se están apagando. Mantén algunas notas pulsadas o sostenidas mientras cambias a un nuevo preset y las notas seguirán sonando hasta que sueltes la tecla/pedal. 

El flujo de trabajo de MIDI-learning es rápido y sencillo, y te permite gestionarlo todo desde tus teclados/controladores.  Los botones se pueden asignar a presets (program-change), los knobs y faders, a parámetros del motor (CC).

![Baggypants en el Escenario](baggypants_on_stage.jpeg)

Zynthian tiene conectores MIDI-IN/THRU/OUT estándar y 4 puertos USB ([especificaciones completas](/technical-specifications)). Puedes configurar cada teclado para tocar una cadena diferente. O dividir tu teclado y asignarle varios instrumentos. O quizá quieras que el step-sequencer controle la línea de Drum & Bass mientras tocas un lead. Las posibilidades son casi infinitas ...

¡La herramienta de configuración web te permite instalar colecciones, gestionar tus presets, soundfonts y snapshots, descargar tus grabaciones y mucho más! También puedes configurar tu zynthian para controlarlo por completo desde tu teclado. Cada acción de la UI se puede asignar a eventos MIDI.

En cuanto a latency y jitter, la configuración predeterminada (<10ms) es suficiente para la mayoría de los músicos, pero si buscas una latency ultrabaja, se puede ajustar la configuración de audio.
