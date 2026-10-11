# Focus Time Only

Static landing page for the Focus Time Only iOS app (temporarily unreleased - contact me for a free direct copy or access to its private repo). It uses HTML and CSS only, so GitHub Pages can host it without a framework, package installation, or build command.

The site includes a prominent scrolling notice explaining that the developer has cancelled their Apple Developer Program membership and the app is temporarily unavailable on the App Store. The CSS marquee moves continuously from right to left on a single line at every screen size. It only pauses when visitors select the Pause control.

## Deploy to GitHub Pages

The workflow in [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml) packages the site on pushes and pull requests targeting `master`. Successful pushes to `master` deploy automatically; pull requests do not deploy. You can also deploy `master` manually from the Actions tab.

## Local preview

From the project directory:

```bash
python3 -m http.server 8000
```

Open <http://localhost:8000>. There are no dependencies to install.

## Project structure

- `index.html` — page content and App Store availability notice.
- `styles.css` — responsive styling and the accessible marquee animation.
- `assets/` — app icons, ranking screenshot, and promotional video.
- `.github/workflows/deploy-pages.yml` — packaging and automatic GitHub Pages deployment.
