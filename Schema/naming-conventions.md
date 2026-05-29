# Naming Conventions

Use short, readable filenames.

## Files

- Use lowercase words separated by hyphens.
- Prefer stable names over temporary names.
- Keep one durable idea per compiled note.

Examples:

- `Raw/Sources/llm-wiki-starter-demo-source.md`
- `Wiki/Concepts/source-backed-claims.md`
- `Wiki/Topics/llm-wiki-workflow.md`

## Skills

Repo-local skills live under `.agents/skills/`.

Each skill folder name must match the `name` field in its `SKILL.md` frontmatter.

Examples:

- `.agents/skills/llm-wiki-ingest/SKILL.md`
- `.agents/skills/llm-wiki-query/SKILL.md`

