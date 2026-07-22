---
title: AMSynth
id: amsynth
description: 'Analog Modelling Synthesizer that uses a traditional subtractive synthesis approach to sound design'
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
    bg_image_landscape: amsynth-hero.png
    bg_image: amsynth-hero_small.png
media_thumb: amsynth.png
audio:
    -
        audioType: local
        audioLabel: 'Particularly Two'
        audioFile: particularlytwo.ogg
    -
        audioType: local
        audioLabel: 'Corg Two Six'
        audioFile: corgtwosix.ogg
    -
        audioType: local
        audioLabel: 'Glass Bay'
        audioFile: glassbay.ogg
    -
        audioType: local
        audioLabel: Partenza
        audioFile: partenza.ogg
    -
        audioType: local
        audioLabel: 'Simple Life'
        audioFile: simplelife.ogg
    -
        audioType: local
        audioLabel: 'End Game'
        audioFile: endgame.ogg
    -
        audioType: local
        audioLabel: 'First Pew'
        audioFile: firstpew.ogg
    -
        audioType: local
        audioLabel: Overpass
        audioFile: overpass.ogg
    -
        audioType: local
        audioLabel: 'Soft Warning'
        audioFile: softwarning.ogg
    -
        audioType: local
        audioLabel: 'Soft Warning'
        audioFile: softwarning.ogg
urls:
    -
        urlLink: 'https://amsynth.github.io'
        urlLabel: 'Project''s Website'
    -
        urlLink: 'http://www.linuxsynths.com/amSynthdemos/amsynth.html'
        urlLabel: 'LinuxSynths Page'
    -
        urlLink: 'https://github.com/amsynth/amsynth'
        urlLabel: 'Source Code'
---

AmSynth, or Analog Modelling Synthesizer, developed and maintained by Nick Dowell, uses a traditional subtractive synthesis approach to sound design, and can be run either as a standalone instrument or as a DSSI or LV2 plug-in within a digital audio workstation such as Ardour or Qtractor.

AmSynth is a realtime, polyphonic/monophonic virtual synthesizer with touch-sensitivity and full MIDI control capability. It includes two oscillators, each capable of generating the classic waveforms: square-to-pulse, triangle-to-saw, sine, noise and sample-and-hold. Oscillator 2 can be synced to oscillator 1, and it can also be detuned: finetuning (plus or minus 4 semitones), coarse detuning (plus or minus 12 semitones) and octave detuning (minus three or plus four). Syncing the oscillators and adjusting the semitone detuning gives some interesting FM-like timbres. An oscillator mix knob allows control of the balance between the two, and turning it all the way to the left or right will isolate the one or the other. Ring modulation level knob is also provided.

A standard ADSR envelope is provided for both amplitude and filter sections. Filter and amplitude velocity sensitivity knobs are located in the lower righthand corner of the GUI.

The filter section includes 9 filter types: low-pass, high-pass, bandpass and notch (each at 12dB and 24dB settings) and a filter bypass option. An envelope strength knob controls the depth of the filter effect, in positive and negative. Filter keyfollow, resonance and cutoff are included in this section.

AmSynth has one Low Frequency Oscillator. This LFO can be completely off, or set to affect the pitch, filter and amplitude, or any combination of the three. The pitch parameter can be routed to either of the oscillators, or both. Waveform shapes include: square, triangle, sine, sample-and-hold, saw-up, saw-down and noise.

Together with the main volume and drive (distortion) controls, amSynth includes a plate-type reverb, a size knob to adjust wideness, stereo and damping knobs. Additional features of the newer version include mono/legato/poly control, and a very broad portamento capability, which can now be set to "always" or "legato" mode. Panning control is also provided, and "ctrl+r" hotkeys will randomize the settings.

Fine-tune knob adjustments can be made by holding down the shift key as the knobs are moved.

AmSynth has unlimited polyphony capability, although 16-note polyphony is usually sufficient. Pitchbend function can be selected in halfsteps, up to 2 octaves. Microtonal scalings are now loadable as well.


## Features:
+ Dual oscillators (sine / saw / square / noise) with hard sync
+ 12/24 dB/oct resonant filter (low-pass / high-pass / band-pass / notch)
+ Mono / poly / legato keyboard modes
+ Dual ADSR envelope generators (filter & amplitude)
+ LFO which can modulate the oscillators, filter, and amplitude
+ Distortion and reverb
