# Associate Price Calculator (installable web app)

Files: index.html, manifest.webmanifest, sw.js, icons/. Upload ALL of them, keeping the icons folder.

## Free hosting with GitHub Pages
1. Create a free account at github.com and click New repository (name it e.g. price-calculator, set Public).
2. Click "uploading an existing file", drag in everything from this folder (including the icons folder), then Commit.
3. Go to Settings > Pages. Under Branch choose "main" and folder "/ (root)", then Save.
4. After a minute your app is live at https://YOURNAME.github.io/price-calculator/

## Installing on a phone
- iPhone: open the link in Safari > Share > Add to Home Screen.
- Android: open the link in Chrome > menu (three dots) > Install app (or Add to Home screen).

## Updating
Edit index.html, and change CACHE = "price-calc-v1" in sw.js to v2 (v3, ...) so phones pick up the new version.
