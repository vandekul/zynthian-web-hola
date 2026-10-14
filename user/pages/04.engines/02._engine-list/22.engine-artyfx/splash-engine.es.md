---
title: ArtyFX
media_order: artyfx.png
description: Una colección de plugins minimalista pero completa
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - effect
  - fx-delay
  - fx-mod
  - fx-other
  - ucase-fx
  - fx-eq
  - fx-filter
  - fx-dynamics
  - fx-distortion
  homepage:
  - 'yes'
date: 17:38 24-04-2020
subtitle: Colección minimalista de plugins
splash:
  bg_image_landscape: artyfx-hero.png
  bg_image: artyfx-hero_small.png
media_thumb: artyfx.png
urls:
- urlLink: http://openavproductions.com/artyfx/
  urlLabel: ArtyFX's Website
- urlLink: http://openavproductions.com/doc/artyfx.html
  urlLabel: ArtyFX's Documentation
- urlLink: https://github.com/openAVproductions/openAV-ArtyFX
  urlLabel: Source Code
---
ArtyFX es un conjunto de efectos de audio minimalistas, que se pueden usar de forma independiente, pero también están integrados en muchos de los proyectos más complejos de OpenAV, como Fabla2, Sorcer y Luppp. Cada efecto se puede usar individualmente como plugin LV2..

ArtyFX contiene muchos plugins diferentes: están presentes todos los efectos «clásicos», como reverbs, delays y filtros. Las siguientes secciones describen cada plugin individualmente, muestran cómo se puede utilizar y ofrecen algunas sugerencias sobre las mejores prácticas..

#### Bitta
Bitta es un plugin bit-crusher. La reducción de bits reduce la profundidad de bits del audio. Como depende del volumen de la señal entrante, ten cuidado al ajustar el mando «crush».

**Crush :** Cambia el número de bits utilizados para acelerar el audio.

#### Della
Della es un Delay que ajusta los BPM, con controles para feedback y volumen del Delay..

**Comentarios:** controla la cantidad de señal que se realimenta en la línea de Delay: súbelo para conseguir ese eco dub reggae frenético que no acaba nunca!

**Volumen:** cambia la cantidad de señal retardada que oyes: útil para mantener los delays en segundo plano en una pista.

**Hora:** cambia la longitud del Delay: ten en cuenta que esto está “cuantizado” en múltiplos del BPM, así que “salta” entre una duración de nota de 1/8, 1/4, 1/2 y una nota entera. Della toma el BPM del programa anfitrión: así que, si cambias el tempo, seguirá manteniendo el compás!

#### Ducka
Ducka es un plugin de envolvente side-chain: resulta muy útil para crear líneas de bajo con efecto «pumping», como las que se encuentran a menudo en la música minimal house. El plugin funciona analizando el volumen de una entrada sidechain y cambiando el volumen de una pista estéreo independiente en función de la amplitud de la entrada sidechain..

**Umbral:** establece el nivel que debe alcanzar el audio de entrada antes de que se reduzca la pista estéreo.

**Soltar:** controla la cantidad de reducción de volumen que se realiza.

**Tiempo:** controla el tiempo que transcurre antes de que la pista estéreo vuelva a aparecer gradualmente. Ten en cuenta que este control depende del BPM y que el centro coincide directamente con los contratiempos. Un ajuste a la mitad (el predeterminado) suele ser musical :)

#### Driva
Driva es una unidad de distorsión múltiple capaz de producir las distorsiones más agresivas y ásperas.

**Tono:** Haz clic en el botón Tone; hay disponible una lista de distintos modelos de distorsión. Solo tienes que hacer clic en la distorsión que quieras y seguir disfrutando. Cancel, en la parte inferior, cierra la vista de cambio de tono..

**Cantidad:** simplemente sube la cantidad de gain / distorsión. Úsalo bajo tu propia responsabilidad.!

#### Filta
Filta es una combinación de filtro lowpass y highpass. Útil para eliminar frecuencias altas y bajas no deseadas de diversas grabaciones o instrumentos.A

**Frecuencia:** controla qué tipo de filtrado se realiza y a qué frecuencia. Los valores bajos corresponden a un filtro lowpass; al subir el dial, se aplica un highpass.

#### Kuiza
Kuiza es un ecualizador de 4 bandas. Es perfecto para moldear creativamente el sonido de un instrumento o sintetizador. Cada uno de los controles de Gain cambia la amplitud en la frecuencia indicada. El master gain se puede usar para reducir o amplificar el volumen general si es necesario. Los controles (de izquierda a derecha):

* Bajo ( ~55 Hz)
* Medios-graves ( ~220 Hz)
* Medios-agudos ( ~1760 Hz)
* Alto ( ~7040 Hz)
* Master Gain

#### Masha
Masha es un plugin beat grinder: graba un segmento de audio y lo reproduce en bucle, causando un efecto de “tartamudeo”.

**Volumen:** cambia el volumen del stutter-loop. PassThru permite que pase la señal normal a través de él.

**Tiempo:** es un control dependiente del BPM que cambia la duración de la grabación en bucle y la reproducción. ¡Reduce gradualmente este valor para conseguir ese efecto de stutter «estándar» de DJ! Este efecto tiene algunas funciones especiales que permiten controlar manualmente el BPM. Normalmente, el BPM se toma del programa host (o del transporte JACK), pero ahora se puede controlar con un control giratorio.

**botón HostBPM:** controla la fuente de BPM. Cuando el botón está azul, HostBPM está activado. Al desactivar el botón, aparece el dial de BPM manual. El dial también muestra el BPM actual.

#### Panda
Panda es una combinación de compresor y expansor, con controles de ataque y relajación..

**Umbral:** el “punto de inflexión” de compresión / expansión. Bajar el dial expande la señal, subirlo provoca compresión.

**Lanzamiento:** cambia el tiempo que tarda Panda en aplicar el fade-out de su compresión/expansión.

**Factor:** controla la cantidad de compresión/expansión aplicada, el dial «maximizer».

#### Espacioso
Roomy es un reverb espacioso y suave.

**El control Time** cambia la duración de la cola de Reverb: los valores más altos crearán una mezcla más amplia y espaciosa.

**Amortiguación** controla la atenuación de las frecuencias altas: los ajustes más bajos ofrecen un sonido espacioso y abierto, mientras que una atenuación alta da una sensación pequeña y cercana.

**El control Dry/Wet** cambia la cantidad de señal de Reverb mezclada: útil para los «subidones de Reverb» del techno y el trance... solo tienes que subirlo al máximo!

#### Satma
Satma es un plugin de distorsión alocado. Útil para dar vida al audio y conseguir un sonido áspero y sucio..

**Distortion** cambia la cantidad de modelado de señal que se produce: la cantidad total de generación de ruido.

**El control Tone** varía sutilmente entre las frecuencias altas y las bajas, o haciendo que ambas suenen igual de ásperas.

#### Vihda
Vihda es un potenciador estéreo que utiliza una matriz mid-side.

**El parámetro Width** afecta a la cantidad de contenido estéreo en la señal. Ten en cuenta que la la técnica mid-side solo mejora el estéreo: no lo crea!

**El botón Invert** invierte el canal derecho, lo que puede hacer que la mezcla parezca más amplia debido a cómo interpreta el cerebro el audio. Pruébalo y comprueba si suena bien.

