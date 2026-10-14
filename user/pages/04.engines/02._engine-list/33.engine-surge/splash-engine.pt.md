---
title: Surge
media_order: surge.png
description: Surge é um sintetizador digital e não esconde isso. Em seu núcleo pulsa
  um mecanismo híbrido de síntese subtrativa com uma poderosa cadeia de efeitos.
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-kb
  - ucase-pr
  homepage:
  - 'yes'
date: 17:38 20-10-2020
subtitle: Hybrid Synthesizer
splash:
  bg_image_landscape: surge-hero.png
  bg_image: surge-hero_small.png
media_thumb: surge.png
audio:
- audioType: soundcloud
  audioLink: https://soundcloud.com/user-589036812-258992427/surge-2237-ad
  audioLabel: 2237 AD
- audioType: soundcloud
  audioLink: https://soundcloud.com/user-589036812-258992427/surge-demo-001-microtonal-soundscape-1-x-surge
  audioLabel: Microtonal Soundscape
- audioType: soundcloud
  audioLink: https://soundcloud.com/theexponent/resurgence
  audioLabel: Resurgence
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=2GLp6FD6oVE
urls:
- urlLink: https://surge-synthesizer.github.io/
  urlLabel: Surge's Website
- urlLink: https://surge-synthesizer.github.io/manual/
  urlLabel: Surge's Manual
- urlLink: https://github.com/surge-synthesizer/surge
  urlLabel: Source Code
---
Surge usa um algoritmo de síntese híbrida subtrativa. Cada patch contém duas “cenas”, que são instâncias separadas de todo o motor de síntese (exceto pelos efeitos) e podem ser usadas para patches em camadas ou divididos..

Inclui uma rica biblioteca de sons de fábrica:

+ 1725 patches
+ 523 wavetables

##Recursos
**Oscillators:**
+ 3 osciladores por cena.
+ 8 algoritmos versáteis de oscilador: Classic, Sine, Wavetable, Window, FM2, FM3, S&H Noise e Entrada de áudio.
+ O oscilador Classic é um oscilador de pulso/dente de serra/duplo dente de serra com morphing, sub-oscilador e hard sync.
+ Os osciladores FM2/FM3 consistem em uma portadora e 2 ou 3 moduladores e várias opções.
+ A maioria dos algoritmos (exceto FM2, FM3 e Audio input) oferece uníssono de até 16 vozes no nível do oscilador.
+ FM do oscilador e modulação em anel entre osciladores 1-2 e 2-3.
+ A maioria dos algoritmos de oscilador (exceto FM2, FM3 e Sine) é estritamente limitada em banda, mas ainda cobre todo o espectro audível, proporcionando um som claro, impactante e limpo..
+ Gerador de ruído com espectro variável.

**Bloco de filtro:**
+ Duas unidades de filtro em 8 configurações diferentes.
+ Loop de feedback disponível em 7 dessas configurações.
+ Algoritmos de filtro disponíveis: Lowpass (12 e 24 dB/oct, cada um com 3 variações), Lowpass 24 dB/oct (3 variações), Ladder Lowpass (6-24 dB/oct), Highpass (12 e 24 dB/oct, cada um com 3 variações), Bandpass (12 e 24 dB/oct, cada um com 3 variações), Notch (12 e 24 dB/oct, cada um com 2 variações), Comb (4 variações), S&H.
+ Os filtros podem entrar em auto-oscilação (com excitação) e responder de forma surpreendentemente rápida a alterações na frequência de corte..
+ Waveshaper (5 formas).

**Modulation:**
+ 12 unidades LFO disponíveis, 6 são por voz e 6 são globais para toda a cena.
+ Geradores de envelope DAHDSR em cada LFO.
+ 7 formas de onda deformáveis de LFO e modo de sequenciador por etapas.
+ Os LFOs de voz permitem o retrigger do envelope quando usados como sequenciador por etapas..
+ Roteamento de modulação extremamente rápido e flexível. Quase todos os parâmetros contínuos podem ser modulados!

**Efeitos:**
+ 8 unidades de efeitos organizadas como 2 inserts por cena, 2 sends e 2 efeitos master.
+ 13 algoritmos de efeitos: EQ, Distortion, Conditioner (EQ, controle da imagem estéreo e limiter), Frequency Shifter, Rotary Speaker, Ring Modulator, Vocoder, Chorus, Phaser, Flanger, Delay, Reverb 1, Reverb 2
