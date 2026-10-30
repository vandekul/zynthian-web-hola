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
subtitle: Laissez vos doigts jouer le son souhaité
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
Zynthian est un excellent outil pour les claviéristes souhaitant élargir leurs possibilités de jeu sans avoir à transporter du matériel lourd et coûteux.

Zynthian comprend plus de 30 moteurs de synthèse, des centaines d'effets et des milliers de presets. Vous pouvez jouer le style de musique que vous voulez, en recréant des instruments vintage ou en explorant de nouveaux sons et textures. Vous pouvez combiner plusieurs moteurs et presets, ajuster les paramètres de synthèse et ajouter des effets et des filtres.

![zui_vangelis_chain_control_obxd_filter](zui_vangelis_chain_control_obxd_filter.png)

Zynthian prend en charge le format de plugins LV2, la liste des moteurs de synthèse & des effets ne cesse donc de s'allonger. La plupart des plugins disponibles sont des logiciels libres, mais certains plugins commerciaux sont disponibles, comme l'incroyable [Pianoteq](https://www.modartt.com/pianoteq?target=_blank) modélisateur physique ou TAL-U-NO-LX, un émulateur fidèle du JUNO-60. Des versions de démonstration sont incluses pour les deux.

Vous pouvez facilement combiner plusieurs chaînes (instruments) pour créer des sons superposés tout en gardant un contrôle indépendant sur les paramètres de votre choix. Vous pouvez transposer chacune indépendamment et diviser le clavier comme vous le souhaitez. 

![zui_vangelis_chain_control_keyrange](zui_vangelis_chain_control_keyrange.png)

Chaque contrôleur MIDI (clavier, etc.) que vous connectez à zynthian peut être routé vers un nombre quelconque de chaînes et configuré pour fonctionner en *actif* ou *multi* mode. *Actif* est le mode par défaut. Dans *actif* mode, la chaîne sélectionnée reçoit les notes que vous jouez, **quel que soit le canal MIDI**. D'un autre côté, le *multi* mode vous permet de **tirez parti des canaux MIDI**, permettant à différentes chaînes de recevoir différents canaux MIDI.

Les Sub-snapshots (ZS3s) permettent des changements rapides de preset et des transitions fluides entre les instruments. Aucune coupure du son lors du changement d'instrument. Vous commencez à jouer un nouveau preset alors que les dernières notes de l'ancien continuent de s'estomper. Maintenez certaines notes enfoncées ou prolongées avec la pédale tout en passant à un nouveau preset et les notes continueront de sonner jusqu'à ce que vous relâchiez la touche/pédale. 

Le workflow MIDI-learning est rapide et facile, vous permettant de tout gérer depuis vos claviers/contrôleurs.  Les boutons peuvent être assignés aux presets (program-change), les knobs et faders, aux paramètres du moteur (CC).

![Baggypants sur Scène](baggypants_on_stage.jpeg)

Zynthian dispose de connecteurs MIDI-IN/THRU/OUT standard et de 4 ports USB ([spécifications complètes](/technical-specifications)). Vous pouvez configurer chaque clavier pour jouer une chaîne différente. Ou diviser votre clavier et y assigner plusieurs instruments. Ou encore utiliser le step-sequencer pour contrôler la ligne Drum & Bass pendant que vous jouez un lead. Les possibilités sont presque infinies ...

L'outil de configuration web vous permet d'installer des collections, de gérer vos presets, soundfonts et snapshots, de télécharger vos enregistrements et bien plus encore! Vous pouvez également configurer votre zynthian pour le contrôler entièrement depuis votre clavier. Chaque action de l'interface utilisateur peut être assignée à des événements MIDI.

Concernant la Latency et le Jitter, la configuration par défaut (<10ms) suffit à la plupart des musiciens, mais si vous recherchez une Latency extrêmement faible, la configuration audio peut être ajustée.
