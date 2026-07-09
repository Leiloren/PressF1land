# PressF1land — The Paddock

Landing page for all Press F1 activities: a hub linking the four F1 products
built by two friends who take the sport very seriously and themselves not at all.

- **Press F1** — the podcast
- **Silly Season** — driver-market web app (live)
- **Safety Car** — spoiler-free Telegram replay bot
- **Predicts & Awards** — podium predictions + season awards

## Development

The site is a single static file, [`index.html`](index.html), with all styles
and SVG artwork inlined. No build step. Open it directly in a browser to preview.

The design was handed off from [Claude Design](https://claude.ai/design) and
recreated here as production HTML/CSS (the design-tool `style-hover` attributes
became real CSS `:hover` rules).

## Deployment

Pushes to `main` (or the active feature branch) trigger the
[`Deploy to GitHub Pages`](.github/workflows/deploy.yml) workflow, which
publishes the repo root to GitHub Pages.

> First-time setup: in the repo **Settings → Pages**, set **Source** to
> **GitHub Actions**.

Product links are placeholders (`#anchors`) except Silly Season, which is live.
They'll be wired to real destinations as each product ships.
