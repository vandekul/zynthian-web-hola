---
title: setBfree
id: setbfree
description: 'Highly customizable Hammond B3 & Leslie emulator'
taxonomy:
    category:
        - synthesizer
    tag:
        - free-software
        - synth-add
        - ucase-kb
        - synth-emu
        - synth-phy
date: '17:38 10-03-2020'
subtitle: 'Tonewheel Organ Emulator'
splash:
    bg_image: setbfree-hero_small.jpg
    bg_image_landscape: setbfree-hero.jpg
media_thumb: setbfree.jpg
sitemap:
    lastmod: '07-05-2026 14:23'
urls:
    -
        urlLink: 'http://setbfree.org'
        urlLabel: 'Project''s Website'
    -
        urlLink: 'http://www.linuxsynths.com/SetBfreePatchesDemos/setbfree.html'
        urlLabel: 'LinuxSynths Page'
    -
        urlLink: 'https://github.com/pantherb/setBfree'
        urlLabel: 'Source Code'
video:
    -
        type: vimeo
        youtube:
            youtubeLink: ''
            youtubeLabel: ''
        vimeo:
            vimeoLink: 'https://vimeo.com/130633814'
            vimeoLabel: 'A rendition of Jimmy Smith''s The Cat'
audio:
    -
        type: local
        local:
            audioFile: georgia_on_my_waltzin_mind.ogg
            audioLabel: 'Georgia on my waltzin mind, by TKC (MDA EPiano + setBfree)'
        soundcloud:
            audioLink: ''
            soundcloudLabel: ''
    -
        type: local
        local:
            audioFile: setBfreeDrawbarsManipulationByBaggypants.mp3
            audioLabel: 'Hammond Drawbars Manipulations, by Baggypants (setBfree)'
        soundcloud:
            audioLink: ''
            soundcloudLabel: ''
    -
        type: local
        local:
            audioFile: RhodesHammondByHumi.mp3
            audioLabel: 'Rhodes & Hammond, by Humi'
        soundcloud:
            audioLink: ''
            soundcloudLabel: ''
---

setBfree is a MIDI-controlled software synthesizer designed to imitate the sound and properties of the electromechanical organs and sound modification devices that brought world-wide fame to the names and products of Laurens Hammond and Don Leslie.

## Features:
setBfree is a _Tonewheel Organ Construction Kit_, a physical model with over 1000 configurable parameters. Like a real B3 one can 'open it' and tweak parameters from mint'53 condition (default) to dusty tube 80's run-down.

When running on zynthian, setBfree offers 7 pre-defined keyboard configurations combining manuals and pedals:
+ **Upper:** 1 keyboard (1 x MIDI channel)
+ **Upper + Lower:** 2 keyboards (2 x MIDI channels)
+ **Upper + Pedals:** 2 keyboards (2 x MIDI channels)
+ **Upper + Lower + Pedals:** 3 keyboards (3 x MIDI channels)
+ **Split Lower/Upper:** 1 keyboard (1 x MIDI channel)
+ **Split Pedals/Upper:** 1 keyboard (1 x MIDI channel)
+ **Split Pedals/Lower/Upper:** 1 keyboard (1 x MIDI channel)

On zynthian, setBfree also offers 4 types of waveform for the tone-wheel generator:
+ **Sine:** Hammond sound
+ **Square:** Combo organ sound
+ **Triangle:** Combo organ sound
+ **Sawtooth:** Combo organ sound

All controls can be assigned to MIDI-CC as needed via the MIDI-learn mechanism.


