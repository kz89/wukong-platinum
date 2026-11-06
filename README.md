# Destined One’s Ledger — Black Myth: Wukong Platinum

A chronological platinum roadmap and completionist checklist for **Black Myth: Wukong** (PS5).
It’s an installable web app: one HTML page, an offline service worker, a manifest and icons. Progress stays in the browser on your device.

## Publish on GitHub Pages (about 5 minutes, all in the browser)

1. Sign in at github.com → **New repository**. Name it `wukong-platinum`, set it to **Public**, and click **Create repository**.
2. On the new repo page, click **uploading an existing file**. Drag in **all the files in this folder** (the files themselves, not the folder) and click **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, pick **main** and **/ (root)**, then click **Save**.
4. Wait 1–2 minutes. Your guide is at `https://<your-username>.github.io/wukong-platinum/`.

## Install on iPad

Open that address in **Safari** → **Share** → **Add to Home Screen**. It opens full-screen and works offline.
A Home Screen app keeps its own progress, separate from Safari, so start ticking from the Home Screen icon.

## Updating later

Edit `index.html`, then open `sw.js` and bump `VERSION` (e.g. `ledger-v1.1`), and upload both files again.
Open the app twice to pick up the new version. Your ticks are kept.

Sources: PowerPyx trophy roadmap and location guides, cross-checked with the PSNProfiles trophy guide (compiled November 2026). Fan-made, not affiliated with Game Science.
