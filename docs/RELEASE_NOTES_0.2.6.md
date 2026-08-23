# Canvas Learning Center 0.2.6

Release date: 23 August 2026

## Fixed

- Course PPT, Canvas page, and module synchronization is now reported separately
  from assignment-submission checks.
- The desktop app checks for stale material on launch. When proactive reminders
  are enabled, the background helper ensures an incremental material refresh at
  least every 24 hours.
- Both Feedback buttons now use a local system-mail bridge with a visible copy-
  address fallback.
- Course and personal-library views now show the real local storage location and
  provide an allowlisted Open folder action.

## Safety boundary

- Canvas access remains restricted to the application's predefined read-only GET
  requests. The app does not submit assignments or modify courses.
- Restricted and unpublished Canvas items remain reported as unavailable; the app
  does not bypass institution permissions.
- The packages remain explicitly labelled `UNSIGNED-CANARY` and are not formally
  signed or notarized.
