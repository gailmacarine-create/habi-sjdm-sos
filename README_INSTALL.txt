HABI SJDM SOS — INSTALLABLE APP PACKAGE

Included:
- HABI_User_PWA/: User app (index.html), PWA manifest, service worker, and HABI logo icons.
- HABI_Admin_PWA/: Admin app (index.html), PWA manifest, service worker, and the same HABI logo icons.

IMPORTANT DEPLOYMENT NOTES
1. Publish both folders on an HTTPS host (for example, Firebase Hosting). PWA installation will not work reliably by opening index.html directly from a computer.
2. Keep each folder and its manifest.json, service-worker.js, and icons/ folder together.
3. User app URL will be the deployed /HABI_User_PWA/ path; Admin app URL will be /HABI_Admin_PWA/.
4. Firebase Authentication authorized domains must include the hosting domain.
5. The app shell can be cached, but sign-in, Firestore reports, login history, and other Firebase-backed features still require an internet connection.
6. iPhone/iPad: open the deployed app in Safari (or supported browser), Share > Add to Home Screen. Android: Chrome menu > Install app/Add to Home Screen. Windows/macOS: use the browser Install option.

The icons are generated from the exact logo embedded in the existing HABI User app. Existing app content and Firebase configuration are retained.
