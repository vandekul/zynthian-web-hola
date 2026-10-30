---
title: MDA JX-10
id: mda-jx10
description: Synthétiseur soustractif inspiré de certaines machines Roland des années
  1980
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
MDA JX-10 est un synthétiseur logiciel soustractif inspiré de certaines machines Roland des années 80. Il consomme très peu de ressources et la qualité sonore est excellente..

Il fournit deux oscillateurs (saw et pulsewidth) qui peuvent être isolés ou mélangés. La polyphonie s’obtient en réglant le contrôle du glide : zéro pour le mode polyphonique, maximum pour le mode monophonique. Des enveloppes ADSR standard sont fournies pour le timbre (filter) et l’amplitude. Le Pitchbend est réglé sur un ton entier. La profondeur du LFO est directement reliée à la molette de modulation. J’ai ajouté une démo pour donner une idée du filtre LP très riche (dernière démo ci-dessus).

Au XXe siècle, les plugins de Maxim Digital Audio (mda) figuraient parmi les premiers plugins VST disponibles sous Windows. Ils sont réputés pour leur grande qualité et leur faible utilisation du CPU. Il y a plusieurs années, le code source de ces plugins a été publié et David Robillard a porté les plugins mda au format LV2. La plupart des plugins mda sont des effets, mais il existe également quatre instruments : DX10, JX10, Piano et ePiano.

## Fonctionnalités:
+ 2 oscillateurs fixes (Mix sélectionnable entre 100:0 et 50:50) & Noise
+ Accordage de l’oscillateur +-24 demi-tons
+ Filtre résonant (contrôlable par Env/LFO/Velocity)
+ ADSR pour VCF & Amp/Env
+ Glide - 6 modes (Poly, P-Legato, P-Glide, Mono, M-Legato, M-Glide)
+ LFO
+ Vibrato
+ Accordage du synthé +-2 octaves
+ Faible utilisation du CPU
+ Banque par défaut de 52 patches
+ Pas de GUI
