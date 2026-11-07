# DuoSynth

Sintetizador de acordes para iPhone, inspirado no HiChord (Pocket Audio) e seguindo o manual oficial Rev 3.0. Roda no navegador, em um único arquivo HTML, sem dependências nem build.

Funciona em pé e deitado. Em pé, a tela fica no topo, os controles logo abaixo e a área de tocar (joystick + 7 teclas) num painel separado embaixo.

## Como usar no iPhone

1. Publique a pasta com GitHub Pages (Settings → Pages → branch `main`, pasta `/`) ou sirva `index.html` em qualquer servidor estático.
2. Abra o link no Safari e toque em **Ligar o HiChord**.
3. Para tela cheia: Compartilhar → **Adicionar à Tela de Início**.
4. Sem som? Desligue o modo silencioso ou use fone.

## O que tem

- **Acordes:** 7 teclas com os acordes do tom, 12 tons e 10 escalas, inversões, oitava por tecla, baixo invertido (segure duas teclas) e Chord Lock.
- **Joystick:** 8 direções nos modos DEFAULT, EXTEND, CHROMATIC, BORROW e OG. A tela mostra o acorde de cada direção antes de você mexer.
- **Modos:** Play, Strum, Lead, Drone, Arp, Repeat, Drums (6 kits, rolo automático), Beat (7 estilos × 8 variações), Seq (até 16 passos) e Mixer (teclas 1–6 silenciam faixas, 7 liga o metrônomo). Arp com padrão Fingerpick.
- **Looper:** 6 faixas de até ~20 s, modo livre ou de 1 a 8 compassos com contagem, sincronia entre faixas, pausa com efeito de fita e gravação de Beat/Seq direto numa faixa.
- **Aprender:** as teclas mostram o nome do acorde (ou da nota, do tambor, do estilo e da faixa, conforme o modo); 5 progressões guiadas em que a próxima tecla acende; Guia (?) com a tabela do joystick para a tecla atual e o exercício "música do zero" em 7 passos que já preparam som e modo de cada faixa.
- **Presets:** 4 espaços (P1–P4) em Som, com tom, escala, BPM, timbre, efeitos, modo e sequência.
- **Som:** 29 timbres por síntese (analógico, FM, ruído, formantes), 9 efeitos (reverb, delay, chorus, flanger, drive, tape, tremolo, LFO, filtro) e ajustes de voz, ADSR, bass, glide, V.Lead e estéreo.

## Controles

| Onde | O que faz |
|---|---|
| ? (na tela) | Guia: progressões, joystick, exercício passo a passo |
| Tom · BPM · Som | Abrem os ajustes; TAP marca o tempo. Progressão guiada em Tom, presets em Som |
| Modos | Toque para trocar; toque de novo no ativo para ver as opções |
| Inversão · Oitava · Cadeado | Valem para a última tecla tocada |
| STD … OG | Modo do joystick |
| Faixas ● ■ ▲ | Toque para escolher, segure para apagar |
| Gravar · Play/Pausa · Lixeira | Transporte do looper (segure a lixeira para apagar tudo) |
| Clique no joystick | Seq: tocar/parar · Beat: gravar no looper · Mixer: mute |

## Arquivos

- `index.html`: o app atual (interface light, controles expostos).
- `legacy/hichord-device-v1.html`: a primeira versão, que imitava o visual do aparelho físico.

## Fora desta versão

Chord Hiro, Ear Trainer, Tuner, microfone (Sampler/Vocoder), Companion App e MIDI. Os timbres gravados do aparelho são aproximados por síntese, e os loops não ficam salvos ao fechar o app.

Projeto independente, sem vínculo com a Pocket Audio.
