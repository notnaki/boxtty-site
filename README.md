# boxtty-site

Marketing + documentation site for [boxtty](https://github.com/notnaki/boxtty), the fast,
private, local-first Gmail client for macOS.

Plain static HTML/CSS — no build step. Served directly by GitHub Pages.

## Structure

```
index.html      landing page (centered terminal hero)
features.html   feature list
docs.html       comprehensive documentation (sticky TOC)
download.html   build-from-source instructions
styles.css      design system (ported from the original boxtty-site)
favicon.svg     the boxtty mark
.nojekyll       serve files as-is (skip Jekyll)
```

## Develop

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8080   # → http://localhost:8080
```

## Deploy (GitHub Pages)

Pushed to the default branch; Pages is configured to serve from the branch root.
Any push updates the live site. Design language (palette, JetBrains Mono accents,
hairline borders, brand `#3551f3`) mirrors the original `boxtty-site`.
