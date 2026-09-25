P04 OFFLINE PWA — BUILD PACKAGE

Baseline: P03E5 = PASS.

IMPORTANT:
This package is structurally ready for offline PWA, but TWO required local PDF.js
files are intentionally NOT faked:
- pdf.min.mjs
- pdf.worker.min.mjs

Use exact PDF.js version 4.10.38 for both files.
Official/cdnjs listing confirms both files exist for 4.10.38.

Once those two files are placed beside index.html, upload ALL files in this folder
to the same GitHub Pages directory. Open index.html online once and allow the
service worker to cache the app. Then test airplane mode.

Do not declare OFFLINE PASS until airplane-mode test succeeds on iPhone.
