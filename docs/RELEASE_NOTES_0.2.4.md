# Canvas Learning Center 0.2.4 — privacy-safe diagnostics beta

**Release date:** 23 August 2026  
**Developer:** ZihengHuang  
**Feedback:** canvas-center@z-hstudio.com

## Changes

- Added one-click diagnostic bundle export to first-run setup and System Status.
- Added safe Canvas connection categories and traceable diagnostic IDs.
- Included only allowlisted platform, Canvas hostname, aggregate storage, SQLite health, sync status, and structured event fields.
- Excluded credentials, identity data, course titles/content, notes, submissions, grades, databases, signed URLs and local paths.
- Kept both Chinese-default and English-default installers for macOS and Windows.

All installers remain explicitly labelled `UNSIGNED-CANARY`. They are not
formally signed or notarized and may be warned about or blocked by Gatekeeper or
SmartScreen. This is an independent beta, not an official Instructure or
University of Sydney product.
