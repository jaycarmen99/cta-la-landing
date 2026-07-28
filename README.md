# CTA BLACK - Los Angeles Application

Landing page for Circuit Training Academy's LA masterclass application flow.

## Setup

The Google Sheet integration is already wired to a deployed Apps Script endpoint
in `CONFIG.SHEET_ENDPOINT_URL` inside `index.html`. See the project's
`CTA_LA_AppsScript.gs` file for the backing script and setup steps if you ever
need to redeploy it.

## Optional: mark logo

Drop a file named `cta-ring-logo.gif` next to `index.html` to show the ring
logo next to "CTA" in the top-left corner. It's optional - the page hides it
gracefully if the file isn't present.
