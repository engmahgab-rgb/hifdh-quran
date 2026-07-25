HIFDH PWA

FILES
- index.html: application, including the embedded Quran corpus parsed from the user's uploaded source.
- manifest.webmanifest: install metadata.
- sw.js: offline cache/service worker.
- icon-192.png / icon-512.png: app icons.

IMPORTANT
A PWA must be served over HTTPS (or localhost). Opening index.html directly as a file will not enable the service worker/install behavior.

QUICK LOCAL TEST
1. Unzip this folder.
2. In the folder run:
   python3 -m http.server 8080
3. Open http://localhost:8080 in a browser.

IPHONE INSTALL
After deploying the folder to any HTTPS static host, open its URL in Safari, tap Share, then Add to Home Screen.

QURAN DATA INTEGRITY
The app preserves the existing source warning: the uploaded document parsed 6,235 numbered Ayahs and 113/114 Surah counts validated. Al-Hijr 15:99 is not silently reconstructed.

V2: Quran tab now has explicit Surah/Ayah controls, previous/next navigation, Start Memorizing From Here, and Add to Revision.
