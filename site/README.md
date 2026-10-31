# Housecall website

A one-page site plus the privacy policy, with no build step and no external scripts.

**Before publishing**, replace these placeholders:
- `YOUR_APP_ID` (in the `apple-itunes-app` tag): the App Store ID
- the App Store button's `href="#"`: your App Store link. Swap the button for Apple's official "Download on the App Store" badge from the [App Store marketing guidelines](https://developer.apple.com/app-store/marketing/guidelines/).
- `YOUR_CONTACT_EMAIL`, and `[DATE]` in `privacy.html`

**To publish on GitHub Pages (free):**
1. `.github/workflows/pages.yml` deploys this folder on every push to `main` that touches `site/`.
2. One-time setup: in the repo's Settings › Pages, set Source to "GitHub Actions".
3. Your privacy URL becomes `https://<you>.github.io/<repo>/privacy.html`. Put it in `Monetisation.Links.privacy` and in App Store Connect.

The images come from `design/screenshots/raw/`. Recapture with the scripts there if the app changes.
