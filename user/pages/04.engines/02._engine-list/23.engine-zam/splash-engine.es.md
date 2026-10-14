---
title: ZAM Plugins
media_order: redwave.jpg
description: Una colección de plugins para procesamiento de sonido
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
  - fx-eq
  - fx-filter
  - fx-dynamics
  - fx-distortion
date: 17:38 24-04-2020
subtitle: Colección de plugins
splash:
  bg_image_landscape: redwave-hero.jpg
  bg_image: redwave-hero_small.jpg
media_thumb: redwave.jpg
audio:
- audioType: local
  audioFile: angie-20141010_follow.ogg
  audioLabel: Follow, by Angie Hudson (2013)
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=MGErjKRu_dQ
urls:
- urlLink: http://www.zamaudio.com/
  urlLabel: ZamAudio's Website
- urlLink: http://github.com/zamaudio/zam-plugins
  urlLabel: Source Code
---
Zam-plugins es una colección de plugins de audio LV2/LADSPA/VST/JACK para el procesamiento de sonido desarrollados internamente en ZamAudio. Los ajustes predeterminados y casi todos los sliders están calibrados según los rangos estándar.

Muchas gracias a falktx por escribir Distrho Plugin Framework. Me ha permitido crear estas GUIs para zam-plugins de forma rápida y ordenada. Gracias también a mira, nphilipp, adi, edogawa y Haskellfant, que ayudaron a empaquetar el software para distintas distribuciones.!

## Descripción general

#### ZaMaximX2
Uno de los mejores plugins de la serie, actúa como un limitador brickwall para mastering en su estado predeterminado, pero también se puede ajustar para elevar el nivel medio como maximizador estéreo sin llegar nunca a saturar. Suena musical incluso con un tratamiento brusco. (Basado en DSP encontrado en un artículo DAFX’02).

#### ZamAutoSat
Un plugin de saturación automático, es conocido por proporcionar una nivelación suave a los canales de micrófono en directo.
Puedes aplicar este plugin generosamente sin afectar al tono.

#### ZamComp
Una potente tira de compresión mono. Añade mucho cuerpo a un bombo o una caja con los ajustes adecuados.

#### ZamCompX2
Versión estéreo de ZamComp con control de suavizado de knee.

#### ZamEQ2
Ecualizador paramétrico de dos bandas con circuitos shelving de agudos y graves.

#### ZamGEQ31
Ecualizador gráfico de 31 bandas, ideal para ecualizar espacios en directo, eliminar ruidos no deseados de una pista, etc..

#### ZamHeadX2
Plugin de filtrado acústico HRTF para sonido direccional.

#### ZamPhono
Una colección de filtros de fono para restaurar discos de vinilo, o preparar nuevos para su corte.

#### ZamGate
Plugin Gate para ducking de sonidos de baja ganancia.

#### ZamGateX2
Plugin Gate para atenuar sonidos de baja ganancia, versión estéreo.

#### ZamTube
Efecto de distorsión bestial. Modelo físico de Wave digital filter de una etapa de amplificador de válvulas triodo, con tone stacks modelados a partir de amplificadores de guitarra reales (gracias a D. Yeh et al).

#### ZamDelay
Una unidad de Delay de feedback sencilla con función de sincronización al BPM del host y filtro.

#### ZamDynamicEQ
Un ecualizador dinámico que cambia su Gain al detectar una banda estrecha de frecuencias. Se puede ajustar para modificar otros rangos de frecuencias sobre la marcha..

#### ZaMultiComp
Compresor multibanda mono, con 3 bandas ajustables.

#### ZaMultiCompX2
Buque insignia de zam-plugins: versión estéreo de ZaMultiComp, con controles de umbral individuales para cada banda y visualización en tiempo real de las curvas de compresión..
