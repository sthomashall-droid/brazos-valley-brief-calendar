# Brazos Valley Brief — Public Calendar

Static hosting for the Brazos Valley Brief meetings calendar. This is a **public, standalone** repo on purpose: it holds only the calendar feed and its landing page, never the editorial drafts, tracker, or notes from the main (private, local) project.

## Contents

- `BV-Calendar.ics` — the calendar feed. Overwrite this file in place each week; the URL never changes, so subscribers stay current.
- `index.html` — a landing page with Apple / Google / Outlook subscribe buttons. It builds every link from its own URL, so nothing here needs editing when the repo name or username changes.

## Published URLs (once GitHub Pages is on)

- Landing page: `https://<USERNAME>.github.io/<REPO>/`
- Feed: `https://<USERNAME>.github.io/<REPO>/BV-Calendar.ics`
- Subscribe (Apple/iPhone): `webcal://<USERNAME>.github.io/<REPO>/BV-Calendar.ics`

## Weekly update

Replace `BV-Calendar.ics` with the freshly generated file from the main project and commit. The publish step is human-approved by design; it is not part of any unattended run.
