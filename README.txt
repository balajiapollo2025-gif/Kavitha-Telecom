MobiStock — Kavitha Telecom Wholesale Manager (PWA)
=====================================================

WHAT'S IN THIS ZIP
-------------------
index.html            -> the app itself
manifest.json         -> makes the app installable (name, icon, colors)
sw.js                 -> service worker, makes the app work fully offline after first load
icon-192.png          -> app icon
icon-512.png          -> app icon (large)
icon-apple-touch.png  -> app icon (iOS)

All 6 files sit in ONE folder — no subfolders. This means you can upload
them individually (even from a mobile phone) and nothing will 404.

WHY YOU NEED TO "HOST" THIS FOLDER
------------------------------------
Installing an app as a real Android / Desktop app (icon on home screen,
opens full-screen with no browser bar) only works when the files are
served from a web address (http/https), not when you just double-click
index.html on your computer. This is a browser security rule, not a
limitation of this app.

The good news: you do NOT need a paid server. Pick any ONE option below.

OPTION 1 — Netlify Drop (easiest, no account needed, desktop only)
------------------------------------------------------------------
1. Go to https://app.netlify.com/drop
2. Drag ALL 6 files onto the page (select all of them together)
3. You'll get a free link like https://your-app.netlify.app
4. Open that link on your phone in Chrome -> menu (⋮) -> "Install app"
5. Open the same link on your computer in Chrome -> click the install
   icon (⊕) in the address bar -> it installs as a Desktop app

OPTION 2 — GitHub Pages (free, permanent link, works from mobile too)
-----------------------------------------------------------------------
1. Create a free GitHub account, create a new repository
2. "Add file" -> "Upload files" -> select ALL 6 files (index.html,
   manifest.json, sw.js, icon-192.png, icon-512.png, icon-apple-touch.png)
   and upload them together. Do NOT put them inside a subfolder.
3. Repository Settings -> Pages -> Deploy from branch -> main -> Save
4. You'll get a link like https://yourusername.github.io/reponame/
5. To check nothing is missing, open these two links directly —
   both should load (not show 404):
     https://yourusername.github.io/reponame/manifest.json
     https://yourusername.github.io/reponame/icon-192.png
6. Install it on Android/Desktop the same way as Option 1

OPTION 3 — Run it on your own shop computer (local network only)
---------------------------------------------------------------------
If you have Python installed on your computer:
1. Open this folder in a terminal / command prompt
2. Run:  python3 -m http.server 8000
3. On the SAME computer open: http://localhost:8000 in Chrome and install it
4. On phones connected to the same WiFi, use http://<your-computer-IP>:8000

AFTER INSTALLING
------------------
- Android: shows up as a normal app icon, opens full-screen, works offline
- Desktop (Windows/Mac/Chromebook): opens in its own window like a
  regular desktop app, also works offline
- Your product, billing and customer data is stored only on that
  device/browser (not on any server) — so back up regularly from
  Settings -> Export Backup inside the app

SHOP DETAILS ALREADY FILLED IN
---------------------------------
Shop Name : KAVITHA TELECOM
Address   : Shop No.34, Adhithya Complex, Meeran Sahib Street,
            Mount Road, Chennai - 600 002
Phone     : 89390 00833 / 90436 65107
You can change these anytime from Settings inside the app.

