# ReconTool — PayNearby Payment Reconciliation

Deploy these 4 files to any static host (GitHub Pages, Netlify, etc.)

## GitHub Pages (free, 2 minutes)
1. Create a new repo on github.com (e.g. `recontool`)
2. Upload all 4 files: `index.html`, `manifest.json`, `sw.js`, `icon.svg`
3. Go to repo Settings → Pages → Source: Deploy from branch → main → / (root)
4. Your URL: `https://<your-username>.github.io/recontool/`
5. Open that URL in Chrome → install prompt appears → click Install
6. ReconTool installs with your logo on desktop, taskbar, Start menu

## Files
- `index.html` — the full ReconTool app
- `manifest.json` — PWA metadata and icon config
- `sw.js` — service worker for offline support
- `icon.svg` — RT logo (navy + green)
