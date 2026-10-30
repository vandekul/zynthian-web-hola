---
title: ArtyFX
media_order: artyfx.png
description: Une collection de plugins minimaliste mais complète
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
subtitle: Collection minimaliste de plugins
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
ArtyFX est une suite d’effets audio minimalistes, qui peuvent être utilisés de manière autonome, mais qui sont également intégrés à plusieurs projets plus complexes d’OpenAV, comme Fabla2, Sorcer et Luppp. Chaque effet peut être utilisé individuellement comme plugin LV2..

ArtyFX contient de nombreux plugins différents : tous les effets « classiques » comme les Reverb, les Delay et les filtres sont présents. Les sections suivantes détaillent chaque plugin individuellement, en montrant comment l’utiliser et en proposant quelques bonnes pratiques..

#### Bitta
Bitta est un plugin bit-crusher. Le bit crushing réduit la profondeur de bits de l’audio. Comme cela dépend du volume du signal entrant, soyez prudent lorsque vous réglez le bouton « crush ».

**Écrasement :** Modifie le nombre de bits utilisés pour dégrader l’audio..

#### Della
Della est un Delay réglable en BPM, avec des commandes pour le feedback et le volume du Delay..

**Feedback:** contrôle la quantité de signal réinjectée dans la ligne de Delay : augmentez-le pour obtenir cet écho dub-reggae complètement dingue qui n’en finit pas.!

**Volume:** modifie le niveau du signal retardé que vous entendez : utile pour garder les delays en arrière-plan d’une piste.

**Temps:** modifie la longueur du Delay : notez que celle-ci est « quantifiée » en multiples du BPM, elle « saute » donc entre une durée de croche, de noire, de blanche et de ronde. Della récupère le BPM du programme hôte : ainsi, si vous modifiez le tempo, elle restera synchronisée.!

#### Ducka
Ducka est un plugin d’enveloppe sidechain : il est très utile pour créer des lignes de basse « pompage », comme on en trouve souvent dans la minimal house. Le plugin fonctionne en analysant le volume d’une entrée sidechain et en modifiant le volume d’une piste stéréo distincte, en fonction de l’amplitude de l’entrée sidechain..

**Threshold:** définit le niveau que le signal audio d’entrée doit atteindre avant que la piste stéréo ne soit réduite.

**Déposer:** contrôle la quantité de réduction du volume effectuée.

**Temps:** contrôle la durée avant que la piste stéréo ne soit à nouveau réintroduite en fondu. Notez que ce contrôle dépend du BPM, et que le centre se trouve directement sur les contretemps. Un réglage à la moitié (sa valeur par défaut) est généralement musical :)

#### Driva
Driva est une unité de distorsion multiple capable de produire les distorsions les plus agressives et rugueuses..

**Tonalité:** Cliquez sur le bouton Tone, une liste de différents modèles de distorsion est disponible. Cliquez simplement sur la distorsion souhaitée et continuez à jouer. Annuler, en bas, permet de quitter la vue de changement de son..

**Quantité:** augmente simplement la quantité de gain / distorsion. À utiliser à vos risques et périls.!

#### Filta
Filta est une combinaison de filtres passe-bas et passe-haut. Utile pour supprimer les fréquences aiguës et graves indésirables de divers enregistrements ou instruments.A

**Frequency:** contrôle le type de filtrage effectué et la fréquence. Les valeurs basses correspondent à un filtre passe-bas ; augmenter le bouton provoque un filtre passe-haut..

#### Kuiza
Kuiza est un égaliseur 4 bandes. Il est parfait pour façonner de manière créative le son d’un instrument ou d’un synthé. Chacune des commandes de gain modifie l’amplitude à la fréquence indiquée. Le gain général peut être utilisé pour réduire ou amplifier le volume global si nécessaire. Les commandes (de gauche à droite):

* Graves ( ~55 Hz)
* Bas médium ( ~220 Hz)
* Médium aigu ( ~1760 Hz)
* Élevé ( ~7040 Hz)
* Gain principal

#### Masha
Masha est un plugin beat grinder : il enregistre un segment audio et le lit en boucle, créant un effet de « stutter ».

**Volume:** modifie le volume de la boucle de stutter. PassThru permet de laisser passer le signal normal..

**Temps:** est une commande dépendante du BPM qui modifie la durée d’enregistrement et de lecture en boucle. Réduisez progressivement cette valeur pour obtenir cet effet de bégaiement DJ « standard » ! Cet effet possède une fonctionnalité spéciale qui permet de contrôler manuellement le BPM. En général, le BPM est fourni par le programme hôte (ou le transport JACK), mais il peut désormais être contrôlé à l’aide d’une molette..

**Bouton HostBPM:** contrôle la source du BPM. Lorsque le bouton est bleu, HostBPM est activé. Désactiver le bouton fait apparaître le cadran BPM manuel. Le cadran affiche également le BPM actuel..

#### Panda
Panda est une combinaison compresseur-expanseur, avec des réglages d’attack et de release..

**Seuil:** le « point de bascule » de la compression / expansion. Baisser le potentiomètre amplifie le signal, le monter entraîne une compression.

**Publication:** modifie la durée du fondu de sortie de la compression/expansion de Panda.

**Facteur:** contrôle la quantité de compression/d'expansion effectuée, le cadran “maximizer”.

#### Spacieux
Roomy est un reverb spacieux et doux.

**Le contrôle Time** modifie la longueur de la queue de reverb : des valeurs plus élevées créeront un mixage plus ample et plus spacieux.

**Damping** contrôle l’atténuation des hautes- fréquences : des réglages plus bas donnent un son spacieux et ouvert, tandis qu’un amortissement élevé donne une impression de son petit et proche.

**La commande Dry/Wet** modifie la quantité de signal de Reverb mélangée : utile pour les « montées de Reverb » en techno et en trance... il suffit de la pousser à fond!

#### Satma
Satma est un plugin de distorsion déjanté. Utile pour donner du caractère et obtenir un son granuleux et sale..

**Distortion** modifie la quantité de mise en forme du signal qui se produit : la quantité globale de production de bruit.

**Le réglage de tonalité** varie subtilement entre les hautes fréquences et les fréquences plus basses, ou en rendant les deux tout aussi granuleuses.

#### Vihda
Vihda est un élargisseur stéréo, utilisant une matrice mid-side.

**Le paramètre Width** affecte la quantité de contenu stéréo dans le signal. Notez que la technique mid-side ne fait qu’améliorer la stéréo : elle ne la crée pas.!

**Le bouton Inverser** inverse le canal droit, ce qui peut donner un mixage perçu comme plus large en raison de la façon dont le cerveau interprète l'audio. Essayez-le et voyez si le son est bon.

