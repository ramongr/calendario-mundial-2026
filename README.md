# Calendário do Mundial 2026 (em português)

Calendário (`.ics`) com todos os jogos do Campeonato do Mundo FIFA 2026, em **hora de Lisboa**, indicando o **canal português** que vai transmitir cada jogo.

- Inclui os **104 jogos** (72 da fase de grupos + 32 da fase a eliminar).
- Pode ser **subscrito** em Google Calendar, Apple Calendar (iPhone/Mac), Outlook, etc. — assim, qualquer atualização ao ficheiro (horas a confirmar, adversários da fase a eliminar, alterações de canal) aparece automaticamente nos teus dispositivos.
- Fonte da informação: [A Bola — Mundial 2026: todos os jogos, horas, transmissões e grupos](https://www.abola.pt/noticias/mundial-2026-todos-os-jogos-horas-transmissoes-e-grupos-resultados-classificacao-calendario-onde-ver-2026051915373936358).

## URL para subscrever

```
https://raw.githubusercontent.com/jpgcc/calendario-mundial-2026/main/mundial-2026.ics
```

Copia este URL — vais usá-lo nas instruções abaixo.

> Nota: o GitHub pode demorar alguns minutos a refletir alterações no `raw.githubusercontent.com`. Os calendários só voltam a sincronizar de tempos a tempos (normalmente entre algumas horas e um dia), portanto não esperes ver alterações em tempo real.

## Como subscrever

### Google Calendar (computador)

1. Abre o [Google Calendar](https://calendar.google.com/) no browser.
2. Na barra lateral esquerda, ao lado de **"Outros calendários"**, clica no **+**.
3. Escolhe **"A partir do URL"** / **"From URL"**.
4. Cola o URL acima e clica em **"Adicionar calendário"**.

O calendário aparece na barra lateral. No telemóvel (Android/iPhone com app Google Calendar), basta abrir a app — sincroniza automaticamente após adicionares no computador.

> Importante: usa **"A partir do URL"** (subscrição) e **não** "Importar" — só com a subscrição é que recebes atualizações automáticas.

### Apple Calendar — iPhone / iPad

1. **Definições** → **Calendário** → **Contas** → **Adicionar conta**.
2. **Outra** → **Adicionar calendário subscrito**.
3. No campo **Servidor**, cola o URL e toca em **Seguinte**.
4. Confirma com **Guardar**.

### Apple Calendar — Mac

1. Abre a app **Calendário**.
2. Menu **Ficheiro** → **Nova subscrição de calendário…** (`⌥⌘S`).
3. Cola o URL e clica em **Subscrever**.
4. Em **"Atualizar"**, recomenda-se escolher **"Cada hora"** (ou o intervalo mais curto disponível).

### Outlook (Microsoft 365 / Outlook.com — web)

1. Abre o [Outlook](https://outlook.live.com/calendar/) na web.
2. Na barra lateral, clica em **"Adicionar calendário"**.
3. Escolhe **"Subscrever a partir da Web"**.
4. Cola o URL, dá-lhe um nome (ex.: *Mundial 2026*) e clica em **"Importar"**.

## O que vais ver no calendário

Cada evento tem um título no formato `Mundial 2026: Equipa A vs Equipa B (Grupo X)`. A descrição inclui a fase da prova e o canal que transmite, por exemplo:

```
Mundial 2026 — Fase de Grupos, Grupo K.
Transmissão: Sport TV, Livemode.
```

Locais aproximados (cidade/país) também estão incluídos, para o caso de a tua app de calendário ajustar fusos horários por localização (não devia — as horas estão fixadas em Lisboa).

### Sobre as horas

- **Fase de grupos:** todas as horas indicadas são em hora local de Lisboa (junho/julho ⇒ WEST, UTC+1). O ficheiro inclui a *timezone* `Europe/Lisbon`, por isso as apps de calendário ajustam corretamente caso estejas noutro fuso horário.
- **Fase a eliminar (16-avos em diante):** os adversários e as **horas exatas ainda não estão confirmados pela FIFA**. Estes jogos aparecem como **eventos de dia inteiro** na data correta. Quando as horas forem confirmadas, o ficheiro será atualizado.

### Canais

A informação de canais segue a fonte [A Bola](https://www.abola.pt/). Tipicamente:
- **Sport TV** transmite todos os jogos do Mundial.
- **Livemode** (streaming) acompanha os jogos de maior interesse, incluindo todos os de Portugal.

Caso a RTP venha a anunciar transmissão em sinal aberto de alguns jogos (habitual nos jogos de Portugal e na final), o ficheiro será atualizado.

## Atualizações

Este repositório será atualizado à medida que houver novidades (horas confirmadas para os jogos a eliminar, alterações de transmissão, etc.). Como subscreveste por URL, **não precisas de fazer nada** — a tua app de calendário vai buscar a versão mais recente periodicamente.

Se quiseres forçar uma atualização imediata:
- **Google Calendar:** não há um botão de "atualizar agora"; tipicamente sincroniza várias vezes por dia.
- **Apple Calendar (Mac):** clica com o botão direito no calendário → **Atualizar**.
- **Apple Calendar (iOS):** "puxa para baixo" na lista de calendários.

## Contribuir / reportar erros

Se detetares um erro (hora errada, canal errado, equipa mal escrita), abre uma *issue* ou um *pull request* neste repositório.

## Licença

Os dados do calendário são factuais (calendário desportivo público). O ficheiro `.ics` e o presente README são disponibilizados ao abrigo da licença [Creative Commons Zero (CC0)](https://creativecommons.org/publicdomain/zero/1.0/) — usa, copia, modifica e partilha à vontade.
