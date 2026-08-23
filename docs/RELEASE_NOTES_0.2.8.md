# Canvas Learning Center 0.2.8

Released: 23 August 2026

## What changed

- Learning units without confirmed knowledge points can now receive locally
  generated, source-backed drafts after a successful Canvas material sync.
- Drafts include a question, two hints, a provisional source excerpt, and an
  exact page, slide, or section locator when available.
- Drafts are not counted as learning progress and do not enter Today or review
  queues until the student checks and confirms them.
- PDF, HTML, PPTX, Markdown, and plain text are supported. Scanned PDFs,
  restricted sources, external-only links, and insufficient text are reported
  without inventing knowledge points.
- Both Feedback entries now open a visible contact panel with default-mail,
  Gmail web, and copy-address options.
- The course source panel states where local Canvas material is stored and can
  open that folder directly.

## Trust boundary

Canvas access remains read-only. This build does not modify courses or submit
assignments. Automatic knowledge drafts are generated locally from material
already synchronized to the user's device; no paid runtime model is enabled.

## Known issue

All installers are unsigned beta canaries. macOS Gatekeeper or Windows
SmartScreen may warn or block installation. Verify `SHA256SUMS.txt` before use.
