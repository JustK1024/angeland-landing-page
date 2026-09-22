# Angeland Kareta Falls Nature Park

Static HTML, CSS and vanilla JavaScript landing site based on the supplied 38-page 2026 rates brochure.

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server` from this folder and visit the shown local URL.

## Structure

- `index.html` - content and semantic page structure
- `css/styles.css` - responsive presentation
- `js/script.js` - menu, filters and accessible map modal
- `assets/images/` - selected brochure-derived imagery and maps

## Updating content

Update rates, contacts, map links, Facebook links, or developer credits directly in `index.html`. Replace any image in `assets/images/` while preserving its filename, or update its matching `src`.

## Deploy

For Firebase Hosting: install Firebase CLI, run `firebase login`, `firebase init hosting` (set this folder as public), then `firebase deploy`.

For GitHub Pages: push this folder to a repository, then enable **Settings → Pages → Deploy from a branch**, selecting the branch root. Embed the published HTTPS URL in Google Sites via **Insert → Embed → By URL**.

## Verification notes

All displayed pricing and schedules were manually cross-checked with the source brochure. The Google Maps and Facebook URLs were added from owner-provided links. All room/cottage rates are separate from entrance and other fees. No external imagery or third-party dependencies are used.
