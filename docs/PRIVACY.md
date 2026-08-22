# Privacy

Canvas Learning Center is designed as a local-first desktop application.

## Stored locally

- selected courses and downloaded course resources;
- assignment status snapshots used by Assignment Guard;
- knowledge topics, progress, review history, and personal notes;
- user-imported files and extracted local search text; and
- sync status and non-sensitive diagnostic records.

## Credential storage

The Canvas Access Token is stored in macOS Keychain or Windows Credential
Manager. It should not be stored in the app database, logs, URLs, release files,
or this repository.

## Current Canvas scope

The app uses read-only Canvas requests. It does not submit work, modify courses,
send messages, or mark content complete. Restricted and unpublished resources
remain inaccessible.

Grades, teacher feedback, quiz responses, personal submission files, and other
students' information are outside the intended sync scope.

## Network and analytics

The local interface is bound to your own computer. The released app does not
include a third-party analytics or advertising SDK. External Canvas pages and
links open through your normal browser.

## User responsibility

Only connect an account and download material you are authorised to access.
Course material is for personal study and must not be republished or shared
without permission.
