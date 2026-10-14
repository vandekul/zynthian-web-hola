---
title: Conceito
smallTitle: Irúfẹ́ ohun èlò orin tuntun kan!
onpage_menu: true
menu: Conceito
visible: false
lead: Zynthian é um dispositivo compacto e autônomo de criação musical que pode ser
  usado como expansor de teclado, unidade de efeitos de áudio, processador e roteador
  MIDI, groovebox e micro-DAW.
subtitle: ''
buttonText1: Saiba mais na nossa Wiki
buttonLink1: https://wiki.zynthian.org
buttonText2: Leia o Guia do Usuário
buttonLink2: https://help.zynthian.org/
---
Zynthian é um [projeto impulsionado pela comunidade](https://discourse.zynthian.org)—100% open-source, com software livre a funcionar em hardware aberto. É completamente configurável e totalmente hackable! **Livre no sentido de Liberdade**. Pode construir o seu Zynthian do zero ou [compre um kit oficial](https://shop.zynthian.org).

### Mais de 100 instrumentos virtuais
Zynthian inclui uma coleção completa de instrumentos virtuais e emuladores:
+ **Teclas Acústicas e Elétricas** como pianos de cauda, Rhodes, Wurlitzer, Clavinet, e Farfisa.
+ **Órgãos** como Hammonds tonewheel, órgãos combo de transístores e órgãos de tubos.
+ **Synths Icônicos** como o DX7, Oberheim, Juno-60, e TB-303.
+ **Sintetizadores Analógicos Virtuais** como ZynAddSubFX, Surge-XT, Vaporizer2, NoizeMaker, Odin2, MiMi-d, Monique, Helm, e Amsynth.
+ **Emuladores de Hardware Real** como os desenvolvidos por [Os Suspeitos do Costume](https://theusualsuspects.io/), incluindo Osirus, OsTIrus, Vavra, Xenia, VirtualJV, e JE-8086. (<i>Nota: É necessário obter uma cópia legal do ficheiro ROM do firmware do dispositivo para o funcionamento</i>).

<a class="minilink" href="/engines#synthesizers">mais detalhes sobre instrumentos virtuais &nbsp;&nbsp;&gt;</a>

### Instrumentos Sample-based
Reproduza enormes bancos de sons multisampled com suporte nativo para **SF2**, **SF3**, **SFZ**, **DecentSampler (DS)**, e **GIG** formatos. O Zynthian vem com uma extensa coleção integrada de instrumentos amostrados, que pode expandir facilmente com pacotes de extensão e as suas próprias bibliotecas personalizadas.

Para os formatos mais potentes (**SFZ**, **DS**, e **GIG**), o tamanho do instrumento não é limitado pela memória. Os motores Sfizz e LinuxSampler implementam algoritmos avançados de play-from-disk que permitem carregar instrumentos arbitrariamente grandes.

<a class="minilink" href="https://github.com/zynthian/zynthian-packages/tree/main/Soundfonts">mais detalhes sobre instrumentos sampleados &nbsp;&nbsp;&gt;</a>

### Mais de 1,000 efeitos de áudio & ferramentas MIDI
+ **Efeitos de áudio clássicos** incluindo recursos essenciais como reverb, delay, chorus, distortion, saturation, EQ, compression, flanger, phaser, e wah-wah.
+ **Efeitos de áudio modernos** incluindo simuladores de fita, granulators, vocoders, pitch-shifters, e auto-tune.
+ **Modelagem de rede neural** para uma emulação precisa de equipamentos não lineares como a maioria dos amplificadores e stompboxes. Instale os seus timbres favoritos a partir de [Tone3000](https://tone3000.com) com apenas alguns cliques.
+ **Modelagem de Impulse response** para reverb e emulação de cabinet.
+ **Ferramentas MIDI** como curvas de velocity, chorders, arpeggiators, conversores monofônicos, utilitários de strumming, e analisadores de harmonia.

<a class="minilink" href="/engines#effects">mais detalhes sobre FXs de áudio & ferramentas MIDI &nbsp;&nbsp;&gt;</a>

### Pacotes de extensão gratuitos
O Zynthian pode ser facilmente expandido com pacotes, instaláveis com apenas um clique. Os pacotes podem conter instrumentos sampleados, coleções de samples, loops, patterns e IRs. Os utilizadores podem criar os seus próprios pacotes e partilhá-los com a comunidade.

<a class="minilink" href="https://zynthian.github.io/zynthian-packages/">mais detalhes sobre pacotes de extensão &nbsp;&nbsp;&gt;</a>

### Ferramentas de Produção
+ **[Zynseq](/use-case/groovebox-udaw)** é um step sequencer completo com captura ao vivo, quantization, operações em blocos e swing. Inclui humanização de velocity e tempo, frequência e probabilidade de reprodução dos passos, efeitos avançados de stutter e automação de parâmetros.
+ **[Clippy](/use-case/groovebox-udaw)** é um motor de audio-clip que permite reproduzir samples de áudio sincronizados com a batida com auto-warping e beat-slicing em tempo real.
+ **[Lançador](/use-case/groovebox-udaw)** é uma grelha de controlo para atuações que permite acionar padrões, clips de áudio ou frases musicais organizados em linhas sequenciais. Programe alterações precisas de compasso e andamento, loops de frases e reprodução condicional de frases para alcançar *Da Capo* e *CODA* comportamento.
+ **[Zynmixer](/use-case/groovebox-udaw)** é um mixer potente e flexível que permanece intuitivo, oferecendo recursos profissionais de canal: comutação mono/stereo, inversão de fase, alternância M+S, mixbuses personalizáveis, níveis de send independentes, AB-mixing, e escuta pre-fader (PFL).
+ **[SooperLooper](https://sonosaurus.com/sooperlooper/features.html)** por Jesse Chappell é um looper de áudio multicanal ao vivo inspirado no lendário **Gibson Echoplex Digital Pro (EDP)** hardware. Oferece gravação imediata de loop, overdubbing em múltiplas camadas, multiplicação de loop, inversão em tempo real, e decaimento variável de feedback.
+ **[Integração nativa com controladores MIDI populares](https://wiki.zynthian.org/index.php/Supported_plug_%26_play_MIDI_controllers)** oferece suporte plug-and-play para padrões da indústria como o Akai APC40, APC Key 25, e MIDI Mix, Novation Launchpads e Launchkeys, o Korg nanoKONTROL, e superfícies Mackie Control Universal (MCU) completas.
+ **Gravador de áudio multipista** permite capturar cadeias individuais de instrumentos e efeitos de forma independente numa sessão WAV multitrack de qualidade impecável.
+ **Gravador/reprodutor de arquivos MIDI** permite gravar, armazenar, e reproduzir facilmente arquivos MIDI padrão (.MID) em tempo real.
+ **[Pure Data](http://www.pd-tutorial.com/english/index.html)** integra uma poderosa linguagem de programação visual para sound design personalizado de áudio e MIDI.

<a class="minilink" href="/use-case/groovebox-udaw">mais detalhes sobre ferramentas de produção &nbsp;&nbsp;&gt;</a>
