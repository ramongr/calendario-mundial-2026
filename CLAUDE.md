# CLAUDE.md — Instruções para o assistente

## Atualizar o ficheiro `mundial-2026.ics`

Sempre que o ficheiro `mundial-2026.ics` for modificado, **atualiza obrigatoriamente** a linha `LAST-MODIFIED` no cabeçalho do VCALENDAR para o timestamp UTC atual no formato `YYYYMMDDTHHmmssZ`.

A linha a atualizar fica no início do ficheiro, logo após `X-PUBLISHED-TTL:PT12H`:

```
LAST-MODIFIED:20260615T203700Z
```

O formato é sempre UTC (`Z` no fim). Exemplo para 3 de julho de 2026 às 14:30 UTC:

```
LAST-MODIFIED:20260703T143000Z
```

Nunca omitas esta atualização quando editas o `.ics` — serve para que os clientes de calendário detetem que houve alterações e sincronizem mais rapidamente.
