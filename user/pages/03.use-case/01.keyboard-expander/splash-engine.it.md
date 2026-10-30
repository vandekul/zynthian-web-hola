---
title: Keyboard Expander
media_order: ui_screenshots_kb.png,SalamanderGrandPianoDemoByHumi.mp3,PatMathenyByMauroBorgadelloRhodesStrings.mp3,IfIAintGotYou.mp3,LovelornManFracescoNutiByMauroBorgadello.mp3,PianoteqMidiDemoSteinweyD.mp3,baggypants_on_stage.jpeg,setBfreeDrawbarsManipulationByBaggypants.mp3,georgia_on_my_waltzin_mind.ogg,SmoothPillowByDhrupadiya.mp3,BodySoulByJoostRhodes.mp3,RhodesHammondByHumi.mp3,MorningSunshineByJTunes.mp3,RadioheadByTkc-SalamanderGrandPianoV3.mp3,night_track.ogg,CosmicSynthGuitarByJTunes.mp3,SpaceChoir1ByJTunes.mp3,keyexpander_combined.png,RelaxingThemeByDhrupadiya.mp3,use-cases-1-new.jpg,_DSC4481_02_web_use_case_production.jpg
content_position: center
date: 09:57 09-03-2020
margin_top: half
padding_top: none
padding_bottom: none
margin_bottom: none
role: default
body_classes: use-case custom-list
limit_reveal: '0'
background: _DSC4481_02_web_use_case_production.jpg
subtitle: Lascia che le dita suonino come vuoi
splash:
  bg_image_landscape: _DSC4481_02_web_use_case_production.jpg
media_thumb: _DSC4481_02_web_use_case_production.jpg
tag: ucase-kb
audio:
- audioType: local
  audioFile: autumn_leaves_low.ogg
  audioLabel: Autum Leaves, by TKC (Accurate Salamander Grand Piano)
