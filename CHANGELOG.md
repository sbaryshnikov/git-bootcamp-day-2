# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com),
and this project adheres to [Semantic Versioning](https://semver.org).

## [Unreleased]

### Added
- Multi-language support for French and Spanish localization.
- Dark mode toggle option in the user settings dashboard.

### Changed
- Refactored the authentication API pipeline to reduce latency by 15%.

### Deprecated
- The legacy `/v1/login` endpoint is deprecated and will be removed in v2.0.0.

## [1.0.0] - 2026-04-15

### Added
- Automatic database automated backups scheduled daily at 02:00 UTC.

### Fixed
- Fixed a memory leak occurring during large file uploads on the client side.
- Resolved a rendering bug on mobile viewports for the profile card widget.

### Security
- Patched a critical SQL injection vulnerability within the query builder engine.

## - 2026-02-10

### Fixed
- Fixed broken password reset links that failed to transmit token values.

## - 2026-01-05

### Added
- Initial baseline production release of the core software application.
