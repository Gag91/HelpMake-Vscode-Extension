# Changelog

## [1.1.0] - 2026-10-21

### Added
- `Dependency: name { }` block highlighting, including all fields (`Git`, `Url`, `Path`, `Tag`, `Commit`, `Hash`, `Build`, `Include`, `Link`, `LinkDir`, `LinkFlags`)
- `Depends:` field highlighting
- `Set { }`, `Copy { }`, `Arguments { }` block highlighting
- `Kind:`, `Jobs:`, `PCH:` field highlighting
- Variable expansion `[[name]]` highlighting
- Config and dependency names highlighted distinctly (`Config: debug {` → `debug` as entity name)

### Changed
- Block keyword highlighting requires `{` (so `InputFiles:` inline form now uses field coloring instead of block coloring)
- Bumped to match HelpMake 11.1.0

### Fixed
- Value-after-colon highlighting (previous regex used variable-length lookbehind, which Oniguruma rejects — the values never actually highlighted)
- Broken link and typos in README

## [1.0.0] - 2026-XX-XX

### Added
- Initial release: syntax highlighting for `HelpMake.txt` and `.helpmake` files
- Comments, block keywords, field names