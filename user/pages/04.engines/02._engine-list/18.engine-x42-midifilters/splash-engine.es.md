---
title: x42 MIDI-filters
media_order: x42-midifilter.jpg
description: Una potente colección de filtros y herramientas MIDI sencillos
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - ucase-pr
  - effect
  - fx-midi
date: 17:38 24-04-2020
subtitle: Una potente colección de sencillos filtros y herramientas MIDI
splash:
  bg_image_landscape: x42-midifilter-hero.jpg
  bg_image: x42-midifilter-hero_small.jpg
media_thumb: x42-midifilter.jpg
urls:
- urlLink: http://x42-plugins.com/x42/x42-midifilter
  urlLabel: x42 MIDI-filter's Website
- urlLink: https://github.com/x42/x42-plugins
  urlLabel: Source Code
---
Una colección de más de 25 filtros de datos MIDI en formato de plugin LV2, desarrollados y mantenidos por [Robin Gareus](http://x42-plugins.com). Los filtros siguen estas reglas básicas:
+ Una entrada MIDI, una salida MIDI (sin generadores ni sintes)
+ Sin GUI personalizada, solo entradas de control
+ Todos los controles se pueden automatizar, los plugins gestionan los cambios dinámicos de parámetros.
+ Todos los plugins indican su latency al host (para la mayoría es cero)
+ DRY (principio «Don't Repeat Yourself») - filtros sencillos que se pueden combinar en una red
+ Autodocumentado: descripción integrada y documentación de los puertos de control

##Resumen
**CC2Note:** Convierte los mensajes MIDI control change en mensajes note-on/off. Note off se pone en cola 10msec después.

**Filtro de canal MIDI:** Filtro de canal MIDI sencillo. Solo pueden pasar los datos de los canales seleccionados. Este filtro solo afecta a los midi-data relevantes para el canal (es decir, note-on/off, cambios de control y de programa, presión de tecla y de canal, y pitchbend). Los mensajes MIDI-SYSEX y Realtime siempre pasan. Este plugin está pensado para uso en directo y control mediante botones. Véase también el filtro 'MIDI Channel Map.

**Mapa de canales MIDI:** Reescribe el número de canal MIDI. Este filtro solo afecta a los datos MIDI relevantes para el canal (es decir, note-on/off, cambios de control y de programa, presión de tecla y de canal, y pitchbend). Los mensajes MIDI-SYSEX y Realtime siempre se transmiten sin modificar..

**MIDI Forzar escala:** Filtra los eventos note-on/off en función de la escala musical. Si se cambia la tonalidad, se envían eventos note-off para todas las notas activas fuera de la tonalidad.

**Filtro de eventos MIDI:** Filtro de mensajes de tipo Notch. Suprime mensajes específicos. Para un rango flexible de note-on/off, consulta también 'keyrange' y 'velocityrange'.

**Filtro de rango de teclas MIDI:** Este filtro permite definir un rango de notas midi permitidas. Los eventos de note-on/off fuera del rango permitido se descartan. Si cambia el rango, se envían eventos de note-off a las notas actualmente activas que quedan fuera del rango válido.

**MIDI Keysplit:** Cambia el número de midi-channel en función de la nota. El plugin mantiene un seguimiento de las midi-notes transpuestas por si acaso y envía eventos note-off en consecuencia si se cambia el rango, incluso si hay una nota activa. Sin embargo, el split-point y las channel-assignments de cada manual solo deberían cambiarse cuando no se estén reproduciendo notas..

**MapCC:** Cambia un mensaje de control por otro -- combínalo con scalecc para modificar/escalar el valor real.

**Transposición de teclas MIDI:** Mapa flexible de 12 tonos. Permite asignar una nota dentro de una octava a otra nota del mismo rango de octava +- 12 semitonos. También se pueden enmascarar (deshabilitar) notas. Si dos teclas se asignan a la misma nota, los eventos de note on/off correspondientes quedan enclavados: solo se enviará el primer note on y el último note off. Los ajustes se pueden cambiar dinámicamente: los eventos de Note-on/off se enviarán según corresponda..

**Acorde MIDI:** Armonizador - crea acordes a partir de una única nota (fundamental) en una escala musical determinada. Tanto la escala como los intervalos se pueden automatizar libremente (los acordes que se estén manteniendo cambiarán). Los note-ons quedan enclavados; para acordes múltiples/combinados, solo se activará un note-on/off durante la duración de los acordes combinados. Si se recibe una nota fuera de la escala, se dejará pasar; no se asignará ningún acorde. Nota: Combina este efecto con el 'MIDI
Filtro Enforce Scale' para eliminarlas.

**MIDI Delayline:** Línea de delay MIDI. Delay todos los eventos MIDI durante un tiempo determinado, indicado en BPM y beats. Si el delay incluye un factor aleatorio, este efecto se encarga de mantener siempre secuenciales los eventos note on/off, independientemente de la aleatorización..

**MIDI Canal Unísono:** Duplica eventos MIDI de un canal a otro.

**MIDI Strum:** Un efecto de arpegio midi pensado para simular el rasgueo de un instrumento de cuerda (p. ej., una guitarra). Se «recoge» un acorde y las notas individuales del acorde se reproducen espaciadas en el tiempo. «Note Collect Timeout» permite tocar el efecto en directo con un midi-keyboard; compensa que una persona no pulse las teclas exactamente al mismo tiempo. Si el efecto se usa con un secuenciador que puede enviar acordes con todas las notas activadas exactamente al mismo tiempo, debe ajustarse a cero.

**MIDI Transposición cromática:** Transposición cromática de notas midi y key-pressure. Si se establece un punto de inversión, la escala se refleja alrededor de este punto antes de transponer. Las notas que quedan fuera del rango válido 0..127 se descartan..
MIDI Monophonic Legato	Mantén una nota hasta que llegue la siguiente. -- Vuelve a tocar la misma nota para desactivarla.

**Eliminar Active Sensing MIDI:** Filtro para bloquear todos los eventos de Active Sensing. Los mensajes de Active Sensing son mensajes MIDI opcionales y están pensados para enviarse repetidamente para indicar a un receptor que la conexión sigue activa; sin embargo, pueden saturar el canal MIDI o grabarse inadvertidamente al volcar datos MIDI sin procesar en el disco..

**Bloqueador de duplicados MIDI:** MIDI Duplicate Blocker. Filtra los mensajes de note on/off solapados y duplicados.

**Note2CC:** Convierte mensajes MIDI note-on en mensajes de control change.

**Alternar nota MIDI:** Alternar notas: toca una nota para activarla, tócala de nuevo para desactivarla.

**MIDI N-Tap Delay:** Este efecto repite las notas N veces. Donde N es un número fijo o ilimitado mientras se mantenga pulsada una tecla determinada. BPM y la variable delay-time permiten rampas de tempo. En cada repetición se suma o se resta el ajuste de Velocity indicado; el resultado se limita a un valor entre 1 y 127.

**MIDI Thru:** MIDI All pass. Este plugin no tiene efecto y está pensado como ejemplo..

**Cuantización MIDI:** Cuantización de eventos en directo. Este filtro alinea los eventos MIDI entrantes con una cuadrícula de tiempo fija. Como el efecto opera en una transmisión en directo, introducirá Latency: los eventos se retrasarán hasta el siguiente 'tick'. Si el host de plugins proporciona información BBT, los eventos se alinean con el reloj del host; de lo contrario, el efecto funciona con su propio tiempo.

**Aleatorización de Velocity MIDI:** Aleatorizar Velocity de las notas MIDI (tanto note on como note off).

**Escalar valor CC:** Modifica el valor (data-byte) de un mensaje MIDI control change.

**MIDI Sostenuto:** Este filtro retrasa los mensajes note-off durante un tiempo determinado, emulando un pedal de sostenuto de piano. Al soltar el pedal, los mensajes note-off en cola se envían inmediatamente. El tiempo de retardo se puede cambiar dinámicamente; los cambios afectan a los mensajes note-off que aún están en cola.

**Filtro de rango de Velocity MIDI:** Filtra los eventos MIDI note-on según la Velocity. Los eventos note-on fuera del rango permitido se descartan. Si se recibe un evento Note-off para una nota que se había filtrado previamente, tampoco se transmite. Si cambia el rango permitido, se envían eventos note-off a las notas que están activas y que quedan fuera del rango válido.

**Ajuste de Velocity MIDI:** Cambia la velocity de los eventos de nota con controles independientes para Note-on y Note-off. El rango de entrada 1 - 127 se asigna al rango entre Min y Max. Si Min es mayor que Max, el rango se invierte. El valor de offsets se añade al evento de velocity después de asignar el rango Min/Max.
