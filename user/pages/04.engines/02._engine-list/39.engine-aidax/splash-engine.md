---
title: AIDA-X
media_order: aidax.jpg
description: 'Neural-network and IR modeler for amplifiers, stompboxes, cabinets and other gear.'
taxonomy:
    category:
        - effect
    tag:
        - free-software
        - ucase-pr
        - effect
        - fx-other
        - ucase-fx
        - fx-distortion
date: '17:38 24-04-2020'
subtitle: 'AI Crafted Tone'
splash:
    bg_image: aidax-hero.jpg
    bg_image_landscape: aidax-hero.jpg
media_thumb: aidax.jpg
audio:
    -
        audioType: local
        audioFile: always-with-me-always-with-you.wav
        audioLabel: 'Always with me, always with you (Joe Satriani, played by Stojos)'
    -
        audioType: local
        audioFile: 2024-06-17_13_40_18_last_state.001.wav
        audioLabel: 'Distortion test, by stojos'
    -
        audioType: local
        audioFile: clean-test.wav
        audioLabel: 'Clean test, by stojos'
urls:
    -
        urlLink: 'https://aida-x.cc/'
        urlLabel: 'AIDA-X Website'
    -
        urlLink: 'https://tonehunt.org/models?tags%5B0%5D=aida-x'
        urlLabel: 'AIDA-X Models in ToneHunt'
    -
        urlLink: 'https://github.com/AidaDSP/AIDA-X'
        urlLabel: 'Source Code'
---

AIDA-X is an Amp Model Player, allowing it to load models of AI trained music gear, which you can then play through!

Its main intended use is to provide high fidelity simulations of amplifiers. However, it is also possible to run entire signal chains consisting of any combination of ampplifier, cabinet, distortion, drive, fuzz, boost and eq.

#### Get models from a large community

[Tonehunt.org](https://tonehunt.org/models?tags%5B0%5D=aida-x) has become the place to get the best models for Neural Amp Modeler, Aida-X and Proteus, while expanding to support more platforms in the future. Not only models, but our collection of IRs is also growing and becoming very popular within the platform.

[[figure class="center"]![Tonehunt.org](tonehunt.png)[/figure]](https://tonehunt.org/models?tags%5B0%5D=aida-x)

#### Loading files
AIDA-X comes built-in with a single Amp Model and Cabinet IR. Click on the related filename to open a file browser and load a different file.
The little icon on the left side allows to turn on/off the Amp Model and Cabinet IR. Both wav and flac audio formats are supported for IR files.

From the zynthian-ui you can also load model and IR files easily. Simply move the knob assigned to the model or IR controls and the file selector will popup.