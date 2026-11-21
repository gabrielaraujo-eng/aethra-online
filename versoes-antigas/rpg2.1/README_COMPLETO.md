# RPG — versão `rpg2.1`

Documentação técnica gerada em 07/11/2026. Esta análise usa os arquivos principais da pasta `rpg2.1` e ignora backups com prefixo `[backup antes da coleta]`.

## O que foi encontrado

- `game.js` — 254,231 caracteres, 3,095 linhas, SHA-256 `e95ebb2fcdf4`
- `index.html` — 2,481 caracteres, 56 linhas, SHA-256 `c255c48fc803`
- `style.css` — 19,062 caracteres, 137 linhas, SHA-256 `604ef80041a8`

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
- ${CLS[P.cls].i} ${esc(P.name)} — ${CLS[P.cls].n[P.f]} Nv ${P.lv}${P.ng ? ` · NG+${P.ng}` : ''}
- Atributos ${P.pts ? ` (${P.pts} pontos) Auto
- Estatísticas
- 🏆 Conquistas (${Object.keys(P.ach).length}/${ACH.length})
- ⭐ História — ${P.q}/${FINAL_Q}
- Missões secundárias
- Contratos de caçada
- Concluídas
- ${CONS[k].price}💰

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
- matC
- cylT
- mergeParts
- chunkedInstances

## Diferenças em relação à versão anterior

- `game.js` alterado: 27,636 → 254,231 caracteres; 293 → 3,095 linhas
- `index.html` alterado: 1,369 → 2,481 caracteres; 33 → 56 linhas
- `style.css` alterado: 3,182 → 19,062 caracteres; 36 → 137 linhas
- rótulos/elementos de interface detectados como novos: `${CLS[P.cls].i} ${esc(P.name)} — ${CLS[P.cls].n[P.f]} Nv ${P.lv}${P.ng ? ` · NG+${P.ng}` : ''}`, `${CONS[k].price}💰`, `${esc(o.t)}`, `+1`, `Atributos ${P.pts ? ` (${P.pts} pontos) Auto`, `Concluídas`, `Consumíveis`, `Continuar ▸`, `Contratos de caçada`, `Desequipar`, `Equipado`, `Equipar`
- rótulos/elementos de interface ausentes nesta versão: `${id[0]==='w'||id[0]==='a'?'Equipar':'Usar'}`, `0?'cd':''}" ${P.lv ${P.lv ${i+1} · ${P.lv 0?SC[i].toFixed(1)+'s':s.mp+'mp'}`, `Aethra Online 3D`, `Comprar`, `Não participar`, `Participar`, `⚔️ Aethra Online 3D`, `❤️ H · ${pc('h')}`, `🎒 Mochila`, `🎒 Mochila (I)`, `🏹 Arqueiro Ataque à distância`, `💰${price(id)>>1}`
- funções detectadas como novas: `AU`, `H`, `Hbase`, `Hraw`, `T_`, `ach`, `achPop`, `addBuilt`, `addCol`, `addItem`, `angDiff`, `angTo`, `animLimbs`, `arp`, `attackNearest`
- funções que deixaram de ser detectadas: `BX`, `M`, `RG`, `add`, `b`, `basic`, `bx`, `dmgP`, `eyes`, `face`, `flash`, `gear`, `go`, `hit`, `hud`
- recursos/indicadores novos: colisão, inimigos, áudio/música

## Controles, conteúdo e descrição manual

- Objetivo do jogo: **a confirmar após jogar**.
- Controles completos: **a confirmar após jogar**.
- Diferenças percebidas pelo jogador: **a confirmar após jogar**.
- Bugs conhecidos: **a confirmar após testar**.

## Observação

Este documento foi gerado por análise dos arquivos e não substitui um teste manual. Diferenças de jogabilidade podem existir mesmo quando os arquivos parecem semelhantes.
