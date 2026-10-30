---
title: OBX-D
id: obxd
description: Sintetizzatore software ispirato ad alcuni classici dispositivi Oberheim
  degli anni '80
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-kb
  - ucase-pr
  - synth-emu
  homepage:
  - 'yes'
date: 17:38 24-04-2020
subtitle: Oberheim Emulator
splash:
  bg_image: obxd-hero_small.png
  bg_image_landscape: obxd-hero.png
media_thumb: obxd.jpg
sitemap:
  lastmod: 07-05-2026 16:19
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=NdfcgiLsp88
audio:
- audioType: local
  audioFile: OBXdLoveByHumi.mp3
  audioLabel: Oberheim Love, by Humi
- audioType: local
  audioFile: chirpybellstwo.ogg
  audioLabel: Chirpy Bells 2
- audioType: local
  audioFile: lotshappenin.ogg
  audioLabel: Lots Happenin
- audioType: local
  audioFile: madderthan.ogg
  audioLabel: Madderthan
- audioType: local
  audioFile: saladdressing.ogg
  audioLabel: Salad Dressing
- audioType: local
  audioFile: withair.ogg
  audioLabel: Withair
urls:
- urlLink: http://www.linuxsynths.com/ObxdPatchesDemos/obxd.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/2DaT/Obxd
  urlLabel: Source Code
---
OBXD è un sintetizzatore monofonico/polifonico a 8 voci in tempo reale sviluppato da 2DaT, Layzer e Breeze (su KVR) e recentemente portato su Linux. OBXD è disponibile nei formati LV2 e VST e può essere eseguito nella maggior parte degli host, come Ardour, Carla, Jalv e Qtractor..

OBXD include molte caratteristiche del celebre synth hardware OB-X degli anni '80, oltre ad alcune modifiche (vedere i link al manuale qui sotto). Sono presenti due oscillatori con controlli di livello discreti e una manopola per il livello del noise, forme d’onda saw e square indipendenti con controllo della pulsewidth modulation; una manopola di cross-modulation, un pulsante sync e un pulsante step (per regolare l’accordatura dell’oscillatore in semitoni anziché in modo continuo). Sono inclusi il pulsante della modalità Unison (tutte le note polifoniche vengono sovrapposte in un’unica voce monofonica più corposa), spread, glide (portamento), accordatura e controllo di trasposizione dell’ottava. La manopola "Bright" controlla la precisione delle frequenze più alte dello spettro sonoro, mentre la manopola "P Env" fornisce un inviluppo dell’intonazione, collegato direttamente alla sezione dell’inviluppo del filtro..

## Funzionalità:
La sezione filtro di OBXD dispone di un filtro multi-mode a 12 dB. Oltre ai tradizionali controlli di cutoff, resonance ed envelope depth, questa sezione consente di controllare key follow, l'interpolazione di alta qualità (che aumenta leggermente il consumo di CPU) e il controllo multi-mode.

La manopola "Multi" consente di passare tra le seguenti opzioni di filtro: low-pass (manopola a sinistra), notch (posizione centrale) e high-pass (manopola a destra). Attivando il pulsante "BP" si ottiene un filtro bandpass invece di notch (manopola in posizione centrale). Il pulsante "24dB" offre un filtro lowpass a 24 dB, che passa da 24 dB (manopola a sinistra) a 6 dB (manopola a destra).

C'è un pulsante VAM (voice allocation mode) che dà priorità all'ultima nota invece che alla nota più bassa. La Control Section include un intervallo di bend di 12 semitoni (2 note quando disattivato) e un pulsante per il bend solo dell'oscillatore 2. Vibrato Rate è collegato direttamente alla modwheel, ma interagisce anche con la manopola LFO rate in modi interessanti. La Control Section ha anche controlli di sensibilità alla velocity sia del filtro che dell'ampiezza..

La sezione LFO include forme d’onda sinusoidali, quadre e sample-and-hold, che possono essere mixate tra loro. La sezione Voice Variation offre un ulteriore controllo di filtro, glide e ampiezza, mentre Voice Pan consente di controllare indipendentemente la direzione del pan di ciascuna delle 8 voci..

