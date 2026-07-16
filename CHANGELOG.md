# Changelog

All notable changes to this project will be documented in this file.

## [2.0.0] - 2026-07-16
### Added
- `[METADATA OVERRIDE]` strict ingestion rules.
- `Course Name` and `Lesson Theme` tracking.
- `<notebooklm_notes>` and `<mastery_ledger>` extraction blocks.

### Changed
- Standardized `Lesson Name` to `Lesson Title` across all prompts and outputs.
- Refactored the Markdown Report header from an inline string to a multi-line structured block.
- Expanded the forced JSON serialization schema to include new academic variables.

### Fixed
- Prevented AI hallucination of metadata by enforcing "N/A" strict fallbacks.