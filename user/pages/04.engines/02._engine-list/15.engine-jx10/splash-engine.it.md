---
title: MDA JX-10
id: mda-jx10
description: Sintetizzatore software sottrattivo ispirato ad alcune macchine Roland
  degli anni '80
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-kb
  - synth-emu
date: 17:38 24-04-2020
subtitle: JX-8p/JX-10 Emulator
splash:
  bg_image_landscape: djx10-hero.jpg
  bg_image: djx10-hero_small.jpg
media_thumb: djx10.jpg
urls:
- urlLink: http://mda.smartelectronix.com
  urlLabel: MDA's Website
- urlLink: https://github.com/moddevices/mda-lv2
  urlLabel: MDA-LV2 Source Code
audio:
- audioType: local
  audioFile: fifthsweeppad.ogg
  audioLabel: Fifth Sweep Pad
- audioType: local
  audioFile: hardlead.ogg
  audioLabel: Hard Lead
- audioType: local
  audioFile: solidbacking.ogg
  audioLabel: Solid Backing
- audioType: local
  audioFile: detunedsynbrass.ogg
  audioLabel: Detuned Syn-Brass
- audioType: local
  audioFile: sawbass.ogg
  audioLabel: Saw Bass
- audioType: local
  audioFile: touchyfellow.ogg
  audioLabel: Touchy Fellow
- audioType: local
  audioFile: helicopter.ogg
  audioLabel: Helicopter
- audioType: local
  audioFile: wobblebass.ogg
  audioLabel: Wobble Bass
- audioType: local
  audioFile: filterdemo.ogg
  audioLabel: Filter Demo
---
MDA JX-10 è un sintetizzatore software sottrattivo ispirato ad alcune macchine Roland degli anni '80. Consuma pochissime risorse e la qualità del suono è ottima..

Offre due oscillatori (a dente di sega e pulsewidth) che possono essere isolati o miscelati. La polifonia si ottiene usando l'impostazione del controllo glide: zero per il controllo polifonico, max per quello monofonico. Sono disponibili inviluppi ADSR standard per il timbro (filtro) e l'ampiezza. Il Pitchbend è impostato su un tono intero. La profondità dell'LFO è collegata direttamente alla modulation wheel. Ho aggiunto una demo per dare un'idea del filtro LP molto ricco (ultima demo sopra).

Nel XX secolo, i plugin di Maxim Digital Audio (mda) erano tra i primi plugin VST disponibili per Windows. Sono noti per l'elevata qualità e il basso utilizzo della CPU. Alcuni anni fa è stato rilasciato il codice sorgente di questi plugin e David Robillard ha convertito i plugin mda in formato LV2. La maggior parte dei plugin mda sono effetti, ma ci sono anche quattro strumenti: DX10, JX10, Piano ed ePiano.

## Funzionalità:
+ 2 oscillatori fissi (Mix selezionabile tra 100:0 e 50:50) & Noise
+ Accordatura dell'oscillatore +-24 semitoni
+ Filtro risonante (Controllabile da Env/LFO/Velocity)
+ ADSR per VCF & Amp/Env
+ Glide - 6 modalità (Poly, P-Legato, P-Glide, Mono, M-Legato, M-Glide)
+ LFO
+ Vibrato
+ Accordatura del synth +-2 ottave
+ Basso utilizzo della CPU
+ Banco predefinito di 52 patch
+ Nessuna GUI
