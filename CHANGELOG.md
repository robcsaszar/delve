# Changelog

All notable changes to this project are documented here. Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/); versioning follows [SemVer](https://semver.org/).

## [0.6.0] - 2026-08-14

### Fixed

- Removed the unconditional closing `See REFERENCE.md` pointer, which contradicted the conditional load rule above it ("Do NOT load for single-source/conversational research") and pulled the reference into every run.
- The two `## NEVER` sections had identical headings, leaving it ambiguous which mode each governed. The second is now `## NEVER (multi-source mode)`, pairing with the single-source block.

## [0.5.0] - 2026-07-10

### Added

- Initial release: delve skill.

[0.5.0]: https://github.com/robcsaszar/delve/releases/tag/v0.5.0
