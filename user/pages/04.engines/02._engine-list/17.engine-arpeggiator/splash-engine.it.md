---
title: Arpeggiator
media_order: arpeggiator.jpg
description: Un semplice plugin MIDI per arpeggi e pattern MIDI
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - effect
  - fx-midi
date: 17:38 24-04-2020
subtitle: Un semplice plugin per arpeggi e pattern MIDI
splash:
  bg_image_landscape: arpeggiator-hero.jpg
  bg_image: arpeggiator-hero_small.jpg
media_thumb: arpeggiator.jpg
urls:
- urlLink: https://github.com/BramGiesen/arpeggiator_LV2
  urlLabel: Source Code
---
Arpeggiatore e un plugin per pattern MIDI sviluppato per la piattaforma MOD da Bram Giesen.

####Arpeggiator
L'arpeggiatore ha le seguenti opzioni:

**Opzioni di tempo:**
Ci sono alcune opzioni per impostare il tempo del plugin. La prima è la modalità Free Running. In questa modalità, il tempo è controllato dal controllo BPM del plugin. Sopra il controllo BPM c'è un controllo Divisions. Il plugin può anche essere sincronizzato con l'host.

**Modalità dell’arpeggiatore:**
L’arpeggiatore ha le seguenti modalità:
+ Su
+ Giù
+ Su-Giù
+ Su-Giù(alternativa)
+ Riprodotto
+ Casuale

**Modalità di ottava:**
L'arpeggiatore dispone di un controllo dell'estensione delle ottave. L'arpeggiatore può ripetere le note in ingresso su più ottave. Questo controllo imposta l'estensione delle ottave in cui verrà ripetuta la nota originale. Il modo in cui queste ottave verranno aggiunte alle note originali è determinato dal controllo della modalità delle ottave..

####MIDI-pattern
Il plugin MIDI-pattern può essere utilizzato per creare pattern ritmici. Il plugin prende la nota in ingresso e sostituisce la velocity della nota con un valore impostato da uno dei fader del plugin. Poiché il plugin scorre i fader, genera una sorta di sequenza ritmica. Il controllo CV del plugin può essere utilizzato per riattivare la sequenza.
