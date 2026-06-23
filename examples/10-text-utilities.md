---
title: Text utilities
---

# Text utilities

Inline HTML classes for editorial typography — kickers, leads, stats, highlights. Use a `<span>` (inline) or `<p>` (block).

| Class | Effect |
|-------|--------|
| `at-kicker` | Mono small-caps eyebrow with a copper tick (add `no-dot` to drop it) |
| `at-badge` | Pill badge (add `ghost` for outline) |
| `at-display` | Oversized display run with a drop-cap first letter |
| `at-lead` | Standfirst / lede paragraph (italic serif) |
| `at-stat` | Monospace figure, copper |
| `at-mark` | Gold highlighter sweep |
| `at-gradient` | Accent-coloured emphasis run |

## In use

<p class="at-lead">A standfirst paragraph reads as the lede of the note — slightly larger, italic, and quietly authoritative.</p>

<p class="at-kicker">Chapter 01 · Life</p>

A normal line with a <span class="at-stat">13,000</span>-page statistic and a phrase that is <span class="at-mark">worth marking</span>.

<span class="at-badge">New</span> <span class="at-badge ghost">Draft</span>

## Syntax

```html
<p class="at-lead">Your standfirst paragraph.</p>

<span class="at-kicker no-dot">Filed under</span>

Left <span class="at-stat">42</span> notes, all <span class="at-mark">reviewed</span>.
```

## Sizes

`at-xs · at-sm · at-md · at-lg · at-xl · at-2xl · at-3xl` set inline font-size; `at-fs` is the flexible step.

```html
<span class="at-3xl">Big</span> <span class="at-sm">small</span>
```

**Use it for:** magazine-style openers, callout-free emphasis, stat lines. Whole-note heading/tag styles live in [Structural casts](12-structural-casts.md) and Style Settings.
