---
title: SynthV1
id: synthv1
description: Synthétiseur polyphonique soustractif à 4 oscillateurs, vintage, avec
  effets stéréo
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-pr
date: 17:38 24-04-2020
subtitle: Virtual Analog Synthesizer
splash:
  bg_image_landscape: synthv1-hero.png
  bg_image: synthv1-hero_small.png
media_thumb: synthv1.png
audio:
- audioType: local
  audioFile: woodpecker.ogg
  audioLabel: Woodpecker
- audioType: local
  audioFile: undeniable.ogg
  audioLabel: Undeniable
- audioType: local
  audioFile: noizeexportdemo.ogg
  audioLabel: Noize Export Demo
- audioType: local
  audioFile: saturnone.ogg
  audioLabel: Saturn One
- audioType: local
  audioFile: spaceorgan.ogg
  audioLabel: Space Organ
- audioType: local
  audioFile: clavone.ogg
  audioLabel: Clav One
- audioType: local
  audioFile: bubbler.ogg
  audioLabel: Bubbler
- audioType: local
  audioFile: isitterrific.ogg
  audioLabel: Is it terrific?
- audioType: local
  audioFile: phasedout.ogg
  audioLabel: Phased Out
- audioType: local
  audioFile: solohornone.ogg
  audioLabel: Solo Horn One
- audioType: local
  audioFile: synthkeysfour.ogg
  audioLabel: Synth Keys Four
- audioType: local
  audioFile: eightmm.ogg
  audioLabel: Eight MM
- audioType: local
  audioFile: solohornthree.ogg
  audioLabel: Solohornthree
urls:
- urlLink: https://synthv1.sourceforge.io
  urlLabel: Project's Website
- urlLink: http://www.linuxsynths.com/Synthv1PatchesDemos/synthv1.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/rncbc/synthv1
  urlLabel: Source Code
---
SynthV1 est un synthétiseur polyphonique soustractif entièrement numérique à l’ancienne, doté de 4 oscillateurs et d’effets stéréo. Il est conçu et développé par Rui Nuno Capela, et fait partie de la Vee One Suite (qui comprend Padthv1, Samplv1 et Drumkv1). Il peut fonctionner comme synthétiseur autonome ou comme plugin LV2 dans une configuration DAW telle qu’Ardour ou QTractor. Il peut fonctionner dans une session Jack ou Non Session Management (NSM), et prend en charge Jack Midi et Alsa Midi..

## Fonctionnalités:
Synthv1 dispose de capacités polyphoniques (32 notes) et monophoniques, ainsi que de commandes de sensibilité à la velocity et à l’aftertouch. La disposition comprend deux pages identiques, nommées Synth 1 et Synth 2, ainsi qu’une troisième page (effets). Les deux pages de synthé comprennent une section DCO, une section Filter, une section Amplitude, une section LFO, une section Controller et une section General Output. La section Output contrôle le niveau audio par rapport à la sortie de l’autre synthé, ainsi que la quantité de signal d’effets.

La section oscillateur de chaque page comprend deux sélecteurs de forme d’onde, avec les formes d’onde classiques et leurs équivalents à bande limitée : pulse-to-square, triangle-to-saw, sine, random et noise. Un réglage à zéro (lorsqu’il est réglé sur pulse) désactive l’oscillateur. Une fonction sync est également incluse. Les knobs width modulent les formes d’onde ainsi que les signaux random et noise..

Le désaccordage de plus ou moins quatre octaves, ainsi qu’un réglage fin du désaccordage. Le Portamento (glide) et un réglage global de la vitesse de l’enveloppe ADSR se trouvent dans la partie supérieure droite de l’interface graphique..

La section Filtre propose des types de filtres 12-dB (à variable d’état), 24-dB (Stilson/Smith Moog) et biquadratiques : passe-bas, passe-haut, passe-bande et réjecteur de bande. Il y a également un filtre à formants. Des enveloppes ADSR traditionnelles sont fournies pour le filtre et l’amplitude, ainsi qu’une autre enveloppe ADSR pour la section LFO. Le LFO dispose d’un contrôle BPM qui peut être synchronisé au transport ou à la fréquence de l’hôte..

La section « DEF » comporte des commandes pour régler le pitchbend, la modulation et Velocity. La page Effects (non visible sur la capture d’écran ci-dessus) propose différents types d’effets : Chorus, flanger, phaser, Reverb et Delay, ainsi qu’un compresseur et un limiteur..
