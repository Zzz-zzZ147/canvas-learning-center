# Canvas Learning Center 0.2.11

Release date: 27 August 2026

## What changed

- Checks the official GitHub release channel when the app starts and every 24
  hours while it remains open.
- Adds an opt-in **Download and verify new installers automatically** setting
  under **System Status → App update**. It is off by default.
- Downloads only the package that matches the current operating system and
  interface language, then verifies its URL, declared size, and SHA-256.
- Keeps installation fully manual. The user must open and confirm the normal
  macOS or Windows installer.
- Keeps Canvas, course material, and local study records usable when update
  checks or downloads fail.
- Adds the branded startup animation with pointer, keyboard, and reduced-motion
  skip paths.
- Uses the official product name **Canvas Learning Center** without the former
  Sydney beta label.
- Fixes the compatibility channel used by installed 0.2.10 clients after the
  public GitHub repository migration.

## Important limitation

These packages do not yet have Apple Developer ID or Windows Authenticode
signatures. Their filenames therefore continue to contain `UNSIGNED-CANARY`, and
macOS Gatekeeper or Windows SmartScreen may show a warning. Download only from
the official GitHub Release and verify the SHA-256 before installing.
