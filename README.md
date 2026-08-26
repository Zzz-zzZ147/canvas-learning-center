# Canvas Learning Center

**A local-first learning operations layer for students who use Canvas.**

Canvas tells you what exists in a course. Canvas Learning Center helps you see
what to do today, whether an assignment may have been missed, how far you have
studied, and which knowledge points still need review.

> Independently developed by **ZihengHuang** (social: **Manyousang Z**).
> Not affiliated with or endorsed by Instructure, University of Sydney, or any
> other educational institution.

![Canvas Learning Center dashboard using demo data](screenshots/dashboard-demo.png)

*The screenshot uses fictional demo courses and tasks. It contains no student
account or institutional data.*

## Download

Current public release: **0.2.11 — 27 August 2026**

Choose the package whose first-launch language you prefer. Both editions have
the same features and can switch language at any time using the language button
in the top-right corner.

| Platform | First-launch language | Download |
|---|---|---|
| macOS 13+ (Apple Silicon and Intel) | English | [Download macOS English](https://github.com/z-hstudio/canvas-learning-center/releases/download/v0.2.11/CanvasLearningCenter-0.2.11-macOS-universal-en-UNSIGNED-CANARY.pkg) |
| macOS 13+ (Apple Silicon and Intel) | Chinese | [Download macOS Chinese](https://github.com/z-hstudio/canvas-learning-center/releases/download/v0.2.11/CanvasLearningCenter-0.2.11-macOS-universal-zh-CN-UNSIGNED-CANARY.pkg) |
| Windows 11 x64 | English | [Download Windows English](https://github.com/z-hstudio/canvas-learning-center/releases/download/v0.2.11/CanvasLearningCenter-0.2.11-Windows-x64-en-UNSIGNED-CANARY.msi) |
| Windows 11 x64 | Chinese | [Download Windows Chinese](https://github.com/z-hstudio/canvas-learning-center/releases/download/v0.2.11/CanvasLearningCenter-0.2.11-Windows-x64-zh-CN-UNSIGNED-CANARY.msi) |

[View the complete v0.2.11 release](https://github.com/z-hstudio/canvas-learning-center/releases/tag/v0.2.11)
· [Installation guide](docs/INSTALLATION.md)
· [SHA-256 checksums](https://github.com/z-hstudio/canvas-learning-center/releases/download/v0.2.11/SHA256SUMS.txt)

> **Unsigned package warning:** all 0.2.11 installers are explicitly marked
> `UNSIGNED-CANARY`. They are not yet signed or notarized by Apple or Microsoft,
> so Gatekeeper or SmartScreen may show a warning or block installation. Read
> the installation guide and verify the checksum before continuing.

## Start here

1. Open the [v0.2.11 Releases page](https://github.com/z-hstudio/canvas-learning-center/releases/tag/v0.2.11).
2. Download the installer for your operating system and preferred first-launch language.
3. Follow the [macOS or Windows installation steps](docs/INSTALLATION.md).
4. Sign in to your own institution's Canvas website and create your own Access Token.
5. Paste the token into the app once. Never send it by email or post it in an Issue.
6. Confirm the courses discovered by the app and begin the first read-only sync.

For the full token walkthrough, read [Create and protect your Canvas Access Token](docs/CANVAS_TOKEN.md).

## What it helps with

### Know what to do today

- A focused **Today Top 3** action list
- Upcoming assignments, study tasks, and due reviews in one view
- A next-step queue based on current coursework and review progress

### Check whether an assignment needs attention

- **Assignment Guard** separates submitted, upcoming, at-risk, and manual-check items
- Direct links open the official Canvas page for final confirmation or submission
- The app never submits work on your behalf

### See what you have learned — and what is still weak

- Course → module → topic → knowledge-point structure
- Local, source-backed draft generation for learning units whose knowledge
  structure has not been created yet
- Separate learning coverage and current mastery indicators
- Active recall with two-stage hints, reference answers, and source links
- Weak-topic markers and review scheduling

Automatic drafts are built only from locally synchronized PDF, HTML, PPTX, or
text material. They remain outside progress, recommendations, and review queues
until the student checks the source and confirms them.

### Keep local learning material organised

- A file inbox for downloaded course material
- A personal knowledge library for user-added notes and files
- Local search and links between files, courses, modules, and knowledge points
- Visible local storage paths with a safe **Open folder** action

### Keep accessible Canvas material current

- Separates assignment-status checks from PPT/page/module sync status
- Checks for stale material whenever the desktop app opens
- After proactive reminders are enabled, performs an hourly background check and
  ensures a read-only incremental material refresh at least every 24 hours

### Update without finding the installer again

- Version 0.2.11 checks the official release channel on launch and every 24
  hours while the app remains open.
- Users can choose whether the matching installer is downloaded and verified in
  the background. This option is off by default.
- Installation is always manual: the app never runs an installer or changes the
  installed version without the user's operating-system confirmation.
- Installed 0.2.10 clients can discover 0.2.11, but the one-time 0.2.10 → 0.2.11
  transition must be installed from this Release page because the old client
  cannot safely follow GitHub's repository-rename download redirect. Versions
  from 0.2.11 onward use the stable `z-hstudio` update channel.
- An offline or failed check does not block local learning features.

### See what changed in each version

- **System Status → Version history** lists this release and earlier changes.
- The bilingual in-app history and this repository's [CHANGELOG](CHANGELOG.md)
  are generated from the same structured release record.
- Changing the app language also changes the displayed release history; the
  packaged history remains available offline.

## Privacy and trust

- Canvas access is **read-only in the application**. The app does not modify a
  course, mark modules complete, send messages, or submit assignments.
- Your Canvas token is stored in the operating system credential store, not in
  this repository, the local database, a URL, or an analytics service.
- Learning data stays on your computer. No analytics or tracking SDK is included.
- Restricted or unpublished Canvas content is not bypassed.
- Grades, teacher feedback, quiz answers, and personal submission files are not
  part of the current sync scope.

Important: a Canvas Access Token is still a powerful credential. Treat it like a
password even though this app only uses read-only requests. See the full
[privacy statement](docs/PRIVACY.md).

## Platform and institution support

- macOS 13 or later: Apple Silicon and Intel
- Windows 11: x64
- The current release has been validated primarily with University of Sydney's
  Canvas environment. Other Canvas institutions may configure APIs and Access
  Tokens differently and may need additional compatibility work.

See [Known limitations](docs/KNOWN_LIMITATIONS.md) before installing.

## Feedback and institution support

If the app cannot connect or sync, use **Export to Downloads** on the first-run
page or under **System Status**, then email the generated diagnostic ZIP. It
contains privacy-filtered technical state and error identifiers—not credentials,
names, course content, notes, submissions, grades, databases, or local paths.

- [Report a bug](https://github.com/z-hstudio/canvas-learning-center/issues/new?template=bug_report.yml)
- [Suggest a feature](https://github.com/z-hstudio/canvas-learning-center/issues/new?template=feature_request.yml)
- Private or security-sensitive feedback: **canvas-center@z-hstudio.com**

Inside the app, both **Feedback** and **System Status → Contact developer** open
a pre-addressed Gmail compose page on the first click. Default-mail and
copy-address options remain available as fallbacks.

Do not include tokens, signed URLs, student IDs, grades, teacher comments,
course files, or other private information in a public Issue.

## Distribution and source availability

Canvas Learning Center is **free to download and use for personal educational
purposes**. The complete source code and internal implementation are currently
not publicly distributed. This repository is a product information, support,
and official download channel; it is not an open-source source repository.

GitHub automatically adds files labelled `Source code (zip)` and
`Source code (tar.gz)` to every Release. In this project those archives contain
only the public documentation, Issue templates, checksum list, and demo image
from this repository — not the application source code.

Copyright © 2026 ZihengHuang. All rights reserved. See [Terms](TERMS.md).

## Documentation

- [Installation and first launch](docs/INSTALLATION.md)
- [Canvas Access Token guide](docs/CANVAS_TOKEN.md)
- [Privacy](docs/PRIVACY.md)
- [Known limitations](docs/KNOWN_LIMITATIONS.md)
- [Changelog](CHANGELOG.md)
- [Security reporting](SECURITY.md)
