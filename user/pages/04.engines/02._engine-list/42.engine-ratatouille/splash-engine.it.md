---
title: Ratatouille - Dual Neural Modeler
media_order: ratatouille.jpg
description: Modellatore a doppia rete neurale. Combina 2 modelli neurali + IRs
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - ucase-fx
  - fx-distortion
date: 17:38 24-04-2020
subtitle: Combina 2 modelli neurali e 2 IR
splash:
  bg_image: ratatouille-hero.jpg
  bg_image_landscape: ratatouille-hero.jpg
media_thumb: ratatouille.jpg
urls:
- urlLink: https://github.com/brummer10/Ratatouille.lv2
  urlLabel: Source Code
- urlLink: https://tone3000.com
  urlLabel: Ratatouille's Models in Tone3000
---
Ratatouille è un caricatore e mixer di modelli neurali per Linux/Windows.
Può caricare due modelli, che possono essere file *.nam (Neural Amp Modeler) o *.json / .aidax (RTNeural) e usare
il controllo "Blend" per fondere i due modelli e mixarli, così da simulare il timbro specifico che stai cercando.
Certo, puoi anche caricare un singolo file modello e il controllo "Blend" non farà nulla..

Ratatouille usa l'elaborazione parallela per i modelli neurali, quindi caricare un secondo modello neurale non sarebbe
notevole sul carico DSP. Facoltativamente, Ratatouille potrebbe eseguire l'intero processo in modalità bufferizzata.
Questo riduce ulteriormente il carico dsp. La latenza risultante verrà comunicata all'host in modo che possa essere
compensata. Per informazione, la latenza risultante verrà mostrata nell’interfaccia grafica.

Il controllo "Delay" potrebbe aggiungere un leggero ritardo per superare problemi di fase, o aggiungere un po' di colore/reverb al suono.
Il tasto 'ctrl' attiva la regolazione fine per impostare un Delay accurato al campione. Ratatouille può anche rilevare la fase
offset e compensa internamente.

Per completare il tuo suono puoi caricare due file Impulse Response e mixarli secondo le tue esigenze. I file IR potrebbero essere
normalizzati al caricamento, così da non influenzare il volume.

Ratatouille.lv2 supporta il ricampionamento quando necessario per corrispondere alla frequenza di campionamento prevista dei modelli caricati. Entrambi
i modelli e i file IR potrebbero avere aspettative diverse riguardo alla frequenza di campionamento.
#### Ottieni modelli da una vasta community

[Tone3000.com](https://tone3000.com) è diventato il luogo ideale per trovare i migliori modelli per Neural Amp Modeler, Aida-X e Proteus, con l’obiettivo di supportare altre piattaforme in futuro. Non solo modelli, ma anche la nostra raccolta di IR sta crescendo e sta diventando molto popolare sulla piattaforma.

#### Caricamento dei file

Dall'interfaccia zynthian-ui puoi caricare facilmente i file modello. Basta spostare la manopola assegnata al controllo del modello e comparirà il selettore di file..

