# HW5 — Vue SFC Conversion

This repository contains a Vite + Vue conversion of the original Threads-like login page for the HW5 assignment.

How this is organized:

- `index.html` — minimal Vite entry that mounts the Vue app.
- `src/main.js` — boots the Vue app and imports global CSS.
- `src/App.vue` — composes the UI using SFCs.
- `src/components/` — contains `LoginForm.vue`, `QrPanel.vue`, and `FooterBar.vue`.
- `src/style.css` — global styles copied from the original project.
- `gf40BP6SRYU.avif`, `QRcode.png` — image assets left in repository root (referenced from components).
- `.github/workflows/gh-pages.yml` — GitHub Actions workflow to build and deploy to GitHub Pages.

To run locally:

```bash
npm install
npm run dev
```

Notes:
- `index.html` and `src/main.js` are kept minimal and free of unrelated markup or inline scripts.
- The app demonstrates componentization via SFCs in `src/components`.
