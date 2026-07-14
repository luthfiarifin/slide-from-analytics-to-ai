# From Analytics to AI

Guest-lecture deck for **From Analytics to AI — How Digital Business Turns Data into Decisions**.
Delivered to E-Business Concept students (BINUS) as a bridge from their *Analytics System* lecture into applied, AI-assisted analytics.

Part of [luthfiarifin/research](https://github.com/luthfiarifin/research) (linked as a submodule) and published via GitHub Pages.

## Contents

- `index.html` — landing page that redirects to the deck (GitHub Pages entry point)
- `from-analytics-to-ai.html` — the slide deck (single, dependency-free HTML file)
- `assets/` — drop real screenshots here when replacing the placeholders
- Outline & sourced data live one level up: `../from-analytics-to-ai-outline.md`

## Viewing the deck

Just open `from-analytics-to-ai.html` in any browser.

- **Navigate:** `→` / `←` / `Space` / `PageUp`–`PageDown`, mouse wheel, or swipe. `Home` / `End` jump to first/last slide.
- **Edit inline:** press `E` (or hover the top-left corner) to make any text editable; edits auto-save to `localStorage`. `Ctrl/⌘+S` exports a fresh copy of the HTML.
- The stage is authored at a fixed **1920×1080** and scaled to fit the viewport, so it looks identical on any screen and prints cleanly to PDF (one slide per page).

## Assets

Real screenshots live in `assets/` and are already wired into the deck:

| Slide (deck chrome) | Asset | Shows |
|---|---|---|
| 02 · Data hook | `gartner-predicts-40-percent.png` | Gartner headline behind the 40% stat |
| 03 · Hook | `ss-ai-your-day.PNG` | Luthfi's own Claude app ("Afternoon, Luthfi") |
| 10 · Descriptive | `abadikan-blended-performance-revenue-ads-spend.jpeg` | Blended Performance dashboard (rupiah masked), MER 3.25× |
| 11 · Diagnostic | *(no image)* | Real MER-by-month table — May peak → June cliff (1.91×) |
| 15 · Demo | `abadikan-blended-claude.jpeg` | Claude + Metabase MCP diagnosing the drop + 3 real findings |
| 16 · The actual output | `abadikan-blended-claude.jpeg` (full) | Same screenshot full-size + a 5-step walk-through of how it worked |

> Note: numbers above are the deck's own `NN / 22` chrome (the 5 section dividers are unnumbered). The three data-hook stat cards each carry a clickable source link.

Still optional to swap: the **Abadikan** intro slide (09) uses an Unsplash placeholder — replace with a real Abadikan product / invitation shot if you have one.

Screenshots render via the `.photo.shot` (dark UI) and `.photo.light` (light UI) variants — full-frame `object-fit:contain`, no cinematic gradient.

Confirmed for the talk: MER **3.25×**, and MCP is the **official Metabase MCP server** (read-only, scoped).

## Style: Stencil & Tablet

A West-Coast skate-poster / municipal-stencil system. **Stardos Stencil** carries every headline and numeral; **Barlow Condensed** (extra-heavy, uppercase) runs all chrome and labels; **Inter** handles body. Bone (`#E2DCC9`) field energised by retro-print accents. All tokens live in `:root` at the top of the HTML, so retuning the whole deck is a one-place edit.

| Token | Value | Role |
|---|---|---|
| `--bone` | `#E2DCC9` | default page field |
| `--ink` | `#0A0A0A` | text on light surfaces |
| `--orange` | `#EE7A2E` | primary accent / cognitive highlight |
| `--magenta` | `#C73B7A` | loudest warm accent (cover, quote) |
| `--teal` | `#2D7E73` | cool accent ("now" column, payoff ladder) |
| `--mustard` | `#D8A93B` | action bars / callouts |

Built with the [frontend-slides](https://github.com/zarazhangrui/frontend-slides) Claude Code skill.
