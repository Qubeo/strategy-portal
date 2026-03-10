# DigiHub Strategy Portal

Strategic position paper for DigiHub Liechtenstein (EDIH), published as an interactive web document.

## Project Structure

- `docs/` — The live web publication (HTML shell + markdown sections + manifest)
- `docs/sections/` — Individual section content as `.md` files, loaded client-side via marked.js
- `docs/sections/manifest.json` — Section metadata (titles, previews, status)
- `resources/` — Briefs, notes, changelogs, and reference material (not deployed)
- `web/` — Original monolithic HTML (historical reference, not active)

## Canonical Documents

| File | Role |
|---|---|
| `resources/web-brief-digihub-position-paper.md` | Build brief — source of truth for page structure, scope, acceptance criteria |
| `resources/web-brief-digihub-position-paper-notes.md` | Strategy notes, open questions, editorial principles, glossary, content watchouts |
| `resources/web-brief-workflow.md` | Workflow definition: artifact roles, revision cycle, GitHub integration |

New thinking goes into notes first, gets decided, then gets distilled into the brief. Never put unresolved questions directly into the brief.

## Branch Workflow

- `main` — Production. Deploys to site root via GitHub Actions.
- `draft` — Staging/editing. Deploys to `/preview/` via GitHub Actions.
- Content edits happen on `draft`. Merge to `main` via PR for production updates.

## Key Editorial Rules

- **Institutional capability before technology** (P1) — always lead with what communities/institutions can do
- **Pattern over platform** (P7) — IXO is a reference implementation, not the point of the paper
- **Honest about limits** — acknowledge what cannot be sovereignized, adoption barriers, privilege

## Tech Stack

- No build tools, no npm, no frameworks
- Static HTML + CSS + vanilla JS
- marked.js (CDN) for client-side markdown rendering
- GitHub Pages from `gh-pages` branch
