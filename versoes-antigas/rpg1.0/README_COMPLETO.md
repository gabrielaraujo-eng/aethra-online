# RPG — versão `rpg1.0`

Documentação técnica gerada em 07/11/2026. Esta análise usa os arquivos principais da pasta `rpg1.0` e ignora backups com prefixo `[backup antes da coleta]`.

## O que foi encontrado

- `game.js` — 14,637 caracteres, 229 linhas, SHA-256 `f84ca9ed91b0`
- `index.html` — 877 caracteres, 32 linhas, SHA-256 `7632a41b1859`
- `style.css` — 2,860 caracteres, 43 linhas, SHA-256 `7d64a79dc900`

## Interface detectada

Elementos de título, cabeçalho, botões e labels encontrados no HTML:

- Herói — Nv ${P.lv}
- 🏅 Progresso
- ${E.n}
- ⚔️ Atacar
- ${s.i} ${s.n} (${s.mp})
- 🏃 Fugir
- ${IT[id].i} ${IT[id].n} x${P.inv[id]}
- ${P.lv<x.lv?'🔒':P.area===i?'Aqui':'Ir'}
- 🗡️ Caçar em ${a.n}
- 👑 Boss: ${a.b[0]} ${P.kills[P.area]<5?`(${P.kills[P.area]}/5 abates)`:''}
- 🛏️ Descansar (10💰)
- ${it.t==='p'?'Usar':'Equipar'}
- 💰${Math.floor(it.p/2)}
- 💰${it.p}
- Participar
- Não participar
- Reino de Aethra RPG
- ⚔️ Reino de Aethra
- 💾 Salvar
- 🗑️ Reiniciar

## Controles detectados no código

- Teclas/eventos encontrados: `w`, `a`

## Tecnologias e recursos detectados

- armazenamento local
- pontuação
- inimigos
- fase/nível
- tempo/cronômetro
- salvamento

## Funções detectadas

- NEW
- mh
- add
- bar
- spawn
- hurt
- clean
- post
- win
- die
- draw
- battleView
- mapView
- invView
- shopView
- skillView
- __coletaTempo
- __coletaNumero
- __coletaPontuacao
- __coletaMundos
- __coletaMortes
- __coletaEnviar
- __coletaConsentimento
- __coletaInit

## Diferenças em relação à versão anterior

Esta é a primeira versão/pasta encontrada para este jogo; não há uma versão anterior local para comparação.

## Controles, conteúdo e descrição manual

- Objetivo do jogo: **a confirmar após jogar**.
- Controles completos: **a confirmar após jogar**.
- Diferenças percebidas pelo jogador: **a confirmar após jogar**.
- Bugs conhecidos: **a confirmar após testar**.

## Observação

Este documento foi gerado por análise dos arquivos e não substitui um teste manual. Diferenças de jogabilidade podem existir mesmo quando os arquivos parecem semelhantes.
