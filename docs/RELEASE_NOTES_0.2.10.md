# Canvas Learning Center 0.2.10

**Release date:** 24 August 2026  
**Feedback:** canvas-center@z-hstudio.com

## What changed

- Added **System Status → Version history** for offline access to the current
  and previous release records.
- Each release shows its date, change categories, known limitations, and link to
  the official GitHub Release when one exists.
- The history follows the app's `EN / 中文` language setting.
- The in-app bilingual history and public `CHANGELOG.md` are now generated from
  one structured release record, with a release check that detects drift.
- Packaged history contains no Canvas token, local path, course material, or
  personal learning data.

## Upgrading

Users on 0.2.9 can open **System Status → App update** to check, download, verify,
and open the 0.2.10 installer. Installation still requires explicit confirmation
in the normal macOS or Windows installer.

## Important beta boundary

These files remain `UNSIGNED-CANARY` packages. Gatekeeper or SmartScreen may
display a warning, and the app never installs an update silently.
