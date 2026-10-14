---
title: Sfizz
id: sfizz
description: 'Sample-based synthesizer that supports SFZ format'
taxonomy:
    category:
        - synthesizer
    tag:
        - free-software
        - ucase-kb
        - synth-sample
date: '17:38 10-03-2020'
subtitle: 'SFZ Player'
splash:
    bg_image_landscape: redwave-hero.jpg
    bg_image: redwave-hero_small.jpg
media_thumb: redwave-card.jpg
audio:
    -
        audioType: local
        audioFile: OrionsBelt.ogg
        audioLabel: "Orion's Belt, MIDI Sequenced"
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
        urlLabel: "Project's Website"
    -
        urlLink: 'https://sfztools.github.io/sfizz/quick_reference'
        urlLabel: 'Official Documentation'
    -
        urlLink: 'https://github.com/sfztools/sfizz'
        urlLabel: 'Source Code'
---

Sfizz is a sample-based synthesizer featuring the well-established SFZ instrument format at its core, which permits to use existing instrument libraries, or create personal instruments with ease. Sfizz fully supports SFZv1, and it partially supports SFZv2. Sfizz also includes experimental support for the "Decent Sampler" file format (.dspreset).

Sfizz implements an advanced disk streaming system that loads the samples on demand, and dynamically reclaims the memory of sounds which are no longer used, keeping the RAM memory requirement at minimum, allowing to play massive instruments.
