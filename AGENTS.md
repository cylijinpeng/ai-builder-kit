# AGENTS.md

## Repository purpose

This repository curates reusable builder assets for AI agents: skills, prompts, instruction files, MCP resources, frameworks, evals, workflows, and examples.

## High-value locations

- `README.md`: public project overview
- `content/`: curated resource entries and starter assets
- `templates/`: templates for new prompts, skills, and instruction files
- `docs/`: taxonomy, style, and curation policy
- `scripts/`: metadata and link validation helpers

## Contribution rules

- Keep one resource per folder under `content/`
- Add `README.md` and `meta.yml` for each resource entry
- Prefer short summaries with concrete use cases
- Avoid adding low-signal marketing links or duplicates

## Validation

Run:

- `node scripts/validate-metadata.js`
- `node scripts/check-links.js`

## Editing style

- Prefer additive, focused changes
- Keep category README files in sync when adding resources
- Update `README.md` when the repository scope or counts materially change
