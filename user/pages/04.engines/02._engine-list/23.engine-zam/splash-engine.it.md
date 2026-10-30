---
title: ZAM Plugins
media_order: redwave.jpg
description: Una raccolta di plugin per l'elaborazione audio
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - fx-delay
  - fx-mod
  - fx-other
  - ucase-fx
  - fx-eq
  - fx-filter
  - fx-dynamics
  - fx-distortion
date: 17:38 24-04-2020
subtitle: Raccolta di plugin
splash:
  bg_image_landscape: redwave-hero.jpg
  bg_image: redwave-hero_small.jpg
media_thumb: redwave.jpg
audio:
- audioType: local
  audioFile: angie-20141010_follow.ogg
  audioLabel: Follow, by Angie Hudson (2013)
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=MGErjKRu_dQ
urls:
- urlLink: http://www.zamaudio.com/
  urlLabel: ZamAudio's Website
- urlLink: http://github.com/zamaudio/zam-plugins
  urlLabel: Source Code
---
Zam-plugins è una raccolta di plugin audio LV2/LADSPA/VST/JACK per l'elaborazione del suono, sviluppati internamente da ZamAudio. Le impostazioni predefinite e quasi tutti i cursori sono calibrati su intervalli standard..

Un grande grazie a falktx per aver scritto Distrho Plugin Framework. Mi ha permesso di realizzare rapidamente e con ordine queste GUI per zam-plugins. Grazie anche a mira, nphilipp, adi, edogawa e Haskellfant per aver contribuito a pacchettizzare il software per diverse distribuzioni.!

## Panoramica

#### ZaMaximX2
Uno dei migliori plugin della serie, nello stato predefinito funziona come un limiter brickwall per il mastering, ma può anche essere regolato per aumentare il livello medio come stereo maximizer senza mai andare in clipping. Suona musicale anche se usato in modo estremo. (Basato sul DSP descritto in un articolo DAFX’02).

#### ZamAutoSat
Un plugin di saturazione automatica, è noto per fornire un livellamento uniforme ai canali microfonici live.
Puoi applicare questo plugin abbondantemente senza influire sul tono.

#### ZamComp
Una potente strip di compressione mono. Aggiunge corpo a kick o snare con le impostazioni giuste..

#### ZamCompX2
Versione stereo di ZamComp con controllo dello slew del knee.

#### ZamEQ2
Equalizzatore parametrico a due bande con circuiti shelving per alte e basse frequenze.

#### ZamGEQ31
Equalizzatore grafico a 31 bande, ideale per l’equalizzazione degli ambienti dal vivo, per rimuovere i rumori indesiderati da una traccia, ecc..

#### ZamHeadX2
Plugin di filtraggio acustico HRTF per audio direzionale.

#### ZamPhono
Una raccolta di filtri phono per restaurare dischi in vinile o prepararne di nuovi per il taglio.

#### ZamGate
Plugin Gate per il ducking dei suoni a basso gain.

#### ZamGateX2
Plugin Gate per attenuare i suoni a basso Gain, versione stereo.

#### ZamTube
Effetto di distorsione mostruoso. Filtro digitale a onde con modello fisico di uno stadio di amplificatore a valvole triodo, con tone stack modellati da veri amplificatori per chitarra (grazie a D. Yeh et al.).

#### ZamDelay
Una semplice unità Delay con feedback, funzione di sincronizzazione al BPM dell'host e filtro.

#### ZamDynamicEQ
Un equalizzatore dinamico che modifica il proprio Gain in base al rilevamento di una banda di frequenze ristretta. Può essere regolato per modificare al volo altre gamme di frequenza..

#### ZaMultiComp
Compressore multibanda mono, con 3 bande regolabili.

#### ZaMultiCompX2
Prodotto di punta di zam-plugins: versione stereo di ZaMultiComp, con controlli individuali della soglia per ogni banda e visualizzazione in tempo reale delle curve di compressione.
