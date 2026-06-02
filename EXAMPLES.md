# Atelier — examples

Paste this whole note into Obsidian (reading view + Atelier selected) to see every feature. Works the
same under the companion **Aurora** theme — only the skin changes.

---

## Text & utilities

# H1 — From zero to *merged*
Body with **bold**, *italic* (coral), `code`, ==highlight==, and an [external link](https://obsidian.md).

<span class="at-kicker">THE SKILL</span>

<span class="at-badge">01 · ALL-TIME CONTRIBUTOR</span>  <span class="at-badge ghost">DRAFT</span>

<span class="at-display">From zero to <em>merged</em>, in an afternoon.</span>

<span class="at-stat">37</span> commits · <span class="at-mark">soft highlight</span> · <span class="at-gradient at-2xl">gradient text</span>

Inline sizes: normal, <span class="at-xs">xs</span>, <span class="at-lg">lg</span>, <span class="at-2xl">2xl</span>, exact <span class="at-fs" style="--fs: 30px">30px</span>.

## Lists
1. Hand the line to the agent
2. Wake the skill
- bullet with a coral marker
    - nested
- [ ] open task
- [x] done task

## Standard callouts
> [!note] Note
> A standard callout, themed with a mono small-caps title.

> [!warning] Warning
> Amber / terracotta accent.

---

## Cards

### Flexible grid (auto-flow)
> [!grid]
>
> > [!card] First
> > A plain card. Add as many as you like; the grid wraps them into rows.
>
> > [!card] Second
> > Resize the pane — columns reflow like a web page.
>
> > [!card] Third
> > Min card width is set in Style Settings.

### Skill card
> [!card|skill] Let the *agent* ship for you.
> ###### THE SKILL
> ```bash
> curl -sSL https://example.com/install.sh
> ```
> 1. **Hand the line to the agent** — it installs itself.
> 2. **Wake the skill** — type `/contribute`.

### Profiles (cols3)
> [!grid|cols3]
>
> > [!card|profile]
> > ###### MAINTAINER
> > ### Nagendra
> > Finds the failure, fixes it properly.
> > [github](https://github.com/)
>
> > [!card|profile dark]
> > ###### FROM THE STUDIO
> > ### Koki
> > Wave any time, on any question.
>
> > [!card|profile dark]
> > ###### STEWARD
> > ### Victor
> > Keeps the room warm.

### Hero (accent)
> [!card|hero accent spanfull]
> ###### FOUR STEPS · ANY SKILL LEVEL
> # From zero to *merged*, in an afternoon.
> Whether you're a designer, a writer, or an engineer, there's a shape for you.
>
> **[Read the guide →](https://obsidian.md)** [GitHub](https://github.com/)

---

## Multi-column notes
> [!columns|ruled]
>
> > [!col|w3]
> > ### Narrow
> > - one
> > - two
>
> > [!col|w7]
> > ### Wide
> > Roughly 70% of the width. Normal note content — no card chrome.

## Infobox (floats; text wraps beside)
> [!infobox|right] Cloud Storage
> ## Amazon S3
> *Durable object store for the web.*
>
> | Field | Value |
> | --- | --- |
> | Vendor | AWS |
> | Released | 2006 |

A paragraph beside the infobox wraps naturally to its left. Lorem ipsum dolor sit amet, consectetur
adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
