---
title: X42 Equalizer
media_order: x42-fil4.png
description: Ecualizador paramétrico de 4 bandas
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - fx-filter
content:
  items: '@self.modular'
date: 17:38 24-04-2020
subtitle: Ecualizador paramétrico de 4 bandas
splash:
  bg_image_landscape: x42-fil4-hero_small.png
  bg_image: x42-fil4-hero_small.png
media_thumb: x42-fil4.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-eq
  urlLabel: X42 Equalizer's Website
- urlLink: https://github.com/x42/fil4.lv2
  urlLabel: Source Code
---
x42-eq (también conocido como fil4.lv2) es un ecualizador paramétrico de 4 bandas con shelfing adicional de graves y agudos, y filtros pasa-altos y pasa-bajos. El ecualizador está diseñado para igualar la ganancia analógica equivalente con latencia cero y sin desfase al acercarse a la frecuencia de Nyquist. No tiene una respuesta limitada, a menudo denominada sonido digital. x42-eq incluye visualizaciones de espectro en tiempo real y espectrograma (cascada), una visualización de retención de picos que el usuario puede restablecer y un control de ganancia de salida.

fil4.lv2 está basado en los fil-plugins LADSPA de Fons Adriaensen.

#### Controles de espectro
Los controles del espectrograma están en la parte inferior derecha,

**Desactivado:** No mostrar el espectro<br>
**Especificación:** Muestra un espectro ponderado de ruido rosa (1/octava.<br>
**Hist:** Visualización del espectrograma; vista del historial (las líneas blancas discontinuas indican el cambio de ajustes)<br>
**Pre:** Analiza la entrada<br>
**Publicación:** Analiza la salida procesada<br>

La variante Stereo tiene una opción para analizar la suma (All) o solo el canal izquierdo o derecho. El Knob de Gain permite alinear el espectro; consulta la escala en el lado derecho de la pantalla..

**Alto:** Deformación de altas frecuencias, mayor resolución en las frecuencias bajas.<br>
**Med:** Deformación de Frecuencia Media<br>
**Ladrido:** Sin Frequency Warping, enfatiza las frecuencias altas<br>

**Rpd:** Caída rápida (~~20ms)<br>
**Rápido:** Caída rápida (~~80ms)<br>
**Mod:** Tiempo de caída moderado (~~200ms)<br>
**Lento:** Caída lenta (~~2sec)<br>
**Ns.:** Medición de ruido (~20sec)<br>

#### Especificaciones del filtro
Fil4 consta de cuatro filtros resonantes de 2.º orden que utilizan un filtro de celosía de estilo Regalia-Mitra, que tiene la interesante propiedad de ser estable incluso mientras se cambian los parámetros..

Los filtros high/low-shelf son filtros biquad/IIR estándar de 2.º orden.

Los filtros paso alto y paso bajo son filtros resonantes de 2.º orden (-12 dB/octava):

+ Calidad 0.0: -6dB en cutoff-freq (sin feedback)
+ Calidad 0.7: -3dB en cutoff-freq
+ Calidad 1.0: 0dB en cutoff (resonant)

Todos los filtros tienen Latency cero con el Gain analógico equivalente correcto en Nyquist (el desplazamiento de fase de la señal en la frecuencia de Nyquist es cero).

