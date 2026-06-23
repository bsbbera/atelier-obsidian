---
title: Code
---

# Code

Code blocks render on a dark surface by default. Wrap a fence in a `code` callout to add a titled frame.

## Bar — titled terminal

> [!code|bar] codex.log
> ```text
> 1478 — earliest dated notebook entries begin
> 1490 — Vitruvian Man; studies of light and shadow
> 1517 — final notebooks: water and the deluge
> ```

## Clay — tablet

> [!code|clay] phi.py
> ```python
> def phi(n: int) -> float:
>     a, b = 0, 1
>     for _ in range(n):
>         a, b = b, a + b
>     return b / a
> ```

## Syntax

````markdown
> [!code|bar] filename.log
> ```text
> your code here
> ```
````

A **bare** ```` ```lang ```` fence (no callout) is also fully styled — clean frame, no stray run-button chrome, in reading view.

**Use it for:** `bar` → logs, shell, config with a filename header. `clay` → highlighted snippets you want to feel like a tablet. The text after the cast becomes the frame title.
