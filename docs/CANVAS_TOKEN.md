# Create and protect your Canvas Access Token

Canvas Learning Center does not ship with a shared school login. Every user must
create and enter their own Canvas Access Token.

## Create a token

The exact wording can vary by institution:

1. Sign in to your institution's official Canvas website in your browser.
2. Open **Account → Settings**.
3. Find **Approved Integrations**.
4. Select **New Access Token**.
5. Use a clear purpose such as `Canvas Learning Center`.
6. Choose a reasonable expiry date.
7. Create the token and copy it immediately.
8. Paste it only into Canvas Learning Center's setup screen.

Some institutions disable personal Access Tokens. If the button is unavailable,
the app cannot bypass that policy; contact your institution or report the school
environment through GitHub Issues without sharing private account information.

## Treat the token like a password

- Never paste it into a GitHub Issue, email, comment, screenshot, or chat.
- Do not store it in a text file, browser bookmark, source code, or URL.
- Revoke it immediately in Canvas if you believe it was exposed.
- Create a replacement token instead of reusing a leaked one.

The application uses the token only for its read-only Canvas requests, but the
token itself may carry the authority of your Canvas account. Protect it even if
the app reports a read-only connection.

## Revoke or replace a token

Return to **Canvas → Account → Settings → Approved Integrations**, locate the
token, and remove it. Then create a new token and reconnect the app.

## What the app does not do

Canvas Learning Center does not use the token to submit assignments, edit
courses, mark modules complete, send messages, or change Canvas settings.
