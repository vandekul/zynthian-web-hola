---
title: SynthV1
id: synthv1
description: Sintetizzatore polifonico sottrattivo vintage a 4 oscillatori con effetti
  stereo
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
SynthV1 è un sintetizzatore sottrattivo polifonico old-school, completamente digitale, a 4 oscillatori con FX stereo. È progettato e sviluppato da Rui Nuno Capela e fa parte della Vee One Suite (che include Padthv1, Samplv1 e Drumkv1). Può funzionare come sintetizzatore standalone o come plugin LV2 all'interno di una configurazione DAW come Ardour o QTractor. Può funzionare in una sessione Jack o Non Session Management (NSM) e supporta Jack Midi e Alsa Midi..

## Funzionalità:
Synthv1 ha sia capacità polifonica (32 note) sia monofonica, oltre ai controlli di sensibilità a Velocity e Aftertouch. La struttura prevede due pagine identiche, denominate Synth 1 e Synth 2, più una terza pagina (effetti). Entrambe le pagine synth includono una sezione DCO, una sezione Filter, una sezione Amplitude, una sezione LFO, una sezione Controller e una sezione General Output. La sezione Output controlla il livello audio rispetto all’output dell’altro synth, oltre alla quantità di segnale degli effetti.

La sezione dell'oscillatore di ogni pagina include due selettori di forma d'onda, con le forme d'onda classiche e le relative versioni band-limited: da impulso a onda quadra, da triangolare a dente di sega, sinusoidale, casuale e rumore. Un'impostazione pari a zero (quando è impostata su impulso) disattiva l'oscillatore. È inclusa anche una funzione sync. I Knob Width modulano le forme d'onda, oltre ai segnali casuali e di rumore..

Detuning di quattro ottave in positivo e in negativo, più un detuning fine. Portamento (glide) e una regolazione globale della velocità dell’inviluppo ADSR si trovano nell’area in alto a destra della GUI.

La sezione Filter offre tipi di filtro 12-dB (a variabile di stato), 24-dB (Stilson/Smith Moog) e bi-quad: lowpass, highpass, bandpass e band-reject. È disponibile anche un filtro formante. Sono presenti inviluppi ADSR tradizionali sia per il filtro sia per l’ampiezza, oltre a un altro inviluppo ADSR per la sezione LFO. L’LFO dispone di un controllo BPM che può essere sincronizzato al transport o alla frequenza dell’host.

La sezione "DEF" contiene controlli per impostare pitchbend, modulation e velocity. La pagina Effects (non mostrata nello screenshot sopra) offre vari tipi di effetti: chorus, flanger, phaser, reverb e delay, oltre a un compressore e un limiter..
