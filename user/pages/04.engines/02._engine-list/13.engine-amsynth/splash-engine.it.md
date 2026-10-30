---
title: AMSynth
id: amsynth
description: Sintetizzatore a modellazione analogica che utilizza un approccio tradizionale
  alla sintesi sottrattiva per la creazione dei suoni
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-pr
date: 17:38 24-04-2020
subtitle: Synth analogico virtuale
splash:
  bg_image_landscape: amsynth-hero.png
  bg_image: amsynth-hero_small.png
media_thumb: amsynth.png
audio:
- audioType: local
  audioLabel: Particularly Two
  audioFile: particularlytwo.ogg
- audioType: local
  audioLabel: Corg Two Six
  audioFile: corgtwosix.ogg
- audioType: local
  audioLabel: Glass Bay
  audioFile: glassbay.ogg
- audioType: local
  audioLabel: Partenza
  audioFile: partenza.ogg
- audioType: local
  audioLabel: Simple Life
  audioFile: simplelife.ogg
- audioType: local
  audioLabel: End Game
  audioFile: endgame.ogg
- audioType: local
  audioLabel: First Pew
  audioFile: firstpew.ogg
- audioType: local
  audioLabel: Overpass
  audioFile: overpass.ogg
- audioType: local
  audioLabel: Soft Warning
  audioFile: softwarning.ogg
- audioType: local
  audioLabel: Soft Warning
  audioFile: softwarning.ogg
urls:
- urlLink: https://amsynth.github.io
  urlLabel: Project's Website
- urlLink: http://www.linuxsynths.com/amSynthdemos/amsynth.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/amsynth/amsynth
  urlLabel: Source Code
---
AmSynth, o sintetizzatore a modellazione analogica, sviluppato e mantenuto da Nick Dowell, utilizza un approccio tradizionale di sintesi sottrattiva per la progettazione del suono e può essere eseguito come strumento autonomo oppure come plug-in DSSI o LV2 all'interno di una workstation audio digitale come Ardour o Qtractor.

AmSynth è un sintetizzatore virtuale polifonico/monofonico in tempo reale, sensibile al tocco e dotato di controllo MIDI completo. Include due oscillatori, ciascuno in grado di generare le forme d’onda classiche: square-to-pulse, triangle-to-saw, sine, noise e sample-and-hold. L’oscillatore 2 può essere sincronizzato con l’oscillatore 1 e può anche essere scordato: fine tuning (più o meno 4 semitoni), coarse detuning (più o meno 12 semitoni) e detuning dell’ottava (da meno tre a più quattro). Sincronizzando gli oscillatori e regolando il detuning in semitoni si ottengono timbri interessanti, simili alla FM. Un knob per il mix degli oscillatori consente di controllare il bilanciamento tra i due; ruotandolo completamente a sinistra o a destra si isola l’uno o l’altro. È presente anche un knob per il livello della modulazione ad anello..

È fornito un inviluppo ADSR standard sia per la sezione di ampiezza sia per quella di filtro. I knobs di sensibilità alla Velocity di filtro e ampiezza si trovano nell'angolo inferiore destro della GUI..

La sezione del filtro include 9 tipi di filtro: passa-basso, passa-alto, passa-banda e notch (ciascuno con impostazioni a 12dB e 24dB) e un'opzione di bypass del filtro. Una manopola per l'intensità dell'inviluppo controlla la profondità dell'effetto del filtro, in positivo e in negativo. In questa sezione sono inclusi keyfollow, resonance e cutoff del filtro..

AmSynth ha un Low Frequency Oscillator. Questo LFO può essere completamente disattivato oppure impostato per influenzare il pitch, il filtro e l’ampiezza, o qualsiasi combinazione dei tre. Il parametro pitch può essere indirizzato a uno dei due oscillatori o a entrambi. Le forme d’onda includono: quadra, triangolare, sinusoidale, sample-and-hold, saw-up, saw-down e rumore.

Oltre ai controlli principali di volume e drive (distorsione), amSynth include un Reverb di tipo plate, un Knob Size per regolare l'ampiezza, e Knob Stereo e Damping. Le funzionalità aggiuntive della versione più recente includono il controllo mono/legato/poly e un'ampia gamma di opzioni per il portamento, che ora può essere impostato in modalità "always" o "legato". È disponibile anche il controllo del panning e i tasti di scelta rapida "ctrl+r" randomizzano le impostazioni..

Le regolazioni di precisione dei knob possono essere effettuate tenendo premuto il tasto shift mentre si spostano i knob..

AmSynth ha una polifonia illimitata, anche se solitamente 16 note sono sufficienti. La funzione Pitchbend può essere selezionata in semitoni, fino a 2 ottave. È ora possibile caricare anche scale microtonali..

## Funzionalità:
+ Due oscillatori (sinusoide / dente di sega / onda quadra / rumore) con hard sync
+ filtro risonante da 12/24 dB/ottava (passa-basso / passa-alto / passa-banda / notch)
+ Modalità di tastiera mono / poly / legato
+ Generatori di inviluppo ADSR doppi (filtro e ampiezza)
+ LFO che può modulare gli oscillatori, il filtro e l'ampiezza
+ Distorsione e reverb
