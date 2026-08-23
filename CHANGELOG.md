# Changelog

## 0.2.5 — 2026-08-23

- Fixed Canvas connection failures in packaged macOS builds by using the app's bundled certificate-authority store.
- Added a distinct, privacy-safe TLS certificate error category for diagnostics.
- Rebuilt the Chinese-default and English-default macOS and Windows installers.
- Kept Canvas access read-only and preserved token storage in the operating-system credential store.

Known release limitation: these installers remain unsigned beta canaries and
may be blocked or warned about by Gatekeeper or SmartScreen.

## 0.2.4 — 2026-08-23

- Added one-click privacy-safe diagnostic bundle export to first-run setup and System Status.
- Replaced generic Canvas connection failures with safe error categories and diagnostic IDs.
- Included only allowlisted platform, Canvas host, aggregate storage, SQLite health, sync status, and structured event fields.
- Excluded credentials, identity data, course titles/content, notes, submissions, grades, databases, signed URLs, and local paths from the bundle.
- Fixed Windows diagnostic-log lifecycle handling found by the Windows CI canary.

Known release limitation: these installers remain unsigned beta canaries and
may be blocked or warned about by Gatekeeper or SmartScreen.

## 0.2.3 — 2026-08-22

- Added an in-app `EN / 中文` language switch.
- Added separate Chinese-default and English-default packages for macOS and Windows.
- Preserved a user's saved language choice during an upgrade.
- Added bilingual installation and download instructions.
- Strengthened release metadata and package-integrity checks.
- Kept the Canvas connection read-only.

Known release limitation: these installers remain unsigned beta canaries and
may be blocked or warned about by Gatekeeper or SmartScreen.

## 0.2.2 — 2026-08-21

- Added plain-text installation instructions.
- Corrected developer attribution and support contact details.
- Added package metadata, third-party notices, and release checksums.
- Added the in-app feedback link.
