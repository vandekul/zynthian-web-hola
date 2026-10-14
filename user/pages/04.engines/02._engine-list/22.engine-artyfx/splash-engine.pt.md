---
title: ArtyFX
media_order: artyfx.png
description: Uma coleção minimalista, porém completa, de plugins
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
subtitle: Coleção Minimalista de Plugins
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
ArtyFX é um conjunto de efeitos de áudio minimalistas, que podem ser usados de forma independente, mas também estão integrados em muitos dos projetos mais complexos da OpenAV, como Fabla2, Sorcer e Luppp. Cada efeito pode ser usado individualmente como um plugin LV2.

ArtyFX contém muitos plugins diferentes - todos os efeitos “clássicos”, como reverbs, delays e filtros, estão presentes. As seções a seguir detalham cada plugin individualmente, mostrando como ele pode ser usado e dando algumas sugestões de boas práticas..

#### Bitta
Bitta é um plugin bit-crusher. O bit-crushing reduz o bit-depth do áudio. Como depende do volume do sinal de entrada, tenha cuidado ao ajustar o controle “crush”.

**Esmagar :** Altera o número de bits usados para acelerar o áudio..

#### Della
Della é um delay com ajuste de BPM, com controles de feedback e volume do delay.

**Feedback:** controla a quantidade do sinal realimentado na linha de delay: aumente para obter aquele eco maluco de dub reggae que não acaba nunca!

**Volume:** altera a quantidade do sinal com Delay que você ouve: útil para manter os delays em segundo plano em uma faixa.

**Tempo:** altera a duração do Delay: note que ela é “quantizada” em múltiplos do BPM, então “salta” entre durações de uma semínima, uma mínima, uma semibreve e uma breve. Della obtém o BPM do programa host: então, se você alterar o tempo, ela continuará sincronizada!

#### Ducka
Ducka é um plugin de envelope sidechain: é muito útil para criar linhas de baixo com “pumping”, como as frequentemente encontradas na música minimal house. O plugin funciona analisando o volume de uma entrada sidechain e alterando o volume de uma faixa estéreo separada, com base na amplitude da entrada sidechain..

**Threshold:** define o nível que o áudio de entrada deve atingir antes que a faixa estéreo seja reduzida.

**Soltar:** controla a quantidade de redução de volume realizada.

**Tempo:** controla o tempo que leva antes de a faixa estéreo voltar a entrar em fade. Note que este controle depende do BPM, e o centro fica diretamente nos off- beats. Uma configuração de metade (o padrão) geralmente é musical :)

#### Driva
A Driva é uma unidade de múltiplas distorções capaz de produzir as distorções mais agressivas e ásperas..

**Tom:** Clique no botão Tone; uma lista de diferentes modelos de distorção estará disponível. Basta clicar na distorção desejada e continue tocando. Cancelar, na parte inferior, fecha a visualização de alteração de timbre..

**Quantidade:** apenas aumenta a quantidade de gain / distorção. Use por sua conta e risco.!

#### Filta
Filta é uma combinação de filtro lowpass e highpass. Útil para remover frequências altas e baixas indesejadas de várias gravações ou instrumentos.A

**Frequência:** controla que tipo de filtragem é feita e em que frequência. Valores mais baixos correspondem ao filtro lowpass; aumentar o botão causa highpass.

#### Kuiza
Kuiza é um equalizador de 4 bandas. É perfeito para moldar criativamente o som de um instrumento ou sintetizador. Cada um dos controles de Gain altera a amplitude na frequência indicada. O Gain master pode ser usado para reduzir ou amplificar o volume geral, se necessário. Os controles (da esquerda para a direita):

* Baixo ( ~55 Hz)
* Médios-graves ( ~220 Hz)
* Médios-agudos ( ~1760 Hz)
* Alto ( ~7040 Hz)
* Gain mestre

#### Masha
Masha é um plugin beat grinder: ele grava um segmento de áudio e o reproduz em loop, causando um efeito de “stutter”.

**Volume:** altera o volume do stutter-loop. PassThru permite a passagem do sinal normal..

**Tempo:** é um controle dependente de BPM que altera a duração da gravação em loop e da reprodução. Reduza gradualmente esse valor para obter aquele efeito de stutter “padrão” de DJ! Esse efeito tem algumas funcionalidades especiais que permitem o controle manual do BPM. Geralmente, o BPM é obtido do programa host (ou do transporte JACK), mas agora pode ser controlado por um dial.

**Botão HostBPM:** controla a fonte de BPM. Quando o botão está azul, o HostBPM está ativado. Ao desativar o botão, o seletor manual de BPM aparece. O seletor também mostra o BPM atual.

#### Panda
Panda é uma combinação de compressor e expander, com controles de attack e release.

**Threshold:** o “ponto de virada” da compressão / expansão. Diminuir o botão expande o sinal, aumentá-lo causa compressão.

**Lançamento:** altera o tempo para o Panda reduzir gradualmente sua compressão/expansão.

**Fator:** controla a quantidade de compressão/expansão realizada, o botão “maximizer” dial.

#### Espaçoso
Roomy é um reverb amplo e suave..

**O controle de tempo** altera a duração da cauda de Reverb: valores mais altos criarão uma mixagem maior e mais espaçosa.

**Damping** controla o amortecimento de altas frequências: configurações mais baixas proporcionam um som espaçoso e aberto, enquanto um amortecimento alto soa pequeno e próximo.

**controle Dry/Wet** altera a quantidade de sinal de reverb misturado: útil para “crescimentos de reverb” de techno e trance... basta aumentar bastante!

#### Satma
Satma é um plugin de distorção maluco. Útil para dar mais energia e obter um áudio áspero e sujo.

**Distortion** altera a quantidade de modelagem do sinal que ocorre: a quantidade geral de produção de ruído.

**O controle de tonalidade** varia sutilmente entre frequências agudas e frequências mais baixas, ou tornando ambas igualmente ásperas.

#### Vihda
Vihda é um aprimorador estéreo, usando uma matriz mid-side.

**O parâmetro Width** afeta a quantidade de conteúdo estéreo no sinal. Note que a técnica mid-side apenas aprimora o estéreo: ela não o cria!

**O botão Invert** inverte o canal direito, o que pode criar a percepção de uma mixagem mais ampla devido à forma como o cérebro interpreta o áudio. Experimente e veja se soa bem.

