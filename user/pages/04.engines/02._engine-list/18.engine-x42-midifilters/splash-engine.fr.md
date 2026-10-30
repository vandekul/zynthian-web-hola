---
title: x42 MIDI-filters
media_order: x42-midifilter.jpg
description: Une puissante collection de filtres et d’outils MIDI simples
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - ucase-pr
  - effect
  - fx-midi
date: 17:38 24-04-2020
subtitle: Une puissante collection de filtres et d’outils MIDI simples
splash:
  bg_image_landscape: x42-midifilter-hero.jpg
  bg_image: x42-midifilter-hero_small.jpg
media_thumb: x42-midifilter.jpg
urls:
- urlLink: http://x42-plugins.com/x42/x42-midifilter
  urlLabel: x42 MIDI-filter's Website
- urlLink: https://github.com/x42/x42-plugins
  urlLabel: Source Code
---
Une collection de plus de 25 filtres de données MIDI au format de plugin LV2, développés et maintenus par [Robin Gareus](http://x42-plugins.com). Les filtres suivent ces règles de base:
+ Une entrée MIDI, une sortie MIDI (pas de générateurs, pas de synthés)
+ Aucune interface graphique personnalisée, entrées de contrôle uniquement
+ Chaque commande peut être automatisée, les plugins gèrent les changements dynamiques de paramètres
+ Tous les plugins indiquent leur Latency à l’hôte (pour la plupart, elle est nulle)
+ DRY (principe Don't Repeat Yourself) - des filtres simples qui peuvent être combinés dans un réseau
+ Auto-documenté : description intégrée et documentation des ports de contrôle

##Vue d’ensemble
**CC2Note:** Convertir les messages de changement de contrôle MIDI en messages note-on/off. Note off est mis en file d’attente 10 msec plus tard..

**Filtre de canal MIDI:** Filtre simple de canal MIDI. Seules les données des canaux sélectionnés peuvent passer. Ce filtre affecte uniquement les données MIDI liées aux canaux (c.-à-d. note-on/off, changements de contrôle et de programme, pression par touche et pression de canal, et Pitchbend). Les messages MIDI-SYSEX et Realtime sont toujours transmis. Ce plugin est destiné à une utilisation en direct, avec contrôle par boutons. Voir également le filtre 'MIDI Channel Map.

**Carte des canaux MIDI:** Réécrit le numéro de canal MIDI. Ce filtre n’affecte que les données MIDI pertinentes pour le canal (c.-à-d. note-on/off, control and program changes, key and channel pressure et pitchbend). Les messages MIDI-SYSEX et Realtime sont toujours transmis sans modification..

**MIDI impose la gamme:** Filtre les événements note-on/note-off en fonction de la gamme musicale. Si la tonalité est modifiée, des événements note-off sont envoyés pour toutes les notes actives hors tonalité..

**Filtre d’événements MIDI:** Filtre de messages de type notch. Supprime des messages spécifiques. Pour une plage note-on/off flexible, voir aussi 'keyrange' et 'velocityrange'.

**Filtre de plage de notes MIDI:** Ce filtre permet de définir une plage de notes midi autorisées. Les événements note-on/off en dehors de la plage autorisée sont ignorés. Si la plage change, des événements note-off sont envoyés aux notes actuellement actives qui se retrouvent en dehors de la plage valide.

**MIDI Keysplit:** Changez le numéro de canal midi en fonction de la note. Le plugin garde une trace des notes midi transposées et envoie les événements note-off correspondants si la plage est modifiée, même si une note est active. Cependant, le point de séparation et les affectations de canal pour chaque clavier ne doivent être modifiés que lorsqu’aucune note n’est jouée actuellement..

**MapCC:** Transformer un message de contrôle en un autre -- combiner avec scalecc pour modifier/mettre à l’échelle la valeur réelle.

**Transposition des touches MIDI:** Mappage flexible sur 12 notes. Permet de mapper une note dans une octave vers une autre note dans la même plage d’octave +- 12 demi-tons. Il est également possible de masquer (désactiver) des notes. Si deux touches sont mappées sur la même note, les événements note-on/off correspondants sont verrouillés : seul le premier note-on et le dernier note-off seront envoyés. Les réglages peuvent être modifiés dynamiquement : les événements Note-on/off seront envoyés en conséquence..

**MIDI Accord:** Harmoniseur - crée des accords à partir d’une seule note (fondamentale) dans une gamme donnée. La gamme ainsi que les intervalles peuvent être automatisés librement (les accords actuellement maintenus changeront). Les note-ons sont verrouillés ; pour les accords multiples/combinés, un seul note-on/off sera déclenché pendant toute la durée des accords combinés. Si une note hors gamme est jouée, elle sera transmise telle quelle - aucun accord n’est attribué. Remarque : combinez cet effet avec le 'MIDI
Appliquer le filtre Enforce Scale' pour les éliminer.

**MIDI Delayline:** Ligne de delay MIDI. Delay tous les événements MIDI d'un temps donné, défini en BPM et en beats. Si le delay inclut un facteur aléatoire, cet effet veille à toujours conserver l'ordre des événements note on/off, quelle que soit la randomisation..

**Canal MIDI Unisono:** Dupliquer les événements MIDI d’un canal vers un autre.

**Battement MIDI:** Un effet d’arpège midi destiné à simuler le grattement d’un instrument à cordes (par exemple, une guitare). Un accord est « collecté » et les notes qui le composent sont jouées successivement au fil du temps. Le « Note Collect Timeout » permet de jouer l’effet en direct avec un clavier midi ; il compense le fait qu’un humain n’appuie pas sur les touches exactement au même moment. Si l’effet est utilisé avec un séquenceur capable d’envoyer des accords dont toutes les notes sont déclenchées exactement au même moment, il doit être réglé sur zéro..

**MIDI Transposition chromatique:** Transposition chromatique des notes MIDI et du key-pressure. Si un point d’inversion est défini, la gamme est inversée autour de ce point avant la transposition. Les notes qui se retrouvent en dehors de la plage valide 0..127 sont supprimées..
MIDI Monophonique Legato	Maintenez une note jusqu’à l’arrivée de la suivante. -- Rejouez la même note pour l’éteindre..

**Supprimer Active Sensing MIDI:** Filtre pour bloquer tous les événements Active Sensing. Les messages Active Sensing sont des messages MIDI facultatifs, conçus pour être envoyés de manière répétée afin d’indiquer à un récepteur qu’une connexion est active. Cependant, ils peuvent encombrer le canal MIDI ou être enregistrés par inadvertance lors de l’enregistrement de données MIDI brutes sur disque..

**Bloqueur de doublons MIDI:** Bloqueur de doublons MIDI. Filtre les messages note on/off qui se chevauchent et les messages en double..

**Note2CC:** Convertir les messages note-on MIDI en messages de changement de contrôle.

**Bascule de note MIDI:** Activer/désactiver les notes : jouez une note pour l’activer, rejouez-la pour la désactiver..

**MIDI N-Tap Delay:** Cet effet répète les notes N fois. N est soit un nombre fixe, soit illimité tant qu'une touche donnée est maintenue enfoncée. Les variables BPM et delay-time permettent des rampes de tempo. À chaque répétition, l'ajustement de Velocity indiqué est ajouté ou soustrait, le résultat étant limité entre 1 et 127..

**MIDI Thru:** MIDI All pass. Ce plugin n’a aucun effet et est destiné à servir d’exemple.

**Quantification MIDI:** Quantification des événements en direct. Ce filtre aligne les événements MIDI entrants sur une grille temporelle fixe. Comme l'effet fonctionne sur un flux en direct, il introduira une latence : Les événements seront retardés jusqu'au prochain 'tick'. Si l'hôte de plugin fournit des informations BBT, les événements sont alignés sur l'horloge de l'hôte, sinon l'effet fonctionne selon son propre temps.

**MIDI Velocity Randomisation:** Randomiser la Velocity des notes MIDI (à la fois note on et note off).

**Mettre à l’échelle la valeur CC:** Modifier la valeur (octet de données) d'un message MIDI Control Change.

**MIDI Sostenuto:** Ce filtre retarde les messages note-off pendant une durée donnée, simulant une pédale de sostenuto de piano. Lorsque la pédale est relâchée, les messages note-off en attente sont envoyés immédiatement. Le délai peut être modifié dynamiquement ; les modifications affectent les messages note-off encore en attente..

**Filtre de plage de Velocity MIDI:** Filtrer les événements MIDI note-on en fonction de la vélocité. Les événements note-on hors de la plage autorisée sont ignorés. Si un événement Note-off est reçu pour une note précédemment filtrée, il n’est pas non plus transmis. Si la plage autorisée change, des événements note-off sont envoyés aux notes actuellement actives qui se retrouvent hors de la plage valide..

**Réglage de MIDI Velocity:** Modifiez la Velocity des événements de note avec des commandes distinctes pour Note-on et Note-off. La plage d’entrée 1 - 127 est mappée sur la plage comprise entre Min et Max. Si Min est supérieur à Max, la plage est inversée. La valeur des offsets est ajoutée à l’événement de Velocity après le mappage de la plage Min/Max..
