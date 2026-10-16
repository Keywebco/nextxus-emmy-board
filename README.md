# NextXus Emmy Board

The sovereign backup mirror of **nextxus.tech** — the Federation Admin Throne (job: `emmy-board`). Backed up 2026-08-25.

This is the command dashboard build: the Command Center front page plus `/council`, `/federation-map`, `/gate.html`, `/senate`, `/store`, and `/tokens`. FastAPI backend with a vanilla HTML/CSS/JS frontend — no React build artifacts, every page is plain HTML. This repo preserves the full build so the Throne can be re-hosted from sovereign ground — no single platform holds the only copy.

## Live

[https://keywebco.github.io/nextxus-emmy-board/](https://keywebco.github.io/nextxus-emmy-board/)

## What's inside

- `index.html` — "NEXUS THRONE — Federation Command Dashboard"
- `SOURCES.md` — backup sources: the full readable source archive, the ZIP archive, and the Google Drive backup (all files preserved)
- `backend/gemini_endpoint.py` — backend endpoint code
- `assets/`, `static/` — assets and static files
- `.nojekyll` — GitHub Pages serves the files as-is
- `.gitlab-ci.yml` — CI configuration

## Deploy

Static files can be served via GitHub Pages or any static host. The backend requires a Python/FastAPI deployment (Render.com recommended).

---

Part of the [NextXus Federation](https://keywebco.github.io).
