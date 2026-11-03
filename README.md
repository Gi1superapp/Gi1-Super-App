# The Gi1 Prime Card: 3D + camera AR

Open source (MIT). Anyone who scans the card sees it in 3D and AR. No login, no account, no app.

## Put it online free with GitHub Pages (about 3 minutes)
1. Make a free GitHub account, then press **New repository**. Name it `gi1-card`. Keep it **Public**.
2. Press **uploading an existing file** and drag in everything from this folder (including `.nojekyll`). Commit.
3. Open **Settings > Pages**. Under Source choose **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
4. After a minute your page is live at `https://YOUR-USERNAME.github.io/gi1-card/`.
5. Open `https://YOUR-USERNAME.github.io/gi1-card/#qr` and press **Download card back with this QR**. Print that.

Anyone in the world can then scan the QR. Viewers need nothing.

## Edit your details
`app.js`, top of the file: `LINKS` (Instagram, WhatsApp, YouTube, website, Play Store), `CONTACT`, `PAGE_URL`, `beacon` (optional scan counter).

## Files
`index.html`, `app.css`, `app.js`, `assets/` (card art, video, tracking target), `vendor/` (three.js, QR, MindAR), `fonts/`.
