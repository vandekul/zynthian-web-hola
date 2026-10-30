---
title: AMSynth
id: amsynth
description: Synthétiseur à modélisation analogique utilisant une approche traditionnelle
  de synthèse soustractive pour la création sonore
taxonomy:
  category:
  - synthesizer
  tag:
  - free-software
  - synth-sub
  - ucase-pr
date: 17:38 24-04-2020
subtitle: Virtual Analog Synthesizer
splash:
  bg_image_landscape: amsynth-hero.png
  bg_image: amsynth-hero_small.png
media_thumb: amsynth.png
audio:
- audioType: local
  audioLabel: Particularly Two
  audioFile: particularlytwo.ogg
- audioType: local
  audioLabel: Corg Two Six
  audioFile: corgtwosix.ogg
- audioType: local
  audioLabel: Glass Bay
  audioFile: glassbay.ogg
- audioType: local
  audioLabel: Partenza
  audioFile: partenza.ogg
- audioType: local
  audioLabel: Simple Life
  audioFile: simplelife.ogg
- audioType: local
  audioLabel: End Game
  audioFile: endgame.ogg
- audioType: local
  audioLabel: First Pew
  audioFile: firstpew.ogg
- audioType: local
  audioLabel: Overpass
  audioFile: overpass.ogg
- audioType: local
  audioLabel: Soft Warning
  audioFile: softwarning.ogg
- audioType: local
  audioLabel: Soft Warning
  audioFile: softwarning.ogg
urls:
- urlLink: https://amsynth.github.io
  urlLabel: Project's Website
- urlLink: http://www.linuxsynths.com/amSynthdemos/amsynth.html
  urlLabel: LinuxSynths Page
- urlLink: https://github.com/amsynth/amsynth
  urlLabel: Source Code
---
AmSynth, ou synthétiseur à modélisation analogique, développé et maintenu par Nick Dowell, utilise une approche traditionnelle de synthèse soustractive pour la conception sonore et peut être utilisé soit comme instrument autonome, soit comme plug-in DSSI ou LV2 dans une station de travail audio numérique telle qu’Ardour ou Qtractor..

AmSynth est un synthétiseur virtuel polyphonique/monophonique en temps réel, sensible au toucher et entièrement contrôlable par MIDI. Il comprend deux oscillateurs, chacun capable de générer les formes d’onde classiques : carré à impulsion, triangle à dent de scie, sinus, bruit et sample-and-hold. L’oscillateur 2 peut être synchronisé sur l’oscillateur 1 et désaccordé : accord fin (plus ou moins 4 demi-tons), désaccord grossier (plus ou moins 12 demi-tons) et désaccord d’octave (moins trois ou plus quatre). La synchronisation des oscillateurs et le réglage du désaccord en demi-tons produisent des timbres intéressants, proches de la FM. Un knob de mixage des oscillateurs permet de régler l’équilibre entre les deux ; le tourner complètement vers la gauche ou la droite isolera l’un ou l’autre. Un knob de niveau de modulation en anneau est également fourni..

Une enveloppe ADSR standard est fournie pour les sections d’amplitude et de filtre. Les knobs de sensibilité à la vélocité du filtre et de l’amplitude se trouvent dans le coin inférieur droit de la GUI..

La section du filtre comprend 9 types de filtre : passe-bas, passe-haut, passe-bande et coupe-bande (chacun avec des réglages de 12dB et 24dB), ainsi qu’une option de bypass du filtre. Un Knob d’intensité de l’enveloppe contrôle la profondeur de l’effet du filtre, en positif et en négatif. Le suivi du clavier, la résonance et la fréquence de coupure du filtre sont inclus dans cette section.

AmSynth dispose d’un LFO. Celui-ci peut être complètement désactivé ou réglé pour agir sur la hauteur, le filtre et l’amplitude, ou sur n’importe quelle combinaison des trois. Le paramètre de hauteur peut être routé vers l’un ou l’autre des oscillateurs, ou vers les deux. Les formes d’onde disponibles sont : carré, triangle, sinusoïdale, sample-and-hold, dent de scie montante, dent de scie descendante et bruit..

En plus des contrôles principaux de volume et de drive (distorsion), amSynth inclut une Reverb de type plate, un Knob de taille pour ajuster la largeur, ainsi que des Knobs de stéréo et d’amortissement. Les fonctionnalités supplémentaires de la version plus récente incluent un contrôle mono/legato/poly et une très grande plage de portamento, qui peut désormais être réglé en mode « always » ou « legato ». Un contrôle de panning est également disponible, et les raccourcis clavier « ctrl+r » permettent de randomiser les réglages..

Les réglages fins des Knob peuvent être effectués en maintenant la touche Maj enfoncée pendant leur déplacement..

AmSynth dispose d’une polyphonie illimitée, bien que 16 notes de polyphonie soient généralement suffisantes. La fonction Pitchbend peut être réglée par demi-tons, jusqu’à 2 octaves. Les gammes microtonales peuvent désormais être chargées également..

## Fonctionnalités:
+ Deux oscillateurs (sinusoïdal / dent de scie / carré / bruit) avec synchronisation dure
+ Filtre résonant 12/24 dB/oct (passe-bas / passe-haut / passe-bande / coupe-bande)
+ Modes de clavier mono / poly / legato
+ Générateurs d’enveloppe ADSR doubles (filtre & amplitude)
+ LFO pouvant moduler les oscillateurs, le filtre et l'amplitude
+ Distorsion et reverb
