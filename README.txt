STUDY TRACKER FREE — VERSION 2

CONTENTS
- index.html: complete app
- manifest.webmanifest: installable PWA metadata
- sw.js: offline service worker
- icon-192.png and icon-512.png: Android/Chrome install icons

PUBLISH ON GITHUB PAGES
1. Extract this ZIP.
2. Upload every file directly into the ROOT of your new study-tracker-free repository (not inside a subfolder).
3. Open repository Settings > Pages.
4. Under Build and deployment choose Deploy from a branch; select main and /(root), then Save.
5. Wait for the Pages deployment to finish. Open the HTTPS Pages URL in Chrome and refresh once.

INSTALL ON ANDROID
- Use the app's Install App button if Chrome provides the install prompt.
- Otherwise open Chrome menu (three dots) > Install app. The menu wording can vary by Chrome version.
- If the option is absent, confirm the site is HTTPS, all five package assets are at repository root, and the service worker has loaded; then refresh and try again.

DATA
Study data is stored locally in this browser. Export JSON backups from Settings. Screen-time values are entered manually; the app does not monitor device-wide screen usage automatically.
