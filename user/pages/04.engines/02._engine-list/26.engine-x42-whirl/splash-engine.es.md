---
title: X42 Whirl Speaker
media_order: x42-whirl.png
description: Rotary Speaker Simulator
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - effect
  - fx-mod
  - ucase-fx
date: 17:38 24-04-2020
subtitle: Colección de plugins
splash:
  bg_image_landscape: x42-whirl-hero.png
  bg_image: x42-whirl-hero_small.png
media_thumb: x42-whirl.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-whirl
  urlLabel: Whirl Speaker's Website
- urlLink: https://github.com/pantherb/setBfree
  urlLabel: Source Code
---
x42-whirl está diseñado para imitar el sonido y las características del dispositivo de altavoz giratorio electromecánico que dio fama mundial al nombre y a los productos de Don Leslie.

Es una versión independiente del efecto que se creó con el sintetizador setBfree. En lugar de simular el efecto neto del dispositivo electromecánico, x42-whirl modela físicamente sus propiedades, lo que da como resultado una representación muy precisa del sonido del dispositivo real.

Como todas las piezas individuales están modeladas, x42-whirl no solo ofrece un control avanzado, sino que también facilita las personalizaciones, algunas de las cuales no son viables en el dispositivo mecánico..

#### Detalles
El flujo de señal coincide con el del hardware original. Para mayor comodidad, se muestra en la UI del plugin. Se utilizan dos filtros para separar los graves y los agudos, que se envían a los altavoces de bocina y de tambor. Un EQ adicional permite personalizar el sonido del driver de altas frecuencias..

El corazón del efecto es un altavoz de bocina giratoria. Se aprecian dos bocinas, pero una (la oscura en la GUI) es ficticia y sirve principalmente para contrarrestar la fuerza centrífuga de la otra durante la rotación. El plugin utiliza una combinación de Doppler-shift y respuestas al impulso con desplazamiento cero dependiente del ángulo para una bocina Model 600 (la bocina Model 44W es idéntica a la de la Model 600 y, por lo visto, es estándar en todos los modelos Leslie [1]). La medición de la bocina fue realizada por J.O. Smith III et al([2]). El sonido del woofer está dominado por una modulación de amplitud causada por la concavidad del tambor giratorio.

x42-whirl calcula seis reflexiones según los ángulos de la bocina y el tambor, así como la distancia y posición de los micrófonos, para emular la dispersión reverberante correspondiente a las dimensiones y características de dispersión del gabinete. Además, el modelo tiene en cuenta artefactos como la fuga de señal del tweeter, que no pasa a través de la bocina.

El control del motor permite establecer dos velocidades objetivo (lenta/chorale y rápida/tremolo) para cada uno de los rotores de agudos y graves, en RPM, así como las constantes de tiempo de aceleración y desaceleración en segundos (para alcanzar la mitad de la velocidad). Aunque no tiene en cuenta la fricción, se aproxima a una configuración original correctamente lubricada..

A veces, la trompa o el tambor apunta hacia la parte trasera del recinto cuando se detiene, lo que produce un sonido poco deseable. Un ajuste opcional adicional permite establecer una posición de parada.

Por comodidad la etapa de salida incluye dos mezcladores matriciales estéreo que permiten reducir el campo estéreo y aumentar la compatibilidad mono.

#### Nota sobre los parámetros
Por defecto, el plugin utiliza ajustes correspondientes a un Model 44 (velocidades de rotación, radios del tambor y la bocina) y una característica técnica de microfonía izquierda/derecha de 180deg. Sin embargo, se pueden personalizar los distintos aspectos..

La posición descentrada de la bocina se tiene en cuenta en el cálculo de las reflexiones de la caja, sin embargo los micrófonos están colocados simétricamente a la misma distancia del centro del rotor. Al aumentar los radios aumenta la modulación de frecuencia Doppler; al aumentar la distancia de los micrófonos, el espectro cambia sutilmente debido a la diferente duración del recorrido de la señal para cada una de las posiciones de reflexión y del altavoz..

Todas las distancias se miden desde el centro de cada rotor. El plugin permite algunas configuraciones imposibles en el mundo real (p. ej., mover el micrófono dentro del dispositivo giratorio). En esos casos, solo se tienen en cuenta los cálculos de distancia y ángulo, y no se corresponderán con lo que podrías oír si fuera posible hacerlo mecánicamente. Aunque el objetivo es modelar el dispositivo con la mayor precisión posible, se mantienen en el plugin porque pueden dar lugar a sonidos interesantes, que, al fin y al cabo, es de lo que se trata..
