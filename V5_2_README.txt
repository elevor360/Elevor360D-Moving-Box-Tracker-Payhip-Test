Elevor360D Moving Box Tracker V5.2 - automatic reopening fix

Changes:
- After first activation, saved licence is checked on opening.
- If server verification returns false, the app automatically retries activation using the saved licence.
- Offline opening remains available for previously activated customers.
- Updated service worker cache and versioned licence script reference.
- Service worker now only removes this app family's old caches.

Install: Upload/replace all files in the GitHub Pages repository root, commit, and wait for Pages deployment. Keep browser storage; do not clear site data.

No Payhip or Cloudflare changes required.
