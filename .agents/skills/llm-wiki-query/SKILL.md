---
name: llm-wiki-query
description: Query an LLM Wiki efficiently. Use when answering questions from the vault, searching compiled notes, or deciding whether Raw source context is needed.
---

# LLM Wiki Query

Use this skill when answering questions from the LLM Wiki.

## Steps

1. Start with `Wiki/index.md`.
2. Search `Wiki/catalog.jsonl` when it exists.
3. Read matching compiled Wiki notes.
4. Open Raw sources only when compiled notes are insufficient or source-level verification is requested.
5. Cite the compiled note and Raw source when evidence matters.

