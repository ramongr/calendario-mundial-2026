# Calendário do Mundial 2026 (em português)

Calendário (`.ics`) com todos os jogos do Campeonato do Mundo FIFA 2026, em **hora de Portugal Continental**, indicando os canais portugueses previstos para cada jogo.

* Inclui os **104 jogos** (72 da fase de grupos + 32 da fase a eliminar).
* Pode ser **subscrito** no Google Calendar, Apple Calendar (iPhone/Mac), Outlook, etc. — assim, qualquer atualização ao ficheiro (adversários da fase a eliminar, alterações de horário ou mudanças de canal) aparece automaticamente nos teus dispositivos.
* Fonte da informação: [A Bola — Mundial 2026: todos os jogos, horas, transmissões e grupos](https://www.abola.pt/noticias/mundial-2026-todos-os-jogos-horas-transmissoes-e-grupos-resultados-classificacao-calendario-onde-ver-2026051915373936358).

## URL para subscrever

```txt
https://raw.githubusercontent.com/jpgcc/calendario-mundial-2026/main/mundial-2026.ics
```

Copia este URL — vais utilizá-lo nas instruções abaixo.

> Nota: o GitHub pode demorar alguns minutos a refletir alterações no `raw.githubusercontent.com`. Os calendários também só voltam a sincronizar de tempos a tempos (normalmente entre algumas horas e um dia), por isso não esperes ver alterações em tempo real.

## Como subscrever

### Google Calendar (computador)

1. Abre o [Google Calendar](https://calendar.google.com/) no browser.
2. Na barra lateral esquerda, ao lado de **Outros calendários**, clica no **+**.
3. Escolhe **A partir do URL** / **From URL**.
4. Cola o URL acima e clica em **Adicionar calendário**.

O calendário aparece na barra lateral. No telemóvel (Android/iPhone com app Google Calendar), basta abrir a app — sincroniza automaticamente após adicionares no computador.

> Importante: utiliza **A partir do URL** (subscrição) e **não** **Importar** — só com a subscrição recebes atualizações automáticas.

### Apple Calendar — iPhone / iPad

1. **Definições** → **Calendário** → **Contas** → **Adicionar conta**.
2. **Outra** → **Adicionar calendário subscrito**.
3. No campo **Servidor**, cola o URL e toca em **Seguinte**.
4. Confirma com **Guardar**.

### Apple Calendar — Mac

1. Abre a app **Calendário**.
2. Menu **Ficheiro** → **Nova subscrição de calendário…** (`⌥⌘S`).
3. Cola o URL e clica em **Subscrever**.
4. Em **Atualizar**, recomenda-se escolher **Cada hora** ou o intervalo mais curto disponível.

### Outlook (Microsoft 365 / Outlook.com — web)

1. Abre o [Outlook](https://outlook.live.com/calendar/) na web.
2. Na barra lateral, clica em **Adicionar calendário**.
3. Escolhe **Subscrever a partir da Web**.
4. Cola o URL, dá-lhe um nome (ex.: *Mundial 2026*) e clica em **Importar**.

## O que vais ver no calendário

Cada evento tem um título no formato `🏳 Equipa A vs 🏳 Equipa B (Grupo X)`. A descrição inclui a fase da prova e a transmissão prevista, por exemplo:

```txt
Mundial FIFA 2026 — Fase de Grupos, Grupo K.
Transmissão: SIC, Sport TV, LiveModeTV.
```

Os locais aproximados (cidade/país) também estão incluídos.

### Sobre as horas

* Todas as horas estão configuradas com a timezone `Europe/Lisbon`.
* Em junho/julho, Portugal Continental está em WEST (UTC+1).
* Se estiveres noutro fuso horário, a tua app de calendário deverá ajustar automaticamente a hora apresentada.
* A fase de grupos e os dezasseis avos de final já terminaram — os oitavos de final (a partir de 4 de julho) já têm os adversários confirmados. Os quartos de final, meias-finais e final ainda aparecem como "Vencedor do Jogo X" até serem conhecidos os apurados.

### Canais

* **Sport TV** transmite todos os jogos do Mundial.
* **LiveModeTV** acompanha jogos selecionados, incluindo jogos de maior interesse.
* **RTP, SIC e TVI** transmitem jogos em sinal aberto.

| Canal   | Jogos indicados                                                                                                                                                               |
| ------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **RTP** | França vs Senegal (16 jun) · Suíça vs Bósnia e Herzegovina (18 jun) · Colômbia vs Portugal (28 jun) · Portugal vs Espanha — oitavos (6 jul) · Final                            |
| **SIC** | Canadá vs Bósnia e Herzegovina (12 jun) · Portugal vs RD Congo (17 jun) · Equador vs Alemanha (25 jun) · Colômbia vs Gana — dezasseis avos (4 jul) · 1 meia-final              |
| **TVI** | México vs África do Sul — jogo inaugural (11 jun) · Alemanha vs Costa do Marfim (20 jun) · Portugal vs Uzbequistão (23 jun) · Noruega vs França (26 jun) · 1 jogo dos quartos |

> Os jogos da fase a eliminar podem mudar de canal ou descrição quando forem conhecidos os adversários finais e a grelha definitiva de transmissões.

## Atualizações

Este repositório será atualizado à medida que houver novidades, como adversários confirmados na fase a eliminar, alterações de horário ou mudanças nas transmissões.

Como o calendário é subscrito por URL, **não precisas de fazer nada** — a tua app de calendário vai buscar a versão mais recente periodicamente.

Se quiseres forçar uma atualização:

* **Google Calendar:** não há um botão de “atualizar agora”; normalmente sincroniza várias vezes por dia.
* **Apple Calendar (Mac):** clica com o botão direito no calendário → **Atualizar**.
* **Apple Calendar (iOS/iPadOS):** abre a lista de calendários e puxa para baixo para atualizar.

## Contribuir / reportar erros

Se detetares um erro (hora errada, canal errado, equipa mal escrita), abre uma *issue* ou um *pull request* neste repositório.

## Licença

Os dados do calendário são factuais (calendário desportivo público). O ficheiro `.ics` e este README são disponibilizados ao abrigo da licença [Creative Commons Zero (CC0)](https://creativecommons.org/publicdomain/zero/1.0/) — podes utilizar, copiar, modificar e partilhar à vontade.
