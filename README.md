# Kairo Bible Packs

Generated, installable Bible translation packs for the Kairo desktop app.
Each asset is a gzipped SQLite database (verses + FTS5 search index) produced
by Kairo's `scripts/build-bible-pack.ts` converter and verified by SHA-256
inside the client before install.

## Assets (`bible-packs-v1`)

| Asset | Translation | Verses | Chapters | Uncompressed |
| ----- | ----------- | -----: | -------: | -----------: |
| `nkjv-pack.db.gz` | New King James Version | 31,102 | 1,189 | ~13.4 MB |

## Notes

- Source texts are never committed here — only the generated `.db.gz` assets.
- Distribution rights for each translation are held separately; do not
  mirror or redistribute these assets outside their licensed use.
