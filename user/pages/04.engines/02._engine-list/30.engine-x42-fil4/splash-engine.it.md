---
title: X42 Equalizer
media_order: x42-fil4.png
description: 4 band parametric equalizer
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - fx-filter
content:
  items: '@self.modular'
date: 17:38 24-04-2020
subtitle: Equalizzatore parametrico a 4 bande
splash:
  bg_image_landscape: x42-fil4-hero_small.png
  bg_image: x42-fil4-hero_small.png
media_thumb: x42-fil4.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-eq
  urlLabel: X42 Equalizer's Website
- urlLink: https://github.com/x42/fil4.lv2
  urlLabel: Source Code
---
x42-eq (aka fil4.lv2) è un equalizzatore parametrico a 4 bande con ulteriori filtri shelving low e high e filtri passa-alto e passa-basso. L'equalizzatore è progettato per riprodurre un guadagno equivalente a quello analogico con latenza zero e senza sfasamento quando ci si avvicina alla frequenza di Nyquist. Non ha una risposta compressa, spesso definita come suono digitale. x42-eq offre display integrati in tempo reale di spettro e spettrogramma (waterfall), un display peak-hold resettabile dall'utente e un controllo del Gain in uscita.

fil4.lv2 si basa sui fil-plugins LADSPA di Fons Adriaensen.

#### Controlli dello spettro
I controlli dello spettrogramma si trovano in basso a destra.,

**Disattivato:** Non visualizzare lo spettro<br>
**Specifica:** Visualizza uno spettro ponderato con rumore rosa (1/ottava.<br>
**Hist:** Visualizzazione dello spettrogramma; vista della cronologia (le linee tratteggiate bianche indicano la modifica delle impostazioni)<br>
**Pre:** Analizza l'input<br>
**Articolo:** Analizza l'output elaborato<br>

La variante Stereo offre la possibilità di analizzare la somma (All) o solo il canale Left o Right. Il Knob Gain consente di allineare lo spettro; vedi la scala sul lato destro del display..

**Alto:** Warping ad alta frequenza, risoluzione aumentata nelle frequenze basse.<br>
**Med:** Warping delle frequenze medie<br>
**Bark:** No Frequency Warping, enfatizza le alte frequenze<br>

**Rpd:** Rapido decadimento (~~20ms)<br>
**Veloce:** Decadimento rapido (~~80ms)<br>
**Mod:** Tempo di decadimento moderato (~~200ms)<br>
**Lento:** Decadimento lento (~~2sec)<br>
**Ns.:** Misurazione del rumore (~20sec)<br>

#### Specifiche dei filtri
Fil4 è composto da quattro filtri risonanti del 2° ordine che utilizzano un filtro reticolare in stile Regalia-Mitra, che ha la piacevole proprietà di rimanere stabile anche quando i parametri vengono modificati.

I filtri high/low-shelf sono filtri biquad/IIR standard del 2° ordine.

I filtri passa-alto e passa-basso sono filtri risonanti del 2° ordine (-12 dB/ottava):

+ Qualità 0.0: -6dB alla frequenza di cutoff (nessun feedback)
+ Qualità 0.7: -3dB alla frequenza di cutoff
+ Qualità 1.0: 0dB al cutoff (resonant)

Tutti i filtri hanno latenza zero con il corretto guadagno analogico equivalente alla frequenza di Nyquist (lo sfasamento del segnale alla frequenza di Nyquist è zero).

