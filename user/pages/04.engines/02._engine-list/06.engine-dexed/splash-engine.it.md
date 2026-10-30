---
title: Dexed
id: dexed
image: dexed.jpg
description: Sintetizzatore FM ispirato ai classici Yamaha DX7 e TX7 degli anni ’80
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - ucase-kb
  - ucase-pr
  - synth-emu
  - synth-fm
  homepage:
  - 'yes'
date: 17:38 24-04-2020
subtitle: FM Synthesizer
splash:
  bg_image_landscape: dexed-hero.png
  bg_image: dexed-hero_small.png
media_thumb: dexed.jpg
sitemap:
  lastmod: 07-05-2026 14:15
urls:
- urlLink: https://asb2m10.github.io/dexed
  urlLabel: Project's Website
- urlLink: http://www.linuxsynths.com/DexedPatchesDemos/dexed.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/asb2m10/dexed
  urlLabel: Source Code
- urlLink: https://yamahablackboxes.com/collection/yamaha-dx7-synthesizer/
  urlLabel: Yamaha DX7 Info
audio:
- audioLink: https://soundcloud.com/starling-studios/mmoncur-hexed-osc74
  audioLabel: mmoncur - Hexed (OSC74)
  audioType: soundcloud
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=wSs1-020nNY
---
Dexed è un softsynth di tipo FM sviluppato da Pascal Gauthier di Digital Suburban. È un'applicazione ideale per importare, riprodurre e modificare/gestire patch sysex sia del classico sintetizzatore Yamaha DX7 che del TX7.

Dexed include sei operatori, fedeli alla struttura DX. Ogni operatore ha un indicatore di livello. Gli operatori possono essere disposti in vari algoritmi, indicati dai riquadri verdi. I banchi di patch sono chiamati "cartucce" e ce ne sono molti (circa 32) inclusi nel pacchetto di installazione. Selezionando una cartuccia si caricano le patch del banco corrispondente.

Dexed può essere configurato per utilizzare alcune delle limitazioni matematiche originali di un sintetizzatore DX. Questo non riguarda solo il DAC, ma anche la risoluzione in bit delle onde sinusoidali e il modo in cui l'ampiezza viene applicata a ciascun operatore. Poiché tutto questo è sperimentale, saranno disponibili più motori per poterli confrontare facilmente..

Dexed include 3 tipi di motore:
+ **Moderno:** questa è l'implementazione originale di music-synthesizer-for-android a 24 bit.
+ **Mark I:** Basato sulla serie OPL ma con una risoluzione più alta (le LUT sono a 10 bit). L'obiettivo di questo motore è avvicinarsi il più possibile al DX7 reale..
+ **Serie OPL:** questa è un’implementazione sperimentale dei chip della famiglia OPL ottenuta tramite reverse engineering. 8-bit. Tieni presente che gli inviluppi devono ancora essere regolati.

## Funzionalità:
+ Multi piattaforma (OS X, Windows o Linux) e multi formato (VST, AU, LV2)
+ Il motore sonoro music-synthesizer-for-android è modellato fedelmente sulle caratteristiche del DX7 originale
+ 144 parametri DX7 automatizzabili dalla DAW disponibili da un unico pannello
+ Supporta pienamente i messaggi sysex in ingresso e in uscita del DX7; inclusi i controller change. Questo significa che puoi usarlo con un DX7/TX7 nativo come editor di patch e gestore sysex.
+ Ogni operatore ha un VU meter in tempo reale per sapere quale è attivo
+ Può caricare/salvare qualsiasi programma Sysex DX7/TX7. È anche possibile salvare un singolo programma in un file Sysex diverso..
