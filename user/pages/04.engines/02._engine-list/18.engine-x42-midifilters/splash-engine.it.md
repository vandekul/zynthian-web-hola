---
title: x42 MIDI-filters
media_order: x42-midifilter.jpg
description: Una potente raccolta di filtri MIDI e strumenti semplici
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - ucase-pr
  - effect
  - fx-midi
date: 17:38 24-04-2020
subtitle: Una potente raccolta di semplici filtri e strumenti MIDI
splash:
  bg_image_landscape: x42-midifilter-hero.jpg
  bg_image: x42-midifilter-hero_small.jpg
media_thumb: x42-midifilter.jpg
urls:
- urlLink: http://x42-plugins.com/x42/x42-midifilter
  urlLabel: x42 MIDI-filter's Website
- urlLink: https://github.com/x42/x42-plugins
  urlLabel: Source Code
---
Una raccolta di oltre 25 filtri di dati MIDI in formato plugin LV2, sviluppata e mantenuta da [Robin Gareus](http://x42-plugins.com). I filtri seguono queste regole di base:
+ Un ingresso MIDI, un'uscita MIDI (nessun generatore, nessun synths)
+ Nessuna GUI personalizzata, solo ingressi di controllo
+ Ogni controllo può essere automatizzato, i plugin gestiscono le modifiche dinamiche dei parametri
+ Tutti i plugin comunicano la loro latency all'host (per la maggior parte di essi è zero)
+ DRY (principio Don't Repeat Yourself) - filtri semplici che possono essere combinati in una rete
+ Auto-documentante: descrizione integrata e documentazione delle porte di controllo

##Panoramica
**CC2Note:** Converti i messaggi MIDI control change in messaggi note-on/off. Note off viene accodato 10msec dopo.

**Filtro del canale MIDI:** Semplice filtro di canale MIDI. Possono passare solo i dati dei canali selezionati. Questo filtro agisce solo sui dati MIDI relativi ai canali (cioè note-on/off, control e program changes, key e channel pressure e pitchbend). MIDI-SYSEX e i messaggi Realtime vengono sempre trasmessi. Questo plugin è pensato per l'uso dal vivo, con controllo a pulsanti. Vedi anche il filtro 'MIDI Channel Map.

**Mappa dei canali MIDI:** Riscrivi il numero del canale MIDI. Questo filtro influisce solo sui dati MIDI pertinenti al canale (cioè note-on/off, control e program change, key e channel pressure e pitchbend). I messaggi MIDI-SYSEX e Realtime vengono sempre inoltrati senza modifiche..

**MIDI Forza la scala:** Filtra gli eventi note-on/off in base alla scala musicale. Se la tonalità viene modificata, vengono inviati eventi note-off per tutte le note fuori tonalità attive..

**Filtro eventi MIDI:** Filtro messaggi stile notch. Sopprime messaggi specifici. Per un intervallo note-on/off flessibile, vedere anche 'keyrange' e 'velocityrange'.

**Filtro dell’intervallo di tasti MIDI:** Questo filtro consente di definire un intervallo di note MIDI consentite. Gli eventi Note-on/off al di fuori dell’intervallo consentito vengono scartati. Se l’intervallo cambia, vengono inviati eventi note-off alle note attualmente attive che finiscono al di fuori dell’intervallo valido..

**MIDI Keysplit:** Cambia il numero del canale MIDI in base alla nota. Il plugin tiene traccia delle note MIDI trasposte e invia gli eventi note-off di conseguenza nel caso in cui l'intervallo venga modificato mentre una nota è ancora attiva. Tuttavia, il punto di split e le assegnazioni dei canali per ciascun manuale devono essere modificati solo quando non vengono suonate note..

**MapCC:** Converti un messaggio di controllo in un altro -- combina con scalecc per modificare/ridimensionare il valore effettivo.

**Trasposizione dei tasti MIDI:** Mappa flessibile a 12 toni. Consente di mappare una nota all'interno di un'ottava su un'altra nota nello stesso intervallo di ottava, +- 12 semitoni. In alternativa, è possibile mascherare (disabilitare) le note. Se due tasti sono mappati sulla stessa nota, i corrispondenti eventi note on/off vengono agganciati: verranno inviati solo il primo note on e l'ultimo note off. Le impostazioni possono essere modificate dinamicamente: gli eventi Note-on/off verranno inviati di conseguenza..

**Accordo MIDI:** Harmonizer - crea accordi da una singola nota (fondamentale) in una determinata scala musicale. La scala e gli intervalli possono essere automatizzati liberamente (gli accordi attualmente tenuti cambieranno). I note-on vengono mantenuti; per accordi multipli/combinati verrà attivato un solo note-on/off per la durata degli accordi combinati. Se viene inserita una nota fuori scala, verrà lasciata passare - non viene assegnato alcun accordo. Nota: combina questo effetto con il 'MIDI
Applica il filtro Scale per eliminarli.

**MIDI Delayline:** Linea di delay MIDI. Ritarda tutti gli eventi MIDI di un tempo specificato in BPM e battiti. Se il delay include un fattore casuale, questo effetto si occupa di mantenere sempre gli eventi note on/off in sequenza, indipendentemente dalla casualizzazione..

**Canale MIDI Unisono:** Duplica gli eventi MIDI da un canale a un altro.

**MIDI Strum:** Un effetto di arpeggio MIDI pensato per simulare lo strumming di uno strumento a corde (ad es. la chitarra). Un accordo viene «raccolto» e le singole note dell’accordo vengono riprodotte distribuite nel tempo. Il 'Note Collect Timeout' consente di suonare l’effetto dal vivo con una midi-keyboard, compensando il fatto che una persona non preme i tasti esattamente nello stesso momento. Se l’effetto viene usato con un sequencer in grado di inviare accordi con tutte le note-on esattamente nello stesso momento, dovrebbe essere impostato a zero..

**Trasposizione cromatica:** Trasposizione cromatica delle note midi e della pressione dei tasti. Se è impostato un punto di inversione, la scala viene specchiata attorno a questo punto prima della trasposizione. Le note che finiscono fuori dall'intervallo valido 0..127 vengono scartate.
MIDI Legato monofonico	Mantieni una nota premuta finché non arriva la nota successiva. -- Suona di nuovo la stessa nota per disattivarla..

**MIDI Rimuovi Active Sensing:** Filtro per bloccare tutti gli eventi Active Sensing. I messaggi Active Sensing sono messaggi MIDI facoltativi, destinati a essere inviati ripetutamente per segnalare a un ricevitore che la connessione è attiva; tuttavia, possono intasare il canale MIDI o essere registrati accidentalmente quando si scaricano dati MIDI grezzi su disco..

**Blocco dei duplicati MIDI:** Blocco duplicati MIDI. Filtra i messaggi di note on/off sovrapposti e duplicati.

**Note2CC:** Converti i messaggi MIDI note-on in messaggi control change.

**Attivazione/disattivazione delle note MIDI:** Attiva/disattiva le note: suona una nota per attivarla, suonala di nuovo per disattivarla.

**MIDI N-Tap Delay:** Questo effetto ripete le note N volte. Dove N è un numero fisso oppure illimitato finché viene premuto un determinato tasto. Le variabili BPM e delay-time consentono le rampe di tempo. A ogni ripetizione, la regolazione della Velocity specificata viene aggiunta o sottratta; il risultato è limitato tra 1 e 127..

**MIDI Thru:** MIDI All pass. Questo plugin non ha effetto ed è pensato come esempio..

**Quantizzazione MIDI:** Quantizzazione degli eventi live. Questo filtro allinea gli eventi MIDI in ingresso a una griglia temporale fissa. Poiché l'effetto opera su uno stream live, introdurrà latency: gli eventi verranno ritardati fino al 'tick' successivo. Se il plugin-host fornisce informazioni BBT, gli eventi vengono allineati al clock dell'host, altrimenti l'effetto usa il proprio tempo.

**Randomizzazione della Velocity MIDI:** Randomizza la Velocity delle note MIDI (sia note on che note off).

**Scala valore CC:** Modifica il valore (data-byte) di un messaggio MIDI control change.

**MIDI Sostenuto:** Questo filtro ritarda i messaggi note-off per un intervallo di tempo specificato, emulando il pedale del sostenuto del pianoforte. Quando il pedale viene rilasciato, i messaggi note-off in coda vengono inviati immediatamente. Il tempo di ritardo può essere modificato dinamicamente; le modifiche influiscono sui messaggi note-off ancora in coda..

**Filtro dell’intervallo di Velocity MIDI:** Filtra gli eventi MIDI note-on in base alla Velocity. Gli eventi note-on al di fuori dell'intervallo consentito vengono scartati. Se viene ricevuto un evento Note-off per una nota che era stata precedentemente filtrata, anche questo non viene trasmesso. Se l'intervallo consentito cambia, vengono inviati eventi note-off alle note attualmente attive che finiscono al di fuori dell'intervallo valido..

**Regolazione MIDI Velocity:** Modifica la Velocity degli eventi di nota con controlli separati per Note-on e Note-off. L'intervallo di input 1 - 127 viene mappato sull'intervallo tra Min e Max. Se Min è maggiore di Max, l'intervallo viene invertito. Il valore degli offset viene aggiunto all'evento Velocity dopo la mappatura dell'intervallo Min/Max.
