Love Letter 💌
A tiny, cute, interactive pixel-art love letter that runs in your browser.

Aim Cupid's bow, release to fire the arrow at the floating envelope, and a retro "LOVE" window pops open. Answer the question — and the screen fills with falling hearts. 🎯❤️

Live demo   Built with HTML · CSS · JS   No dependencies

▶︎ Open the live demo →
by Code & Chill 💙

Preview of the love letter page

About
A small, heartfelt web toy built with plain HTML, CSS, and JavaScript — no frameworks, no build step, no dependencies. The whole thing is ~120 KB and works offline.

Features
🏹 Interactive bow & arrow — aim with the mouse/finger, release (or press Space) to shoot Cupid's arrow.
💌 Animated reveal — the envelope bursts open into a retro pixel "LOVE" window with a little cat.
😉 A playful "NO" button that dodges your cursor.
🎉 Heart confetti & rain celebration.
♿ Respects prefers-reduced-motion — shows a calm, static version when your system has reduced motion enabled.
📱 Responsive — works on desktop and touch.
How to play
Aim — move your mouse (or finger) to aim the bow.
Shoot — press & hold, then release — or hit the Space bar.
The envelope opens into the LOVE window.
Press YES (the NO button is shy 😉).
Enjoy the hearts. Press ✕ to close and shoot again.
Run it locally
The page loads its JavaScript as a module, so browsers won't run it from a file:// path — you need to serve the folder. Pick any one (run it inside this folder):

# Python (already on most Macs & Linux)
python3 -m http.server 8000
#   → open http://localhost:8000

# …or Node.js
npx serve
#   → open the printed http://localhost:3000

# …or VS Code: install the "Live Server" extension,
#   right-click index.html → "Open with Live Server"
Stop a running server with Ctrl + C.

Tech
Plain HTML5, CSS3 (animations, gradients), and vanilla JavaScript — zero libraries, zero build tooling. Fonts (Press Start 2P, Pixelify Sans) load from Google Fonts when online and fall back gracefully offline. The cat is drawn on a <canvas>.

Project structure
love-letter/
├── index.html      # the page
├── love.css        # styling & animation
├── love.js         # interactions (vanilla JS)
├── favicon.png     # browser-tab icon
├── preview.jpg     # screenshot used in this README
└── textures/
    └── grain.png   # subtle film-grain background
