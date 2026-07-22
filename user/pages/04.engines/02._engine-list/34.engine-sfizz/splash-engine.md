---
title: Sfizz
id: sfizz
description: 'Sample-based synthesizer that supports SFZ soundfont format'
taxonomy:
    category:
        - synthesizer
    tag:
        - free-software
        - ucase-kb
        - synth-sample
date: '17:38 10-03-2020'
subtitle: 'SFZ Soundfont Synthesizer'
splash:
    bg_image_landscape: redwave-hero.jpg
    bg_image: redwave-hero_small.jpg
media_thumb: redwave-card.jpg
audio:
    -
        audioType: local
        audioFile: OrionsBelt.ogg
        audioLabel: 'Orion''s Belt, MIDI Sequenced'
    -
        audioType: local
        audioFile: SalamanderGrandPianoDemoByHumi.mp3
        audioLabel: 'Demo, by Humi (Salamander Grand Piano SFZ)'
    -
        audioType: local
        audioFile: RhodesHammondByHumi.mp3
        audioLabel: 'Too many EPs, by Humi (Straight Rhodes SFZ)'

urls:
    -
        urlLink: 'https://sfztools.github.io/'
        urlLabel: 'Project''s Website'
    -
        urlLink: 'https://sfztools.github.io/sfizz/quick_reference'
        urlLabel: 'Official Documentation'
    -
        urlLink: 'https://github.com/sfztools/sfizz'
        urlLabel: 'Source Code'
---

Sfizz is a sample-based musical synthesizer.

It features the well-established SFZ instrument format at its core, which permits to use existing instrument libraries, or create personal instruments with ease. Sfizz supports SFZv1, and is partially compatible with SFZv2, the current revision of the instrument specification. The objective is to achieve a high level of SFZ compatibility, and the quality improves with every release. 
Sfizz also includes experimental (partial) support for the "Decent Sampler" file format (.dspreset).

The library allows developers to create instruments of their own, taking advantage of the abilities of SFZ. The hot reload ability helps you to design intruments. You are able to edit your custom instrument and test the change on the fly, without having to interact with the software manually.

The streaming system loads the sounds on demand, and dynamically reclaims the memory of sounds which are no longer used. This keeps the RAM memory requirement at minimum.
