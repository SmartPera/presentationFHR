# SmartPera Financial Status Check — PWA

This is a Progressive Web App (PWA) you can host on GitHub Pages. It works offline and can be added to a phone’s Home Screen.

## Deploy on GitHub Pages
1. Create a new repo (e.g., `smartpera-fhc-pwa`).
2. Upload all files in this folder to the repo root.
3. Go to **Settings → Pages** → **Deploy from a branch** → Branch `main` → Folder `/`.
4. Open the published URL on your phone:
   - **Android/Chrome:** Menu → *Add to Home screen*.
   - **iOS/Safari:** Share → *Add to Home Screen*.

## Notes
- Icons are generated from `smartpera.png` (192/512px).
- Offline capability is handled by `service-worker.js`.