- audioType: local
  audioFile: night_track.ogg
  audioLabel: Night Track, by TKC (MDA EPiano + ZASFX + SooperLooper
- audioType: local
  audioFile: georgia_on_my_waltzin_mind.ogg
  audioLabel: Georgia on my waltzin mind, by TKC (MDA EPiano + setBfree)
- audioType: local
  audioFile: RadioheadByTkc-SalamanderGrandPianoV3.ogg
  audioLabel: Everything In Its Right Place, by Radiohead. Solo rendition by tkc.(Salamander
    Grand Piano V3 + Zynreverb Room)
- audioType: local
  audioFile: BodySoulByJoostRhodes.ogg
  audioLabel: Body & Soul, by Joost (Pianoteq Fender Rhodes)
- audioType: local
  audioFile: IfIAintGotYou.ogg
  audioLabel: If I Aint Got You, by Alicia Keys. Solo rendition by TKC (Salamander
    Grand Piano V3 + Dragonfly Hall Reverb
- audioType: local
  audioFile: PianoteqMidiDemoSteinweyD.ogg
  audioLabel: Pianoteq MIDI demo (Steinwey D)
- audioType: local
  audioFile: SalamanderGrandPianoDemoByHumi.ogg
  audioLabel: Salamander Grand Piano demo, by Humi
- audioType: local
  audioFile: setBfreeDrawbarsManipulationByBaggypants.ogg
  audioLabel: Hammond Drawbars Manipulations, by Baggypants (setBfree)
- audioType: local
  audioFile: RhodesHammondByHumi.ogg
  audioLabel: Rhodes & Hammond, by Humi
- audioType: local
  audioFile: MorningSunshineByJTunes.ogg
  audioLabel: Morning Sunshine, by JTunes
- audioType: local
  audioFile: SpaceChoir1ByJTunes.ogg
  audioLabel: Space Choir1, by JTunes
- audioType: local
  audioFile: CosmicSynthGuitarByJTunes.ogg
  audioLabel: Cosmic Synth Guitar, by JTunes
- audioType: local
  audioFile: PatMathenyByMauroBorgadelloRhodesStrings.ogg
  audioLabel: Pat Metheny, by Mauro Borgadello (Rhodes+Strings)
- audioType: local
  audioFile: LovelornManFracescoNutiByMauroBorgadello.ogg
  audioLabel: Lovelorn Man (Francesco Nuti), by Mauro Bordello
- audioType: local
  audioFile: RelaxingThemeByDhrupadiya.ogg
  audioLabel: Relaxing Theme, by Dhrupadiya
noHeader: true
engines: true
---
Zynthian è un ottimo strumento per i tastieristi che desiderano ampliare le proprie possibilità esecutive senza dover trasportare hardware pesante e costoso.

Zynthian include più di 30 motori di sintesi, centinaia di effetti e migliaia di preset. Puoi suonare lo stile musicale che vuoi, ricreando strumenti vintage o esplorando nuovi suoni e texture. Puoi combinare diversi motori e preset, regolare i parametri del synth e aggiungere effetti e filtri.

![zui_vangelis_chain_control_obxd_filter](zui_vangelis_chain_control_obxd_filter.png)

Zynthian supporta il formato plugin LV2, quindi la lista di motori di sintesi & effetti è in continua crescita. La maggior parte dei plugin disponibili è software libero, ma sono disponibili anche alcuni plugin commerciali, come lo straordinario [Pianoteq](https://www.modartt.com/pianoteq?target=_blank) physical modeller o TAL-U-NO-LX, un accurato emulatore del JUNO-60. Sono incluse versioni demo per entrambi.

Puoi combinare facilmente più catene (strumenti) per creare suoni stratificati mantenendo il controllo indipendente sui parametri desiderati. Puoi trasporre ciascuna di esse in modo indipendente e suddividere la tastiera come preferisci. 

![zui_vangelis_chain_control_keyrange](zui_vangelis_chain_control_keyrange.png)

Ogni controller MIDI (tastiera, ecc.) che colleghi a zynthian può essere instradato verso un numero qualsiasi di catene e configurato per funzionare in *attivo* o *multi* modalità. *Attivo* è la modalità predefinita. In *attivo* modalità, la catena selezionata riceve le note che suoni, **non importa il canale MIDI**. D'altra parte, il *multi* la modalità ti consente di **sfrutta i canali MIDI**, consentendo a catene diverse di ricevere canali MIDI diversi.

I Sub-snapshots (ZS3s) consentono cambi di preset rapidi e transizioni fluide tra gli strumenti. Nessuna interruzione del suono quando si cambia strumento. Puoi iniziare a suonare un nuovo preset mentre le ultime note di quello precedente sono ancora in fase di rilascio. Tieni premute o sostenute alcune note mentre passi a un nuovo preset e le note continueranno a suonare finché non rilasci il tasto/pedale. 

Il workflow MIDI-learning è rapido e semplice e ti consente di gestire tutto dalle tue tastiere/controller.  I pulsanti possono essere assegnati ai preset (program-change), knob e fader, ai parametri del motore (CC).

![Baggypants sul palco](baggypants_on_stage.jpeg)

Zynthian dispone di connettori standard MIDI-IN/THRU/OUT e 4 porte USB ([specifiche complete](/technical-specifications)). Puoi configurare ogni tastiera per suonare una catena diversa. Oppure dividere la tua tastiera e mapparvi diversi strumenti. Oppure potresti volere che lo step-sequencer controlli la linea Drum & Bass mentre suoni un lead. Le possibilità sono quasi infinite ...

Lo strumento di configurazione web ti consente di installare raccolte, gestire i tuoi preset, soundfont e snapshot, scaricare le tue registrazioni e molto altro! Puoi anche configurare il tuo zynthian per controllarlo completamente dalla tua tastiera. Ogni azione dell'interfaccia utente può essere mappata a eventi MIDI.

Per quanto riguarda latency e jitter, la configurazione predefinita (<10ms) è sufficiente per la maggior parte dei musicisti, ma se cerchi una latency estremamente bassa, la configurazione audio può essere ottimizzata.
