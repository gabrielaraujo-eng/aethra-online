# RPG — versão `rpg2.4`

Documentação técnica gerada em 07/11/2026. Esta análise usa os arquivos principais da pasta `rpg2.4` e ignora backups com prefixo `[backup antes da coleta]`.

## O que foi encontrado

- `game.js` — 297,039 caracteres, 3,471 linhas, SHA-256 `13bfbe14454e`
- `index.html` — 3,237 caracteres, 64 linhas, SHA-256 `326dd8949509`
- `style.css` — 21,676 caracteres, 167 linhas, SHA-256 `8f78f22b12c0`

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
- Mochila (${P.inv.length}/${INV_MAX}) Vender comuns
- +1
- Atributos ${P.pts ? ` (${P.pts} pontos) Auto
- Redistribuir
- Estatísticas
- 🏆 Conquistas (${Object.keys(P.ach).length}/${ACH.length})
- Redistribuir pontos
- ⭐ História — ${P.q}/${FINAL_Q}
- Missões secundárias
- Contratos de caçada
- Concluídas

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

- `game.js` alterado: 312,694 → 297,039 caracteres; 3,663 → 3,471 linhas
- `index.html` alterado: 3,303 → 3,237 caracteres; 65 → 64 linhas
- `style.css` alterado: 26,351 → 21,676 caracteres; 222 → 167 linhas
- rótulos/elementos de interface detectados como novos: `Mochila (${P.inv.length}/${INV_MAX}) Vender comuns`, `Redistribuir`, `Redistribuir pontos`
- rótulos/elementos de interface ausentes nesta versão: `${CONS[k].price} ${ic('coin')}`, `Mochila (${P.inv.length}/36) Vender comuns`, `×5 · ${CONS[k].price * 5} ${ic('coin')}`
- funções detectadas como novas: `card`, `migrateSaves`
- funções que deixaram de ser detectadas: `GRAD`, `addOutlineNormals`, `buildGrass`, `buildSky`, `buildUpdrafts`, `jump`, `movePL`, `rimPatch`, `toon`, `updateSky`, `updateUpdrafts`

## Controles, conteúdo e descrição manual

- Objetivo do jogo: **a confirmar após jogar**.
- Controles completos: **a confirmar após jogar**.
- Diferenças percebidas pelo jogador: **a confirmar após jogar**.
- Bugs conhecidos: **a confirmar após testar**.

## Observação

Este documento foi gerado por análise dos arquivos e não substitui um teste manual. Diferenças de jogabilidade podem existir mesmo quando os arquivos parecem semelhantes.
