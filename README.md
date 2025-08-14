# Polymath-Lab

![Docs CI](https://github.com/ChaseMinShrimp/Polymath-Lab/actions/workflows/docs-ci.yml/badge.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Purpose: research + projects + notes in one repo. Obsidian-compatible but the
app is optional.

## Quickstart

1. Open in browser editor: press `.` on the repo (github.dev).
2. Notes live under `obsidian/`; templates in `obsidian/99_Templates/`.
3. Flow: feature branch → PR → CI checks → merge to `main`.

## Repository Structure

- `docs/` — public docs and write-ups  
- `projects/` — high-level project briefs and outcomes  
- `research/` — raw notes and summaries (non-Obsidian)  
- `obsidian/` — vault-friendly notes (Daily, Papers, Projects, Dashboards, Templates)  
- `src/`, `scripts/` — code and automation  
- `notebooks/` — Jupyter etc.  
- `data/` — binary/large files (tracked via LFS)

## Conventions

Frontmatter for notes: `type`, `status`, `due`, `tags`.  
Status values: `idea | active | blocked | done`.  
Use conventional commits and small PRs.

## CI & Quality

Docs CI checks: markdownlint, cspell, link check on PRs. Dependabot runs weekly.

## Security

See `SECURITY.md` for reporting vulnerabilities.

## License

MIT — see `LICENSE`.
