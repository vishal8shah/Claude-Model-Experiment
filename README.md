# Aurora · Blind Taste Test

One prompt. One shot. Three frontier AI models. Zero follow-ups, zero edits, single HTML file each.

Each model was given the exact same prompt (below) and produced a complete customer dashboard for **Aurora**, a fictional smart home energy company. The outputs are published unlabelled as **A**, **B**, and **C** — can you tell which model made which?

**Live site:** open `index.html` on the GitHub Pages deployment and flip between A / B / C.

## The prompt

```
Create a single-file HTML page (all CSS and JS inline, no external
libraries, no images) for "Aurora", a fictional smart home energy
company's customer dashboard.

It must include:
- Current energy usage with a live-updating visualisation
- A 7-day usage history chart built from scratch
- Solar generation vs grid consumption breakdown
- 3 smart suggestions to reduce the next bill
- A dark/light mode toggle
- At least one interaction that delights you

Design constraints: no default fonts, no pure black or white,
must feel like a product people would pay for.

One shot. Make every design decision yourself. Do not ask questions.
```

## Rules

- No cherry-picking, no iterations — first output, as-is
- All CSS/JS inline, no libraries, no images
- The A/B/C order is shuffled and the mapping is not in this repo

Run the prompt yourself and compare.
