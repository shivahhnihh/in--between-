IN BETWEEN — personal memory app
====================================

Version 1 includes:
- Your selected IN BETWEEN logo and splash screen
- "For everything I felt, lived, and loved." tagline
- A lively mobile-first home layout
- Add memories with date, place, feeling, writing and photo
- Local browser storage for saved memories
- Memory archive and "Today, I felt..." surface
- PWA manifest + service worker for installable/offline-capable hosting

IMPORTANT:
Opening index.html directly is useful for previewing, but browser security rules mean
the full PWA installation experience requires the app to be served from HTTPS (or localhost).
After hosting the folder on an HTTPS site, open it in Chrome on Android and use
"Install app" / "Add to Home screen."

Privacy:
This first version stores memories in the browser's local storage. It does not upload
them to a server. Clearing browser/app data can remove them, so a later version should
add encrypted backup/export before relying on it for irreplaceable memories.
