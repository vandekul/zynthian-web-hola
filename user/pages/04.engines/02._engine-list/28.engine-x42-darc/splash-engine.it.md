---
title: X42 Compressor
media_order: x42-darc.png
description: Compressore dinamico audio per uso generale
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - ucase-fx
  - fx-dynamics
content:
  items: '@self.modular'
date: 17:38 24-04-2020
subtitle: Compressore dinamico audio generico
splash:
  bg_image_landscape: x42-darc-hero_small.png
  bg_image: x42-darc-hero_small.png
media_thumb: x42-darc.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-compressor
  urlLabel: X42 Compressor's Website
- urlLink: https://github.com/x42/darc.lv2
  urlLabel: Source Code
---
x42-compressor (aka darc.lv2) è un compressore della gamma dinamica audio ispirato a zita-dc1 di Adriaensen. È un compressore downward dal suono molto gradevole, che si concentra sul workflow ed espone solo un set minimo di controlli. La compressione risponde alla potenza del segnale (RMS), alla loudness percepita dagli esseri umani, non al digital-peak legato al mezzo..

Il compressore dispone di auto makeup-gain, fissato a -10 dBFS/RMS. Questo mantiene il volume percepito su un'ampia gamma di impostazioni di soglia e rapporto..

Una funzione «Hold» distinta modifica il tempo di rilascio, che viene applicato solo finché il segnale supera la soglia. In altre parole: quando «Hold» è abilitato, il guadagno (o l’attenuazione) corrente viene mantenuto invariato quando il segnale scende sotto la soglia.
Questo impedisce al compressore di aggiungere un gain eccessivo (ad es. modulare il noise-floor) e può contrastare il «pumping» eccessivo quando si usano tempi di release brevi..

Il plugin è disponibile nelle varianti mono e stereo. Nel caso della seconda, entrambi gli ingressi vengono sommati e la potenza del segnale viene mediata per determinare il fattore di gain.

darc.lv2 si ispira all'algoritmo e all'interfaccia utente di zita-dc1 di Fons Adriaensen.

#### Parametri
**Input Gain:** Gain applicato prima del rilevamento del livello o di qualsiasi altra elaborazione. Nota che questo non è visualizzato come offset dell'asse x nella visualizzazione della curva. L'intervallo va da -10 a +30dB con incrementi di 1dB (0.2dB con regolazione fine).

**Threshold:** Livello del segnale (RMS) al quale viene attivato l'effetto di compressione. L'intervallo va da -50 a -10dB con incrementi di 0.5dB (0.1dB a grana fine).

**Ratio:** La quantità di gain o attenuazione da applicare (dB/dB sopra la soglia). Unity viene mantenuto a -10dBFS/RMS (auto makeup-gain).

**Attack time:** Tempo necessario affinché il segnale venga completamente compresso dopo aver superato la soglia.

**Release time:** Tempo minimo di recupero al livello del segnale non compresso dopo essere sceso sotto la soglia.

**Tieni premuto (check-button):** Mantieni l'attenuazione attuale quando il segnale scende sotto la soglia. Questo impedisce la modulazione del fondo di rumore e può contrastare il 'pumping'.

#### Visualizza
Il meter orizzontale in basso mostra il Gain applicato al segnale. Il display mostra l'intervallo min/max negli ultimi 50ms. I valori a sinistra &lt; 0 indicano che il segnale è attenuato (l'input è più alto di -10 dBFS/RMS).

Il grafico in alto visualizza la mappatura del gain dall’input all’output in dB. Quando «Hold» è abilitato, l’area in cui il gain non viene rilasciato è ombreggiata in blu. Il display mostra anche il livello del segnale in input come area bianca ombreggiata sotto la curva e il livello attuale dell’output (media su 50 ms) come punto..
