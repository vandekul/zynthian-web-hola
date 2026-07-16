---
title: Guitarix
media_order: guitarix.jpg
description: 'GNU/Linux Virtual Guitar Amplifier'
taxonomy:
    category:
        - effect
    tag:
        - free-software
        - effect
        - fx-delay
        - fx-mod
        - ucase-fx
        - fx-distortion
content:
    items: '@self.modular'
date: '17:38 24-04-2020'
subtitle: 'GNU/Linux Virtual Guitar Amplifier'
splash:
    bg_image_landscape: guitarix.jpg
    bg_image: guitarix-hero_small.jpg
media_thumb: guitarix.jpg
audio:
    -
        type: local
        local:
            audioFile: guitarixDemoI.ogg
            audioLabel: 'Guitarix Demo I'
        soundcloud:
            audioLink: ''
            soundcloudLabel: ''
    -
        type: local
        local:
            audioFile: guitarixDemoII.ogg
            audioLabel: 'Guitarix Demo II'
        soundcloud:
            audioLink: ''
            soundcloudLabel: ''
    -
        type: local
        local:
            audioFile: guitarixDemoIII.ogg
            audioLabel: 'Guitarix Demo III'
        soundcloud:
            audioLink: ''
            soundcloudLabel: ''
video:
    -
        type: youtube
        youtube:
            youtubeLink: 'https://www.youtube.com/watch?v=KEVs_P0Rglo'
            youtubeLabel: ''
        vimeo:
            vimeoLink: ''
            vimeoLabel: ''
    -
        type: youtube
        youtube:
            youtubeLink: 'https://www.youtube.com/watch?v=hlGKDQj2Wmk'
            youtubeLabel: ''
        vimeo:
            vimeoLink: ''
            vimeoLabel: ''
urls:
    -
        urlLink: 'https://guitarix.org/'
        urlLabel: 'Guitarix''s Website'
    -
        urlLink: 'http://sourceforge.net/projects/guitarix'
        urlLabel: 'Guitarix''s Source Code'
    -
        urlLink: 'https://github.com/brummer10/GxPlugins.lv2'
        urlLabel: 'Extra Plugins Source Code'
---

Guitarix is a virtual guitar amplifier for Linux running on Jack Audio Connection Kit. It is free as in speech and free as in beer. The available sourcecode allows to build it on other UNIX-like systems, too, namely for BSD and for MacOSX.

Guitarix takes the signal from your guitar as any real amp would do: as a mono-signal from your sound card. The input is processed by a main amp and a rack-section. Both can be routed separately and deliver a processed stereo-signal via Jack. You may fill the rack with effects from more than 25 built-in modules including stuff from a simple noise gate to brain-slashing modulation f/x like flanger, phaser or auto-wah.

Your signal is processed with minimum latency. On any properly set-up Linux-system you don't have to wait more than 10ms until your sound is processed by guitarix.