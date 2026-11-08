# NoteNest PWA

## Features
- Rich-text notes (bold, italic, underline, lists)
- Folders, search, note colours
- Add images (up to 5 MB each)
- IndexedDB storage on this device
- Export/import JSON backups for manual Google Drive upload
- Print a note or save it as PDF
- Dark/light themes
- Installable PWA with offline app shell

## Install on Android
A Progressive Web App must be served from HTTPS (or localhost) for Chrome to install it and use its service worker. Opening `index.html` directly as a `file://` file will not enable installation/offline PWA caching.

1. Publish the contents of this folder to an HTTPS static host (for example GitHub Pages).
2. Open the published site in Chrome on your Android tablet.
3. Open Chrome menu (⋮) → **Install app** or **Add to Home screen**.
4. Launch NoteNest from the new home-screen icon.

## Google Drive manual backup
In NoteNest, tap the down-arrow backup button to download a `.json` backup. Upload that file to Google Drive. To restore, download the backup from Drive and tap the up-arrow button in NoteNest.

## Important
Notes and images are stored locally in the browser on this device. They do not automatically sync between devices. Keep Drive backups current. Clearing browser site data can erase local notes.
