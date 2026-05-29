# LLM Wiki Agent Rules

This repository is an Obsidian LLM Wiki. It separates source material from compiled knowledge so future agents can work quickly without reading every raw note first.

## Required Workflow

1. Treat `Raw/Sources/` as source material, not compiled notes.
2. Write reusable knowledge only under `Wiki/`.
3. Keep every compiled note linked to one or more Raw sources.
4. Search `Wiki/catalog.jsonl` before opening broad Raw context.
5. Run build, lint, and source checks before commits.
6. Do not invent citations or create unsupported claims.

## Repository Areas

- `Raw/Sources/` stores source notes.
- `Raw/Files/` stores supporting files and binaries.
- `Wiki/` stores compiled notes.
- `Schema/` stores rules and reference docs.
- `_templates/` stores copyable note templates.
- `.agents/skills/` stores repo-local skills for future agents.
- `scripts/` stores deterministic maintenance tools.

## Before Handoff Or Commit

Run the maintenance checks once the tooling exists:

```bash
python3 scripts/wiki_tool.py build
python3 scripts/wiki_tool.py lint
python3 scripts/wiki_tool.py source-lint
```

If source coverage changed, also run:

```bash
python3 scripts/wiki_tool.py source-scan --update --accept-covered
```

