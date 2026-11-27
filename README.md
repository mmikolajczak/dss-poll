# dss-poll

Live audience poll for the Data Science Summit 2026 round table "AI at scale in healthcare".

- `index.html` – participant view (opened from the QR code)
- `present.html` – presenter view (needs the admin key in the URL hash)

The backend is a Google Apps Script web app that stores answers in a private Google Sheet. These static pages call its JSON API without cookies. No keys or answers are stored in this repository.
