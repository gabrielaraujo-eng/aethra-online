# RPG — versão `rpg2.2`

Documentação técnica gerada em 07/11/2026. Esta análise usa os arquivos principais da pasta `rpg2.2` e ignora backups com prefixo `[backup antes da coleta]`.

## O que foi encontrado

- `game.js` — 294,227 caracteres, 3,444 linhas, SHA-256 `4e952d7e7e10`
- `index.html` — 3,237 caracteres, 64 linhas, SHA-256 `326dd8949509`
- `style.css` — 20,851 caracteres, 159 linhas, SHA-256 `da86ea183793`

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

- `game.js` alterado: 254,231 → 294,227 caracteres; 3,095 → 3,444 linhas
- `index.html` alterado: 2,481 → 3,237 caracteres; 56 → 64 linhas
- `style.css` alterado: 19,062 → 20,851 caracteres; 137 → 159 linhas
- rótulos/elementos de interface detectados como novos: `${CONS[k].price} ${ic('coin')}`, `×5 · ${CONS[k].price * 5} ${ic('coin')}`
- rótulos/elementos de interface ausentes nesta versão: `${CLS[P.cls].i} ${esc(P.name)} — ${CLS[P.cls].n[P.f]} Nv ${P.lv}${P.ng ? ` · NG+${P.ng}` : ''}`, `${CONS[k].price}💰`
- funções detectadas como novas: `DF`, `ICON`, `_L`, `_nlook`, `arenaEnd`, `arenaSpawnWave`, `arenaStart`, `arenaUpdate`, `greetLine`, `ic`, `initPost`, `netBoot`, `netChat`, `netCode`, `netDrop`

## Controles, conteúdo e descrição manual

- Objetivo do jogo: **a confirmar após jogar**.
- Controles completos: **a confirmar após jogar**.
- Diferenças percebidas pelo jogador: **a confirmar após jogar**.
- Bugs conhecidos: **a confirmar após testar**.

## Observação

Este documento foi gerado por análise dos arquivos e não substitui um teste manual. Diferenças de jogabilidade podem existir mesmo quando os arquivos parecem semelhantes.
