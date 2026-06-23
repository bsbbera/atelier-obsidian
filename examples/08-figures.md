---
title: Figures
---

# Figures

The `fig` callout frames an image with a caption (the callout title). Each cast is a different mat/treatment.

| Cast | Treatment |
|------|-----------|
| `plate` | Museum plate — clean mat + ruled caption |
| `tape` | Photo taped into a journal |
| `medallion` | Circular vignette portrait |
| `duotone` | Copper duotone wash |
| `blueprint` | Cyanotype blueprint grid |
| `hero` | Full-bleed banner image |

> [!fig|plate] Mona Lisa, c. 1503–19 — oil on poplar, Louvre
> ![[mona-lisa.jpg]]

## Float left / right

Add `left` or `right` to wrap text around a smaller figure:

```markdown
> [!fig|medallion right] Portrait
> ![[leonardo-portrait.png]]

Body text flows alongside the floated medallion…
```

## Syntax

```markdown
> [!fig|hero] The Last Supper, 1495–98 — Milan
> ![[the-last-supper.jpg]]

> [!fig|blueprint] Vitruvian Man, c. 1490
> ![[vitruvian-man.jpg]]
```

**Use it for:** `plate`/`hero` → the key artwork of a note. `tape`/`medallion` → scrapbook & portraits. `blueprint`/`duotone` → technical or stylised treatments. The image goes on the line *after* the title.
