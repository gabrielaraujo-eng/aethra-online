# RPG — versão `rpg2.5`

Documentação técnica gerada em 07/11/2026. Esta análise usa os arquivos principais da pasta `rpg2.5` e ignora backups com prefixo `[backup antes da coleta]`.

## O que foi encontrado

- `game.js` — 309,128 caracteres, 3,556 linhas, SHA-256 `980e5acc9c94`
- `index.html` — 3,138 caracteres, 62 linhas, SHA-256 `a2ce13a98f48`
- `style.css` — 22,141 caracteres, 174 linhas, SHA-256 `ea7b108b4efa`

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
- ${n === 'max' ? 'Máx' : n}
- +${stpN}
- Tudo
- Atributos ${P.pts ? ` (${P.pts} pontos) Auto
- Redistribuir
- Estatísticas
- 🏆 Conquistas (${Object.keys(P.ach).length}/${ACH.length})
- Redistribuir pontos
- +1
- ⭐ História — ${P.q}/${FINAL_Q}

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
- storyEnqueue
- storyTick
- questTick
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

## Diferenças em relação à versão anterior

- `game.js` alterado: 297,039 → 309,128 caracteres; 3,471 → 3,556 linhas
- `index.html` alterado: 3,237 → 3,138 caracteres; 64 → 62 linhas
- `style.css` alterado: 21,676 → 22,141 caracteres; 167 → 174 linhas
- rótulos/elementos de interface detectados como novos: `${n === 'max' ? 'Máx' : n}`, `+${stpN}`, `Tudo`
- rótulos/elementos de interface ausentes nesta versão: `Concluídas`, `Contratos de caçada`, `Missões secundárias`
- funções detectadas como novas: `closeSaveBox`, `exportSlot`, `importBox`, `questTick`, `saveBox`, `storyEnqueue`, `storyTick`, `unpackSave`
- funções que deixaram de ser detectadas: `_nlook`, `netBoot`, `netChat`, `netCode`, `netDrop`, `netHit`, `netJoin`, `netLeave`, `netPartyHTML`, `netPeers`, `netUpdate`, `onlineHTML`

## Controles, conteúdo e descrição manual

- Objetivo do jogo: **a confirmar após jogar**.
- Controles completos: **a confirmar após jogar**.
- Diferenças percebidas pelo jogador: **a confirmar após jogar**.
- Bugs conhecidos: **a confirmar após testar**.

## Observação

Este documento foi gerado por análise dos arquivos e não substitui um teste manual. Diferenças de jogabilidade podem existir mesmo quando os arquivos parecem semelhantes.
