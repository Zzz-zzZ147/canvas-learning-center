# Canvas Learning Center 0.2.7

Release date: 23 August 2026

## Fixed

- All macOS installer identity fields now report 0.2.7 consistently, including
  the welcome page, Distribution, component package, application bundle, and
  installed application.
- The dashboard now defaults to courses in the current Canvas teaching term,
  instead of mixing in old courses, portal shells, or exam containers. Existing
  historical local data is retained and is not deleted.
- Long Canvas course names are shortened safely in the vertical course ribbon.
- Both Feedback links now use the operating system's native email handler
  directly. The address is also copied as a fallback.

## Release checks

- The complete private test suite passed.
- macOS PKG metadata was inspected after packaging.
- Windows MSI `ProductVersion` is inspected on the Windows build runner.
- Packaged payloads are checked for private data, source maps, and local paths.

## Important limitation

These installers are still `UNSIGNED-CANARY` beta packages. They do not yet have
Apple notarization or a Microsoft code-signing certificate, so Gatekeeper or
SmartScreen may warn or block installation.

Version 0.2.6 is superseded. Please use 0.2.7.
