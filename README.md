# Pip's Pancake Job

**Play:** https://mrfalc0n.github.io/pip-pancakes/ (best on a tablet, sideways, sound on)

A playable prototype of a learning game for kids aged 4–6. The child helps Pip, a silly purple creature, make pancakes by building a request from picture tiles: how many, what size, and what goes on top.

Pip behaves like an AI helper. When a detail is missing or vague, Pip guesses, wrongly and hilariously: a tower of pancakes, a giant pancake, pickles on top. The child spots what went wrong, fixes the request, and tries again. In one round Pip makes a mistake while sounding completely sure of itself, and the child has to catch it.

**What it practices**
- Counting and comparing sizes
- Giving clear, complete instructions (prompting, not coding)
- Checking a helper's work instead of trusting it

**Design notes**
- Single self-contained HTML file. No accounts, ads, analytics, or network calls. Progress is kept only in the browser's local storage.
- Pre-reader friendly: the device's voice reads every line; tiles are picture-first.
- A hidden grown-ups panel (press and hold for 2 seconds) shows a per-round log: tries, hint level, which mistakes happened, and whether the child caught Pip's confident mistake.
- Help steps up gradually: Pip explains its guess and the wrong groups blink red; then the slot glows; then the right tile wiggles.

**Status:** early prototype (M1.4, October 2026). Pip's dialogue is pre-written; no live AI model runs in this version.

**How it was built:** designed with AI-assisted product critique and built by Claude (Anthropic) under human product direction, with automated browser playthrough tests and an independent AI review pass.

© 2026 Chris Collins. All rights reserved.
