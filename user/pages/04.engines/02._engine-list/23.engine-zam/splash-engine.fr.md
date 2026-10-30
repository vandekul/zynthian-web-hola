---
title: ZAM Plugins
media_order: redwave.jpg
description: Une collection de plugins de traitement du son
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - fx-delay
  - fx-mod
  - fx-other
  - ucase-fx
  - fx-eq
  - fx-filter
  - fx-dynamics
  - fx-distortion
date: 17:38 24-04-2020
subtitle: Collection de plugins
splash:
  bg_image_landscape: redwave-hero.jpg
  bg_image: redwave-hero_small.jpg
media_thumb: redwave.jpg
audio:
- audioType: local
  audioFile: angie-20141010_follow.ogg
  audioLabel: Follow, by Angie Hudson (2013)
video:
- videoType: youtube
  videoLink: https://www.youtube.com/watch?v=MGErjKRu_dQ
urls:
- urlLink: http://www.zamaudio.com/
  urlLabel: ZamAudio's Website
- urlLink: http://github.com/zamaudio/zam-plugins
  urlLabel: Source Code
---
Zam-plugins est une collection de plugins audio LV2/LADSPA/VST/JACK pour le traitement du son, développés en interne chez ZamAudio. Les paramètres par défaut et presque tous les curseurs sont calibrés sur des plages standard..

Un grand merci à falktx pour avoir écrit Distrho Plugin Framework. Cela m'a permis de créer rapidement et proprement ces GUIs pour zam-plugins. Merci également à mira, nphilipp, adi, edogawa et Haskellfant qui ont aidé à empaqueter le logiciel pour différentes distributions.!

## Vue d’ensemble

#### ZaMaximX2
L'un des meilleurs plugins de la série, il agit comme un brickwall limiter pour le mastering dans son état par défaut, mais peut aussi être réglé pour augmenter le niveau moyen en tant que maximiseur stéréo sans jamais clipper. Le son reste musical même avec un traitement brutal. (Basé sur le DSP présenté dans un article de DAFX’02).

#### ZamAutoSat
Un plugin de saturation automatique, réputé pour offrir un nivellement fluide aux canaux de micro en direct.
Vous pouvez appliquer généreusement ce plugin sans affecter la sonorité..

#### ZamComp
Une puissante tranche de compression mono. Avec les bons réglages, elle donne vraiment du corps à une grosse caisse ou à une caisse claire..

#### ZamCompX2
Version stéréo de ZamComp avec contrôle du slew du knee.

#### ZamEQ2
Égaliseur paramétrique à deux bandes avec circuits de shelving pour les aigus et les graves.

#### ZamGEQ31
égaliseur graphique à 31 bandes, idéal pour l’égalisation des espaces de concert, éliminer les bruits indésirables d’une piste, etc..

#### ZamHeadX2
Plugin de filtrage acoustique HRTF pour le son directionnel.

#### ZamPhono
Une collection de filtres phono pour restaurer des disques vinyles, ou préparer la gravure de nouveaux..

#### ZamGate
Plugin Gate pour atténuer les sons de faible gain.

#### ZamGateX2
Plugin Gate pour le ducking des sons à faible Gain, version stéréo.

#### ZamTube
Effet de distorsion dément. Modèle physique de filtre numérique à ondes d’un étage d’amplificateur à tube triode, avec des réseaux de tonalité modélisés à partir de vrais amplificateurs de guitare (merci à D. Yeh et al.).

#### ZamDelay
Une unité de Delay à rétroaction simple avec une fonction de synchronisation du BPM à l’hôte et un filtre.

#### ZamDynamicEQ
Un égaliseur dynamique qui modifie son Gain en fonction de la détection d’une bande étroite de fréquences. Peut être réglé pour modifier d’autres plages de fréquences en temps réel..

#### ZaMultiComp
Compresseur multibande mono, avec 3 bandes réglables.

#### ZaMultiCompX2
Produit phare de zam-plugins : version stéréo de ZaMultiComp, avec des commandes de seuil individuelles pour chaque bande et une visualisation en temps réel des courbes de compression.
