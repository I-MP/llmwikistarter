# Workflow Examples

## Ingest A New Source

1. Add cleaned Markdown to `Raw/Sources/`.
2. Search the compiled Wiki catalog for related existing notes.
3. Read only the most relevant compiled notes first.
4. Create or update focused notes under `Wiki/`.
5. Link each compiled note back to the Raw source in `sources`.
6. Keep `source_count` accurate.
7. Run build, lint, source scan, and source lint before committing.

## Query The Wiki

1. Start with `Wiki/index.md`.
2. Search `Wiki/catalog.jsonl`.
3. Open matching compiled Wiki notes.
4. Open Raw sources only when the compiled note is not enough or source-level verification is needed.

## Maintain The Wiki

1. Rebuild generated indexes and catalogs.
2. Check source coverage.
3. Fix lint errors before committing.
4. Add a log note when the meaning of the Wiki changes.

