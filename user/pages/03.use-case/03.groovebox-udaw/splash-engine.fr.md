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
subtitle: Un outil de production bien doté
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
Zynthian est également un outil puissant pour la production. Il comprend plus de 100 moteurs de synthèse avec des milliers de presets et plus de 1000 effets audio & MIDI.

![zui_vangelis_add_chain](zui_vangelis_add_chain.png)

Il est entièrement multitimbral, capable de gérer jusqu'à 16 chaînes d'instruments et un nombre quelconque d'effets audio, de processeurs midi et de bus de mixage. Il prend en charge le standard LV2-plugin, la liste des processeurs disponibles est donc immense et ne cesse de s'allonger.

![01-zui_vangelis_mixerer](01-zui_vangelis_mixer.png)
![05-zui_vangelis_chainman](05-zui_vangelis_chainman.png)

Il intègre un puissant step-sequencer avec des fonctionnalités de jeu en direct et de composition de morceaux:

+ haute résolution (1920 ppqn)
+ éditeur de patterns (événements & blocs)
+ copier/coller & transposer des blocs
+ copier/coller des patterns
+ capture en direct
+ annuler/rétablir
+ options avancées de stutter:  speed, duration, volume-fade, speed-ramp
+ options de répétition et de randomisation: probabilité de lecture/saut, fréquence de lecture/saut, etc. 
+ automation des paramètres
+ beaucoup plus!

![zui_vangelis_pated_stuter](zui_vangelis_pated_stuter.png)

Il intègre également un lecteur de clips audio avancé capable de charger n’importe quel format de fichier audio, d’effectuer du time-stretch et de synchroniser des samples audio, etc.

![zui_clippy_wave](zui_clippy_wave.png)

La vue launcher permet de combiner des patterns de step sequencer et des clips audio, de les démarrer et de les arrêter de manière synchronisée, en proposant différents modes  pour la lecture unique, les boucles, etc. Phrases vous permet de structurer vos morceaux, en automatisant les changements de tempo & de signature rythmique, en définissant des boucles et des sections CODA, etc.

![02-zui_vangelis_launcher](02-zui_vangelis_launcher.png)

Une liste toujours plus longue de contrôleurs midi pris en charge permet de contrôler zynthian dès le départ, entièrement plug & play:

+ **Novation:** LaunchPad Mini / Pro / X. LaunchKey Mini, etc.
+ **Akai:** APC Key-25, APC 40, MPK mini, MIDI Mix
+ **Korg:** nanoKONTROL
+ **Behringer:** Motör 61 / 49
+ **Arturia:** Keylab 61
+ **Teenage Engeneering:** OP1
+ **Worlde:** Mini
+ **Foxtex:** Mixtab
+ **Mackie (MCU)**

[Cliquez ici](https://wiki.zynthian.org/index.php/Supported_MIDI_controllers) pour consulter la liste complète des contrôleurs MIDI pris en charge.

Zynthian peut également être contrôlé depuis des DAWs et des séquenceurs externes. Il offre de nombreuses options de connexion:

+ connecteurs MIDI DIN-5 traditionnels (IN / OUT / THRU)
+ 4 x ports USB-A (hôte)
+ 1 x ports USB-B (périphérique)
+ Connectivité réseau Ethernet et WIFI

et il prend également en charge les protocoles réseau MIDI les plus couramment utilisés, comme:

+ NetUMP (MIDI 2.0)
+ RTP (Apple MIDI)
+ QMidiNet (IP-multicast)
+ TouchOSC (tablette comme contrôleur MIDI)

Et il y a bien plus encore:

+ midi-learning facile avec plage de valeurs et mise à l'échelle
+ routage audio & midi flexible
+ mixbuses
+ enregistreur audio multipiste
+ enregistreur et lecteur midi
+ midi-filter basé sur des règles
+ Patches PureData & Organelle
+ Intégration MOD-UI

Concernant la latency et le jitter, la configuration par défaut (<10ms) suffit à la plupart des musiciens, mais si vous recherchez une latency extrêmement faible, la configuration audio peut être ajustée.

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


