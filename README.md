# Michigan EA website

A static four-page website for GitHub Pages. No install, build step, external fonts, or framework is required.

## Publish

Upload index.html, about.html, events.html, contact.html, styles.css, script.js, and favicon_ea.png to the root of the existing repository, replacing the corresponding files. Keep any existing CNAME or GitHub configuration files. Under Settings → Pages, publish main / (root). Keep the custom domain set to umichea.org.

## Update content

- Homepage: index.html
- Fellowship and cause areas: about.html
- Meeting information: events.html (also update index.html and contact.html when the weekly schedule changes)
- Contact details and existing Formspree form: contact.html
- Shared styling: styles.css
- Mobile navigation: script.js

The existing fellowship URL and Formspree endpoint are preserved. The form uses a native POST; delivery depends on the existing Formspree account. No test messages were sent.

## Redesign notes

Rebuilt all four pages with responsive layouts, local system fonts, keyboard focus indicators, a skip link, semantic landmarks, and mobile navigation that remains usable without JavaScript. Removed placeholder organizer profiles and September dates labeled as upcoming. Preserved the supplied favicon, email, meeting time, fellowship link, and form endpoint.

Validation: checked HTML tag nesting, landmarks, and unique IDs with Python’s HTML parser; checked local links, fragment targets, and JavaScript syntax. Browser rendering and live form delivery have not been tested.
