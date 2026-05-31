# ProApps Website

Single-page site for my Google Play developer page: https://play.google.com/store/apps/dev?id=8067309061059365942

## Files
- `index.html` — page markup
- `styles.css` — styling

## Deploy to GitHub Pages
1. Push this folder to a GitHub repo.
2. Repo **Settings → Pages → Build from branch** → pick `main` / root.
3. Your site will be live at `https://<username>.github.io/<repo>/`.

To use it as your user/organization site, name the repo `<username>.github.io` and it'll be served at `https://<username>.github.io/`.

## Edit
- Update the intro copy in `index.html` (look for `hero__lede` and `about` sections).
- Tweak colors in `styles.css` under `:root` (the `--accent`, `--accent-2`, etc. variables).
- Add more app categories by duplicating a `.card` block in `index.html`.
