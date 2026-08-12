# Vault Schema

## Folder Structure
- `raw/` — input notes (immutable, never edited by synto)
- `wiki/` — AI-synthesised articles (managed by synto)
- `wiki/.drafts/` — pending human review

## Note Format
Every wiki note has YAML frontmatter with: title, tags, sources, confidence, status, created, updated.

## Links
Use `[[Article Title]]` wikilinks between notes.
