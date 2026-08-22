# Canvas Learning Center 0.2.3 — bilingual public beta

**Release date:** 22 August 2026

This is the first conservatively published GitHub beta for Canvas Learning
Center. The public repository contains product information, documentation,
support channels, a privacy-safe demo screenshot, and release downloads. The
complete application source code is not publicly distributed.

## Choose your installer

### macOS 13 or later

- English on first launch: `CanvasLearningCenter-0.2.3-macOS-universal-en-UNSIGNED-CANARY.pkg`
- 中文首次启动: `CanvasLearningCenter-0.2.3-macOS-universal-zh-CN-UNSIGNED-CANARY.pkg`

Both macOS packages are universal packages for Apple Silicon and Intel.

### Windows 11 x64

- English on first launch: `CanvasLearningCenter-0.2.3-Windows-x64-en-UNSIGNED-CANARY.msi`
- 中文首次启动: `CanvasLearningCenter-0.2.3-Windows-x64-zh-CN-UNSIGNED-CANARY.msi`

All four packages have the same features. Use `EN / 中文` inside the app to
switch language at any time.

## Main capabilities

- Today Top 3 priorities and next-step planning
- Assignment Guard for submitted, upcoming, at-risk, and manual-check items
- Course, module, topic, and knowledge-point progress
- Active recall with staged hints, weak-topic markers, answers, and sources
- Local file inbox and personal knowledge library
- Read-only Canvas connection and local-first learning data

## Changes in 0.2.3

- Added in-app Chinese/English switching.
- Added separate English-default and Chinese-default installers.
- Preserved a saved language choice when upgrading.
- Added bilingual download and installation documentation.
- Strengthened package metadata and integrity checks.

## Install

1. Download the correct `.pkg` or `.msi` from **Assets** below.
2. Download `SHA256SUMS.txt` and verify the installer checksum.
3. Follow the repository's [installation guide](https://github.com/Zzz-zzZ147/canvas-learning-center/blob/main/docs/INSTALLATION.md).
4. Create your own Canvas Access Token from your institution's Canvas settings.
5. Paste the token only into the app, confirm discovered courses, and start the
   first read-only sync.

Never send a Canvas token through GitHub Issues, email, comments, screenshots,
or chat.

## Known issues and limitations

- **Unsigned packages:** every installer is marked `UNSIGNED-CANARY`. The macOS
  package is not Apple-notarized and the Windows MSI does not have a trusted
  Microsoft code signature. Gatekeeper or SmartScreen may warn or block it.
- The beta has been tested primarily with University of Sydney's Canvas
  environment. Other institutions may require additional compatibility work.
- Restricted or unpublished Canvas content cannot be bypassed.
- External learning systems may appear as links rather than offline downloads.
- Knowledge topics and reference answers require source verification.
- Official Canvas remains the final authority for deadlines and submissions.

## Safety and status

This is an independent beta by ZihengHuang, not an official Instructure or
University of Sydney product. The application does not submit assignments or
modify Canvas content.

Feedback and school adaptation: **canvas-center@z-hstudio.com**
