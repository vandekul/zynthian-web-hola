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
subtitle: La mejor librería de FX gratis
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
Zynthian puede utilizarse como una potente unidad de Audio Effects que permite crear una effect-chain personalizada para cada entrada de audio disponible.

El kit oficial Zynthian V5 tiene 2 entradas de audio balanceadas con control de Gain independiente que va de -12db a +32dB. Consulta las especificaciones completas [aquí](/technical-specifications). Puedes conectar directamente una amplia gama de dispositivos de entrada, como micrófonos dinámicos, guitarras eléctricas & acústicas, piezos, line-in, etc. Si necesitas más entradas de audio, simplemente conecta tu interfaz de audio USB favorita y obtén todos los canales adicionales de entrada/salida de audio que necesites.

Zynthian es compatible con el estándar de plugins LV2 e incluye cientos de plugins de procesamiento de audio. Puedes combinarlos como quieras para esculpir el sonido, recrear paisajes vintage o explorar nuevas texturas. Puedes tener cualquier número de cadenas de FX con un enrutamiento flexible que permite una configuración tan sencilla o compleja como desees.

Si eres guitarrista, disfrutarás de los modeladores neuronales incluidos en zynthian:

+ [NAM](/engines/_engine-list/engine-nam)
+ [Ratatouille](/engines/_engine-list/engine-ratatouille)
+ [Aida-X](/engines/_engine-list/engine-aidax)
+ [Neural Rack](/engines/_engine-list/engine-neuralrack)

Ofrecen una emulación precisa y de última generación de equipos analógicos como amplificadores, distorsión, fuzz, pedales de overdrive, etc. Hay literalmente miles de modelos disponibles gratuitamente en [Tone3000](https://tone3000.com), que está totalmente integrado con zynthian. Elige un modelo para tu equipo favorito y consigue el tono que te encanta con unos pocos clics.

Si te gusta el looping, SooperLooper está totalmente integrado, lo que permite controlar hasta 6 loops independientes con record, overdub, reverse, multiply, replace, time-stretch, pitch-shift instantáneos, y mucho más.

![Zynthian_UI_SooperLooper](ui_screenshots_sl.png)

El flujo de trabajo de MIDI-learning es rápido y sencillo. Puedes ajustar los parámetros que quieras desde tu controlador MIDI favorito. Los botones se pueden asignar a presets (program-change), y los knobs y faders a parámetros (CC).

En cuanto a latency y jitter, la configuración predeterminada (<10ms) es suficiente para la mayoría de los músicos, pero si buscas una latency ultrabaja, se puede ajustar la configuración de audio.
