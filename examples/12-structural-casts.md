---
title: Structural casts
---

# Structural casts

Three casts that drop the callout box entirely — for margin notes that sit *in* the page, not on it. They lift on hover without a drop shadow (transparent surfaces).

| Cast | Look |
|------|------|
| `seal` | Wax-seal sigil with corner brackets |
| `folio` | Vertical folio label down the side |
| `marg` | Caveat handwriting marginalia |

> [!note|marg] on her smile
> The expression shifts because the corners of the mouth and eyes are deliberately blurred — peripheral vision completes a smile the central vision can't pin down.

> [!note|seal] Certified
> A sealed aside, framed like a stamp pressed into the page.

## Syntax

```markdown
> [!note|marg] short title
> Handwritten-feel marginal note in Caveat.

> [!info|folio] Folio
> A vertically-labelled side note.
```

## Whole-note cssclasses

Set these in frontmatter to restyle a note globally:

```yaml
---
cssclasses:
  - mw-h-illum   # illuminated headings
  - mw-tag-pill  # pill-style tags
  - mw-bq-gloss  # gloss blockquotes note-wide
---
```

**Use it for:** `marg`/`seal`/`folio` → annotations and asides that should feel handwritten or stamped, not boxed. cssclasses → opt a single note into a heading/tag/quote treatment.
