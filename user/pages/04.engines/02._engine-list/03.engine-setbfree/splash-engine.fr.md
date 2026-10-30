---
title: setBfree
id: setbfree
description: Émulateur Hammond B3 et Leslie hautement personnalisable
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
setBfree est un synthétiseur logiciel contrôlé par MIDI, conçu pour imiter le son et les caractéristiques des orgues électromécaniques et des dispositifs de modification du son qui ont fait connaître dans le monde entier les noms et les produits de Laurens Hammond et Don Leslie..

## Fonctionnalités:
setBfree est un *Kit de construction d’orgue à roues phoniques*, un modèle physique avec plus de 1000 paramètres configurables. Comme un vrai B3, on peut « l’ouvrir » et ajuster les paramètres, de l’état mint'53 (par défaut) à un état délabré de tube poussiéreux des années 80.

Lorsqu’il fonctionne sur zynthian, setBfree propose 7 configurations de clavier prédéfinies combinant claviers et pédalier.:
+ **Haut:** 1 clavier (1 x canal MIDI)
+ **Supérieur + inférieur:** 2 claviers (2 x canaux MIDI)
+ **Clavier supérieur + pédales:** 2 claviers (2 x canaux MIDI)
+ **Supérieur + Inférieur + Pédales:** 3 claviers (3 x canaux MIDI)
+ **Séparer grave/aigu:** 1 clavier (1 x canal MIDI)
+ **Pédales séparées/Supérieur:** 1 clavier (1 x canal MIDI)
+ **Pédales divisées/Inférieur/Supérieur:** 1 clavier (1 x canal MIDI)

Sur zynthian, setBfree propose également 4 types de forme d’onde pour le générateur tone-wheel.:
+ **Sine:** son Hammond
+ **Carré:** Son d’orgue combo
+ **Triangle:** Son d’orgue combo
+ **Dent de scie:** Son d'orgue combo

Toutes les commandes peuvent être assignées à des MIDI-CC selon les besoins via le mécanisme MIDI-learn..

