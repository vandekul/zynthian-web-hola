---
title: Concept
smallTitle: Irúfẹ́ ohun èlò orin tuntun kan!
onpage_menu: true
menu: Concept
visible: false
lead: Zynthian est un appareil musical compact et autonome, utilisable comme expandeur
  de clavier, unité d’effets audio, processeur et routeur MIDI, groovebox et micro-DAW.
subtitle: ''
buttonText1: En savoir plus sur notre Wiki
buttonLink1: https://wiki.zynthian.org
buttonText2: Lire le guide utilisateur
buttonLink2: https://help.zynthian.org/
---
Zynthian est un [projet porté par la communauté](https://discourse.zynthian.org)—100% open-source, intégrant des logiciels libres fonctionnant sur du matériel libre. Il est entièrement configurable et totalement hackable! **Libre au sens de Liberté**. Vous pouvez construire votre Zynthian de A à Z ou [acheter un kit officiel](https://shop.zynthian.org).

### Plus de 100 instruments virtuels
Zynthian comprend une collection complète d’instruments virtuels et d’émulateurs:
+ **Claviers Acoustiques et Électriques** comme les pianos à queue, Rhodes, Wurlitzer, Clavinet, et Farfisa.
+ **Orgues** comme les Hammond à roues phoniques, les orgues combo à transistors et les orgues à tuyaux.
+ **Synths Emblématiques** comme le DX7, Oberheim, Juno-60, et TB-303.
+ **Synthétiseurs Analogiques Virtuels** comme ZynAddSubFX, Surge-XT, Vaporizer2, NoizeMaker, Odin2, MiMi-d, Monique, Helm, et Amsynth.
+ **Émulateurs de Matériel Réel** comme ceux développés par [Les Suspects Habituels](https://theusualsuspects.io/), y compris Osirus, OsTIrus, Vavra, Xenia, VirtualJV, et JE-8086. (<i>Remarque: L’obtention d’une copie légale du fichier ROM du firmware de l’appareil est nécessaire à son fonctionnement</i>).

<a class="minilink" href="/engines#synthesizers">plus de détails sur les instruments virtuels &nbsp;&nbsp;&gt;</a>

### Instruments basés sur des Samples
Jouez d'imposantes banques de sons multisamplés avec une prise en charge native de **SF2**, **SF3**, **SFZ**, **DecentSampler (DS)**, et **GIG** formats. Zynthian est livré avec une vaste collection intégrée d'instruments échantillonnés, que vous pouvez facilement enrichir avec des packs d'extension et vos propres bibliothèques personnalisées.

Pour les formats plus puissants (**SFZ**, **DS**, et **GIG**), la taille de l’instrument n’est pas limitée par la mémoire. Les moteurs Sfizz et LinuxSampler implémentent des algorithmes avancés de lecture depuis le disque qui vous permettent de charger des instruments de taille arbitrairement grande.

<a class="minilink" href="https://github.com/zynthian/zynthian-packages/tree/main/Soundfonts">plus de détails sur les instruments échantillonnés &nbsp;&nbsp;&gt;</a>

### Plus de 1,000 effets audio & outils MIDI
+ **Effets audio classiques** avec des effets essentiels comme reverb, delay, chorus, distortion, saturation, EQ, compression, flanger, phaser, et wah-wah.
+ **Effets audio modernes** y compris les tape simulators, granulators, vocoders, pitch-shifters, et auto-tune.
+ **Modélisation par réseau neuronal** pour une émulation précise de matériel non linéaire comme la plupart des amplificateurs et des pédales d’effet. Installez vos sonorités préférées depuis [Tone3000](https://tone3000.com) en quelques clics seulement.
+ **Impulse response modeling** pour la reverb et l’émulation de baffle.
+ **Outils MIDI** comme les courbes de velocity, les chorders, les arpeggiators, les convertisseurs monophoniques, les utilitaires de strumming, et les analyseurs d’harmonie.

<a class="minilink" href="/engines#effects">plus de détails sur les FXs audio & outils MIDI &nbsp;&nbsp;&gt;</a>

### Packs d’extension gratuits
Zynthian peut être facilement étendu grâce à des paquets, installables en un seul clic. Les paquets peuvent contenir des instruments échantillonnés, des collections de samples, des loops, des patterns, et des IRs. Les utilisateurs peuvent créer leurs propres paquets et les partager avec la communauté.

<a class="minilink" href="https://zynthian.github.io/zynthian-packages/">plus de détails sur les paquets d’extension &nbsp;&nbsp;&gt;</a>

### Outils de Production
+ **[Zynseq](/use-case/groovebox-udaw)** est un step sequencer complet avec capture en direct, quantization, opérations par blocs et swing. Il inclut l'humanisation de la velocity et du timing, la fréquence et la probabilité de lecture des pas, des effets de stutter avancés et l'automation des paramètres.
+ **[Clippy](/use-case/groovebox-udaw)** est un moteur de clips audio qui vous permet de lire des samples audio synchronisés sur le tempo avec auto-warping et beat-slicing en temps réel.
+ **[Lanceur](/use-case/groovebox-udaw)** est une grille de contrôle pour la performance qui vous permet de déclencher des patterns, des clips audio ou des phrases musicales disposés en rangées séquentielles. Programmez des changements précis de signature rythmique et de tempo, des boucles de phrases et une lecture conditionnelle des phrases pour obtenir *Da Capo* et *CODA* comportement.
+ **[Zynmixer](/use-case/groovebox-udaw)** est une console de mixage puissante et flexible qui reste intuitive tout en offrant des fonctionnalités de tranche professionnelles : commutation mono/stéréo, inversion de phase, commutateurs M+S, mixbuses personnalisables, niveaux de send indépendants, AB-mixing, et écoute pre-fader (PFL).
+ **[SooperLooper](https://sonosaurus.com/sooperlooper/features.html)** par Jesse Chappell est un looper audio multicanal pour le live inspiré du légendaire **Gibson Echoplex Digital Pro (EDP)** matériel. Il permet l'enregistrement immédiat de loops, l'overdubbing multicouche, la multiplication des loops, l'inversion en temps réel, et une atténuation variable du feedback.
+ **[Intégration native avec les contrôleurs MIDI populaires](https://wiki.zynthian.org/index.php/Supported_plug_%26_play_MIDI_controllers)** offre une prise en charge plug-and-play des standards de l’industrie comme les Akai APC40, APC Key 25, et MIDI Mix, les Novation Launchpads et Launchkeys, le Korg nanoKONTROL, et les surfaces Mackie Control Universal (MCU) complètes.
+ **Enregistreur audio multipiste** vous permet d’enregistrer séparément chaque chaîne d’instruments et d’effets dans une session WAV multipiste d’une qualité irréprochable.
+ **Enregistreur/lecteur de fichiers MIDI** vous permet d’enregistrer, de stocker, et de lire facilement des fichiers MIDI standard (.MID) à la volée.
+ **[Pure Data](http://www.pd-tutorial.com/english/index.html)** intègre un puissant langage de programmation visuelle pour un sound design audio et MIDI personnalisé.

<a class="minilink" href="/use-case/groovebox-udaw">plus de détails sur les outils de production &nbsp;&nbsp;&gt;</a>
