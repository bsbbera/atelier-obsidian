---
title: Cards
---

# Cards

The `card` callout is Atelier's workhorse surface — a lifted panel for grids, profiles, steps and hero banners. Casts pick the layout; modifiers tune it.

## Casts

> [!card]
> ###### KICKER
> ### Plain card
> The default surface — kicker, heading, body.

> [!card|step icon-search]
> ###### STEP
> ### Step card
> Numbered/iconed process tile. Icons: `icon-search · icon-layers · icon-cloud · icon-book`.

> [!card|profile]
> ###### ROLE
> ### Profile card
> Image-topped people card. Put `![[photo.jpg]]` as the first line.

> [!card|hero dark]
> ###### HERO
> # Hero banner
> Full-bleed dark headline slab for the top of a note.

| Cast | What it is |
|------|-----------|
| `skill` | Tag-list / capability card with a dashed rule |
| `section` | Flat section divider card |
| `step` | Process tile (pair with `icon-*`) |
| `profile` | Image-first people card |
| `honor` | Award / credential card |
| `channels` | Contact / link row card |
| `hero` | Big headline banner |

## Modifiers (stack them)

| Modifier | Effect |
|----------|--------|
| `dark` | Forces the dark surface (great on light theme) |
| `accent` | Copper-tinted fill |
| `wN` | Width weight inside a grid (`w4`, `w6`…) |
| `span2` | Span two grid columns |
| `spanfull` | Span the whole grid row |

## Syntax

```markdown
> [!card|hero dark spanfull]
> ###### RENAISSANCE
> # The man who would *know everything*.
> Supporting standfirst line.

> [!card|step icon-layers]
> ###### AERIAL
> ### Aerial screw
> A helical rotor meant to compress air and lift.
```

**Use it for:** index/landing notes, dashboards, people directories, step-by-step guides. Combine with [Grids](03-grids-and-columns.md).
