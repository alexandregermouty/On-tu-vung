# Ôn tiếng Việt

A personal Vietnamese learning PWA for Alexandre, with a Southern Vietnamese focus.

**Learn to belong.**

## GitHub Pages deployment

This repository is a static app: there is no build step.

1. Upload the files in this folder to the root of `alexandregermouty/On-tu-vung`.
2. On GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`, then save.
5. The site should be available at `https://alexandregermouty.github.io/On-tu-vung/` once GitHub Pages finishes publishing.

All app URLs are relative, so the project works from the `/On-tu-vung/` repository path.

## Phone installation

### iPhone / iPad
Open the GitHub Pages site in Safari → **Share** → **Add to Home Screen**. The `apple-touch-icon.png` asset is used for the home-screen icon.

### Android
Open the site in Chrome → browser menu → **Install app** / **Add to Home screen**. Android uses the PWA manifest and the 192/512 px icons. A maskable 512 px icon is included for adaptive icon shapes.

## Branding assets

- `logo.png` — full transparent-background logo used in the app
- `favicon.ico`, `favicon-16.png`, `favicon-32.png`, `favicon-48.png` — browser favicons
- `apple-touch-icon.png` — iOS home-screen icon
- `icon-192.png`, `icon-512.png` — standard PWA icons
- `icon-maskable-512.png` — Android maskable icon with safe padding
- `icon-1024.png` — high-resolution master app icon

## Updating the app

`sw.js` uses a versioned cache. When publishing a future app update, bump the `CACHE` string so existing installations replace the previous cached assets promptly.

Learner progress remains in the browser's local storage / IndexedDB and is not stored in this repository.
