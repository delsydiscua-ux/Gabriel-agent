# Visual direction (draft v0)

Source: Pinterest board "Warhammer" (https://pin.it/t18WIVQCU, ~29 pins). Inspiration only, not shipped.

## What the board shows
- Ultramarines cobalt blue armor with gold trim, laurels, wings (aquila-style winged motifs).
- Gothic cathedral / stained-glass feel, Ultramar "U" icon, ornate frames.
- Dark void backgrounds with starships and cathedral-ships; warm gold light.
- Red/gold imperial eagle appears too (accent only, not the main palette).
- A humorous Guilliman portrait (sunglasses): a light tone is welcome.

## Palette (initial proposal)
- Void: #070B16 (background)
- Deep ultramarine: #0B2A6F, mid cobalt: #1E4FBF
- Imperial gold: #C9A227, bright gold highlight: #F2D675
- Parchment text: #E8E1CC
- Warning crimson (alerts / overdue only): #A4161A

## Type and UI
- Headings: gothic display serif (e.g. Cinzel); body: clean mono for the "cogitator terminal" feel (e.g. IBM Plex Mono / JetBrains Mono).
- Gold borders with corner ornaments, subtle scanline / glow on the terminal text.
- Mobile first (Gabriel opens it on his phone in the morning).

## Pending
- Pick 5-8 favorite pins to place in `assets/refs/`.
- Decide which images (if any) can ship in `assets/ui/`; prefer original SVG icons (aquila, laurel, "U") over reusing pinned artwork.

## Layout v1 (Figma, desktop 1920x1080)
Figma file: Dashboards > page "Gabriel Brief" > frame "Desktop Brief 1920" (node 2001:2). Reference render: `layout-desktop-1920.png`.
Margins 80 / 64, 24 px gaps. Left column 920 px, right column 800 px, 40 px between.

| Block | x | y | w | h | Content |
|---|---|---|---|---|---|
| Logo | 80 | 64 | 96 | 96 | "U" mark |
| Battle Brief | 200 | 64 | 700 | 96 | Title + today's date + source brief |
| Current Situation | 80 | 184 | 920 | 232 | Global summary |
| Priorities from Pending | 80 | 440 | 920 | 300 | Combined bullets: first 3 = route, status pills, "+N more" |
| Audacy / Medtronic / HSD | 80 / 396 / 712 | 764 | 288 | 252 | Counts + up to 3 items, quiet state |
| Today's Orders | 1040 | 64 | 800 | 200 | Opening phrase + Hear button |
| Primarch Panel | 1040 | 288 | 800 | 728 | Mission log (left), figure (right 436x560), reserved slot (bottom 752x96) |

Text styles: Title (Cinzel Bold 44), Display (Cinzel Bold 36), Panel Title (Cinzel Bold 18, +10% tracking), Quote (Cinzel Regular 24), Body (IBM Plex Mono 16), Body Small (14), Label (IBM Plex Mono Medium 12, +8%).
Panels: Void @ 82% fill, Gold @ 45% 1px inside stroke, square corners. Colors bound to the "Warhammer" variable collection.
