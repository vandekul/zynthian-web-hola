---
title: Konzept
smallTitle: Irúfẹ́ ohun èlò orin tuntun kan!
onpage_menu: true
menu: Konzept
visible: false
lead: Zynthian ist ein kompaktes, eigenständiges Musikgerät, das als Keyboard-Expander,
  Audioeffektgerät, MIDI-Prozessor & -Router, Groovebox und Mikro-DAW genutzt werden
  kann.
subtitle: 'Der zu übersetzende Text beginnt in der nächsten Zeile:'
buttonText1: Mehr dazu in unserem Wiki
buttonLink1: https://wiki.zynthian.org
buttonText2: Benutzerhandbuch lesen
buttonLink2: https://help.zynthian.org/
---
Zynthian ist ein [community-getriebenes Projekt](https://discourse.zynthian.org)—100% open-source, mit freier Software auf offener Hardware. Es ist vollständig konfigurierbar und uneingeschränkt hackbar! **Frei im Sinne von Freiheit**. Du kannst deinen Zynthian von Grund auf bauen oder [kaufe ein offizielles Kit](https://shop.zynthian.org).

### Über 100 virtuelle Instrumente
Zynthian enthält eine vollständige Sammlung virtueller Instrumente und Emulatoren:
+ **Akustische und elektrische keys** wie Flügel, Rhodes, Wurlitzer, Clavinet, und Farfisa.
+ **Orgeln** wie tonewheel Hammonds, Transistor-Combo-Orgeln, und Pfeifenorgeln.
+ **Ikonische Synths** wie der DX7, Oberheim, Juno-60, und TB-303.
+ **Virtuell-Analoge Synthesizer** wie ZynAddSubFX, Surge-XT, Vaporizer2, NoizeMaker, Odin2, MiMi-d, Monique, Helm, und Amsynth.
+ **Echte Hardware-Emulatoren** wie die von entwickelten [Die üblichen Verdächtigen](https://theusualsuspects.io/), einschließlich Osirus, OsTIrus, Vavra, Xenia, VirtualJV, und JE-8086. (<i>Hinweis: Für den Betrieb ist die Beschaffung einer legalen Kopie der Firmware-ROM-Datei des Geräts erforderlich</i>).

<a class="minilink" href="/engines#synthesizers">weitere Details zu virtuellen Instrumenten &nbsp;&nbsp;&gt;</a>

### Sample-basierte Instrumente
Spiele umfangreiche multisampled Soundbanks mit nativer Unterstützung für **SF2**, **SF3**, **SFZ**, **DecentSampler (DS)**, und **GIG** formate. Zynthian bietet eine umfangreiche integrierte Sammlung von Sample-Instrumenten, die du ganz einfach mit Erweiterungspaketen und deinen eigenen benutzerdefinierten Bibliotheken erweitern kannst.

Für die leistungsfähigeren Formate (**SFZ**, **DS**, und **GIG**), die Instrumentengröße ist nicht durch den Arbeitsspeicher begrenzt. Die Sfizz- und LinuxSampler-Engines implementieren fortschrittliche Play-from-Disk-Algorithmen, mit denen Sie beliebig große Instrumente laden können.

<a class="minilink" href="https://github.com/zynthian/zynthian-packages/tree/main/Soundfonts">weitere Details zu gesampelten Instrumenten &nbsp;&nbsp;&gt;</a>

### Über 1,000 Audioeffekte & MIDI-Tools
+ **Klassische Audioeffekte** mit grundlegenden Effekten wie reverb, delay, chorus, distortion, saturation, EQ, compression, flanger, phaser, und wah-wah.
+ **Moderne Audioeffekte** einschließlich tape simulators, granulators, vocoders, pitch-shifters, und auto-tune.
+ **Modellierung neuronaler Netzwerke** für eine präzise Emulation nichtlinearer Geräte wie der meisten Verstärker und stompboxes. Installiere deine bevorzugten tones von [Tone3000](https://tone3000.com) mit nur wenigen Klicks.
+ **Impulse response modeling** für reverb und cabinet emulation.
+ **MIDI-Werkzeuge** wie velocity curves, chorders, arpeggiators, monophonic converters, strumming utilities, und harmony analyzers.

<a class="minilink" href="/engines#effects">mehr Details zu audio FXs & MIDI-Tools &nbsp;&nbsp;&gt;</a>

### Kostenlose Erweiterungspakete
Zynthian lässt sich einfach mit Paketen erweitern, die mit nur einem Klick installiert werden können. Die Pakete können gesampelte Instrumente, Sammlungen von samples, loops, patterns und IRs enthalten. Benutzer können ihre eigenen Pakete erstellen und mit der Community teilen.

<a class="minilink" href="https://zynthian.github.io/zynthian-packages/">weitere Details zu Erweiterungspaketen &nbsp;&nbsp;&gt;</a>

### Produktionswerkzeuge
+ **[Zynseq](/use-case/groovebox-udaw)** ist ein voll ausgestatteter step sequencer mit live capture, Quantisierung, Blockoperationen und swing. Er bietet Humanisierung von velocity und Timing, Wiedergabefrequenz und -wahrscheinlichkeit pro step, erweiterte stutter-Effekte und Parameterautomatisierung.
+ **[Clippy](/use-case/groovebox-udaw)** ist eine Audio-Clip-Engine, mit der du Beat-synchronisierte Audio-Samples mit Auto-Warping und Beat-Slicing in Echtzeit abspielen kannst.
+ **[Launcher](/use-case/groovebox-udaw)** ist ein Steuerraster für Performances, mit dem du Patterns, Audio-Clips oder musikalische Phrasen auslösen kannst, die in aufeinanderfolgenden Reihen angeordnet sind. Programmiere präzise Taktart- und Tempowechsel, Phrasen-Loops und eine bedingte Phrasenwiedergabe, um *Da Capo* und *CODA* verhalten.
+ **[Zynmixer](/use-case/groovebox-udaw)** ist ein leistungsstarker, flexibler Mixer, der intuitiv bleibt und gleichzeitig professionelle Kanalfunktionen bietet: mono/stereo-Umschaltung, Phasenumkehr, M+S-Schalter, anpassbare mixbuses, unabhängige send levels, AB-mixing, und pre-fader listening (PFL).
+ **[SooperLooper](https://sonosaurus.com/sooperlooper/features.html)** von Jesse Chappell ist ein Mehrkanal-Live-Audio-Looper, inspiriert vom legendären **Gibson Echoplex Digital Pro (EDP)** hardware. Es bietet sofortige Loop-Aufnahme, mehrschichtiges Overdubbing, Loop-Vervielfachung, Umkehrung in Echtzeit und variablen Feedback-Decay.
+ **[Native Integration mit beliebten MIDI-Controllern](https://wiki.zynthian.org/index.php/Supported_plug_%26_play_MIDI_controllers)** bietet plug-and-play-Unterstützung für Branchenstandards wie den Akai APC40, APC Key 25, und MIDI Mix, Novation Launchpads und Launchkeys, den Korg nanoKONTROL, und vollwertige Mackie Control Universal (MCU) Control Surfaces.
+ **Mehrspur-Audiorecorder** ermöglicht dir, einzelne Instrumenten- und Effektketten unabhängig voneinander in einer makellosen Multitrack-WAV-Session aufzunehmen.
+ **MIDI-Datei-Recorder/Player** ermöglicht es dir, standardmäßige MIDI-Dateien (.MID) ganz einfach spontan aufzunehmen, zu speichern, und wiederzugeben.
+ **[Pure Data](http://www.pd-tutorial.com/english/index.html)** integriert eine leistungsstarke visuelle Programmiersprache für individuelles audio und MIDI sound design.

<a class="minilink" href="/use-case/groovebox-udaw">mehr Details zu Produktionswerkzeugen &nbsp;&nbsp;&gt;</a>
