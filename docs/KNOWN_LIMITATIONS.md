# Known limitations

## Unsigned beta packages

Version 0.2.3 is an `UNSIGNED-CANARY`. The macOS package is not Apple-notarized,
and the Windows MSI does not have a trusted Microsoft code-signing identity.
Gatekeeper or SmartScreen may warn or block it.

## Institution coverage

The current real-world beta has been tested primarily against University of
Sydney's Canvas environment. Other institutions can change Canvas hostnames,
API access, Access Token availability, and course permissions.

## Canvas permissions

- Unpublished, restricted, or institution-blocked content cannot be downloaded.
- A partial sync is reported as partial; it is not presented as a complete copy.
- External systems such as lecture recording, Studio, or discussion platforms
  may be indexed as links rather than downloaded.

## Learning content

- Knowledge topics and reference answers require source checking.
- Courses without a verified knowledge structure show that the structure is pending.
- Runtime paid-model automation is not enabled in this beta.

## Final authority

Always use the official Canvas page to confirm deadlines, submission receipts,
course announcements, and assessment requirements.
