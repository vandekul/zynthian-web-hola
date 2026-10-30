---
title: X42 Equalizer
media_order: x42-fil4.png
description: 4 band parametric equalizer
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - fx-filter
content:
  items: '@self.modular'
date: 17:38 24-04-2020
subtitle: 4 band Parametric Equalizer
splash:
  bg_image_landscape: x42-fil4-hero_small.png
  bg_image: x42-fil4-hero_small.png
media_thumb: x42-fil4.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-eq
  urlLabel: X42 Equalizer's Website
- urlLink: https://github.com/x42/fil4.lv2
  urlLabel: Source Code
---
x42-eq (alias fil4.lv2) est un égaliseur paramétrique à 4 bandes avec des filtres shelving bas et haut supplémentaires, ainsi que des filtres passe-haut et passe-bas. L’égaliseur est conçu pour reproduire un gain analogique équivalent, avec une Latency nulle et sans déphasage à l’approche de la fréquence de Nyquist. Il n’a pas de réponse étriquée, souvent qualifiée de son numérique. x42-eq comprend des affichages intégrés en temps réel du spectre et du spectrogramme (cascade), un affichage de maintien des crêtes réinitialisable par l’utilisateur et un contrôle de gain de sortie..

fil4.lv2 est basé sur les fil-plugins LADSPA de Fons Adriaensen.

#### Commandes du spectre
Les commandes du spectrogramme se trouvent en bas à droite.,

**Désactivé:** Ne pas afficher le spectre.<br>
**Spécification:** Afficher un spectre pondéré en bruit rose (1/octave.<br>
**Hist:** Affichage du spectrogramme ; vue historique (les lignes blanches en pointillés indiquent un changement de paramètres)<br>
**Pré:** Analysez l’entrée<br>
**Article:** Analyser la sortie traitée<br>

La Stereo Variant dispose d’une option permettant d’analyser la somme (All) ou uniquement le canal Left ou Right. Le gain knob permet d’aligner le spectre, voir l’échelle à droite de l’affichage..

**Élevé:** Déformation des hautes fréquences, résolution accrue dans les basses fréquences.<br>
**Med:** Déformation des fréquences moyennes<br>
**Aboiement:** Pas de déformation de fréquence, accentuer les hautes fréquences<br>

**Rpd:** Atténuation rapide (~~20ms)<br>
**Rapide:** Décroissance rapide (~~80 ms)<br>
**Mod:** Temps de décroissance modéré (~~200ms)<br>
**Lent:** Atténuation lente (~~2 s)<br>
**Ns.:** Mesure du bruit (~20sec)<br>

#### Caractéristiques du filtre
Fil4 est composé de quatre filtres résonants du second ordre utilisant un filtre en treillis de type Regalia-Mitra, qui a l’avantage de rester stable même lorsque les paramètres sont modifiés..

Les filtres shelving aigu/grave sont des filtres biquad/IIR standard du 2e ordre..

Les filtres passe-haut et passe-bas sont des filtres résonants du 2e ordre (-12dB/octave):

+ Qualité 0.0: -6dB à cutoff-freq (no feedback)
+ Qualité 0.7: -3dB à la fréquence de coupure
+ Qualité 1.0 : 0dB à la fréquence de coupure (résonant)

Tous les filtres ont une Latency nulle avec le gain analogique équivalent correct à Nyquist (le déphasage du signal à la fréquence de Nyquist est nul).

