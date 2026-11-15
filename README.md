# GCS Trainer (installable web app)

Glasgow Coma Scale practice: 100 cases, a 30-question rules quiz and a sourced reference. Works offline once installed. Study aid only.

## Put it online (GitHub Pages)
1. Create a new public repository on github.com (for example `gcs-trainer`).
2. Upload every file in this folder, keeping the `icons` folder, to the repository root.
3. Settings → Pages → Source: "Deploy from a branch" → Branch `main`, folder `/ (root)` → Save.
4. After a minute the app is at `https://<your-username>.github.io/gcs-trainer/`.

Any static HTTPS host works the same way (Netlify Drop, Cloudflare Pages).

## Install on a phone
- iPhone (Safari): open the address → Share → Add to Home Screen.
- Android (Chrome): open the address → menu → Install app / Add to Home screen.

## Updating
Replace the files and bump `CACHE` in `sw.js` (e.g. `gcs-trainer-v2`).
