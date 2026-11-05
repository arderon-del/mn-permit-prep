Minnesota Permit Prep - installable offline web app

Host these files on any HTTPS web server (GitHub Pages, Netlify, Cloudflare Pages,
or your own server). Service workers require HTTPS, or http://localhost for testing.

Install on Android:
  1. Open the site in Chrome on the phone.
  2. Tap the menu (three dots) > Add to Home screen > Install.
  3. Open it once while online; after that it works offline.

Progress is stored on the phone in the browser's local storage.
To update questions, edit the Q array in index.html and bump CACHE in sw.js
(e.g. mn-permit-v2) so phones pick up the new version.
