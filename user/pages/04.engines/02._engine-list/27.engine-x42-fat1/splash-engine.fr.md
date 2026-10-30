---
title: X42 Autotune
media_order: x42-fat1.png
description: Auto-tuner plugin
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - fx-other
  - ucase-fx
date: 17:38 24-04-2020
subtitle: Accordeur automatique basé sur zita-at1 de Fons Adriaensens
splash:
  bg_image_landscape: x42-fat1-hero_small.png
  bg_image: x42-fat1-hero_small.png
media_thumb: x42-fat1.png
urls:
- urlLink: http://x42-plugins.com/x42/x42-autotune
  urlLabel: X42 Autotune's Website
- urlLink: https://github.com/x42/fat1.lv2
  urlLabel: Source Code
---
x42-autotune (également connu sous le nom de fat1.lv2) est un accordeur automatique basé sur zita-at1 de Fons Adriaensen.

AT1 est conçu pour corriger la hauteur d’une voix qui chante légèrement faux. Il fonctionne en rééchantillonnant et en bouclant le signal, et n’inclut pas de correction des formants : il ne doit donc être utilisé que pour corriger de petites erreurs, et non pour transposer réellement un morceau. AT1 peut probablement aussi être utilisé sur certains instruments, mais il est principalement conçu pour couvrir la tessiture vocale..

La hauteur « attendue » peut être contrôlée par MIDI ou correspondre à un ensemble fixe de notes.

Les principales différences avec zita-at1 sont que la version du plugin LV2 indique sa latency à l’hôte, enregistre l’état avec la session et que l’entrée MIDI a une sémantique de sidechain.. 

#### Modes de fonctionnement
AT1 réaccorde le signal d'entrée sur la note la plus proche de la gamme configurée. La gamme comprend jusqu'à 12 notes (1 octave), définies et indiquées sur le clavier à gauche. Par défaut, les 12 sont activées.

Un clic gauche permet d’activer/de désactiver des notes individuelles, et un clic droit sur le clavier ouvre une boîte de dialogue permettant de sélectionner des gammes majeures/mineures courantes. Le clavier indique également la note actuelle sélectionnée par l’estimateur de hauteur..

Les modes de fonctionnement suivants sont pris en charge.:

**Manuel:** Utilisez un ensemble fixe de notes (ignorez MIDI). Cliquez avec le bouton gauche pour basculer les notes..

**MIDI:** Répond aux messages MIDI note on/off. Utilise la ou les notes MIDI actuellement actives. Si aucune, utilise n’importe quelle note de la gamme chromatique..

**Automatique (par défaut):** Si aucune note MIDI n'est activée, utilisez l'ensemble fixe de notes (clic gauche pour basculer). Les notes MIDI sont prioritaires..

#### Paramètres

**Sélection du canal MIDI:** Sélectionnez le canal MIDI auquel répondre. Il peut s’agir de « Omni » ou d’un nombre de 1 à 16..

**MIDI Panic:** Réinitialiser toutes les notes MIDI « bloquées ».

**Accordage:** Cela définit la fréquence correspondant à la hauteur de « A », autrement dit l’accordage requis. Elle sera de 440 Hz par défaut dans la plupart des cas. La valeur exacte s’affiche chaque fois que cette commande est touchée, et peut être réglée par incréments de 0,2 Hz..

**Bias:** Normalement, l’estimateur de hauteur sélectionne la note activée la plus proche de la hauteur mesurée. Le contrôle Bias donne une préférence supplémentaire à la note actuelle - cela lui permet d’être plus désaccordée que ce ne serait le cas autrement..

**Filtre:** Cela définit le degré de lissage de la correction de hauteur tant que la note actuelle ne change pas. Si elle change, le filtre est contourné et la correction passe immédiatement à la nouvelle valeur..

**Correction:** Détermine la proportion de l’erreur de hauteur estimée qui est corrigée. Une correction complète peut supprimer l’expression ou le vibrato..

**Décalage:** Ajoute un décalage compris entre +/- deux demi-tons à la correction de hauteur. Lorsque la commande Correction est réglée sur zéro, le résultat est une variation constante de la hauteur..

**Indicateur d’erreur de Pitch:** La barre sous le clavier indique l’écart de hauteur du signal d’entrée par rapport à la note actuelle. La plage est de +/- un demi-ton..
