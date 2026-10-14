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
subtitle: Coleção de plugins
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
x42-whirl foi projetado para imitar o som e as propriedades do dispositivo eletromecânico de alto-falante giratório que trouxe fama mundial ao nome e aos produtos de Don Leslie.

É uma versão independente do efeito que surgiu com o synth setBfree. Em vez de simular o efeito líquido do dispositivo eletromecânico, o x42-whirl modela fisicamente suas propriedades, resultando em uma representação muito precisa do som do dispositivo real..

Como todas as partes individuais são modeladas, x42-whirl não apenas oferece controle avançado, mas também facilita personalizações, algumas das quais não são viáveis no dispositivo mecânico.

#### Detalhes
O fluxo de sinal corresponde ao encontrado no hardware original. Para maior comodidade, ele é exibido na interface do plugin. São usados dois filtros para separar os graves e os agudos, que são enviados aos alto-falantes de corneta e de tambor. Um EQ adicional permite personalizar o som do driver de alta frequência..

O coração do efeito é um alto-falante de corneta rotativa. Duas cornetas são visíveis, mas uma (a escura na GUI) é falsa, servindo principalmente para cancelar a força centrífuga da outra durante a rotação. O plugin usa uma combinação de deslocamento Doppler e respostas ao impulso com deslocamento zero dependente do ângulo para uma corneta Model 600 (a corneta Model 44W é idêntica à da Model 600 e, aparentemente, padrão em todos os modelos Leslie [1]). A medição da corneta foi realizada por J.O. Smith III et al([2]). O som do woofer é dominado por uma modulação de amplitude causada pelo recorte do tambor rotativo.

x42-whirl calcula seis reflexões dependendo dos ângulos da corneta e do tambor, bem como da distância e da posição dos microfones, para emular a dispersão reverberante correspondente às dimensões e às características de dispersão da caixa. Além disso, o modelo leva em conta artefatos como o vazamento de sinal do tweeter, que não passa pela corneta.

O controle do motor permite definir duas velocidades-alvo (lenta/chorale e rápida/tremolo) para cada um dos rotores de horn e drum em RPM, bem como constantes de tempo de aceleração e desaceleração em segundos (para atingir metade da velocidade). Embora isso não leve em conta o atrito, é semelhante a uma configuração original devidamente lubrificada..

Às vezes, a corneta ou o tambor fica voltado para a parte de trás do gabinete quando para, o que resulta em um som menos desejável. Uma configuração opcional adicional permite definir uma posição de parada.

Por conveniência, o estágio de saída inclui dois matrix mixers estéreo que permitem reduzir o campo estéreo e aumentar a compatibilidade mono..

#### Nota sobre parâmetros
Por padrão, o plugin usa configurações correspondentes a um Model 44 (velocidades de rotação, raio do tambor e da corneta) e a uma técnica característica de microfonação esquerda/direita de 180deg. No entanto, os vários aspectos podem ser personalizados..

A posição descentralizada da corneta é considerada no cálculo das reflexões do gabinete; no entanto, os microfones estão posicionados simetricamente, à mesma distância do centro do rotor. Aumentar os raios aumenta a modulação de frequência Doppler; aumentar a distância dos microfones altera sutilmente o espectro devido ao tempo de percurso diferente do sinal para cada posição de reflexão e do alto-falante..

Todas as distâncias são medidas a partir do centro de cada rotor. O plugin permite algumas configurações impossíveis no mundo real (por exemplo, mover a captação do microfone para dentro do dispositivo rotativo). Esses casos afetam apenas os cálculos de distância e ângulo e não corresponderão ao que você ouviria se fosse possível fazê-lo mecanicamente. Embora o objetivo seja modelar o dispositivo da forma mais realista possível, essas configurações foram mantidas no plugin porque podem gerar sons interessantes, que, no fim das contas, é o que importa..
