SHIM VISION - standalone phone app

Files (keep them together in one folder):
  index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, icon-maskable-512.png, apple-touch-icon.png

1. Host the folder on any HTTPS web address (GitHub Pages steps are in the chat).
2. Open the address on your phone once, then Add to Home Screen.
3. After the first load it works offline. Measurements, settings and the log stay on that phone.
To update: replace index.html (and bump VERSION in sw.js). The app picks up the change the next time it opens online.
