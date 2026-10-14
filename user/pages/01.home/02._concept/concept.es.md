---
title: Concepto
smallTitle: Irúfẹ́ ohun èlò orin tuntun kan!
onpage_menu: true
menu: Concept
visible: false
lead: Zynthian es un dispositivo musical compacto y autónomo que puede usarse como
  expansor de teclado, unidad de efectos de audio, procesador y router MIDI, groovebox
  y micro-DAW.
subtitle: 'El texto a traducir empieza en la siguiente línea:'
buttonText1: Más info en nuestra Wiki
buttonLink1: https://wiki.zynthian.org
buttonText2: Lee la guía de usuario
buttonLink2: https://help.zynthian.org/
---
Zynthian es un [proyecto impulsado por la comunidad](https://discourse.zynthian.org)—100% open-source, con software libre que se ejecuta en hardware abierto. Es completamente configurable y totalmente hackeable! **Libre en el sentido de Libertad**. Puedes construir tu Zynthian desde cero o [compra un kit oficial](https://shop.zynthian.org).

### Más de 100 instrumentos virtuales
Zynthian incluye una colección completa de instrumentos virtuales y emuladores:
+ **Teclados Acústicos y Eléctricos** como pianos de cola, Rhodes, Wurlitzer, Clavinet, y Farfisa.
+ **Órganos** como los Hammonds tonewheel, los órganos combo de transistores, y los órganos de tubos.
+ **Synths Icónicos** como el DX7, Oberheim, Juno-60, y TB-303.
+ **Sintetizadores Analógicos Virtuales** como ZynAddSubFX, Surge-XT, Vaporizer2, NoizeMaker, Odin2, MiMi-d, Monique, Helm, y Amsynth.
+ **Emuladores de Hardware Real** como los desarrollados por [Los Sospechosos Habituales](https://theusualsuspects.io/), incluidos Osirus, OsTIrus, Vavra, Xenia, VirtualJV, y JE-8086. (<i>Nota: Es necesario obtener una copia legal del archivo ROM del firmware del dispositivo para su funcionamiento</i>).

<a class="minilink" href="/engines#synthesizers">más detalles sobre instrumentos virtuales &nbsp;&nbsp;&gt;</a>

### Instrumentos basados en Samples
Reproduce enormes bancos de sonidos multisampled con soporte nativo para **SF2**, **SF3**, **SFZ**, **DecentSampler (DS)**, y **GIG** formatos. Zynthian incluye de serie una amplia colección de instrumentos muestreados, que puedes ampliar fácilmente con paquetes de extensión y tus propias bibliotecas personalizadas.

Para los formatos más potentes (**SFZ**, **DS**, y **GIG**), el tamaño del instrumento no está limitado por la memoria. Los motores Sfizz y LinuxSampler implementan algoritmos avanzados de play-from-disk que permiten cargar instrumentos arbitrariamente grandes.

<a class="minilink" href="https://github.com/zynthian/zynthian-packages/tree/main/Soundfonts">más detalles sobre los instrumentos muestreados &nbsp;&nbsp;&gt;</a>

### Más de 1,000 efectos de audio & herramientas MIDI
+ **Efectos de audio clásicos** con elementos esenciales como reverb, delay, chorus, distortion, saturation, EQ, compression, flanger, phaser, y wah-wah.
+ **Efectos de audio modernos** incluyendo tape simulators, granulators, vocoders, pitch-shifters, y auto-tune.
+ **Modelado de redes neuronales** para una emulación precisa de equipos no lineales como la mayoría de los amplifiers y stompboxes. Instala tus tonos favoritos desde [Tone3000](https://tone3000.com) con solo unos pocos clics.
+ **Impulse response modeling** para reverb y emulación de cabinet.
+ **Herramientas MIDI** como velocity curves, chorders, arpeggiators, monophonic converters, strumming utilities, y harmony analyzers.

<a class="minilink" href="/engines#effects">más detalles sobre los FXs de audio & las herramientas MIDI &nbsp;&nbsp;&gt;</a>

### Paquetes de extensiones gratuitos
Zynthian se puede ampliar fácilmente con paquetes, instalables con un solo clic. Los paquetes pueden contener instrumentos sampleados, colecciones de samples, loops, patrones e IRs. Los usuarios pueden crear sus propios paquetes y compartirlos con la comunidad.

<a class="minilink" href="https://zynthian.github.io/zynthian-packages/">más detalles sobre los paquetes de extensión &nbsp;&nbsp;&gt;</a>

### Herramientas de Producción
+ **[Zynseq](/use-case/groovebox-udaw)** es un step sequencer completo con captura en directo, quantization, operaciones por bloques y swing. Incluye humanización de velocity y tiempo, frecuencia y probabilidad de reproducción de los pasos, efectos avanzados de stutter y automatización de parámetros.
+ **[Clippy](/use-case/groovebox-udaw)** es un motor de audio-clip que te permite reproducir samples de audio sincronizados con el tempo con auto-warping y beat-slicing en tiempo real.
+ **[Lanzador](/use-case/groovebox-udaw)** es una cuadrícula de control para actuaciones en directo que te permite disparar patrones, clips de audio o frases musicales organizados en filas secuenciales. Programa cambios precisos de compás y tempo, loops de frases y la reproducción condicional de frases para conseguir *Da Capo* y *CODA* comportamiento.
+ **[Zynmixer](/use-case/groovebox-udaw)** es un mezclador potente y flexible que sigue siendo intuitivo y ofrece funciones de canal profesionales: conmutación mono/stereo, inversión de fase, conmutadores M+S, mixbuses personalizables, niveles de envío independientes, AB-mixing y escucha pre-fader (PFL).
+ **[SooperLooper](https://sonosaurus.com/sooperlooper/features.html)** de Jesse Chappell es un looper de audio en directo multicanal inspirado en el legendario **Gibson Echoplex Digital Pro (EDP)** hardware. Ofrece grabación inmediata de loops, overdubbing multicapa, multiplicación de loops, inversión en tiempo real, y decaimiento variable del feedback.
+ **[Integración nativa con controladores MIDI populares](https://wiki.zynthian.org/index.php/Supported_plug_%26_play_MIDI_controllers)** ofrece compatibilidad plug-and-play con estándares de la industria como el Akai APC40, APC Key 25, y MIDI Mix, los Novation Launchpads y Launchkeys, el Korg nanoKONTROL, y superficies de control Mackie Control Universal (MCU) completas.
+ **Grabadora de audio multipista** permite capturar cadenas individuales de instrumentos y efectos de forma independiente en una sesión WAV multipista impecable.
+ **Grabador/reproductor de archivos MIDI** te permite grabar, guardar, y reproducir fácilmente archivos MIDI estándar (.MID) sobre la marcha.
+ **[Pure Data](http://www.pd-tutorial.com/english/index.html)** integra un potente lenguaje de programación visual para el diseño sonoro personalizado de audio y MIDI.

<a class="minilink" href="/use-case/groovebox-udaw">más detalles sobre herramientas de producción &nbsp;&nbsp;&gt;</a>
