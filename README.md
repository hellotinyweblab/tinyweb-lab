# TinyWeb Lab Portfolio

Static site: plain HTML, CSS and JavaScript. No build tools.

## Files

- `index.html` portfolio, services, contact (all CSS/JS inside)
- `samples/cafe|fitness|saas/index.html` fictional concept projects
- `assets/` logo, favicon, shared demo stylesheet

## Before publishing

1. Open `index.html` in a text editor, find `var CONFIG` near the bottom, and set your **business email**. Optionally add a WhatsApp number (country code, digits only, e.g. `91XXXXXXXXXX`). Leave it `""` to hide WhatsApp buttons. Use a dedicated number/email, not your personal ones, to keep your identity private.
2. Double-click `index.html` to preview locally and click every button.
3. Test in Chrome: press F12, then the device toolbar icon, and check phone widths (e.g. 375px).

## Publish free with GitHub Pages

1. Create a free account at github.com.
2. Click **New repository**, name it `tinyweb-lab`, set **Public**, create it.
3. Click **uploading an existing file**. Drag in `index.html`, `README.md` and the `assets` and `samples` folders (keep the folder structure), then **Commit changes**.
4. Go to **Settings > Pages**. Under **Build and deployment** choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
5. Wait 1-2 minutes. Your site is at `https://YOUR-USERNAME.github.io/tinyweb-lab/`. Open every link there once.

To update later: edit a file on GitHub (pencil icon) or upload it again, and commit.
