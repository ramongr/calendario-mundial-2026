# CLAUDE.md — Instruções para o assistente

## Atualizar o ficheiro `mundial-2026.ics`

Sempre que o ficheiro `mundial-2026.ics` for modificado, **atualiza obrigatoriamente** a linha `X-WR-LAST-MODIFIED` no cabeçalho do VCALENDAR para o timestamp UTC atual no formato `YYYYMMDDTHHmmssZ`.

A linha a atualizar fica no início do ficheiro, logo após `X-PUBLISHED-TTL:PT12H`:

```
X-WR-LAST-MODIFIED:20260615T203700Z
```

O formato é sempre UTC (`Z` no fim). Exemplo para 3 de julho de 2026 às 14:30 UTC:

```
X-WR-LAST-MODIFIED:20260703T143000Z
```

Além disso, atualiza o `LAST-MODIFIED` de cada `VEVENT` que tiver sido alterado (fica logo a seguir ao `DTSTAMP` de cada evento). Se editares apenas alguns eventos, atualiza só esses; se for uma atualização geral ao ficheiro, atualiza todos.

Nunca omitas estas atualizações quando editas o `.ics` — servem para que os clientes de calendário detetem que houve alterações e sincronizem mais rapidamente.

## Emojis das bandeiras nos jogos

Sempre que um `SUMMARY` de um `VEVENT` incluir o nome de uma seleção (fase de grupos, dezasseis avos, oitavos, quartos, meias-finais ou final), **é obrigatório** incluir o emoji da bandeira do respetivo país antes do nome da seleção, no formato:

```
SUMMARY:🇵🇹 Portugal vs 🇭🇷 Croácia (Dezasseis avos)
```

Isto aplica-se sempre que:

* Se cria um novo evento com seleções já conhecidas.
* Se substitui um placeholder (ex.: `Vencedor J83`, `3.º (C/E/F/H/I)`, `Vencedor do Grupo K`) pelo nome real de uma seleção, assim que o adversário fica confirmado.

Nunca deixes um nome de seleção sem a bandeira correspondente. Para o País de Gales, Escócia e Inglaterra usa a bandeira regional (ex.: `🏴󠁧󠁢󠁥󠁮󠁧󠁿` para Inglaterra), não a bandeira do Reino Unido.
