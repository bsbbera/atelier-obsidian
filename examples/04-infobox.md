---
title: Infobox
---

# Infobox

A Wikipedia-style side box for at-a-glance facts. Floats beside your prose; text wraps around it.

## Placement & style

`[!infobox|<align> <style>]` — align is `left · right · center`, style is `v1 · v2 · v3`.

> [!infobox|v2 right] 1452 – 1519
> ## Leonardo da Vinci
> *"Il Genio Universale."*
>
> | Field | Value |
> | --- | --- |
> | Born | 15 Apr 1452 |
> | Died | 2 May 1519 |
> | Era | High Renaissance |

- **v1** — light card, ledger rows.
- **v2** — dark display plate; put an image first (`![[portrait.png]]`) and the heading stays light over it.
- **v3** — boxed catalogue.

## Casts

| Cast | Look |
|------|------|
| `codex` | Specimen / manuscript dossier |
| `manifest` | Stamped record sheet |
| `tag` | Compact stat box with a corner tag |

> [!infobox|tag right] Auction record
> ## $450.3 M
> *Salvator Mundi, 2017.*
>
> | Rank | #1 ever |
> | --- | --- |
> | House | Christie's |

## Per-box width

Override the global width on a single box with `narrow` (240px) · `wide` (380px) · `wider` (460px):

```markdown
> [!infobox|v2 right wide] 1452 – 1519
> ![[portrait.png]]
> ## Leonardo da Vinci
> | Born | 1452 |
> | --- | --- |
> | Died | 1519 |
```

**Use it for:** biographies, specimen records, product/spec at-a-glance. The first markdown table inside becomes the data rows.
