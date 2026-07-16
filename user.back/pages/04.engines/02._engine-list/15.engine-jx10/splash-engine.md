---
title: 'MDA JX-10'
id: mda-jx10
description: 'Subtractive soft-synth inspired by some Roland machines from the 1980s'
taxonomy:
    category:
        - synthesizer
    tag:
        - free-software
        - synth-sub
        - ucase-kb
        - synth-emu
date: '17:38 24-04-2020'
subtitle: 'JX-8p/JX-10 Emulator'
splash:
    bg_image_landscape: djx10-hero.jpg
    bg_image: djx10-hero_small.jpg
media_thumb: djx10.jpg
urls:
    -
        urlLink: 'http://mda.smartelectronix.com'
        urlLabel: 'MDA''s Website'
    -
        urlLink: 'https://github.com/moddevices/mda-lv2'
        urlLabel: 'MDA-LV2 Source Code'
audio:
    -
        type: local
        local:
            audioFile: fifthsweeppad.ogg
            audioLabel: 'Fifth Sweep Pad'
    -
        type: local
        local:
            audioFile: hardlead.ogg
            audioLabel: 'Hard Lead'
    -
        type: local
        local:
            audioFile: solidbacking.ogg
            audioLabel: 'Solid Backing'
    -
        type: local
        local:
            audioFile: detunedsynbrass.ogg
            audioLabel: 'Detuned Syn-Brass'
    -
        type: local
        local:
            audioFile: sawbass.ogg
            audioLabel: 'Saw Bass'
    -
        type: local
        local:
            audioFile: touchyfellow.ogg
            audioLabel: 'Touchy Fellow'
    -
        type: local
        local:
            audioFile: helicopter.ogg
            audioLabel: Helicopter
    -
        type: local
        local:
            audioFile: wobblebass.ogg
            audioLabel: 'Wobble Bass'
    -
        type: local
        local:
            audioFile: filterdemo.ogg
            audioLabel: 'Filter Demo'
---

MDA JX-10 is a substractive soft-synth inspired by some Roland machines from the 80s. It consumes very little resources and the sound quality is great.

It provides two oscillators (saw and pulsewidth) which can be isolated or blended. Polyphony is obtained using the glide control setting: zero for polyphonic, max for monophonic control. Standard ADSR envelopes are provided for timbre (filter) and amplitude. Pitchbend is set at one wholetone. The LFO depth is hardwired to the modulation wheel. I added a demo to give an idea of the very rich LP filter (last demo above).
 
Back in the 20th century, plugins from Maxim Digital Audio (mda) were among the early VST plugins available for Windows. They have a reputation for being high quality with low CPU usage. Several years ago the source code for these plugins was released and David Robillard ported the mda plugins to LV2 format. Most of the mda plugins are effects but there are also four instruments: DX10, JX10, Piano, and ePiano.

## Features:
+ 2 fixed oscillators (Mix selectable between 100:0 to 50:50) & Noise
+ Oscillator tune +-24 semitones
+ Resonant filter (Controllable by Env/LFO/Velocity)
+ ADSR for VCF & Amp/Env
+ Glide - 6 modes (Poly, P-Legato, P-Glide, Mono, M-Legato, M-Glide)
+ LFO
+ Vibrato
+ Synth tuning +-2 Octaves
+ Low CPU usage
+ Default bank of 52 patches
+ No GUI