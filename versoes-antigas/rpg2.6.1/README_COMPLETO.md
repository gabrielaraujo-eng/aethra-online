# RPG — versão `rpg2.6.1`

Documentação técnica gerada em 07/11/2026. Esta análise usa os arquivos principais da pasta `rpg2.6.1` e ignora backups com prefixo `[backup antes da coleta]`.

## O que foi encontrado

- `game.js` — 312,469 caracteres, 3,597 linhas, SHA-256 `bf73b483a3bf`
- `index.html` — 3,140 caracteres, 62 linhas, SHA-256 `1df7be48e46a`
- `style.css` — 22,631 caracteres, 182 linhas, SHA-256 `a7afe5384284`

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

- `game.js` alterado: 310,137 → 312,469 caracteres; 3,568 → 3,597 linhas
- `index.html` alterado: 3,138 → 3,140 caracteres; 62 → 62 linhas
- `style.css` alterado: 22,449 → 22,631 caracteres; 179 → 182 linhas
- funções detectadas como novas: `showFuture`

## Controles, conteúdo e descrição manual

- Objetivo do jogo: **a confirmar após jogar**.
- Controles completos: **a confirmar após jogar**.
- Diferenças percebidas pelo jogador: **a confirmar após jogar**.
- Bugs conhecidos: **a confirmar após testar**.

## Observação

Este documento foi gerado por análise dos arquivos e não substitui um teste manual. Diferenças de jogabilidade podem existir mesmo quando os arquivos parecem semelhantes.
