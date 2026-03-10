╔══════════════════════════════════════════════════════╗
║   CHARLIE CHITTY'S CERTIFIED CARD COLLECTOR — PWA   ║
╚══════════════════════════════════════════════════════╝

FILES IN THIS FOLDER:
  charlie-chitty-card-collector.html  ← the game
  manifest.json                        ← PWA manifest
  sw.js                                ← service worker (offline support)
  icon-192.png                         ← app icon
  icon-512.png                         ← app icon (large)

HOW TO HOST (pick one):

  ── GITHUB PAGES (free, recommended) ──────────────────
  1. Create a free GitHub account at github.com
  2. New repository → name it anything → set to Public
  3. Upload ALL files in this folder
  4. Settings → Pages → Source: main branch / root
  5. Your game is live at: https://USERNAME.github.io/REPONAME/charlie-chitty-card-collector.html

  ── NETLIFY (free, drag & drop) ───────────────────────
  1. Go to netlify.com → sign up free
  2. Drag this entire folder onto the Netlify dashboard
  3. Done — instant live URL

HOW TO INSTALL ON ANDROID:
  1. Open the live URL in Chrome on your phone
  2. Tap the ⋮ menu → "Add to Home screen"
  3. It installs like a real app — full screen, no browser chrome!
  4. Works offline too (service worker caches everything)

HOW TO INSTALL ON iPhone/iPad:
  1. Open the live URL in Safari
  2. Tap the Share button → "Add to Home Screen"
  3. Done!

IMPORTANT: All files must be served from the same folder
for the PWA features to work. Don't rename the HTML file.
