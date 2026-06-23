---
title: Grids & Columns
---

# Grids & Columns

Two layout containers. `grid` lays cards in equal tracks; `columns` flows prose side by side.

## Grid

Nest cards inside a `grid|colsN` (N = 2…6). One blank `>` line between children.

> [!grid|cols3]
>
>> [!card]
>> ###### 01
>> ### First
>> Equal-width track.
>
>> [!card]
>> ###### 02
>> ### Second
>> Equal-width track.
>
>> [!card]
>> ###### 03
>> ### Third
>> Equal-width track.

```markdown
> [!grid|cols3]
>
>> [!card]
>> ### First
>
>> [!card|span2]
>> ### Wide one (spans two tracks)
```

## Columns

For running text in parallel. Add `ruled` for a divider between columns; size children with `col|wN`.

> [!columns|ruled]
>
>> [!col|w6]
>> ### Left, weight 6
>> The wider column takes 60% of the width.
>
>> [!col|w4]
>> ### Right, weight 4
>> The narrower column takes the remaining 40%.

```markdown
> [!columns|ruled]
>
>> [!col|w6]
>> ### What it claims
>> - point one
>> - point two
>
>> [!col|w4]
>> ### Why it matters
>> Short commentary.
```

**Use it for:** `grid` → card galleries & contents. `columns` → compare/contrast prose, claims-vs-notes. Weights are relative, any pair that fits (`w6`+`w4`, `w7`+`w3`…).
