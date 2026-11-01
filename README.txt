MY CHAT PWA PROTOTYPE

Files:
- index.html: the app interface
- manifest.json: installable PWA metadata
- sw.js: basic offline app-shell cache

IMPORTANT:
This is a front-end prototype. Chat messages and profile details are stored only in the current browser on this device.
It does NOT provide real accounts, cross-device messaging, push notifications, photo uploads, voice recording, or real voice/video calls.
Do not enter real passwords or sensitive personal information.

To install as a PWA:
1. Upload all three files to an HTTPS static hosting service, keeping them in the same folder.
2. Open the hosted HTTPS address in Chrome on Android.
3. Use Chrome menu > Install app (or Add to Home screen).
4. For iPhone, open the HTTPS address in Safari and use Share > Add to Home Screen.

For real messaging, connect a secure backend (for example Firebase Authentication, Firestore, and Storage) and implement appropriate security rules.
