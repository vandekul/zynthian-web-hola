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
subtitle: Lass deine Finger deinen Wunschklang spielen
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
Zynthian ist ein großartiges Werkzeug für Keyboarder, die ihre spielerischen Möglichkeiten erweitern möchten, ohne schwere und teure Hardware mitnehmen zu müssen.

Zynthian enthält mehr als 30 Synth-Engines, Hunderte von Effekten und Tausende von Presets. Du kannst den Musikstil spielen, den du möchtest, klassische Instrumente nachbilden oder neue Klänge und Texturen erkunden. Du kannst mehrere Engines und Presets kombinieren, Synth-Parameter anpassen und Effekte und Filter hinzufügen.

![zui_vangelis_chain_control_obxd_filter](zui_vangelis_chain_control_obxd_filter.png)

Zynthian unterstützt das LV2 Plugin-Format, sodass die Liste der Synth-Engines & Effekte ständig wächst. Die meisten verfügbaren Plugins sind freie Software, aber auch einige kommerzielle Plugins sind verfügbar, wie das großartige [Pianoteq](https://www.modartt.com/pianoteq?target=_blank) physical Modeller oder TAL-U-NO-LX, ein präziser JUNO-60-Emulator. Demoversionen sind für beide enthalten.

Du kannst ganz einfach mehrere Chains (Instrumente) kombinieren, um geschichtete Sounds zu erzeugen und dabei die gewünschten Parameter unabhängig voneinander zu steuern. Du kannst jede einzeln transponieren und die Tastatur nach Belieben aufteilen. 

![zui_vangelis_chain_control_keyrange](zui_vangelis_chain_control_keyrange.png)

Jeder MIDI-Controller (Keyboard, etc.), den du mit zynthian verbindest, kann an beliebig viele Chains geroutet und für den Betrieb in konfiguriert werden *aktiv* oder *multi* modus. *Aktiv* ist der Standardmodus. In *aktiv* modus, die ausgewählte Chain empfängt die Noten, die du spielst, **unabhängig vom MIDI-Kanal**. Andererseits, der *multi* modus ermöglicht es dir, **profitiere von MIDI-Kanälen**, wodurch verschiedene Chains unterschiedliche MIDI-Kanäle empfangen können.

Sub-snapshots (ZS3s) ermöglichen schnelle Preset-Wechsel und nahtlose Übergänge zwischen Instrumenten. Keine Klangunterbrechung beim Instrumentenwechsel. Du beginnst, ein neues Preset zu spielen, während die letzten Noten des alten noch ausklingen. Halte einige Noten gedrückt oder mit dem Pedal, während du zu einem neuen Preset wechselst, und die Noten klingen weiter, bis du die Taste/das Pedal loslässt. 

Der MIDI-learning-Workflow ist schnell und einfach und ermöglicht es dir, alles über deine Keyboards/Controller zu steuern.  Tasten können Presets (Program-Change) zugewiesen werden, Knobs und Fader den Engine-Parametern (CC).

![Baggypants auf der Bühne](baggypants_on_stage.jpeg)

Zynthian verfügt über standardmäßige MIDI-IN/THRU/OUT-Anschlüsse und 4 USB-Ports ([vollständige Spezifikationen](/technical-specifications)). Du kannst jede Tastatur so konfigurieren, dass sie eine andere Chain spielt. Oder deine Tastatur aufteilen und ihr mehrere Instrumente zuordnen. Oder du möchtest, dass der Step-Sequencer die Drum & Bass-Linie steuert, während du einen Lead spielst. Die Möglichkeiten sind nahezu endlos ...

Mit dem Web-Konfigurationstool kannst du Sammlungen installieren, deine Presets, Soundfonts und snapshots verwalten, deine Aufnahmen herunterladen und vieles mehr! Du kannst deinen zynthian auch so konfigurieren, dass er vollständig über dein Keyboard gesteuert wird. Jede UI-Aktion kann MIDI-Events zugeordnet werden.

Was latency und jitter betrifft, ist die Standardkonfiguration (<10ms) für die meisten Musiker ausreichend, aber wenn Sie eine besonders niedrige latency wünschen, kann die Audiokonfiguration angepasst werden.
