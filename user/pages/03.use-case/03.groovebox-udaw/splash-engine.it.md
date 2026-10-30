---
title: Groovebox / Micro-DAW
content_position: center
date: 09:57 09-03-2020
margin_top: half
padding_top: none
padding_bottom: none
margin_bottom: none
role: default
body_classes: use-case custom-list
limit_reveal: '0'
subtitle: Uno strumento di produzione ben dotato
background: _DSC4578_02_web_use_case_production.jpg
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=fVEJqswo_1s
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=4wJpog5Z5qQ
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=vpkRrzg_h-Q
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=3arcgoKu9T4
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=-4YbrNM4zRo
audio:
- audioType: local
  audioFile: zcontest23-01-Zynesthesia_by_kosro.ogg
  audioLabel: Zynesthesia, by Kosro
- audioType: local
  audioFile: zcontest23-02-Origin_by_danielwine.ogg
  audioLabel: Origin, by Daniel Wine
- audioType: local
  audioFile: xcontest23-01-The_seas_of_Mars_by_Nicolaz.ogg
  audioLabel: The Seas of Mars, by Nicolaz
- audioType: local
  audioFile: zcontest23-03-Everything_must_flow_by_Nicolaz.ogg
  audioLabel: Everything must flow, by Nicolaz
- audioType: local
  audioFile: xcontest23-03-westernbrassband_by_ivaneo.ogg
  audioLabel: Western Brass Band, by Ivaneo
- audioType: local
  audioFile: ZynthianicTranceByJtunes.ogg
  audioLabel: Zynthianic Trance, by JTunes
- audioType: local
  audioFile: PPG13ByCanTrell.ogg
  audioLabel: PPG13, by Can Trell
- audioType: local
  audioFile: TheWeightByBaggyPants.ogg
  audioLabel: The Weight, by BaggyPants
- audioType: local
  audioFile: MonsieurTheActorByRomanGeneralov.ogg
  audioLabel: Monsieur The Actor, by R.Generalov
- audioType: local
  audioFile: VasculabCOMPDByCanTrell.ogg
  audioLabel: Vasculab COMPD, by Can Trell
media_thumb: ''
splash:
  bg_image_landscape: _DSC4578_02_web_use_case_production.jpg
engines: true
tag: ucase-pr
---
Zynthian è anche un potente strumento per la produzione. Include più di 100 synth-engine con migliaia di preset e oltre 1000 effetti audio & MIDI.

![zui_vangelis_add_chain](zui_vangelis_add_chain.png)

È completamente multitimbrico, in grado di gestire fino a 16 catene di strumenti e un numero qualsiasi di effetti audio, processori midi e mixbus. Supporta lo standard LV2-plugin, quindi l'elenco dei processori disponibili è vastissimo e in continua crescita.

![01-zui_vangelis_mixerer](01-zui_vangelis_mixer.png)
![05-zui_vangelis_chainman](05-zui_vangelis_chainman.png)

Dispone di un potente step-sequencer con funzionalità per l'esecuzione dal vivo e la composizione di brani:

+ alta risoluzione (1920 ppqn)
+ editor di pattern (eventi & blocchi)
+ copia/incolla & trasponi blocchi
+ copia/incolla pattern
+ live capture
+ annulla/ripristina
+ opzioni avanzate di stutter:  velocità, durata, volume-fade, speed-ramp
+ opzioni di ripetizione e randomizzazione: probabilità di riproduzione/salto, frequenza di riproduzione/salto, ecc. 
+ automazione dei parametri
+ molto di più!

![zui_vangelis_pated_stuter](zui_vangelis_pated_stuter.png)

Include anche un lettore avanzato di clip audio in grado di caricare qualsiasi formato di file audio, applicare time-stretch e sincronizzare Samples audio, ecc.

![zui_clippy_wave](zui_clippy_wave.png)

La vista launcher consente di combinare pattern dello step sequencer e clip audio, avviandoli e fermandoli in modo sincronizzato, con diverse modalità  per la riproduzione singola, i loop, ecc. Le frasi consentono di strutturare i brani, automatizzando i cambi di tempo & indicazione metrica, definendo loop e sezioni CODA, ecc.

![02-zui_vangelis_launcher](02-zui_vangelis_launcher.png)

Un elenco in continua crescita di controller midi supportati può essere utilizzato per controllare zynthian fin da subito, in modo totalmente plug & play:

+ **Novation:** LaunchPad Mini / Pro / X. LaunchKey Mini, ecc.
+ **Akai:** APC Key-25, APC 40, MPK mini, MIDI Mix
+ **Korg:** nanoKONTROL
+ **Behringer:** Motör 61 / 49
+ **Arturia:** Keylab 61
+ **Teenage Engeneering:** OP1
+ **Worlde:** Mini
+ **Foxtex:** Mixtab
+ **Mackie (MCU)**

[Fai clic qui](https://wiki.zynthian.org/index.php/Supported_MIDI_controllers) per consultare l'elenco completo dei controller MIDI supportati.

Zynthian può anche essere controllato da DAW e sequencer esterni. Offre numerose opzioni di connessione:

+ connettori MIDI DIN-5 legacy (IN / OUT / THRU)
+ 4 x porte USB-A (host)
+ 1 x porte USB-B (dispositivo)
+ Connettività di rete Ethernet e WIFI

e supporta anche i protocolli di rete MIDI più diffusi, come:

+ NetUMP (MIDI 2.0)
+ RTP (Apple MIDI)
+ QMidiNet (IP-multicast)
+ TouchOSC (tablet come controller MIDI)

E c'è molto altro ancora:

+ midi-learning semplice con intervallo di valori e scaling
+ routing audio & midi flessibile
+ mixbuses
+ registratore audio multitraccia
+ registratore e lettore midi
+ midi-filter basato su regole
+ PureData & patch per Organelle
+ Integrazione MOD-UI

Per quanto riguarda latency e jitter, la configurazione predefinita (<10ms) è sufficiente per la maggior parte dei musicisti, ma se cerchi una latency estremamente bassa, la configurazione audio può essere ottimizzata.

<!--
<small>Trip Jazz Demo, by Humi</small>
![TripJazzdemoByHumi.mp3](TripJazzdemoByHumi.mp3?preload=metadata)
<small>BlueBox is Roughly Great, by Nicolaz</small>
![BlueBoxIsRoughlyGreatByNicolaz.mp3](BlueBoxIsRoughlyGreatByNicolaz.mp3?preload=metadata)
<small>RTPMidi Celebration, by JTunes</small>
![RTPMidiCelebrationByJTunes.mp3](RTPMidiCelebrationByJTunes.mp3)
<small>Epic EnteR, by R.Generalov</small>
![EpicEnteRByRomanGeneralov.mp3](EpicEnteRByRomanGeneralov.mp3)
<small>Electro, by Humi</small>
![ElectroByHumi.mp3](ElectroByHumi.mp3)
<small>Mr Tchaikovsky, by sm7x7</small>
![MrTchaikovskyBySm7x7.mp3](MrTchaikovskyBySm7x7.mp3)
<small>Of Course My Lord, by R.Generalov</small>
![OfCourseMyLordByRomanGeneralov.mp3](OfCourseMyLordByRomanGeneralov.mp3)
<small>First Real Synth, by Can Trell</small>
![FirstRealSynthByCanTrell.mp3](FirstRealSynthByCanTrell.mp3)
<small>For Wyleu, by Humi</small>
![ForWyleuByHumi.mp3](ForWyleuByHumi.mp3)
-->


