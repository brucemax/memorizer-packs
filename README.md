# Memorizer language packs

Downloadable dictionary packs for the Memorizer vocabulary app. This repository holds data only, no code. The
files are published as [releases](../../releases):

- `<lang>-v<N>`: one language version. `<lang>.json` is the manifest; `<lang>-base.db.gz` holds the dictionary
  (entries, senses, word forms, frequency rank, starter lists) and `<lang>-<target>.db.gz` holds translations into
  one target language. All files are gzip-compressed SQLite databases.
- `index`: `index.json`, the list of available packs. The app reads it from
  `https://github.com/brucemax/memorizer-packs/releases/download/index/index.json`.

## License and attribution

The pack files are adapted from the sources listed in each manifest (`sources`) and in
[DATA_LICENSES.md](DATA_LICENSES.md), mainly Wiktionary, and are licensed under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). The data was extracted, filtered, ranked and
restructured. You may copy and reuse the files under the same license.

"Wiktionary" is a trademark of the Wikimedia Foundation. It is used here only to name the source of the data; this
project is not affiliated with or endorsed by the Wikimedia Foundation.
