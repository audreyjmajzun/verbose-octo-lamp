Lift Log for GitHub Pages
=========================
Upload ALL of these files into the same folder of your GitHub repo (replace your old page):

  index.html             the app (rename isn't needed; keep it as index.html)
  manifest.webmanifest   app name, icon, full-screen setting
  sw.js                  lets the app open offline at the gym
  icon-180.png           iPhone/iPad Home Screen icon (the hibiscus)
  icon-192.png, icon-512.png, icon-maskable-512.png   icons for other devices

If your old page had a different name (like liftlog.html), delete it after uploading,
and open the folder's address (ending in /) instead.

Then on your iPhone/iPad:
  1. Delete the old Home Screen icon.
  2. Open the site in Safari, wait a few seconds, and reload once.
  3. Share -> Add to Home Screen. You should see the hibiscus.
The app opens full screen and works offline. When you're online it always loads the newest version.
