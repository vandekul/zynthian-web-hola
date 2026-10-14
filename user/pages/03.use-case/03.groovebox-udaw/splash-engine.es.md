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
subtitle: Una herramienta de producción bien dotada
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
Zynthian también es una potente herramienta de producción. Incluye más de 100 motores de síntesis y miles de presets y más de 1000 efectos de audio & MIDI.

![zui_vangelis_add_chain](zui_vangelis_add_chain.png)

Es completamente multitímbrico, capaz de gestionar hasta 16 cadenas de instrumentos y cualquier número de efectos de audio, procesadores midi y mixbuses. Es compatible con el estándar LV2-plugin, por lo que la lista de procesadores disponibles es enorme y sigue creciendo.

![01-zui_vangelis_mixerer](01-zui_vangelis_mixer.png)
![05-zui_vangelis_chainman](05-zui_vangelis_chainman.png)

Incluye un potente step-sequencer con funciones para tocar en directo y componer canciones:

+ alta resolución (1920 ppqn)
+ editor de patrones (eventos & bloques)
+ copiar/pegar & transponer bloques
+ copiar/pegar patrones
+ captura en directo
+ deshacer/rehacer
+ opciones avanzadas de stutter:  speed, duration, volume-fade, speed-ramp
+ opciones de repetición & aleatorización: probabilidad de reproducción/omisión, frecuencia de reproducción/omisión, etc. 
+ automatización de parámetros
+ mucho más!

![zui_vangelis_pated_stuter](zui_vangelis_pated_stuter.png)

También incluye un reproductor avanzado de clips de audio capaz de cargar cualquier formato de archivo de audio, aplicar time-stretch y sincronizar samples de audio, etc.

![zui_clippy_wave](zui_clippy_wave.png)

La vista launcher permite combinar patrones del step sequencer y clips de audio, iniciándolos y deteniéndolos de forma sincronizada, con diferentes modos  para una sola reproducción, loops, etc. Phrases te permite estructurar tus canciones, automatizando los cambios de tempo & time signature, definiendo loops y secciones CODA, etc.

![02-zui_vangelis_launcher](02-zui_vangelis_launcher.png)

Una lista cada vez mayor de controladores midi compatibles se puede utilizar para controlar zynthian directamente, totalmente plug & play:

+ **Novation:** LaunchPad Mini / Pro / X. LaunchKey Mini, etc.
+ **Akai:** APC Key-25, APC 40, MPK mini, MIDI Mix
+ **Korg:** nanoKONTROL
+ **Behringer:** Motör 61 / 49
+ **Arturia:** Keylab 61
+ **Teenage Engeneering:** OP1
+ **Worlde:** Mini
+ **Foxtex:** Mixtab
+ **Mackie (MCU)**

[Haz clic aquí](https://wiki.zynthian.org/index.php/Supported_MIDI_controllers) para consultar la lista completa de controladores MIDI compatibles.

Zynthian también se puede controlar desde DAWs y secuenciadores externos. Tiene muchas opciones de conexión:

+ conectores MIDI DIN-5 tradicionales (IN / OUT / THRU)
+ 4 x puertos USB-A (host)
+ 1 x puertos USB-B (dispositivo)
+ Conectividad de red Ethernet y WIFI

y también admite los protocolos de red MIDI más utilizados, como:

+ NetUMP (MIDI 2.0)
+ RTP (Apple MIDI)
+ QMidiNet (IP-multicast)
+ TouchOSC (tableta como controlador MIDI)

Y hay mucho más:

+ midi-learning fácil con rango de valores y escalado
+ enrutamiento flexible de audio & midi
+ mixbuses
+ grabadora de audio multipista
+ grabador y reproductor midi
+ midi-filter basado en reglas
+ patches de PureData & Organelle
+ Integración de MOD-UI

En cuanto a latency y jitter, la configuración predeterminada (<10ms) es suficiente para la mayoría de los músicos, pero si buscas una latency ultrabaja, se puede ajustar la configuración de audio.

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


