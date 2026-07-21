---
title: Helm
id: helm
image: helm.jpg
description: 'Monophonic/polyphonic soft-synth based on subtractive synthesis'
taxonomy:
    category:
        - synthesizer
    tag:
        - free-software
        - synth-sub
        - ucase-pr
    homepage:
        - 'yes'
date: '17:38 24-04-2020'
subtitle: 'Virtual Analog Synthesizer'
splash:
    bg_image_landscape: helm-hero.png
    bg_image: helm-hero_small.png
media_thumb: helm.png
sitemap:
    lastmod: '07-05-2026 16:53'
urls:
    -
        urlLink: 'https://tytel.org/helm'
        urlLabel: Website
    -
        urlLink: 'http://linuxsynths.com/HelmPatchesDemos/helm.html'
        urlLabel: 'LinuxSynths''s page'
    -
        urlLink: 'https://github.com/mtytel/helm'
        urlLabel: 'Source Code'
audio:
    -
        audioType: local
        audioFile: bitofbrush.ogg
        audioLabel: 'Bit of Brush'
    -
        audioType: local
        audioFile: cassiopeiaone.ogg
        audioLabel: 'Cassiopeia One'
    -
        audioType: local
        audioFile: girandoone.ogg
        audioLabel: 'Girando One'
    -
        audioType: local
        audioFile: supersawmodified.ogg
        audioLabel: 'Super Saw Modified'
    -
        audioType: local
        audioFile: dripping.ogg
        audioLabel: Dripping
    -
        audioType: local
        audioFile: cassiopeiatwo.ogg
        audioLabel: 'Cassiopeia Two'
    -
        audioType: local
        audioFile: expresstwo.ogg
        audioLabel: 'Express Two'
    -
        audioType: local
        audioFile: pensivealientwo.ogg
        audioLabel: 'Pensive Alien Two'
---

Helm is an open-source realtime monophonic/polyphonic softsynth developed by Matthew Tytel at Tytel.org. It comes in both 32-bit and 64-bit versions, and can be run as an LV2 plugin or as a standalone instrument. It also includes cross-platform patch loading and saving capability.

What distinguishes Helm from a lot of other softsynths is the great amount of flexibility on modulation routing. Clicking on any of the modulation sources will highlight all of the modulateable parameters. Amount of modulation depth is allowed by mouse-clicking and dragging the parameter area.

## Features:
Helm consists of two rich-sounding oscillators that each offer 11 different (anti-aliased) waveforms. A unique cross-modulation function allows to modulate the left oscillator's tone or the right oscillator's phase. Fine and coarse (transposition) detuning for each wave are included. Unison mode is available for each oscillator, as well as control for the amount of spread of each (based on the amount of detuning). The 'h' button adds a harmonic for each voice of that oscillator. Along with the oscillators there is a sub-oscillator with shuffle wave shaping, and a noise source. All four sound sources have discrete amplitude signal level controls.

The filter section allows adjustment among lowpass, highpass, bandpass, high-shelf, low-shelf, band-shelf and allpass filter types. Cutoff and resonance slider controls are provided along the filter graph's x and y axes, respectively. A very useful formant filter with X-Y axis control is also available, and two monophonic LFOs and one polyphonic LFO are included.

Helm also includes a very capable arpeggiator function with gate, octave range and pattern controls, as well as a step-sequencer section. There are several useful effects provided as well, including reverb, stutter (resamples part of the audio signal and repeats it), delay, distortion and feedback. Global controls include pitchbend, polyphony amount (up to 32 voices), portamento with legato option, and velocity tracking. An oscilloscope is located at the top center area to the right of the main volume slider.

Preset management is quite straight-forward. The 'Browse' button near the current preset name will open the preset management window, where preset directories are located. Presets can be searched for by selecting any given folder, or by typing in a key word to search that same folder. Presets can be exported separately, or directly to the desired preset folder by clicking 'save.' Make sure that the name you give to your preset is different than those in the active directory, as Helm will not prompt to confirm overwriting an existing preset with the same name.