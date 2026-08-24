# Canvas Learning Center 0.2.9

**Release date:** 24 August 2026  
**Feedback:** canvas-center@z-hstudio.com

## What changed

- Both Feedback entries now open a pre-addressed Gmail compose page on the first
  click. Default-mail and copy-address options remain available as fallbacks.
- **Log out of Canvas** removes the saved Canvas Token only. Local course files,
  knowledge points, personal notes, progress, and review history are preserved.
- The current application version is visible in the top-left corner.
- **System Status → App update** checks the official GitHub manifest, downloads
  the correct installer for the current operating system and interface language,
  verifies the declared size and SHA-256, and opens the normal OS installer.
- Offline or failed update checks do not block local learning features and do
  not send a Canvas Token, course material, notes, or progress.

## Upgrading

Users on 0.2.8 must manually install 0.2.9 once. After that, future published
versions can be checked and downloaded from inside the app.

## Important beta boundary

These files remain `UNSIGNED-CANARY` packages. The app never silently installs
an update. macOS Installer or Windows Installer still requires user confirmation,
and Gatekeeper or SmartScreen may display a warning.
