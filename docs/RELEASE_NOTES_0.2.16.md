# Canvas Learning Center 0.2.16

Release date: 5 September 2026

This release brings the changes since public version 0.2.11 together, including
multi-institution setup, first-sync fixes and a complete English learning flow.

## Highlights

- Choose Sydney, UTS or another institution's Canvas address before connecting.
  Settings links, token validation, courses and local data follow that school.
- Fixed first course selection not starting material sync, empty assignment
  views before course metadata arrived, and optional requests leaving controls busy.
- Simplified course ribbons and removed repeated course codes and truncated labels.
- English now covers the existing 16-topic knowledge pack: concepts, outlines,
  keywords, questions, two-stage hints and reference answers, as well as interface
  labels, status explanations, editors, search and feedback.
- Progress-only edits do not overwrite the original content with a translation.
  Original notes and source documents are preserved.
- First-run version/update controls, shorter update settings and privacy-filtered
  diagnostics help users troubleshoot without sharing their token.
- Optional paired companion sync is separate from normal desktop use and excludes
  tokens, raw course files, private notes and unconfirmed knowledge drafts.

## Downloads and installation

Choose macOS 13+ universal (Apple Silicon / Intel) or Windows 11 x64, then choose
English (`en`) or Chinese (`zh-CN`) for first launch. Both can switch language.
Expand **Assets** on this Release and download `.pkg` for Mac or `.msi` for Windows.
Do not download the automatically generated **Source code** archives to install.

See [the installation guide](https://github.com/z-hstudio/canvas-learning-center/blob/main/docs/INSTALLATION.md). A plain-text `INSTALLATION.txt`
and SHA-256 checksums are also attached to the Release. Existing users can use
the in-app update check; installing the downloaded update is always manual.

## Verification and known limitations

- Local macOS acceptance: 232 Python tests; browser regression coverage for seven
  pages and complete recall flows; installed-app audit of 109 topics with no
  unexpected Chinese UI residue. These checks are not a universal compatibility guarantee.
- Windows CI builds both language variants and runs the test suite, version,
  checksum and payload checks. Clean Windows 11 and separate Intel Mac device
  acceptance remain outstanding.
- Installers are explicitly **UNSIGNED-CANARY**. There is no Developer ID /
  Apple notarization or trusted Windows code-signing certificate. Operating-system
  security warnings may appear; do not disable system-wide security protections.
- Restricted Canvas content remains partial. External tools and recordings may
  be links only. No guarantee of support for every school or course.
- Original documents and personal notes keep their original language. Custom
  content without an English translation is clearly labelled; it is not guessed.
- The accepted packages retain the pre-publication offline history snapshot;
  this page is authoritative for publication status.

Canvas requests remain read-only. The app never submits work for you. Never post
tokens, course files or personal study data in GitHub Issues.

Developed by **ZihengHuang** · **Manyousang Z**

Feedback: **canvas-center@z-hstudio.com**

Not an official product of Instructure, University of Sydney, UTS or any university.
Free for personal educational use; source code is not publicly distributed.
