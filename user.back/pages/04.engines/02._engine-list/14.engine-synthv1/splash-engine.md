---
title: SynthV1
id: synthv1
description: 'Old-school 4-oscillator subtractive polyphonic synthesizer with stereo FX'
taxonomy:
    category:
        - synthesizer
    tag:
        - free-software
        - synth-sub
        - ucase-pr
date: '17:38 24-04-2020'
subtitle: 'Virtual Analog Synthesizer'
splash:
    bg_image_landscape: synthv1-hero.png
    bg_image: synthv1-hero_small.png
media_thumb: synthv1.png
audio:
    -
        type: local
        local:
            audioFile: woodpecker.ogg
            audioLabel: Woodpecker
    -
        type: local
        local:
            audioFile: undeniable.ogg
            audioLabel: Undeniable
    -
        type: local
        local:
            audioFile: noizeexportdemo.ogg
            audioLabel: 'Noize Export Demo'
    -
        type: local
        local:
            audioFile: saturnone.ogg
            audioLabel: 'Saturn One'
    -
        type: local
        local:
            audioFile: spaceorgan.ogg
            audioLabel: 'Space Organ'
    -
        type: local
        local:
            audioFile: clavone.ogg
            audioLabel: 'Clav One'
    -
        type: local
        local:
            audioFile: bubbler.ogg
            audioLabel: Bubbler
    -
        type: local
        local:
            audioFile: isitterrific.ogg
            audioLabel: 'Is it terrific?'
    -
        type: local
        local:
            audioFile: phasedout.ogg
            audioLabel: 'Phased Out'
    -
        type: local
        local:
            audioFile: solohornone.ogg
            audioLabel: 'Solo Horn One'
    -
        type: local
        local:
            audioFile: synthkeysfour.ogg
            audioLabel: 'Synth Keys Four'
    -
        type: local
        local:
            audioFile: eightmm.ogg
            audioLabel: 'Eight MM'
    -
        type: local
        local:
            audioFile: solohornthree.ogg
            audioLabel: Solohornthree
urls:
    -
        urlLink: 'https://synthv1.sourceforge.io'
        urlLabel: 'Project''s Website'
    -
        urlLink: 'http://www.linuxsynths.com/Synthv1PatchesDemos/synthv1.html'
        urlLabel: 'LinuxSynths Page'
    -
        urlLink: 'https://github.com/rncbc/synthv1'
        urlLabel: 'Source Code'
---

SynthV1 is an old-school all-digital 4-oscillator subtractive polyphonic synthesizer with stereo FX. It's designed and developed by Rui Nuno Capela, and is part of the Vee One Suite (which includes Padthv1, Samplv1 and Drumkv1). It can run as a standalone synth or as an LV2 plugin within a DAW setup such as Ardour or QTractor. It can run in a Jack or Non Session Management (NSM) session, and has Jack Midi and Alsa Midi support.

## Features:
Synthv1 has both polyphonic (32 note) and monophonic capability, as well as velocity and aftertouch sensitivity controls. The layout is such that there are two identical pages, nominated Synth 1 and Synth 2, plus a third (effects) page. Both synth pages include a DCO section, a Filter section, an Amplitude section, an LFO section, a Controller section and a General Output section. The Output section controls the audio level with respect to the other synth's output, as well as the amount of effects signal.

Each page's oscillator section includes two waveform selectors, with the classic waveforms and their bandlimited counterparts: pulse-to-square, triangle-to-saw, sine, random and noise. A setting of zero (when set to pulse) will deactivate the oscillator. A sync function is also included. The width knobs modulate the waveforms as well as the random and noise signals.

Detuning of plus and minus four octaves, plus fine detuning. Portamento (glide) and a global adjustment for the ADSR envelope rate are located in the upper righthand area of the GUI.

The Filter section provides 12-dB (state variable), 24-dB (Stilson/Smith Moog) and bi-quad filter types: lowpass, highpass, bandpass and band-reject. There is also a formant filter. There are traditional ADSR envelopes provided for both filter and amplitude, as well as another ADSR envelope for the LFO section. The LFO has a BPM control that can be synced to the transport or host rate.

The "DEF" section has controls for setting pitchbend, modulation and velocity. The Effects Page (not shown in screenshot above) provides various types of effects: chorus, flanger, phaser, reverb and delay, as well as a compressor and a limiter.