# Blaise xTech Developer Portal

Placeholder landing page for the **xTech Developer Portal** — the future home of Blaise SDK documentation, sample apps, and API references for the [Blaise xTech Competition](https://www.herox.com/xTechIdeaCompetition).

🔗 **Live site:** [developer.blaise-x.ai](https://developer.blaise-x.ai/)

## Status

This is a static placeholder. The full portal (SDK docs, API reference, sample apps) is planned for a later phase.

## Stack

- Single static `index.html` file (no build step, no dependencies)
- Hosted on [GitHub Pages](https://pages.github.com/)
- Custom domain via `CNAME` DNS record on GoDaddy → `blaise-ose.github.io`
- TLS certificate auto-provisioned by GitHub Pages

## Local preview

Just open `index.html` in a browser — no build or server required.

## Deployment

Pushes to `main` are automatically published via GitHub Pages (Settings → Pages → Deploy from a branch).
