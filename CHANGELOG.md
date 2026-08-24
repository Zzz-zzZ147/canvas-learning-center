# Changelog

This file is generated from the same bilingual release history shown inside
Canvas Learning Center. Do not edit it by hand.

## 0.2.10 — 2026-08-24

### Application and GitHub release history

Adds bilingual release history inside the app and generates the GitHub changelog from the same record.

#### Added

- Added an offline release-history entry in System Status for the current and previous versions.
- Each release shows its date, change categories, known limitations, and official GitHub Release link.
- Added a standard-library generator that creates or checks the public CHANGELOG.md.

#### Changed

- Release content is maintained once in a bilingual structured source shared by the app and GitHub.
- English-default packages show English history, Chinese-default packages show Chinese history, and the history follows the in-app language switch.

#### Security

- Release history is read-only packaged data and contains no token, local path, course content, or personal study data.

#### Known issues

- Installers remain unsigned beta canaries, so Gatekeeper or SmartScreen may display a warning.

[View GitHub Release](https://github.com/Zzz-zzZ147/canvas-learning-center/releases/tag/v0.2.10)

## 0.2.9 — 2026-08-24

### Account control, feedback, and in-app updates

Added safe logout, reliable feedback actions, a visible version badge, and a verified in-app update flow.

#### Added

- Added Canvas logout that removes only the token from the operating-system credential store.
- Added update checks, verified downloads, and opening of the normal OS installer from the official manifest.
- Added a visible application version badge.

#### Changed

- Both feedback entries now prefer a pre-addressed Gmail compose page with default-mail and copy-address fallbacks.

#### Security

- Offline or failed update checks do not block local learning or transmit Canvas tokens or study data.

#### Known issues

- Upgrading from 0.2.8 to 0.2.9 requires one final manual install.
- Installers remain unsigned beta canaries.

[View GitHub Release](https://github.com/Zzz-zzZ147/canvas-learning-center/releases/tag/v0.2.9)

## 0.2.8 — 2026-08-23

### Source-backed knowledge drafts and feedback fallbacks

Generated reviewable drafts from local teaching sources and replaced unreliable packaged-WebView mail links.

#### Added

- Added conservative PDF, HTML, PPTX, Markdown, and text extraction for reviewable knowledge drafts.
- Displayed local material locations beside unit sources.

#### Changed

- Unconfirmed drafts stay out of mastery, Today, and review queues.

#### Fixed

- Added default-mail, Gmail web, and copy-address feedback fallbacks.

#### Known issues

- Installers remain unsigned beta canaries.

[View GitHub Release](https://github.com/Zzz-zzZ147/canvas-learning-center/releases/tag/v0.2.8)

## 0.2.7 — 2026-08-23

### Installer identity and current-course filtering

Aligned macOS installer version metadata and prevented old courses or long titles from breaking the dashboard.

#### Added

- Added release gates for macOS PKG and Windows MSI version identity.

#### Changed

- The dashboard now defaults to the current Canvas teaching term.

#### Fixed

- Fixed stale installer version metadata.
- Fixed long course names breaking the vertical course ribbon.

#### Known issues

- Installers remain unsigned beta canaries.

[View GitHub Release](https://github.com/Zzz-zzZ147/canvas-learning-center/releases/tag/v0.2.7)

## 0.2.6 — 2026-08-23

### Material freshness and local storage locations

Separated assignment checks from material sync and added launch-time and 24-hour incremental refresh gates.

#### Added

- Added launch-time freshness checks and a 24-hour background incremental sync.
- Added visible local storage locations and allowlisted open-folder actions.

#### Changed

- Assignment status checks no longer stand in for PPT, page, and module synchronization.

#### Fixed

- Synchronized accessible Week 4 records without bypassing Canvas permissions.

#### Known issues

- Canvas-restricted content remains explicitly marked and is not bypassed.
- Installers remain unsigned beta canaries.

[View GitHub Release](https://github.com/Zzz-zzZ147/canvas-learning-center/releases/tag/v0.2.6)

## 0.2.5 — 2026-08-23

### Packaged Canvas TLS fix

Made packaged desktop builds use the bundled CA store when connecting to Canvas.

#### Added

- Added a privacy-safe TLS certificate error category to diagnostics.

#### Changed

- Rebuilt Chinese-default and English-default macOS and Windows installers.

#### Fixed

- Fixed packaged macOS builds failing to verify the Canvas certificate.

#### Security

- Tokens remain in the OS credential store and Canvas access stays read-only.

#### Known issues

- Installers remain unsigned beta canaries.

[View GitHub Release](https://github.com/Zzz-zzZ147/canvas-learning-center/releases/tag/v0.2.5)

## 0.2.4 — 2026-08-23

### Privacy-safe diagnostic bundles

Enabled one-click export of allowlisted, privacy-filtered technical diagnostics.

#### Added

- Added one-click diagnostic export to first-run setup and System Status.
- Connection failures now show safe error categories and diagnostic IDs.

#### Changed

- Diagnostics include only platform, Canvas host, aggregate storage, SQLite health, and structured events.

#### Fixed

- Fixed a Windows diagnostic-log lifecycle issue.

#### Security

- Diagnostic bundles exclude credentials, identity, course content, notes, submissions, grades, databases, signed URLs, and local paths.

#### Known issues

- Installers remain unsigned beta canaries.

[View GitHub Release](https://github.com/Zzz-zzZ147/canvas-learning-center/releases/tag/v0.2.4)

## 0.2.3 — 2026-08-22

### Bilingual interface and locale-specific installers

Added in-app Chinese/English switching and separate Chinese-default and English-default packages.

#### Added

- Added an in-app EN / 中文 language switch.
- Added Chinese-default and English-default packages for macOS and Windows.
- Added bilingual installation and download instructions.

#### Changed

- Upgrades preserve the user's selected interface language.

#### Security

- Strengthened release metadata and package-integrity checks while keeping Canvas read-only.

#### Known issues

- Installers remain unsigned beta canaries.

[View GitHub Release](https://github.com/Zzz-zzZ147/canvas-learning-center/releases/tag/v0.2.3)

## 0.2.2 — 2026-08-21

### Installation guidance and developer identity

Added plain-text installation guidance, developer attribution, feedback email, and release metadata.

#### Added

- Added TXT installation instructions, third-party notices, checksums, and an in-app feedback entry.

#### Changed

- Standardized developer attribution as ZihengHuang and feedback email as canvas-center@z-hstudio.com.

#### Known issues

- This was an internal beta milestone without public GitHub installer assets.

_Internal beta milestone; no public release asset._
