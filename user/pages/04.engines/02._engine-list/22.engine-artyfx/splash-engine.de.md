---
title: ArtyFX
media_order: artyfx.png
description: Eine minimalistische, aber vollständige Plugin-Sammlung
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - effect
  - fx-delay
  - fx-mod
  - fx-other
  - ucase-fx
  - fx-eq
  - fx-filter
  - fx-dynamics
  - fx-distortion
  homepage:
  - 'yes'
date: 17:38 24-04-2020
subtitle: Minimalistische Plugin-Sammlung
splash:
  bg_image_landscape: artyfx-hero.png
  bg_image: artyfx-hero_small.png
media_thumb: artyfx.png
urls:
- urlLink: http://openavproductions.com/artyfx/
  urlLabel: ArtyFX's Website
- urlLink: http://openavproductions.com/doc/artyfx.html
  urlLabel: ArtyFX's Documentation
- urlLink: https://github.com/openAVproductions/openAV-ArtyFX
  urlLabel: Source Code
---
ArtyFX ist eine Sammlung minimalistischer Audioeffekte, die eigenständig verwendet werden kann, aber auch in viele komplexere Projekte von OpenAV wie Fabla2, Sorcer und Luppp integriert ist. Jeder Effekt kann einzeln als LV2-Plugin verwendet werden..

ArtyFX enthält viele verschiedene Plugins – alle „klassischen“ Effekte wie Reverbs, Delays und Filter sind vorhanden. In den folgenden Abschnitten wird jedes Plugin einzeln vorgestellt. Dabei wird gezeigt, wie es verwendet werden kann, und es werden einige Empfehlungen für bewährte Vorgehensweisen gegeben..

#### Bitta
Bitta ist ein Bit-Crusher-Plugin. Bit-Crushing reduziert die Bittiefe des Audios. Da es von der Lautstärke des eingehenden Signals abhängt, sei beim Einstellen des „crush“-Reglers vorsichtig..

**Crush :** Ändert die Anzahl der Bits, die zum Verzerren des Audios verwendet werden.

#### Della
Della ist ein Delay zur Anpassung des BPM mit Reglern für Feedback und Delay-Lautstärke..

**Feedback:** steuert den Anteil des Signals, der in die Delay Line zurückgeführt wird: Drehe ihn auf, um diesen endlosen, reggae-verrückten Dub-Echo-Effekt zu erzielen!

**Lautstärke:** ändert den Anteil des verzögerten Signals, den du hörst: nützlich, um die Delays im Hintergrund eines Tracks zu halten.

**Zeit:** ändert die Delay-Länge: Beachten Sie, dass diese auf Vielfache des BPM-Werts „quantisiert“ ist und daher zwischen einer Dauer von 1/8-Note, 1/4-Note, 1/2-Note und einer ganzen Note „springt“. Della übernimmt den BPM-Wert vom Host-Programm: Wenn Sie also das Tempo ändern, bleibt sie weiterhin im Takt!

#### Ducka
Ducka ist ein Side-Chain-Hüllkurven-Plugin: Es ist sehr nützlich, um „pumpende“ Basslines zu erzeugen, wie sie häufig in Minimal-House-Musik vorkommen. Das Plugin funktioniert, indem es die Lautstärke eines Sidechain-Eingangs analysiert und die Lautstärke einer separaten Stereo-Spur anhand der Amplitude des Sidechain-Eingangs verändert.

**Schwellenwert:** legt den Pegel fest, den das Eingangsaudio erreichen muss, bevor die Stereospur reduziert wird.

**Ablegen:** steuert die Stärke der Lautstärkereduzierung, die vorgenommen wird.

**Zeit:** steuert die Zeitspanne, bevor die Stereospur wieder eingeblendet wird. Beachten Sie, dass diese Steuerung BPM-abhängig ist und die Mitte direkt auf den Offbeats liegt. Eine Einstellung auf die Hälfte (Standardeinstellung) ist in der Regel musikalisch :)

#### Driva
Driva ist eine Multi-Distortion-Einheit, die zu besonders fiesen und rauen Verzerrungen fähig ist..

**Ton:** Klicke auf die Tone-Schaltfläche. Eine Liste verschiedener Verzerrungsmodelle steht zur Verfügung. Klicke einfach auf die gewünschte Verzerrung und rocke weiter. Mit „Cancel“ unten verlässt du die Tone-Änderungsansicht..

