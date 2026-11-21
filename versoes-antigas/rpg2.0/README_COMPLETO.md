# RPG — versão `rpg2.0`

Documentação técnica gerada em 07/11/2026. Esta análise usa os arquivos principais da pasta `rpg2.0` e ignora backups com prefixo `[backup antes da coleta]`.

## O que foi encontrado

- `game.js` — 27,636 caracteres, 293 linhas, SHA-256 `854a8c92363a`
- `index.html` — 1,369 caracteres, 33 linhas, SHA-256 `1a532e92e651`
- `style.css` — 3,182 caracteres, 36 linhas, SHA-256 `8a7df5d0ef9d`

## Interface detectada

Elementos de título, cabeçalho, botões e labels encontrados no HTML:

- 🎒 Mochila
- 🛒 Mercador
- ✖
- ${id[0]==='w'||id[0]==='a'?'Equipar':'Usar'}
- 💰${price(id)>>1}
- Comprar
- 0?'cd':''}" ${P.lv ${P.lv ${i+1} · ${P.lv 0?SC[i].toFixed(1)+'s':s.mp+'mp'}
- ❤️ H · ${pc('h')}
- 🔹 M · ${pc('m')}
- Participar
- Não participar
- Aethra Online 3D
- 🎒 Mochila (I)
- ⚔️ Aethra Online 3D
- 🗡️ Guerreiro Corpo a corpo, muito HP
- 🏹 Arqueiro Ataque à distância
- 🪄 Mago Magia, gasta mana

## Controles detectados no código

- Teclas/eventos encontrados: `w`, `a`, `s`

## Tecnologias e recursos detectados

- Canvas 2D
- WebGL
- Three.js
- armazenamento local
- pontuação
- fase/nível
- tempo/cronômetro
- menu
- salvamento

## Funções detectadas

- RG
- mh
- M
- BX
- part
- eyes
- limb
- mk
- scatter
- bx
- gear
- setup
- spawnM
- inTown
- dmgText
- toast
- ring
- flash
- hit
- shoot
- basic
- skill
- add
- kill
- dmgP
- pot
- nm
- equip
- nearNpc
- panel

## Diferenças em relação à versão anterior

- `game.js` alterado: 14,637 → 27,636 caracteres; 229 → 293 linhas
- `index.html` alterado: 877 → 1,369 caracteres; 32 → 33 linhas
- `style.css` alterado: 2,860 → 3,182 caracteres; 43 → 36 linhas
- rótulos/elementos de interface detectados como novos: `${id[0]==='w'||id[0]==='a'?'Equipar':'Usar'}`, `0?'cd':''}" ${P.lv ${P.lv ${i+1} · ${P.lv 0?SC[i].toFixed(1)+'s':s.mp+'mp'}`, `Aethra Online 3D`, `Comprar`, `⚔️ Aethra Online 3D`, `✖`, `❤️ H · ${pc('h')}`, `🎒 Mochila`, `🎒 Mochila (I)`, `🏹 Arqueiro Ataque à distância`, `💰${price(id)>>1}`, `🔹 M · ${pc('m')}`
- rótulos/elementos de interface ausentes nesta versão: `${E.n}`, `${IT[id].i} ${IT[id].n} x${P.inv[id]}`, `${P.lv<x.lv?'🔒':P.area===i?'Aqui':'Ir'}`, `${it.t==='p'?'Usar':'Equipar'}`, `${s.i} ${s.n} (${s.mp})`, `Herói — Nv ${P.lv}`, `Reino de Aethra RPG`, `⚔️ Atacar`, `⚔️ Reino de Aethra`, `🏃 Fugir`, `🏅 Progresso`, `👑 Boss: ${a.b[0]} ${P.kills[P.area]<5?`(${P.kills[P.area]}/5 abates)`:''}`
- funções detectadas como novas: `BX`, `M`, `RG`, `b`, `basic`, `bx`, `dmgP`, `dmgText`, `equip`, `eyes`, `face`, `flash`, `gear`, `go`, `hit`
- funções que deixaram de ser detectadas: `NEW`, `bar`, `battleView`, `clean`, `die`, `draw`, `hurt`, `invView`, `mapView`, `post`, `shopView`, `skillView`, `spawn`, `win`
- recursos/indicadores novos: Canvas 2D, Three.js, WebGL, menu
- recursos/indicadores não mais detectados: inimigos

## Controles, conteúdo e descrição manual

- Objetivo do jogo: **a confirmar após jogar**.
- Controles completos: **a confirmar após jogar**.
- Diferenças percebidas pelo jogador: **a confirmar após jogar**.
- Bugs conhecidos: **a confirmar após testar**.

## Observação

Este documento foi gerado por análise dos arquivos e não substitui um teste manual. Diferenças de jogabilidade podem existir mesmo quando os arquivos parecem semelhantes.
