# Canvas Learning Center 0.2.5 — packaged Canvas connection hotfix

**Release date:** 23 August 2026  
**Developer:** ZihengHuang  
**Feedback:** canvas-center@z-hstudio.com

## What changed

- Fixed a certificate-authority configuration problem that could make the packaged macOS app report `internal_error` even when the Canvas token was valid.
- Added a dedicated, privacy-safe TLS certificate error category to exported diagnostics.
- Rebuilt both first-launch languages for macOS and Windows.
- Preserved the read-only Canvas boundary and operating-system credential storage.

Users affected by the 0.2.4 connection failure should install 0.2.5 over the
existing version and try the same token again. A new token is normally not
required unless the old token was exposed or revoked.

All installers remain explicitly labelled `UNSIGNED-CANARY`. They are not
formally signed or notarized and may be warned about or blocked by Gatekeeper or
SmartScreen. Windows packages passed the project CI build and package audit, but
this release is not a claim of clean-machine installation certification.

This is an independent beta, not an official Instructure or University of
Sydney product.
