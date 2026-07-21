---
title: 'Keyboard Expander'
media_order: 'ui_screenshots_kb.png,SalamanderGrandPianoDemoByHumi.mp3,PatMathenyByMauroBorgadelloRhodesStrings.mp3,IfIAintGotYou.mp3,LovelornManFracescoNutiByMauroBorgadello.mp3,PianoteqMidiDemoSteinweyD.mp3,baggypants_on_stage.jpeg,setBfreeDrawbarsManipulationByBaggypants.mp3,georgia_on_my_waltzin_mind.ogg,SmoothPillowByDhrupadiya.mp3,BodySoulByJoostRhodes.mp3,RhodesHammondByHumi.mp3,MorningSunshineByJTunes.mp3,RadioheadByTkc-SalamanderGrandPianoV3.mp3,night_track.ogg,CosmicSynthGuitarByJTunes.mp3,SpaceChoir1ByJTunes.mp3,keyexpander_combined.png,RelaxingThemeByDhrupadiya.mp3,use-cases-1-new.jpg,_DSC4481_02_web_use_case_production.jpg'
content_position: center
date: '09:57 09-03-2020'
margin_top: half
padding_top: none
padding_bottom: none
margin_bottom: none
role: default
body_classes: 'use-case custom-list'
limit_reveal: '0'
background: _DSC4481_02_web_use_case_production.jpg
subtitle: 'Let your fingers play the sound you want'
splash:
    bg_image_landscape: _DSC4481_02_web_use_case_production.jpg
media_thumb: _DSC4481_02_web_use_case_production.jpg
tag: ucase-kb
audio:
    -
        audioType: local
        audioFile: georgia_on_my_waltzin_mind.ogg
        audioLabel: 'Georgia on my waltzin mind, by TKC (MDA EPiano + setBfree)'
    -
        audioType: local
        audioFile: night_track.ogg
        audioLabel: 'Night Track, by TKC (MDA EPiano + ZASFX + SooperLooper'

    -
        audioType: local
        audioFile: RadioheadByTkc-SalamanderGrandPianoV3.mp3
        audioLabel: 'Everything In Its Right Place, by Radiohead. Solo rendition by tkc.(Salamander Grand Piano V3 + Zynreverb Room)'
    -
        audioType: local
        audioFile: BodySoulByJoostRhodes.mp3
        audioLabel: 'Body & Soul, by Joost (Pianoteq Fender Rhodes)'
    -
        audioType: local
        audioFile: IfIAintGotYou.mp3
        audioLabel: 'If I Aint Got You, by Alicia Keys. Solo rendition by TKC (Salamander Grand Piano V3 + Dragonfly Hall Reverb'
    -
        audioType: local
        audioFile: PianoteqMidiDemoSteinweyD.mp3
        audioLabel: 'Pianoteq MIDI demo (Steinwey D)'
    -
        audioType: local
        audioFile: SalamanderGrandPianoDemoByHumi.mp3
        audioLabel: 'Salamander Grand Piano demo, by Humi'
    -
        audioType: local
        audioFile: setBfreeDrawbarsManipulationByBaggypants.mp3
        audioLabel: 'Hammond Drawbars Manipulations, by Baggypants (setBfree)'
    -
        audioType: local
        audioFile: RhodesHammondByHumi.mp3
        audioLabel: 'Rhodes & Hammond, by Humi'
    -
        audioType: local
        audioFile: MorningSunshineByJTunes.mp3
        audioLabel: 'Morning Sunshine, by JTunes'
    -
        audioType: local
        audioFile: SpaceChoir1ByJTunes.mp3
        audioLabel: 'Space Choir1, by JTunes'
    -
        audioType: local
        audioFile: CosmicSynthGuitarByJTunes.mp3
        audioLabel: 'Cosmic Synth Guitar, by JTunes'
    -
        audioType: local
        audioFile: PatMathenyByMauroBorgadelloRhodesStrings.mp3
        audioLabel: 'Pat Metheny, by Mauro Borgadello (Rhodes+Strings)'
    -
        audioType: local
        audioFile: LovelornManFracescoNutiByMauroBorgadello.mp3
        audioLabel: 'Lovelorn Man (Francesco Nuti), by Mauro Bordello'
    -
        audioType: local
        audioFile: RelaxingThemeByDhrupadiya.mp3
        audioLabel: 'Relaxing Theme, by Dhrupadiya'

noHeader: true
engines: true
---

Zynthian is a great tool for keyboardist wanting to expand their playing possibilities without having to carry heavy and expensive hardware.

Zynthian includes more than 30 synth-engines, hundreds of effects and thousands of presets. You can play the music style you want, recreating vintage instruments or exploring new sounds and textures. You can combine several engines and presets, adjust synth parameters and add effects and filters.

[figure class=""]![zui_vangelis_chain_control_obxd_filter](zui_vangelis_chain_control_obxd_filter.png "zui_vangelis_chain_control_obxd_filter")[/figure]

Zynthian supports the LV2 plugin-format, so the list of synth-engines & effects is ever growing. Most of the available plugins are free software, but some commercial plugins are available, like the amazing [Pianoteq](https://www.modartt.com/pianoteq?target=_blank) physical modeller or TAL-U-NO-LX, an accurate JUNO-60 emulator. Demo versions are included for both of them.

You can easily combine several chains (instruments) to create layered sounds whilst keeping independent control over the parameters you want. You can transpose each one independently and split the keyboard as you like. 

[figure class=""]![zui_vangelis_chain_control_keyrange](zui_vangelis_chain_control_keyrange.png "zui_vangelis_chain_control_keyrange")[/figure]

Each MIDI controller (keyboard, etc.) you connect to zynthian can be routed to any number of chains and configured to work in **active** or **multi** mode. **Active** is the default. In **active** mode, the selected chain (active) receives the notes you play, **no matters the MIDI channel**. In the other hand, **multi** mode allows you to **take profit of MIDI channels**, allowing different chains to receive different MIDI channels.

Sub-snapshots (ZS3s) allow fast preset changes and smooth transitions between instruments. No sound cut when changing instrument. You start playing a new preset while the last notes from the old one are still releasing. Keep some notes pressed or sustained while changing to a new preset and the notes will continue to sound until you release the key/pedal. 

The MIDI-learning workflow is quick & easy, allowing you to manage everything from your keyboards/controllers.  Buttons can be assigned to presets (program-change), knobs & faders, to engine parameters (CC).

[figure class=""]![Zynthian UI](baggypants_on_stage.jpeg)[/figure]

Zynthian has standard MIDI-IN/THRU/OUT connectors and 4 USB ports ([full specifications](/technical-specifications)). You can configure each keyboard to play a different chain. Or split your keyboard and map several instruments on it. Or you may want the step-sequencer controlling the Drum & Bass line while you play a lead. Possibilities are almost endless ...

The web configuration tool allows you to install collections, manage your presets, soundfonts and snapshots, download your recordings and much more! You can also configure your zynthian to be totally controlled from your keyboard. Every UI action can be mapped to MIDI events.

Regarding latency and jitter, the default configuration (<10ms) is enough for most players, but if you are looking for extra-low latency, audio configuration can be tweaked.
