---
title: X42 Autotune
media_order: x42-fat1.png
description: Auto-tuner plugin
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - fx-other
  - ucase-fx
date: 17:38 24-04-2020
subtitle: Accordatore automatico basato su zita-at1 di Fons Adriaensens
splash:
  bg_image_landscape: x42-fat1-hero_small.png
  bg_image: x42-fat1-hero_small.png
media_thumb: x42-fat1.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-autotune
  urlLabel: X42 Autotune's Website
- urlLink: https://github.com/x42/fat1.lv2
  urlLabel: Source Code
---
x42-autotune (aka fat1.lv2) è un accordatore automatico basato su zita-at1 di Fons Adriaensen.

AT1 è pensato per correggere l'intonazione di una voce che canta (leggermente) stonata. Funziona ricampionando e mettendo in loop il segnale e non include la correzione dei formanti, quindi dovrebbe essere usato solo per correggere piccoli errori e non per trasporre davvero una canzone. AT1 può probabilmente essere usato anche su alcuni strumenti, ma è progettato principalmente per coprire l'estensione vocale..

L'intonazione "prevista" può essere controllata tramite MIDI oppure essere un insieme fisso di note.

Le principali differenze rispetto a zita-at1 sono che la versione del plugin LV2 comunica la propria latency all'host, salva lo stato insieme alla sessione e l'ingresso MIDI ha semantica sidechain.. 

#### Modalità operative
AT1 riaccorda il segnale in ingresso alla nota più vicina nella scala configurata. La scala è composta da un massimo di 12 note (1 ottava), che vengono impostate e indicate sulla tastiera sul lato sinistro. Per impostazione predefinita, tutte e 12 sono abilitate..

Il clic con il tasto sinistro consente di abilitare/disabilitare singole note, mentre facendo clic con il tasto destro sulla tastiera si apre una finestra di dialogo per selezionare le scale maggiori/minori più comuni. La tastiera indica anche la nota corrente selezionata dal pitch estimator..

Sono supportate le seguenti modalità operative:

**Manuale:** Usa un set fisso di note (ignora MIDI). Fai clic con il tasto sinistro per attivare o disattivare le note..

**MIDI:** Risponde ai messaggi MIDI note on/off. Usa le note MIDI attualmente attive. Se non ce ne sono, usa qualsiasi nota della scala cromatica..

**Automatico (predefinito):** Se non ci sono note MIDI attive, usa l’insieme statico e fisso di note (clic sinistro per attivare/disattivare). Le note MIDI hanno la priorità..

#### Parametri

**Selezione del canale MIDI:** Seleziona il canale MIDI a cui rispondere. Può essere 'Omni' o 1..16.

**Panico MIDI:** Reimposta qualsiasi nota MIDI 'bloccata.

**Accordatura:** Imposta la frequenza corrispondente all'intonazione 'A', in altre parole l'accordatura richiesta. Nella maggior parte dei casi, il valore predefinito sarà 440 Hz. Il valore esatto viene visualizzato ogni volta che si tocca questo controllo e può essere impostato con incrementi di 0.2 Hz.

**Bias:** Normalmente, l'estimatore di altezza selezionerà la nota abilitata più vicina all'altezza rilevata. Il controllo Bias aggiunge una certa preferenza per la nota corrente: questo le consente di scordarsi più di quanto accadrebbe altrimenti..

**Filtro:** Imposta la quantità di smoothing sulla correzione dell'intonazione mentre la nota corrente non cambia. Se cambia, il filtro viene bypassato e la correzione passa immediatamente al nuovo valore..

**Correzione:** Determina quanto viene corretto dell'errore di intonazione stimato. Una correzione completa può rimuovere l'espressività o il vibrato..

**Offset:** Aggiunge un offset nell'intervallo di +/- due semitoni alla correzione del pitch. Con il controllo Correction impostato su zero, il risultato è una variazione costante del pitch..

**Misuratore di errore di intonazione:** La barra sotto la tastiera indica l’errore di intonazione del segnale in ingresso rispetto alla nota corrente. L’intervallo è di +/- un semitono..
