# RPG — versão `rpg2.3`

Documentação técnica gerada em 07/11/2026. Esta análise usa os arquivos principais da pasta `rpg2.3` e ignora backups com prefixo `[backup antes da coleta]`.

## O que foi encontrado

- `game.js` — 312,694 caracteres, 3,663 linhas, SHA-256 `1df597ca4168`
- `index.html` — 3,303 caracteres, 65 linhas, SHA-256 `2a2ba338e63c`
- `style.css` — 26,351 caracteres, 222 linhas, SHA-256 `b3714ca62ab6`

## Interface detectada

Elementos de título, cabeçalho, botões e labels encontrados no HTML:

- ${esc(o.t)}
- Continuar ▸
- ✖
- Desequipar
- Equipar
- Vender (${Math.round(itemValue(sel) / 4)}💰)
- Usar
- Equipado
- Consumíveis
- Mochila (${P.inv.length}/36) Vender comuns
- +1
- Atributos ${P.pts ? ` (${P.pts} pontos) Auto
- Estatísticas
- 🏆 Conquistas (${Object.keys(P.ach).length}/${ACH.length})
- ⭐ História — ${P.q}/${FINAL_Q}
- Missões secundárias
- Contratos de caçada
- Concluídas
- ${CONS[k].price} ${ic('coin')}
- ×5 · ${CONS[k].price * 5} ${ic('coin')}

## Controles detectados no código

- Teclas/eventos encontrados: `s`, `w`, `a`, `d`

## Tecnologias e recursos detectados

- Canvas 2D
- WebGL
- Three.js
- armazenamento local
- áudio/música
- pontuação
- inimigos
- fase/nível
- tempo/cronômetro
- colisão
- menu
- salvamento

## Funções detectadas

- rn
- clamp
- lerp
- sstep
- dist2d
- angTo
- angDiff
- mulberry
- wr
- hash2
- vnoise
- fbm
- saveCfg
- zoneAt
- _L
- ICON
- ic
- AU
- init
- setVol
- tone
- noise
- arp
- play
- deg
- setTheme
- note
- drum
- sched
- initPost

## Diferenças em relação à versão anterior

- `game.js` alterado: 294,227 → 312,694 caracteres; 3,444 → 3,663 linhas
- `index.html` alterado: 3,237 → 3,303 caracteres; 64 → 65 linhas
- `style.css` alterado: 20,851 → 26,351 caracteres; 159 → 222 linhas
- funções detectadas como novas: `GRAD`, `addOutlineNormals`, `buildGrass`, `buildSky`, `buildUpdrafts`, `jump`, `movePL`, `rimPatch`, `toon`, `updateSky`, `updateUpdrafts`

## Controles, conteúdo e descrição manual

- Objetivo do jogo: **a confirmar após jogar**.
- Controles completos: **a confirmar após jogar**.
- Diferenças percebidas pelo jogador: **a confirmar após jogar**.
- Bugs conhecidos: **a confirmar após testar**.

## Observação

Este documento foi gerado por análise dos arquivos e não substitui um teste manual. Diferenças de jogabilidade podem existir mesmo quando os arquivos parecem semelhantes.
