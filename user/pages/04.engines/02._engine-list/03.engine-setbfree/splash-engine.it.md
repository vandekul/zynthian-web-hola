---
title: setBfree
id: setbfree
description: Emulatore Hammond B3 e Leslie altamente personalizzabile
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-add
  - ucase-kb
  - synth-emu
  - synth-phy
  homepage:
  - 'yes'
date: 17:38 10-03-2020
subtitle: Tonewheel Organ Emulator
splash:
  bg_image: setbfree-hero_small.jpg
  bg_image_landscape: setbfree-hero.jpg
media_thumb: setbfree.jpg
sitemap:
  lastmod: 07-05-2026 14:23
urls:
- urlLink: http://setbfree.org
  urlLabel: Project's Website
- urlLink: http://www.linuxsynths.com/SetBfreePatchesDemos/setbfree.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/pantherb/setBfree
  urlLabel: Source Code
video:
- videoType: vimeo
  videoLink: https://vimeo.com/130633814
  videoLabel: A rendition of Jimmy Smith's The Cat
audio:
- audioType: local
  audioFile: georgia_on_my_waltzin_mind.ogg
  audioLabel: Georgia on my waltzin mind, by TKC (MDA EPiano + setBfree)
- audioType: local
  audioFile: setBfreeDrawbarsManipulationByBaggypants.mp3
  audioLabel: Hammond Drawbars Manipulations, by Baggypants (setBfree)
- audioType: local
  audioFile: RhodesHammondByHumi.mp3
  audioLabel: Rhodes & Hammond, by Humi
---
setBfree è un sintetizzatore software controllato via MIDI, progettato per imitare il suono e le caratteristiche degli organi elettromeccanici e dei dispositivi di modifica del suono che hanno dato fama mondiale ai nomi e ai prodotti di Laurens Hammond e Don Leslie.

## Funzionalità:
setBfree è un *Kit di costruzione per organo tonewheel*, un modello fisico con oltre 1000 parametri configurabili. Come un vero B3, lo si può «aprire» e modificare i parametri, passando dalle condizioni di un esemplare del '53 appena uscito di fabbrica (predefinite) a quelle di un esemplare anni '80 malconcio e impolverato in cui le valvole sono consumate.

Quando viene eseguito su zynthian, setBfree offre 7 configurazioni di tastiera predefinite che combinano manuali e pedali:
+ **Superiore:** 1 tastiera (1 x canale MIDI)
+ **Superiore + Inferiore:** 2 tastiere (2 x canali MIDI)
+ **Superiore + Pedali:** 2 tastiere (2 x canali MIDI)
+ **Superiore + Inferiore + Pedali:** 3 tastiere (3 x canali MIDI)
+ **Dividi Inferiore/Superiore:** 1 tastiera (1 x canale MIDI)
+ **Pedali split/Superiore:** 1 tastiera (1 x canale MIDI)
+ **Split Pedali/Inferiore/Superiore:** 1 tastiera (1 x canale MIDI)

Su zynthian, setBfree offre anche 4 tipi di forma d'onda per il generatore tone-wheel.:
+ **Seno:** suono Hammond
+ **Quadrato:** Suono di organo Combo
+ **Triangolo:** Suono di organo combo
+ **Dente di sega:** Suono di organo combo

Tutti i controlli possono essere assegnati a MIDI-CC secondo necessità tramite il meccanismo MIDI-learn..

