---
title: Surge
media_order: surge.png
description: Surge è un sintetizzatore digitale e non ne fa mistero. Nel suo cuore
  pulsa un motore ibrido a sintesi sottrattiva con una potente catena di effetti.
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
subtitle: Sintetizzatore ibrido
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
Surge utilizza un algoritmo di sintesi ibrida sottrattiva. Ogni patch contiene due «scene», che sono istanze separate dell’intero motore di sintesi (effetti esclusi) e possono essere utilizzate per creare patch sovrapposte o suddivise..

Include una ricca libreria di suoni di fabbrica:

+ 1725 patch
+ 523 wavetable

##Funzionalità
**Oscillatori:**
+ 3 oscillatori per scena.
+ 8 algoritmi versatili per oscillatori: Classic, Sine, Wavetable, Window, FM2, FM3, S&H Noise e Audio Input.
+ L'oscillatore Classic è un oscillatore morphable a onda pulse/saw/dual saw con un sub-oscillatore e hard sync.
+ Gli oscillatori FM2/FM3 sono composti da una portante e da 2 o 3 modulatori e varie opzioni.
+ La maggior parte degli algoritmi (tranne FM2, FM3 e Audio input) offre un unisono fino a 16 voci a livello dell'oscillatore..
+ FM dell'oscillatore e modulazione ad anello tra gli oscillatori 1-2 e 2-3.
+ La maggior parte degli algoritmi di oscillatore (tranne FM2, FM3 e Sine) è strettamente limitata in banda, ma copre comunque l’intero spettro udibile, offrendo un suono incisivo e pulito..
+ Generatore di rumore con spettro variabile.

**Blocco filtro:**
+ Due unità filtro in 8 configurazioni diverse.
+ Loop di feedback disponibile in 7 di quelle configurazioni.
+ Algoritmi di filtro disponibili: Lowpass (12 e 24 dB/oct, ciascuno con 3 variazioni), Lowpass 24 dB/oct (3 variazioni), Ladder Lowpass (6-24 dB/oct), Highpass (12 e 24 dB/oct, ciascuno con 3 variazioni), Bandpass (12 e 24 dB/oct, ciascuno con 3 variazioni), Notch (12 e 24 dB/oct, ciascuno con 2 variazioni), Comb (4 variazioni), S&H.
+ I filtri possono auto-oscillare (con eccitazione) e rispondere in modo incredibilmente rapido alle variazioni della frequenza di cutoff.
+ Waveshaper (5 forme).

**Modulazione:**
+ 12 unità LFO disponibili, 6 per voce e 6 globali per l'intera scena.
+ Generatori di inviluppo DAHDSR su ogni LFO.
+ 7 forme d’onda LFO deformabili e modalità step sequencer.
+ Gli LFO vocali consentono il retriggering dell’inviluppo quando vengono usati come step sequencer.
+ Instradamento della modulazione estremamente rapido e flessibile. È possibile modulare quasi tutti i parametri continui!

**Effetti:**
+ 8 unità di effetti disposte con 2 insert per scena, 2 send e 2 effetti master.
+ 13 algoritmi di effetto: EQ, Distortion, Conditioner (EQ, controllo dell'immagine stereo e limiter), Frequency Shifter, Rotary Speaker, Ring Modulator, Vocoder, Chorus, Phaser, Flanger, Delay, Reverb 1, Reverb 2
