---
title: 'ZAM Plugins'
media_order: redwave.jpg
description: 'A plugin collection for sound processing'
taxonomy:
    category:
        - effect
    tag:
        - free-software
        - ucase-pr
        - effect
        - fx-delay
        - fx-mod
        - fx-other
        - ucase-fx
        - fx-eq
        - fx-filter
        - fx-dynamics
        - fx-distortion
date: '17:38 24-04-2020'
subtitle: 'Plugin Collection'
splash:
    bg_image_landscape: redwave-hero.jpg
    bg_image: redwave-hero_small.jpg
media_thumb: redwave.jpg
audio:
    -
        audioType: local
        audioFile: angie-20141010_follow.ogg
        audioLabel: 'Follow, by Angie Hudson (2013)'
video:
    -
        videoType: youtube
        videoLink: 'https://www.youtube.com/watch?v=MGErjKRu_dQ'
urls:
    -
        urlLink: 'http://www.zamaudio.com/'
        urlLabel: 'ZamAudio''s Website'
    -
        urlLink: 'http://github.com/zamaudio/zam-plugins'
        urlLabel: 'Source Code'
---

Zam-plugins is a collection of LV2/LADSPA/VST/JACK audio plugins for sound processing developed in-house at ZamAudio. The default settings and almost every slider is calibrated to standard ranges.

A big thankyou to falktx for writing Distrho Plugin Framework. It has enabled me to make these GUIs for zam-plugins quickly and neatly. Also thanks to mira, nphilipp, adi, edogawa and Haskellfant who helped package the software for different distros!

## Overview

#### ZaMaximX2
One of the best plugins in the series, this acts as a brickwall limiter for mastering in its default state, but can also be tweaked to raise the average level as a stereo maximizer without ever clipping. Sounds musical even with rough treatment. (Based on DSP found in a DAFX’02 paper).

#### ZamAutoSat
An automatic saturation plugin, has been known to provide smooth levelling to live mic channels.
You can apply this plugin generously without affecting the tone.

#### ZamComp
A powerful mono compressor strip. Adds real beef to a kick or snare drum with the right settings.

#### ZamCompX2
Stereo version of ZamComp with knee slew control.

#### ZamEQ2
Two band parametric equaliser with high and low shelving circuits.

#### ZamGEQ31
31 band graphic equaliser, good for eq of live spaces, removing unwanted noise from a track etc.

#### ZamHeadX2
HRTF acoustic filtering plugin for directional sound.

#### ZamPhono
A collection of phono filters for restoring vinyl records, or preparing to cut new ones.

#### ZamGate
Gate plugin for ducking low gain sounds.

#### ZamGateX2
Gate plugin for ducking low gain sounds, stereo version.

#### ZamTube
Wicked distortion effect. Wave digital filter physical model of a triode tube amplifier stage, with modelled tone stacks from real guitar amplifiers (thanks D. Yeh et al).

#### ZamDelay
A simple feedback delay unit with sync-to-host BPM feature and filter.

#### ZamDynamicEQ
A dynamic equalizer that changes its gain based on detecting a narrow band of frequencies. Can be tuned to alter other frequency ranges on-the-fly.

#### ZaMultiComp
Mono multiband compressor, with 3 adjustable bands.

#### ZaMultiCompX2
Flagship of zam-plugins: Stereo version of ZaMultiComp, with individual threshold controls for each band and real-time visualisation of comp curves.