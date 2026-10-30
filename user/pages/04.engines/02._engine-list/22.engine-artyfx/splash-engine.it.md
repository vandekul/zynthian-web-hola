---
title: ArtyFX
media_order: artyfx.png
description: Una raccolta di plugin minimalista ma completa
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - effect
  - fx-delay
  - fx-mod
  - fx-other
  - ucase-fx
  - fx-eq
  - fx-filter
  - fx-dynamics
  - fx-distortion
  homepage:
  - 'yes'
date: 17:38 24-04-2020
subtitle: Raccolta minimalista di plugin
splash:
  bg_image_landscape: artyfx-hero.png
  bg_image: artyfx-hero_small.png
media_thumb: artyfx.png
urls:
- urlLink: http://openavproductions.com/artyfx/
  urlLabel: ArtyFX's Website
- urlLink: http://openavproductions.com/doc/artyfx.html
  urlLabel: ArtyFX's Documentation
- urlLink: https://github.com/openAVproductions/openAV-ArtyFX
  urlLabel: Source Code
---
ArtyFX è una suite di effetti audio minimalisti, utilizzabili autonomamente ma integrati anche in molti dei progetti più complessi di OpenAV, come Fabla2, Sorcer e Luppp. Ogni effetto può essere utilizzato singolarmente come plugin LV2..

ArtyFX contiene molti plugin diversi: sono presenti tutti gli effetti “classici”, come riverberi, delay e filtri. Le sezioni seguenti descrivono ogni plugin singolarmente, illustrando come può essere utilizzato e fornendo alcuni suggerimenti sulle migliori pratiche..

#### Bitta
Bitta è un plugin bit-crusher. Il bit crushing riduce la profondità di bit dell'audio. Poiché dipende dal volume del segnale in ingresso, fai attenzione quando imposti la manopola “crush”.

**Crush :** Modifica il numero di bit utilizzati per elaborare l'audio.

#### Della
Della è un delay regolabile in BPM, con controlli per feedback e volume del delay.

**Feedback:** controlla la quantità di segnale reimmesso nella linea di delay: alzalo per ottenere quell'eco reggae-dub folle che continua all'infinito!

**Volume:** modifica la quantità di segnale ritardato che si sente: utile per mantenere i delay sullo sfondo di una traccia.

**Tempo:** modifica la lunghezza del Delay: nota che è “quantizzata” in multipli del BPM, quindi “salta” tra la durata di una nota da 1/8, 1/4, 1/2 e una nota intera. Della rileva il BPM dal programma host: quindi, se cambi il tempo, continuerà a restare a tempo!

#### Ducka
Ducka è un plugin envelope side- chain: è molto utile per creare linee di basso “pumping”, come si trovano spesso nella minimal house. Il plugin funziona analizzando il volume di un ingresso sidechain e modificando il volume di una traccia stereo separata, in base all’ampiezza dell’ingresso sidechain.

**Soglia:** imposta il livello che l'audio in ingresso deve raggiungere prima che il livello della traccia stereo venga ridotto.

**Rilascia:** controlla la quantità di riduzione del volume applicata.

**Tempo:** controlla il tempo necessario prima che la traccia stereo venga nuovamente sfumata in ingresso. Nota che questo controllo dipende dai BPM e che il centro corrisponde direttamente agli off-beat. Un'impostazione pari alla metà (il valore predefinito) è generalmente musicale :)

#### Driva
Driva è un'unità multi-distorsione capace di creare le distorsioni più cattive e sporche..

**Tono:** Fai clic sul pulsante Tone: è disponibile un elenco di diversi modelli di distorsione. Fai clic sulla distorsione desiderata e continua a suonare. Cancel in basso chiude la schermata di modifica del tono..

**Quantità:** aumenta semplicemente la quantità di Gain / distorsione. Usalo a tuo rischio.!

#### Filta
Filta è una combinazione di filtri passa-basso e passa-alto. Utile per rimuovere le frequenze alte e basse indesiderate da varie registrazioni o strumenti.A

**Frequenza:** controlla quale tipo di filtraggio viene eseguito e a quale frequenza. I valori più bassi corrispondono a un filtro passa-basso, mentre alzando la manopola si ottiene un filtro passa-alto.

#### Kuiza
Kuiza è un equalizzatore a 4 bande. È perfetto per modellare creativamente il suono di uno strumento o di un synth. Ciascun controllo di Gain modifica l’ampiezza alla frequenza indicata. Il Gain master può essere utilizzato per ridurre o amplificare il volume complessivo, se necessario. I controlli (da sinistra a destra):

* Basso ( ~55 Hz)
* Medio-basse ( ~220 Hz)
* Medio-alti ( ~1760 Hz)
* Alto ( ~7040 Hz)
* Master Gain

#### Masha
Masha è un plugin beat grinder: registra un segmento audio e lo riproduce in loop, creando un effetto “stutter”.

**Volume:** modifica il volume dello stutter-loop. PassThru consente al segnale normale di passare attraverso.

**Tempo:** è un controllo dipendente dai BPM che modifica la durata della registrazione e della riproduzione del loop. Riduci gradualmente questo valore per ottenere il classico effetto stutter da DJ! Questo effetto dispone di alcune funzionalità speciali che consentono il controllo manuale dei BPM. Di solito i BPM vengono presi dal programma host (o dal trasporto JACK), ma ora possono essere controllati tramite una manopola.

**Pulsante HostBPM:** controlla la sorgente BPM. Quando il pulsante è blu, HostBPM è abilitato. Disattivando il pulsante, compare la manopola BPM manuale. La manopola mostra anche il BPM corrente.

#### Panda
Panda è una combinazione di compressore ed expander, con controlli Attack e Release.

**Threshold:** il “punto di svolta” della compressione / espansione. Abbassando la manopola si espande il segnale, alzandola si comprime.

**Rilascio:** modifica il tempo di fade-out della compressione/espansione di Panda.

**Fattore:** controlla la quantità di compressione/espansione applicata, la manopola “maximizer”.

#### Spazioso
Roomy è un riverbero ampio e morbido..

**Il controllo Time** modifica la durata della coda di reverb: valori più alti creeranno un mix più ampio e spazioso.

**Damping** controlla l’attenuazione delle alte frequenze: impostazioni più basse danno un suono spazioso e aperto, mentre un’attenuazione elevata dà una sensazione di suono piccolo e ravvicinato.

**Il controllo Dry/Wet** modifica la quantità di segnale Reverb mixato: utile per i “reverb build” techno e trance... basta alzarlo al massimo!

#### Satma
Satma è un plugin di distorsione pazzesco. Utile per dare più energia e ottenere un audio ruvido e sporco..

**Distortion** modifica la quantità di modellazione del segnale che avviene: la quantità complessiva di produzione di rumore.

**Il controllo Tone** varia sottilmente tra le alte frequenze e quelle basse, oppure rendendole entrambe ugualmente ruvide.

#### Vihda
Vihda è un enhancer stereo, che utilizza una matrice mid-side.

**Il parametro Width** influisce sulla quantità di contenuto stereo nel segnale. Nota che la tecnica mid-side migliora solo la stereofonia: non la crea!

**Il pulsante Invert** inverte il canale destro, il che può creare un mix percepito come più ampio, per via di come il cervello interpreta l'audio. Prova e vedi se suona bene.

