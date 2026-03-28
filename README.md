# All for AI

Curated resources for building AI agents: skills, prompts, instruction files, MCP, frameworks, evals, workflows, and runnable examples.

This repository is designed as an **AI Agent Builder Kit** rather than a generic AI link dump. The goal is to collect reusable building blocks that developers can copy, adapt, and ship.

## Why this repo exists

Most AI lists are broad but hard to reuse. This repo focuses on:

- Reusable assets instead of raw links
- Clear metadata for filtering and future automation
- English-first content with Chinese-friendly notes where useful
- Practical builder scenarios such as coding, research, and automation

## What lives here

- `content/`: reviewed resources and starter assets
- `templates/`: authoring templates for contributors
- `docs/`: curation rules, taxonomy, and contributor guidance
- `data/`: shared categories, tags, and validation schema
- `scripts/`: local validation and automation helpers

## Current scope

This repository currently includes **47 curated entries** across **8 categories**:

- 8 skills
- 8 prompts
- 3 instruction resources
- 7 MCP resources
- 10 frameworks
- 4 evals
- 3 workflows
- 4 examples

## Browse by category

- [Skills](content/skills/README.md): reusable agent behaviors and skill references
- [Prompts](content/prompts/README.md): copyable prompts and prompt-engineering references
- [Instructions](content/instructions/README.md): AGENTS.md, Copilot, and prompt-file guidance
- [MCP](content/mcp/README.md): MCP overview, SDKs, servers, and tooling
- [Frameworks](content/frameworks/README.md): major agent and LLM application frameworks
- [Evals](content/evals/README.md): testing and evaluation tools for prompts and agents
- [Workflows](content/workflows/README.md): end-to-end task flows
- [Examples](content/examples/README.md): runnable or near-runnable blueprints and reference repos

## Browse by index

- [Featured](content/indexes/featured.md): short featured list
- [Builder Landscape](content/indexes/landscape.md): broader builder ecosystem map
- [Browse by Scenario](content/indexes/by-scenario.md): coding, research, automation, and prompt-design paths

## Good starting points

If you are new to AI builders, start with:

- [AGENTS.md Standard](content/instructions/agents-md-standard/README.md)
- [Debug Bug Prompt](content/prompts/coding/debug-bug/README.md)
- [Code Review Skill](content/skills/coding/code-review-skill/README.md)
- [Model Context Protocol Overview](content/mcp/official-overview/README.md)
- [OpenAI Agents SDK (JavaScript/TypeScript)](content/frameworks/openai-agents-js/README.md)
- [OpenAI Agents SDK (Python)](content/frameworks/openai-agents-python/README.md)
- [promptfoo](content/evals/promptfoo/README.md)
- [OpenAI Cookbook](content/examples/reference/openai-cookbook/README.md)

## Contribution flow

1. Pick a category in `content/`.
2. Start from the matching file in `templates/`.
3. Add `README.md` and `meta.yml`.
4. Run `node scripts/validate-metadata.js`.
5. Open a pull request.

## Curation principles

- Prefer reusable assets over opinion-only articles
- Prefer active, documented, public resources
- Avoid duplicates and dead links
- Write short summaries that explain why an item matters

## Current status

This repository now has a real curated base rather than just a scaffold. The next focus is increasing content depth inside each category, especially:

- more original prompts and skills
- more scenario-based workflow packs
- better indexes and discovery pages
- more Chinese-friendly usage notes

See `ROADMAP.md` for expansion plans.