**Menge:** dreht einfach die Gain-/Verzerrungsmenge hoch. Auf eigene Gefahr verwenden.!

#### Filta
Filta ist eine Kombination aus Tiefpass- und Hochpassfilter. Nützlich, um unerwünschte hohe und tiefe Frequenzen aus verschiedenen Aufnahmen oder Instrumenten zu entfernen.A

**Frequenz:** steuert, welche Art von Filterung vorgenommen wird und bei welcher Frequenz. Niedrigere Werte entsprechen einem Lowpass-Filter, ein Hochdrehen des Reglers verursacht einen Highpass.

#### Kuiza
Kuiza ist ein 4-Band-Equalizer. Er eignet sich perfekt, um den Klang eines Instruments oder Synths kreativ zu formen. Jeder der Gain-Regler verändert die Amplitude bei der angegebenen Frequenz. Der Master Gain kann bei Bedarf verwendet werden, um die Gesamtlautstärke zu verringern oder zu erhöhen. Die Regler (von links nach rechts):

* Tief ( ~55 Hz)
* Untere Mitten ( ~220 Hz)
* Hohe Mitten ( ~1760 Hz)
* Hoch ( ~7040 Hz)
* Master Gain

#### Masha
Masha ist ein Beat-Grinder-Plugin: Es nimmt einen Audioabschnitt auf und spielt ihn als Loop ab, wodurch ein „Stutter“-Effekt entsteht..

**Lautstärke:** verändert die Lautstärke des Stutter-Loops. PassThru ermöglicht, das normale Signal beizumischen..

**Zeit:** ist eine BPM-abhängige Steuerung, die die Loop-Aufnahme- und Wiedergabelänge verändert. Verringere diesen Wert allmählich, um diesen „Standard“-DJ-Stutter-Effekt zu erzielen! Dieser Effekt bietet einige spezielle Funktionen, die eine manuelle Steuerung der BPM ermöglichen. Normalerweise werden die BPM vom Host-Programm (oder JACK-Transport) übernommen, aber sie können jetzt über einen Drehregler gesteuert werden..

**HostBPM-Schaltfläche:** steuert die BPM-Quelle. Wenn die Schaltfläche blau ist, ist HostBPM aktiviert. Wenn du die Schaltfläche ausschaltest, wird das manuelle BPM-Drehrad angezeigt. Das Drehrad zeigt auch das aktuelle BPM an.

#### Panda
Panda ist eine compressor-expander-Kombination, mit attack- und release-Reglern.

**Threshold:** der „Wendepunkt“ von Kompression / Expansion. Wird der Drehregler heruntergedreht, wird das Signal expandiert, wird er aufgedreht, wird es komprimiert.

**Freigeben:** ändert die Zeit, die Panda benötigt, um seine Kompression/Expansion auszublenden.

**Faktor:** steuert den Umfang der vorgenommenen Kompression/Expansion, der „Maximizer“-Regler.

#### Geräumig
Roomy ist ein räumlicher und weicher Reverb.

**Der Time-Regler** ändert die Länge des Reverb-Tails: höhere Werte erzeugen einen größeren und räumlicheren Mix.

**Damping** steuert die Hochfrequenz- Dämpfung: niedrigere Einstellungen ergeben einen räumlichen, offenen Klang, während eine hohe Dämpfung klein und nah wirkt.

**Der Dry/Wet-Regler** ändert den Anteil des zugemischten Reverb-Signals: nützlich für Techno- und Trance-„Reverb-Builds“ ... einfach voll aufdrehen!

#### Satma
Satma ist ein verrücktes Distortion-Plugin. Nützlich, um Audio aufzupeppen und körnig und schmutzig klingen zu lassen..

**Distortion** ändert das Ausmaß der Signalformung, die stattfindet: das Gesamtausmaß der Rauscherzeugung.

**Die Tone-Steuerung** subtil zwischen hohen und tieferen Frequenzen variiert oder beide gleichermaßen körnig macht.

#### Vihda
Vihda ist ein Stereo-Enhancer, der eine Mid-Side-Matrix verwendet.

**Der Width-Parameter** beeinflusst die Menge an Stereoanteil im Signal. Beachte, dass die die mid-side technique nur Stereo verstärkt: Sie erzeugt es nicht!

**Die Invertieren-Schaltfläche** invertiert den rechten Kanal, was aufgrund der Interpretation von Audio durch das Gehirn zu einem subjektiv breiteren Mix führen kann. Probier es aus und hör, ob es gut klingt..

