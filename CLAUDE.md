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
