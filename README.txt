MY GOLF SCORECARD — PWA
===========================

Files:
- index.html
- manifest.webmanifest
- service-worker.js
- icon-180.png
- icon-192.png
- icon-512.png

IMPORTANT:
A Progressive Web App must be served from HTTPS (or localhost) to install and use its
service worker. Opening index.html directly from the iPhone Files app will let you view
the page, but it will not provide the full "Add to Home Screen" PWA behavior.

EASIEST INSTALL ON IPHONE:
1. Upload this folder to an HTTPS web host.
2. Open the HTTPS address in Safari on your iPhone.
3. Tap Share.
4. Tap "Add to Home Screen".
5. Tap "Add".
6. Launch "My Golf Scorecard" from the Home Screen.

The app stores saved rounds in the browser/device using localStorage. Clearing Safari
website data can remove those saved rounds.

This version includes:
- 1-player or flight mode (up to 4 golfers)
- Malarayat combinations, Summit Point and Fernando Air Base
- 18-hole score entry
- handicap field
- Stroke Play / Stableford selection
- front 9, back 9, total and to-par
- putt tracking
- local round history
- share scorecard
- offline caching after first load
