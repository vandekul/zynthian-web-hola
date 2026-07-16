---
title: 'Effects Unit'
content_position: center
date: '09:57 09-03-2020'
margin_top: half
padding_top: none
padding_bottom: none
margin_bottom: none
role: default
body_classes: 'use-case custom-list'
limit_reveal: '0'
media_order: 'always-with-me-always-with-you.wav,CleanGuitarByRodrigoAmaral.mp3,CrunchGuitarByRodrigoAmaral.mp3,ElectroKalimbaMisteryForestDreamByJofemodo.mp3,LeadGuitarByRodrigoAmaral.mp3,ui_screenshots_sl.png,use-cases-2-new.jpg,_DSC4534_01_web_use_case_fx_unit.jpg'
subtitle: 'Would you like a custom FX-chain for every song?'
background: _DSC4534_01_web_use_case_fx_unit.jpg
audio:
    -
        type: local
        local:
            audioFile: always-with-me-always-with-you.wav
            audioLabel: 'Always with me, always with you (Joe Satriani, played by Stojos)'
        soundcloud:
            audioLink: ''
            soundcloudLabel: ''
    -
        type: local
        local:
            audioFile: CleanGuitarByRodrigoAmaral.mp3
            audioLabel: 'Clean Guitar, by Rodrigo Amaral'
        soundcloud:
            audioLink: ''
            soundcloudLabel: ''
    -
        type: local
        local:
            audioFile: ' CrunchGuitarByRodrigoAmaral.mp3'
            audioLabel: 'Crunch Guitar, by Rodrigo Amaral'
        soundcloud:
            audioLink: ''
            soundcloudLabel: ''
    -
        type: local
        local:
            audioFile: LeadGuitarByRodrigoAmaral.mp3
            audioLabel: 'Lead Guitar, by Rodrigo Amaral'
        soundcloud:
            audioLink: ''
            soundcloudLabel: ''
    -
        type: local
        local:
            audioFile: ElectroKalimbaMisteryForestDreamByJofemodo.mp3
            audioLabel: 'Kalimba Mistery Forest Dream, by Jofemodo'
        soundcloud:
            audioLink: ''
            soundcloudLabel: ''
video:
    -
        type: youtube
        youtube:
            youtubeLink: 'https://www.youtube.com/watch?v=QPQT5gviZbo'
            youtubeLabel: ''
        vimeo:
            vimeoLink: ''
            vimeoLabel: ''
media_thumb: _DSC4534_01_web_use_case_fx_unit.jpg
splash:
    bg_image_landscape: _DSC4534_01_web_use_case_fx_unit.jpg
---

Zynthian can be used as a powerful Audio Effects unit allowing creation of a customized effect-chain for every available audio input.

The official Zynthian V5 Kit have 2 balanced audio-inputs with independent gain-control ranging from -12db to +32dB. Read the full specifications [here](/technical-specifications). You can directly connect a wide rage of input devices, like dynamic microphones, electric & acoustic guitars, piezos, line-in, etc. If you need more audio inputs, you simply connect your favorite USB audio interface and get all the extra audio input/output channels you need.

Zynthian supports the LV2-plugin standard and includes hundreds of audio-processing plugins. You can combine them as you like for sculpting the sound, recreating vintage landscapes or exploring new textures. You can have any number of FX-chains with flexible routing allowing as simple or complex configuration as desired.

If you are a guitar guy, you will enjoy the 3 neural modelers included with zynthian:

+ [Aida-X](/engines/_engine-list/engine-aidax)
+ [NAM](/engines/_engine-list/engine-nam)
+ [Ratatouille](/engines/_engine-list/engine-ratatouille)

They bring state-of-the-art, accurate emulation of analog gear like amplifiers, distortion, fuzz, overdrive stomp-boxes, etc. Literally thousands of models are freely available in places like [ToneHunt](https://tonehunt.org). Simply download your favorite gear model and get the tone you love.

If you like looping, Sooper Looper is fully integrated, allowing to control up to 6 independent loops with instant record, overdub, reverse, multiply, replace, time-stretch, pitch-shift, and much more.

[figure class=""]![Zynthian UI](ui_screenshots_sl.png)[/figure]

The MIDI-learning workflow is quick & easy. You can adjust the parameters you want from your favorite MIDI controller. Buttons can be assigned to presets (program-change), and knobs/faders to parameters (CC).

Regarding latency and jitter, the default configuration (<10ms) is enough for most players, but if you are looking for extra-low latency, audio configuration can be tweaked.
