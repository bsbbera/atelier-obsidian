---
title: Tables
---

# Tables

Wrap a markdown table in a `table` callout to give it a cast. Plain tables are styled too — the cast adds character.

## Ledger

Accounting-style: ruled rows, left-aligned, monospace figures.

> [!table|ledger]
> | Work | Date | Medium | Location |
> | --- | --- | --- | --- |
> | Annunciation | c.1472 | Oil & tempera | Uffizi |
> | The Last Supper | 1495–98 | Tempera & oil | Milan |
> | Mona Lisa | 1503–19 | Oil on poplar | Louvre |

## Box

Boxed catalogue: every cell bordered, header filled.

> [!table|box]
> | Key | Value |
> | --- | --- |
> | Folios | 72 |
> | Subject | Water · fossils · the Moon |
> | Buyer | Bill Gates |

## Syntax

```markdown
> [!table|ledger]
> | Year | Event |
> | --- | --- |
> | 1452 | Born in Vinci |
> | 1519 | Died at Amboise |
```

**Use it for:** `ledger` → catalogues, timelines, finances. `box` → key/value spec sheets. The callout title (after the cast) is optional.
