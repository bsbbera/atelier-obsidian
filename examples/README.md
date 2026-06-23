# Atelier — Element Cookbook

Every Atelier component, one file at a time, with copy-pasteable syntax and a note on when to reach for it.

Atelier styles **reading view**. Most elements are Obsidian callouts with a *cast* — a word after a pipe that picks a visual variant: `> [!card|hero dark]`. A few are whole-note `cssclasses` or inline HTML utilities.

| # | File | Covers |
|---|------|--------|
| 01 | [Callouts](01-callouts.md) | The 13 native callouts, restyled |
| 02 | [Cards](02-cards.md) | `card` casts: skill · section · step · profile · honor · channels · hero |
| 03 | [Grids & Columns](03-grids-and-columns.md) | `grid|colsN`, `columns` + `col|wN` |
| 04 | [Infobox](04-infobox.md) | Wiki side-box: `v1/v2/v3`, `codex/manifest/tag`, width modifiers |
| 05 | [Tables](05-tables.md) | `table|ledger`, `table|box` |
| 06 | [Code](06-code.md) | `code|bar`, `code|clay` |
| 07 | [Quotes](07-quotes.md) | `quote|illum`, `quote|gloss`, `quote|tab` |
| 08 | [Figures](08-figures.md) | `fig|plate/tape/medallion/duotone/blueprint/hero` + float |
| 09 | [Dividers](09-dividers.md) | `hr` casts: rosette · fleuron · stratum |
| 10 | [Text utilities](10-text-utilities.md) | `at-kicker · at-badge · at-display · at-lead · at-stat · at-mark · at-gradient` + sizes |
| 11 | [Emotion casts](11-emotion-casts.md) | 26 styled variants of note/info/tip/success/warning/question/danger/example/todo |
| 12 | [Structural casts](12-structural-casts.md) | `seal · folio · marg` — callouts without the box |

## How a cast works

```markdown
> [!card|hero dark spanfull]
> ###### KICKER
> # Headline with *accent* emphasis
> Supporting line.
```

- `card` = the callout type → the base look.
- `hero dark spanfull` = space-separated cast words → the variant.
- Unknown cast word → it falls back to the plain element. Nothing breaks.

> [!tip|lamp] Tip
> Open any file in this folder in **reading view** to see the element rendered, then copy the fenced block into your own note.
