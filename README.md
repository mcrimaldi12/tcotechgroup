# tcotechgroup.com

The TCO Technology company website. One static page (`index.html`), served by GitHub Pages from the `main` branch.
Anything merged into `main` is live within a minute or two, so changes are made on a branch and looked at first.

## What is here

- `index.html` is the whole page: words, styles and scripts in one file. There is no build step; edit it directly.
- `assets/screens/` holds the WorkPhase FX™ screenshots the page shows. They were taken from the real app running
  on a demo company, so every customer, address and phone number in them is made up. Never replace them with
  screenshots of a real company's data.
- `assets/og.png` is the picture that appears when the site's link is shared.
- `CNAME` and `.nojekyll` are GitHub Pages settings. Leave them alone.

## Looking at it before it goes live

From this folder:

```bash
python3 -m http.server 8765
```

Then open http://127.0.0.1:8765/ in a browser.

## Keeping it honest

- The page only says what WorkPhase FX™ really does. Before adding a claim, check it against the app.
- WorkPhase FX™ is invite-only and still in testing, and the page says so. It does not offer sign-ups.
- The name is written with ™. Switch to ® only once the registration certificate has been issued.
