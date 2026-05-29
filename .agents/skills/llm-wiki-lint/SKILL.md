---
name: llm-wiki-lint
description: Lint and verify an LLM Wiki. Use before commits or handoff to check frontmatter, source links, source coverage, generated catalogs, and public-safety issues.
---

# LLM Wiki Lint

Use this skill before committing or handing off work.

## Steps

1. Run the deterministic maintenance commands once `scripts/wiki_tool.py` exists.
2. Fix frontmatter errors before continuing.
3. Fix missing or unsupported source links.
4. Rebuild generated catalog and index files.
5. Run public audit checks before sharing or pushing.

