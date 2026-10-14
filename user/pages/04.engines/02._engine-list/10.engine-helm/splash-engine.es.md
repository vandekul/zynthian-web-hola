---
title: Helm
id: helm
image: helm.jpg
description: Sintetizador software monofónico/polifónico basado en síntesis sustractiva
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-pr
  homepage:
  - 'yes'
date: 17:38 24-04-2020
subtitle: Sintetizador analógico virtual
splash:
  bg_image_landscape: helm-hero.png
  bg_image: helm-hero_small.png
media_thumb: helm.png
sitemap:
  lastmod: 07-05-2026 16:53
urls:
- urlLink: https://tytel.org/helm
  urlLabel: Website
- urlLink: http://linuxsynths.com/HelmPatchesDemos/helm.html
  urlLabel: LinuxSynths's page
- urlLink: https://github.com/mtytel/helm
  urlLabel: Source Code
audio:
- audioType: local
  audioFile: bitofbrush.ogg
  audioLabel: Bit of Brush
- audioType: local
  audioFile: cassiopeiaone.ogg
  audioLabel: Cassiopeia One
- audioType: local
  audioFile: girandoone.ogg
  audioLabel: Girando One
- audioType: local
  audioFile: supersawmodified.ogg
  audioLabel: Super Saw Modified
- audioType: local
  audioFile: dripping.ogg
  audioLabel: Dripping
- audioType: local
  audioFile: cassiopeiatwo.ogg
  audioLabel: Cassiopeia Two
- audioType: local
  audioFile: expresstwo.ogg
  audioLabel: Express Two
- audioType: local
  audioFile: pensivealientwo.ogg
  audioLabel: Pensive Alien Two
---
Helm es un sintetizador software monofónico/polifónico en tiempo real y de código abierto desarrollado por Matthew Tytel en Tytel.org. Está disponible en versiones de 32 y 64 bits y puede ejecutarse como plugin LV2 o como instrumento independiente. También incluye la capacidad multiplataforma de cargar y guardar patches..

Lo que distingue a Helm de muchos otros sintetizadores software es la gran flexibilidad en el enrutamiento de la modulación. Al hacer clic en cualquiera de las fuentes de modulación, se resaltarán todos los parámetros modulables. La profundidad de modulación se ajusta haciendo clic con el ratón y arrastrando el área del parámetro..

## Características:
Helm consta de dos osciladores con un sonido rico, cada uno de los cuales ofrece 11 formas de onda diferentes (con anti-aliasing). Una función única de modulación cruzada permite modular el tono del oscilador izquierdo o la fase del oscilador derecho. Se incluyen ajustes de desafinación fina y gruesa (transposición) para cada onda. El modo Unison está disponible para cada oscilador, así como el control de la cantidad de dispersión de cada uno (en función de la cantidad de desafinación). El botón 'h' añade un armónico a cada voz de ese oscilador. Además de los osciladores, hay un suboscilador con modelado de onda shuffle y una fuente de ruido. Las cuatro fuentes de sonido disponen de controles discretos de nivel de señal de amplitud.

La sección de filtro permite ajustar los tipos de filtro lowpass, highpass, bandpass, high-shelf, low-shelf, band-shelf y allpass. Los controles deslizantes de Cutoff y resonance están situados en los ejes x e y del gráfico del filtro, respectivamente. También se incluye un filtro formant muy útil con control mediante los ejes X-Y, además de dos LFO monofónicos y uno polifónico..

Helm también incluye una función de arpegiador muy completa con controles de gate, rango de octavas y patrón, así como una sección de secuenciador por pasos. También incluye varios efectos útiles, como reverb, stutter (remuestrea parte de la señal de audio y la repite), delay, distorsión y feedback. Los controles globales incluyen pitchbend, cantidad de polifonía (hasta 32 voces), portamento con opción legato y seguimiento de velocity. Hay un osciloscopio en la zona superior central, a la derecha del control deslizante del volumen principal..

La gestión de preajustes es bastante sencilla. El botón 'Browse' junto al nombre del preajuste actual abrirá la ventana de gestión de preajustes, donde se encuentran los directorios de preajustes. Se pueden buscar preajustes seleccionando una carpeta o escribiendo una palabra clave para buscar en esa misma carpeta. Los preajustes se pueden exportar por separado o directamente a la carpeta de preajustes deseada haciendo clic en 'save.' Asegúrate de que el nombre que le des a tu preajuste sea distinto de los que hay en el directorio activo, ya que Helm no te pedirá que confirmes la sobrescritura de un preajuste existente con el mismo nombre.
