# Gabriel Agent

Space Marines (Ultramarines) themed morning brief for Gabriel. Deadline: 2026-10-16.

Flow: opening phrase -> organized day (Notion, calendars) -> Guilliman's closing phrase (spoken). Later: "consult the commander" chat.

## Structure
- `phrases/` phrase bank (`phrases.json`, English only, original text)
- `assets/refs/` Pinterest inspiration (not shipped)
- `assets/ui/` images used by the app
- `design/` palette, typography, visual notes
- `brief/` brief logic and connectors
- `app/` the page

## Decisions
- Language: English. Voice: Guilliman and Ultramarines only (for now).
- Delivered as a Claude artifact opened in Gabriel's own Claude (his connectors, his data). This repo is the source of truth, not the host.
- Day source: Notion + calendars (2 Outlook, 1 Google) via connectors; manual "mission log" as fallback.
- Phrases are original, in the style of the lore; no verbatim Games Workshop text.

## Plan
0. Validate connectors in Gabriel's account. 1. MVP (theme, phrases, voice, Notion). 2. Calendars. 3. Commander chat. 4. Iterate.
