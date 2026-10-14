---
title: Ratatouille - Dual Neural Modeler
media_order: ratatouille.jpg
description: Modelador dual de redes neuronales. Combina 2 modelos neuronales + IRs
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - ucase-fx
  - fx-distortion
date: 17:38 24-04-2020
subtitle: Mezcla 2 modelos neuronales y 2 IRs
splash:
  bg_image: ratatouille-hero.jpg
  bg_image_landscape: ratatouille-hero.jpg
media_thumb: ratatouille.jpg
urls:
- urlLink: https://github.com/brummer10/Ratatouille.lv2
  urlLabel: Source Code
- urlLink: https://tone3000.com
  urlLabel: Ratatouille's Models in Tone3000
---
Ratatouille es un cargador y mezclador de modelos neuronales para Linux/Windows.
Puede cargar dos modelos, que pueden ser archivos *.nam (Neural Amp Modeler) o *.json / .aidax (RTNeural), y usar
el control "Blend" para combinar los dos modelos y mezclarlos para simular el tono específico que buscas.
Por supuesto, también puedes cargar solo un archivo de modelo y el control "Blend" no hará nada.

Ratatouille utiliza procesamiento en paralelo para los modelos neuronales, así que cargar un segundo modelo neuronal no sería
notable en la carga de dsp.  Opcionalmente, Ratatouille podría ejecutar el proceso completo en modo de búfer.
Esto reduce aún más la carga de dsp. La latency resultante se comunicará al host para que pueda ser
compensado. A título informativo la latencia resultante se mostrará en la GUI.

El control "Delay" podría añadir un pequeño retardo para solucionar problemas de fase o para aportar algo de color/reverb al sonido.
La tecla 'ctrl' activa el ajuste fino para configurar un Delay con precisión de Sample. Ratatouille también puede detectar la fase
offset y compensarlo internamente.

Para redondear tu sonido, puedes cargar dos Impulse Response Files y mezclarlos a tu gusto. Los archivos IR podrían ser
normalizados al cargarlos, para que no influyeran en la sonoridad.

Ratatouille.lv2 admite el remuestreo cuando es necesario para coincidir con la frecuencia de muestreo esperada de los modelos cargados. Both
los modelos y los archivos IR pueden tener distintas expectativas con respecto a la frecuencia de muestreo.
#### Consigue modelos de una gran comunidad

[Tone3000.com](https://tone3000.com) se ha convertido en el lugar donde conseguir los mejores modelos para Neural Amp Modeler, Aida-X y Proteus, mientras amplía la compatibilidad con más plataformas de cara al futuro. No solo modelos, sino que nuestra colección de IRs también está creciendo y haciéndose muy popular dentro de la plataforma.

#### Cargando archivos

Desde la zynthian-ui puedes cargar archivos de modelo fácilmente. Solo tienes que mover el Knob asignado al control del modelo y aparecerá el selector de archivos.

