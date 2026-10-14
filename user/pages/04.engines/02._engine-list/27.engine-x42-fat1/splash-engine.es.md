---
title: X42 Autotune
media_order: x42-fat1.png
description: Auto-tuner plugin
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - fx-other
  - ucase-fx
date: 17:38 24-04-2020
subtitle: Afinador automático basado en zita-at1 de Fons Adriaensens
splash:
  bg_image_landscape: x42-fat1-hero_small.png
  bg_image: x42-fat1-hero_small.png
media_thumb: x42-fat1.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-autotune
  urlLabel: X42 Autotune's Website
- urlLink: https://github.com/x42/fat1.lv2
  urlLabel: Source Code
---
x42-autotune (también conocido como fat1.lv2) es un auto-tuner basado en zita-at1, de Fons Adriaensen..

AT1 está pensado para corregir la afinación de una voz que canta ligeramente desafinada. Funciona remuestreando y reproduciendo en bucle la señal, y no incluye corrección de formantes, por lo que solo debe usarse para corregir pequeños errores y no para transponer realmente una canción. Probablemente también se pueda usar AT1 con algunos instrumentos, pero está diseñado principalmente para cubrir el rango vocal..

El tono «esperado» puede controlarse mediante MIDI o ser un conjunto fijo de notas.

Las principales diferencias con zita-at1 son que la versión del plugin LV2 informa al host de su Latency, guarda el estado con la sesión y la entrada MIDI tiene semántica de sidechain.. 

#### Modos de funcionamiento
AT1 vuelve a afinar la señal de entrada a la nota más cercana de la escala configurada. La escala consta de hasta 12 notas (1 octava), que se ajustan y se indican en el teclado de la izquierda. De forma predeterminada, las 12 están habilitadas..

Haz clic con el botón izquierdo para activar/desactivar notas individuales, y haz clic con el botón derecho en el teclado para abrir un cuadro de diálogo y seleccionar escalas mayores/menores comunes. El teclado también indica la nota actual seleccionada por el estimador de tono..

Se admiten los siguientes modos de funcionamiento:

**Manual:** Utiliza un conjunto fijo de notas (ignora MIDI). Haz clic izquierdo para activar o desactivar notas..

**MIDI:** Responde a los mensajes MIDI note on/off. Utiliza las notas MIDI activas actualmente. Si no hay ninguna, utiliza cualquier nota de la escala cromática..

**Automático (predeterminado):** Si no hay notas MIDI activadas, usa el conjunto estático y fijo de notas (haz clic con el botón izquierdo para alternar). Las notas MIDI tienen prioridad..

#### Parámetros

**Selección de canal MIDI:** Selecciona el canal MIDI al que responder. Puede ser 'Omni' o 1..16.

**MIDI Panic:** Restablecer cualquier nota MIDI «colgada».

**Afinación:** Esto establece la frecuencia correspondiente al tono 'A', es decir, la afinación deseada. En la mayoría de los casos, será el valor predeterminado de 440 Hz. El valor exacto se muestra cada vez que se toca este control, y puede ajustarse en incrementos de 0,2 Hz.

**Sesgo:** Normalmente, el estimador de tono seleccionará la nota habilitada más cercana al tono medido. El control Bias añade cierta preferencia por la nota actual; esto permite que se desafine más de lo que lo haría en otras circunstancias..

**Filter:** Esto establece la cantidad de suavizado de la corrección de tono mientras la nota actual no cambia. Si cambia, se omite el filtro y la corrección salta inmediatamente al nuevo valor..

**Corrección:** Determina cuánto se corrige del error de afinación estimado. Una corrección completa puede eliminar la expresividad o el vibrato.

**Offset:** Añade un desplazamiento de +/- dos semitonos a la corrección de tono. Con el control Correction ajustado a cero, el resultado es un cambio de tono constante.

**Medidor de error de afinación:** La barra debajo del teclado indica el error de afinación de la señal de entrada con respecto a la nota actual. El rango es de +/- un semitono.
