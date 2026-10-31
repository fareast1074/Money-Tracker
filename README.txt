MONEY TRACKER — GITHUB PAGES INSTALL PACKAGE

CONTENTS
- index.html: Money Tracker app
- manifest.webmanifest: install metadata and app identity
- sw.js: offline app-shell and runtime cache
- icons/: app icons

PUBLISH WITH GITHUB PAGES
1. On GitHub, create a new public repository named money-tracker (or use an existing repository).
2. Upload all files and folders in this package to the repository root. Keep the folder structure exactly as supplied.
3. Open the repository Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select branch main and folder /(root), then Save.
6. Wait for GitHub Pages to publish. Your site URL will look like:
   https://YOUR-USERNAME.github.io/money-tracker/
7. Open that HTTPS URL in Chrome on your Android phone while online. Wait for the page to finish loading, then reload once so the service worker controls the page.
8. Tap Chrome menu (⋮) > Install app. If Chrome says Add to Home screen instead, choose that.

IMPORTANT
- Do not open index.html directly from Downloads. PWA installation requires HTTPS or localhost.
- Data is saved in browser LocalStorage on that device/browser. It does not automatically sync between devices.
- External Tailwind, Chart.js and Google Fonts are cached after being loaded online; the first visit requires internet.
- Export a JSON backup from Settings before clearing browser data.
