---
name: llm-wiki-ingest
description: Ingest Raw sources into an LLM Wiki. Use when adding source notes, compiling them into Wiki notes, linking claims to sources, and updating source coverage.
---

# LLM Wiki Ingest

Use this skill when the user adds new source material or asks to turn Raw notes into compiled Wiki notes.

## Steps

1. Put cleaned source Markdown in `Raw/Sources/`.
2. Search the existing catalog before opening broad Raw context.
3. Compile only durable, reusable knowledge into `Wiki/`.
4. Link every compiled note to one or more Raw source files.
5. Keep `source_count` equal to the number of source links.
6. Run the build, lint, source-scan, and source-lint commands once tooling exists.

