---
title: X42 Compressor
media_order: x42-darc.png
description: General Purpose Dynamic Audio Range Compressor
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - ucase-fx
  - fx-dynamics
content:
  items: '@self.modular'
date: 17:38 24-04-2020
subtitle: Compresor de rango dinámico de audio de propósito general
splash:
  bg_image_landscape: x42-darc-hero_small.png
  bg_image: x42-darc-hero_small.png
media_thumb: x42-darc.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-compressor
  urlLabel: X42 Compressor's Website
- urlLink: https://github.com/x42/darc.lv2
  urlLabel: Source Code
---
x42-compressor (también conocido como darc.lv2) es un compresor de rango dinámico de audio inspirado en zita-dc1 de Adriaensen. Es un compresor descendente que suena muy bien y se centra en el flujo de trabajo, exponiendo solo un conjunto mínimo de controles. La compresión responde a la potencia de la señal (RMS), a la sonoridad percibida por las personas, no al pico digital relacionado con el medio-.

El compresor cuenta con makeup-gain automático, fijado en -10 dBFS/RMS. Esto mantiene la sonoridad percibida en un amplio rango de ajustes de umbral y ratio..

Una función «Hold» específica modifica el tiempo de release para que solo se aplique mientras la señal supere el umbral. En otras palabras: Cuando «Hold» está activado, la ganancia (o atenuación) actual se congela cuando la señal cae por debajo del umbral.
Esto evita que el compresor añada una Gain excesiva (por ejemplo, modular el noise-floor) y puede contrarrestar un 'pumping' excesivo al usar tiempos de release cortos..

El plugin está disponible en variantes mono y estéreo. En el caso de esta última, ambas entradas se suman y la potencia de la señal se promedia para determinar el factor de Gain..

darc.lv2 está inspirado en el algoritmo y la interfaz de usuario de zita-dc1 de Fons Adriaensen.

#### Parámetros
**Input Gain:** Gain aplicado antes de la detección de nivel o de cualquier otro procesamiento. Ten en cuenta que esto no se visualiza como un desplazamiento del eje x en la visualización de la curva. El rango va de -10 a +30dB en pasos de 1dB (ajustado con precisión de 0.2dB#+#+#+#+).

**Umbral:** Nivel de señal (RMS) al que se activa el efecto de compresión. El rango va de -50 a -10dB en pasos de 0.5dB (0.1dB de ajuste preciso).

**Relación:** La cantidad de Gain o atenuación que se aplicará (dB/dB por encima del umbral). Unity se mantiene en -10dBFS/RMS (auto makeup-gain).

**Attack time:** Tiempo que tarda la señal en comprimirse por completo tras superar el umbral.

**Release time:** Tiempo mínimo de recuperación hasta el nivel de señal sin comprimir tras caer por debajo del umbral.

**Mantener pulsado (botón de verificación):** Mantener la atenuación actual cuando la señal cae por debajo del umbral. Esto evita la modulación del suelo de ruido y puede contrarrestar el 'bombeo'.

#### Mostrar
El medidor horizontal de la parte inferior muestra la Gain que se aplica a la señal. La pantalla muestra el rango mín./máx. de los últimos 50 ms. Los valores a la izquierda &lt; 0 significan que la señal está atenuada (la entrada está por encima de -10 dBFS/RMS).

El gráfico de la parte superior muestra el mapeo de gain de entrada a salida en dB. Cuando «Hold» está activado, el área donde el gain no se libera aparece sombreada en azul. La pantalla también muestra el nivel de la señal de entrada como un área blanca sombreada bajo la curva, así como el nivel de salida actual (promedio de 50 ms) como un punto.
