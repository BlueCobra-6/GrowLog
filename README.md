# GrowLog

Offline-first tracker for hydroponic gardens: gardens → shelves/nurseries → trays → pod slots.
Plant, move/swap, harvest, and see what's due. Data stays on your device (browser storage).
Back up from the More tab.

## Host it free on GitHub Pages
1. Create a new **public** repository on github.com (e.g. `growlog`). Pages is free for public repos.
2. Put these files in the repo root: `index.html`, `sw.js`, `manifest.webmanifest`, `icon-*.png`.
3. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch `main`, folder `/ (root)` → Save.
4. After a minute your app is at `https://<your-username>.github.io/growlog/`.
5. Open that URL on your phone → Share / menu → **Add to Home Screen**.

Your garden data is never in the repo. It lives only in your phone's browser storage.

## Updating
Replace `index.html` in the repo. The app refreshes itself next time you open it online.
