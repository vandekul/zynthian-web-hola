---
title: Surge
media_order: surge.png
description: Surge est un synthétiseur numérique et ne s’en cache pas. En son cœur
  bat un moteur hybride soustractif doté d’une puissante chaîne d’effets.
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
subtitle: Synthétiseur hybride
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
Surge utilise un algorithme de synthèse hybride soustractive. Chaque patch contient deux « scènes » qui sont des instances distinctes de l'ensemble du moteur de synthèse (à l'exception des effets) pouvant être utilisées pour créer des patchs superposés ou répartis..

Il comprend une riche bibliothèque de sons d’usine.:

+ 1725 patchs
+ 523 wavetables

##Fonctionnalités
**Oscillateurs:**
+ 3 oscillateurs par scène.
+ 8 algorithmes d’oscillateur polyvalents : Classic, Sine, Wavetable, Window, FM2, FM3, S&H Noise et entrée audio.
+ L’oscillateur Classic est un oscillateur à impulsion/dent de scie/double dent de scie à morphing, avec un sous-oscillateur et une synchronisation dure..
+ Les oscillateurs FM2/FM3 se composent d’une porteuse, de 2 ou 3 modulateurs et de diverses options..
+ La plupart des algorithmes (à l’exception de FM2, FM3 et de l’entrée audio) proposent un unisson jusqu’à 16 voix au niveau de l’oscillateur..
+ FM et modulation en anneau entre les oscillateurs 1-2 et 2-3.
+ La plupart des algorithmes d’oscillateur (à l’exception de FM2, FM3 et Sine) sont strictement band-limited, tout en couvrant l’ensemble du spectre audible et en produisant un son clair, percutant et pur..
+ Générateur de bruit à spectre variable.

**Bloc de filtre:**
+ Deux unités de filtre dans 8 configurations différentes.
+ Boucle de rétroaction disponible dans 7 de ces configurations.
+ Algorithmes de filtre disponibles : passe-bas (12 et 24 dB/oct, chacun avec 3 variantes), passe-bas 24 dB/oct (3 variantes), passe-bas Ladder (6-24 dB/oct), passe-haut (12 et 24 dB/oct, chacun avec 3 variantes), passe-bande (12 et 24 dB/oct, chacun avec 3 variantes), réjecteur (12 et 24 dB/oct, chacun avec 2 variantes), peigne (4 variantes), S&H.
+ Les filtres peuvent entrer en auto-oscillation (avec excitation) et réagir incroyablement vite aux changements de fréquence de coupure..
+ Waveshaper (5 formes).

**Modulation:**
+ 12 unités LFO disponibles, 6 sont par voix et 6 sont globales pour toute la scène.
+ Générateurs d’enveloppe DAHDSR sur chaque LFO.
+ 7 formes d’onde LFO déformables et mode séquenceur à pas.
+ Les LFO de voix permettent de redéclencher l’enveloppe lorsqu’ils sont utilisés comme séquenceur pas à pas.
+ Routage de modulation extrêmement rapide et flexible. Presque tous les paramètres continus peuvent être modulés!

**Effets:**
+ 8 unités d’effets disposées en 2 inserts par scène, 2 sends et 2 effets master.
+ 13 algorithmes d’effets : EQ, Distortion, Conditioner (EQ, contrôle de l’image stéréo et limiteur), Frequency Shifter, Rotary Speaker, Ring Modulator, Vocoder, Chorus, Phaser, Flanger, Delay, Reverb 1, Reverb 2
