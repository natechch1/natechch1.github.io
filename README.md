# natechch1.github.io

Personal portfolio site for **Hongce (Nate) Chen** — full-stack developer based in Toronto.

🌐 **Live**: https://natechch1.github.io

---

## What it is

A single-page brutalist/terminal-themed portfolio with a **physics sandbox hero**: every skill, tool, and stat is a draggable card you can throw around. Built with vanilla HTML / CSS / JS and [Matter.js](https://brm.io/matter-js/) for the physics. No build step, no framework, no nonsense.

## Stack

- HTML5 + vanilla CSS (custom properties, no preprocessor)
- Vanilla JavaScript
- [Matter.js](https://brm.io/matter-js/) (loaded via CDN) for the physics engine
- [Google Fonts](https://fonts.google.com/) — JetBrains Mono + Fraunces

## Local development

No build step. Just open `index.html` in a browser, or run a tiny local server:

```bash
# Python 3
python3 -m http.server 8000

# Node (if you have it)
npx serve .
```

Then visit http://localhost:8000.

## Deploy to GitHub Pages

This repo is set up to be served directly from the `main` branch via GitHub Pages.

1. Push the repo to `https://github.com/natechch1/natechch1.github.io` (the repo name **must** match your username + `.github.io`).
2. On GitHub: **Settings → Pages → Source** → choose **Deploy from a branch** → `main` / `/ (root)` → **Save**.
3. Wait ~30 seconds. Your site will be live at `https://natechch1.github.io`.

That's it. Any push to `main` re-deploys automatically.

## File structure

```
.
├── index.html         # Everything: markup, styles, scripts
├── assets/
│   ├── favicon.ico
│   └── portrait.jpg   # (kept for future use)
└── README.md
```

## Credits

- Physics: [Matter.js](https://github.com/liabru/matter-js) by Liam Brummitt (MIT)
- Fonts: JetBrains Mono, Fraunces (both OFL)

---

© 2026 Hongce Chen
