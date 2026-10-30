---
title: Ratatouille - Dual Neural Modeler
media_order: ratatouille.jpg
description: Modélisateur à double réseau neuronal. Combinez 2 modèles neuronaux +
  IRs
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-pr
  - effect
  - ucase-fx
  - fx-distortion
date: 17:38 24-04-2020
subtitle: Mélangez 2 modèles neuronaux et 2 IRs
splash:
  bg_image: ratatouille-hero.jpg
  bg_image_landscape: ratatouille-hero.jpg
media_thumb: ratatouille.jpg
urls:
- urlLink: https://github.com/brummer10/Ratatouille.lv2
  urlLabel: Source Code
- urlLink: https://tone3000.com
  urlLabel: Ratatouille's Models in Tone3000
---
Ratatouille est un chargeur et mélangeur de modèles neuronaux pour Linux/Windows.
Il peut charger deux modèles, qui peuvent être des fichiers *.nam (Neural Amp Modeler) ou *.json / .aidax (RTNeural), et utiliser
la commande "Blend" pour effectuer un fondu entre les deux modèles et les mélanger afin de simuler le son précis que vous recherchez.
Bien sûr, vous pouvez également charger un seul fichier de modèle et le contrôle « Blend » ne fera rien..

Ratatouille utilise le traitement parallèle pour les modèles neuronaux. Ainsi, le chargement d’un deuxième modèle neuronal ne serait pas
remarquable sur la charge DSP. Ratatouille pourrait éventuellement exécuter le processus complet en mode tamponné.
Cela réduit encore davantage la charge dsp. La latence résultante sera communiquée à l'hôte afin qu'il puisse être
compensée. À titre d'information, la latency résultante sera affichée dans le GUI.

La commande "Delay" pourrait ajouter un léger délai pour éviter les problèmes de phase, ou ajouter de la couleur/de la Reverb au son.
La touche 'ctrl' active le réglage fin pour ajuster un délai à l'échantillon près. Ratatouille peut également détecter la phase
décaler et le compenser en interne.

Pour enrichir votre son, vous pouvez charger deux fichiers Impulse Response et les mixer selon vos besoins. Les fichiers IR pourraient être
normalisés au chargement, afin qu'ils n'influencent pas le volume sonore.

Ratatouille.lv2 prend en charge le rééchantillonnage lorsque nécessaire pour correspondre à la fréquence d’échantillonnage attendue des modèles chargés. Les deux
les modèles et les fichiers IR peuvent avoir des attentes différentes concernant la fréquence d’échantillonnage.
#### Obtenez des modèles auprès d'une grande communauté

[Tone3000.com](https://tone3000.com) est devenu l’endroit où trouver les meilleurs modèles pour Neural Amp Modeler, Aida-X et Proteus, tout en s’étendant pour prendre en charge davantage de plateformes à l’avenir. Notre collection d’IRs ne cesse de s’étoffer et gagne également en popularité au sein de la plateforme..

#### Chargement des fichiers

Depuis zynthian-ui, vous pouvez facilement charger des fichiers de modèle. Il suffit de tourner le knob assigné au contrôle du modèle et le sélecteur de fichiers s’ouvrira..

