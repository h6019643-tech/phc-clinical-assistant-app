PHC CLINICAL ASSISTANT V3.6 — PWA PACKAGE

This package is ready to publish as a Progressive Web App (PWA).
It is not yet hosted; a public HTTPS web address is required for Chrome installation.

FREE HOSTING OPTION (GitHub Pages):
1. Create/sign in to a GitHub account.
2. Create a new PUBLIC repository, for example: phc-clinical-assistant.
3. Upload all five files from this folder to the repository root:
   index.html, manifest.webmanifest, service-worker.js, icon-192.png, icon-512.png
4. In repository Settings > Pages, choose deploy from branch, select main and /(root), then Save.
5. Wait for GitHub Pages to publish the HTTPS address.
6. Open that address in Chrome on Android, allow the first load to finish, then use Chrome menu > Install app / Add to Home screen.
7. Open once while online so the service worker caches the app. Then test in airplane mode.

IMPORTANT:
- The first visit and installation require internet.
- Offline availability depends on successful service-worker caching.
- Patient/stock data stored by the app remains local to that browser/app installation.
- Export/backup patient and stock data regularly; clearing Chrome/site data may erase local records.
- This package has not been hosted or tested on a physical phone.
- Before clinical deployment, verify all screens, data persistence, backup/restore and prescription printing.
