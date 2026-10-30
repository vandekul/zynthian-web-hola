---
title: X42 Whirl Speaker
media_order: x42-whirl.png
description: Rotary Speaker Simulator
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - effect
  - fx-mod
  - ucase-fx
date: 17:38 24-04-2020
subtitle: Raccolta di plugin
splash:
  bg_image_landscape: x42-whirl-hero.png
  bg_image: x42-whirl-hero_small.png
media_thumb: x42-whirl.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-whirl
  urlLabel: Whirl Speaker's Website
- urlLink: https://github.com/pantherb/setBfree
  urlLabel: Source Code
---
x42-whirl è progettato per imitare il suono e le caratteristiche del dispositivo elettromeccanico a diffusore rotante che ha reso famosi in tutto il mondo il nome e i prodotti di Don Leslie..

È una versione standalone dell’effetto nato con il synth setBfree. Anziché simulare l’effetto complessivo del dispositivo elettromeccanico, x42-whirl ne modella fisicamente le caratteristiche, ottenendo una rappresentazione molto accurata del suono del dispositivo reale..

Poiché tutte le singole parti sono modellate, x42-whirl non solo offre un controllo avanzato, ma consente anche personalizzazioni, alcune delle quali non sono realizzabili nel dispositivo meccanico.

#### Dettagli
Il flusso del segnale corrisponde a quello dell'hardware originale. Per comodità è raffigurato nell'interfaccia del plugin. Due filtri vengono utilizzati per separare i bassi e gli alti, che vengono inviati agli altoparlanti a tromba e a tamburo. Un EQ aggiuntivo consente di personalizzare il suono del driver delle alte frequenze.

Il cuore dell’effetto è un altoparlante a tromba rotante. Si vedono due trombe, ma una (quella scura nella GUI) è fittizia e serve principalmente a compensare la forza centrifuga dell’altra durante la rotazione. Il plugin utilizza una combinazione di effetto Doppler e risposte all’impulso con shift zero dipendenti dall’angolo per una tromba Model 600 (la tromba Model 44W è identica a quella del Model 600 e, a quanto pare, è standard in tutti i modelli Leslie [1]). La misurazione della tromba è stata effettuata da J.O. Smith III et al([2]). Il suono del woofer è dominato da una modulazione di ampiezza causata dalla concavità del tamburo rotante..

x42-whirl calcola sei riflessioni in base agli angoli del corno e del tamburo, nonché alla distanza e alla posizione dei microfoni, per emulare la diffusione riverberante corrispondente alle dimensioni e alle caratteristiche di diffusione del cabinet. Inoltre, il modello tiene conto di artefatti come la dispersione del segnale dal tweeter, che non passa attraverso il corno.

Il controllo del motore consente di impostare due velocità target (lenta/chorale e veloce/tremolo) in RPM per ciascuno dei rotori del corno e del tamburo, nonché le costanti di tempo di accelerazione e decelerazione in secondi (per raggiungere metà velocità). Sebbene non tenga conto dell'attrito, è vicino a un setup originale correttamente lubrificato.

A volte, quando si ferma, il trombone o il tamburo è rivolto verso il retro del cabinet, producendo un suono poco gradevole. Un'impostazione opzionale aggiuntiva consente di impostare una posizione di arresto.

Per comodità, lo stadio di uscita include due mixer matriciali stereo che consentono di ridurre il campo stereo e aumentare la compatibilità mono..

#### Nota sui Parametri
Per impostazione predefinita il plugin utilizza impostazioni corrispondenti a un Model 44 (velocità di rotazione, raggio del drum e dell'horn) e a una caratteristica tecnica di ripresa microfonica left/right a 180°. Tuttavia, i vari aspetti possono essere personalizzati..

La posizione decentrata della tromba viene presa in considerazione nel calcolo delle riflessioni del cabinet, tuttavia i microfoni sono posizionati simmetricamente alla stessa distanza dal centro del rotore. Aumentando i raggi aumenta la modulazione della frequenza Doppler; aumentando la distanza dei microfoni, lo spettro cambia leggermente a causa dei diversi tempi di percorrenza del segnale per ciascuna delle posizioni di riflessione e degli altoparlanti..

Tutte le distanze sono misurate dal centro di ciascun rotore. Il plugin consente alcune configurazioni impossibili nella realtà (ad es. spostare il pickup del microfono all'interno del dispositivo rotante). In questi casi vengono presi in considerazione solo i calcoli di distanza e angolo e non corrisponderanno a ciò che si potrebbe sentire se fosse possibile farlo meccanicamente. Sebbene l'obiettivo sia modellare il dispositivo nel modo più realistico possibile, queste configurazioni sono mantenute nel plugin perché possono dare origine a suoni interessanti, che in fin dei conti è ciò che conta..
