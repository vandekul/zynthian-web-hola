---
title: X42 Whirl Speaker
media_order: x42-whirl.png
description: Rotary Speaker Simulator
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - effect
  - fx-mod
  - ucase-fx
date: 17:38 24-04-2020
subtitle: Plugin-Sammlung
splash:
  bg_image_landscape: x42-whirl-hero.png
  bg_image: x42-whirl-hero_small.png
media_thumb: x42-whirl.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-whirl
  urlLabel: Whirl Speaker's Website
- urlLink: https://github.com/pantherb/setBfree
  urlLabel: Source Code
---
x42-whirl wurde entwickelt, um den Klang und die Eigenschaften des elektromechanischen rotierenden Lautsprechers nachzuahmen, der dem Namen und den Produkten von Don Leslie weltweiten Ruhm verschaffte..

Es handelt sich um eine eigenständige Version des Effekts, der mit dem Synthesizer setBfree eingeführt wurde. Statt die Gesamtwirkung des elektromechanischen Geräts zu simulieren, modelliert x42-whirl dessen Eigenschaften physikalisch, was zu einer sehr genauen Wiedergabe des Klangs des realen Geräts führt..

Da alle einzelnen Teile modelliert sind, bietet x42-whirl nicht nur eine erweiterte Steuerung, sondern ermöglicht auch Anpassungen, von denen einige am mechanischen Gerät nicht möglich sind.

#### Details
Der Signalfluss entspricht dem des ursprünglichen Hardwaregeräts. Der Übersichtlichkeit halber wird er in der Benutzeroberfläche des Plugins dargestellt. Zwei Filter trennen Bässe und Höhen, die an den Horn- und Trommellautsprecher gesendet werden. Ein zusätzlicher EQ ermöglicht es, den Klang des Hochfrequenztreibers anzupassen..

Das Herzstück des Effekts ist ein rotierender Hornlautsprecher. Zwei Hörner sind zu sehen, aber eines (das dunkle in der GUI) ist ein Dummy, der hauptsächlich dazu dient, die Zentrifugalkraft des anderen während der Rotation auszugleichen. Das Plugin verwendet eine Kombination aus Doppler-Verschiebung und winkelabhängigen, nullverschobenen Impulsantworten für ein Model-600-Horn (das Model-44W-Horn ist identisch mit dem Model 600 und offenbar bei allen Leslie-Modellen Standard [1]). Die Hornmessung wurde von J.O. Smith III et al.([2]) durchgeführt. Der Klang des Woofers wird von einer Amplitudenmodulation dominiert, die durch die Wölbung der rotierenden Trommel verursacht wird.

x42-whirl berechnet sechs Reflexionen abhängig von den Winkeln des Horns und der Trommel sowie vom Abstand und der Position der Mikrofone, um die Nachhallstreuung entsprechend den Abmessungen und Streueigenschaften des Gehäuses zu emulieren. Darüber hinaus berücksichtigt das Modell Artefakte wie Signalübersprechen vom Hochtöner, das nicht durch das Horn geleitet wird..

Die Motorsteuerung ermöglicht es, für jeden der Horn- und Trommelrotoren zwei Zielgeschwindigkeiten (langsam/Chorale und schnell/Tremolo) in RPM sowie Beschleunigungs- und Verzögerungszeitkonstanten in Sekunden (bis zur halben Geschwindigkeit) einzustellen. Auch wenn die Reibung dabei nicht berücksichtigt wird, kommt dies einer originalen, ordnungsgemäß geölten Anlage nahe..

Manchmal ist das Horn oder die Trommel auf die Rückseite des Gehäuses ausgerichtet, wenn es zum Stillstand kommt, was zu einem weniger wünschenswerten Klang führt. Eine zusätzliche optionale Einstellung ermöglicht es, eine Stop-Position festzulegen.

Zur Vereinfachung umfasst die Ausgangsstufe zwei Stereo-Matrixmischer, mit denen sich das Stereofeld reduzieren und die Mono-Kompatibilität erhöhen lässt..

#### Hinweis zu Parametern
Standardmäßig verwendet das Plugin Einstellungen, die einem Model 44 entsprechen (Rotationsgeschwindigkeiten, Trommel- und Hornradius), sowie eine charakteristische 180deg-Links/Rechts-Mikrofonierungstechnik. Die verschiedenen Aspekte können jedoch angepasst werden.

Die außermittige Position des Horns wird bei der Berechnung der Gehäusereflexionen berücksichtigt, allerdings sind die Mikrofone symmetrisch in gleichem Abstand zum Zentrum des Rotors positioniert. Eine Vergrößerung der Radien verstärkt die Doppler-Frequenzmodulation, eine Vergrößerung des Mikrofonabstands verändert das Spektrum subtil aufgrund der unterschiedlichen Signallaufzeiten für jede der Reflexions- und Lautsprecherpositionen.

Alle Abstände werden vom Mittelpunkt jedes Rotors aus gemessen. Das Plugin ermöglicht einige Konfigurationen, die in der realen Welt unmöglich sind (z. B. das Mikrofon in das rotierende Gerät hineinbewegen). In diesen Fällen werden nur Abstands- und Winkelberechnungen berücksichtigt; sie entsprechen nicht dem, was du hören würdest, wenn dies mechanisch möglich wäre. Obwohl das oberste Ziel darin besteht, das Gerät so realistisch wie möglich nachzubilden, sind diese Konfigurationen im Plugin enthalten, weil sie zu interessanten Klängen führen können – und genau darum geht es letztendlich..
