# Changelog

## [Unreleased]

### Added
- Initial open-source hardening pass for project metadata.
- Added contribution and security docs (`CONTRIBUTING.md`, `SECURITY.md`).

### Changed
- Removed mock quota fallback so the app now prefers real local session-derived quotas.
- Menu bar now displays unavailable state when no quota record is available.

## [0.1.0] - 2026-07-09

- Initial release scaffold with 5-hour and weekly quota meter, menu bar status text, and popover panel.
- Local-only inference from `.codex/sessions` logs.
- Optional periodic voice broadcast and low-quota notifications.
- DMG packaging script.
