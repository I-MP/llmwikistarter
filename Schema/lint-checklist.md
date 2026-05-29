# Lint Checklist

Before committing meaningful changes, confirm:

- Required folders exist.
- Raw source notes have required frontmatter.
- Compiled Wiki notes live under the correct `Wiki/` subfolder.
- Compiled Wiki notes use exactly one allowed tag.
- Every compiled note has at least one Raw source unless it is an empty placeholder.
- `source_count` equals the number of entries in `sources`.
- Sources listed in compiled notes point to real files under `Raw/Sources/`.
- Generated catalog and index files are up to date once tooling exists.
- No plugin caches, private workspace state, secrets, or machine-local files are committed.

