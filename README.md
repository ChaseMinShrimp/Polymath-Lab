![Docs CI](https://github.com/ChaseMinShrimp/Polymath-Lab/actions/workflows/docs-ci.yml/badge.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)



# Polymath Lab (Private)

**Thesis (draft):** Master a broad anchor (default: Computer Science) and connect it with Math/Stats, Writing, and Design by shipping one app or explainer each month.

Folders: 10-Concepts / 20-Projects / 30-Logs / 40-Glossary / 50-Metrics

# Polymath-Lab

## Purpose
Research + projects + notes in one repo; Obsidian-compatible but app is optional.

## Quickstart
1. Open in browser editor: press `.` on the repo (github.dev).
2. Notes live under `obsidian/`; templates in `obsidian/99_Templates/`.
3. Flow: feature branch → PR → CI checks → merge to `main`.

## Repository Structure
- docs/ — public docs and write-ups
- projects/ — high-level project briefs and outcomes
- research/ — raw notes & summaries (non-Obsidian)
- obsidian/ — vault-friendly notes (Daily, Papers, Projects, Dashboards, Templates)
- src/, scripts/ — code and automation
- notebooks/ — Jupyter, etc.
- data/ — binary/large files (tracked via LFS)

## Conventions
- Frontmatter for notes: `type`, `status`, `due`, `tags`.
- Status values: `idea | active | blocked | done`.
- Conventional commits and small PRs.

## CI & Quality
Docs CI checks: markdownlint, cspell, link check on PRs. Dependabot weekly.

## Security
See `SECURITY.md` for reporting vulnerabilities.

## License
MIT — see `LICENSE`.
