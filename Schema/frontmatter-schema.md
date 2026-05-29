# Frontmatter Schema

## Raw Source Notes

Raw source notes live in `Raw/Sources/`.

Required frontmatter:

```yaml
---
Title: ""
Author: ""
Reference: ""
ContentType:
  - "markdown"
Created: YYYY-MM-DD
Processed: false
tags:
  - "source"
---
```

Required fields:

- `Title`
- `Reference`
- `Created`
- `Processed`
- `tags`

## Compiled Wiki Notes

Compiled notes live under `Wiki/Topics/`, `Wiki/Concepts/`, `Wiki/Entities/`, `Wiki/Projects/`, or `Wiki/Logs/`.

Required frontmatter:

```yaml
---
tags:
  - "concept"
topics: []
status: seed
created: YYYY-MM-DD
updated: YYYY-MM-DD
sources: []
source_count: 0
aliases: []
---
```

Allowed compiled note tags:

- `topic`
- `concept`
- `entity`
- `project`
- `log`

`source_count` must equal the number of entries in `sources`.

