# Viktor Tisza | personal website

A static personal homepage for [www.tisza.dev](https://www.tisza.dev), hosted on GitHub Pages.

## Files

- `index.html`: homepage content and links.
- `assets/profile.css`: responsive design and project image layout.
- `assets/profile.js`: scroll transitions and footer year.
- `assets/viktor-tisza.jpg`: portrait.
- `assets/favicon.svg`: favicon.
- `CNAME`: custom domain.
- `.nojekyll`: serves the site directly without Jekyll processing.

No package installation or build step is required. Fonts load from Google Fonts with system fallbacks.

## Preview

From the repository directory, run:

```sh
python3 -m http.server 4173
```

Open http://localhost:4173. You can also open `index.html` directly.

## Publication

Commit and push to the branch configured for this repository’s GitHub Pages deployment. Keep `CNAME` and `.nojekyll` in the published root.

The repository license is retained from its original theme.

## Project visuals

Project images are stored locally in `assets/` so the homepage does not rely on hotlinked files.

- `szazkilencvenkilenc.jpg`: published forecast chart from `https://www.szazkilencvenkilenc.hu/assets/images/20260411eng/outcomes.png`.
- `kronikas-logo.svg`: original logo from `https://kronikas.eu/assets/favicon.svg`.
- `chili-classifier.jpg`: original cayenne pepper photo from `https://www.tisza.dev/ChiliClassifier/images/Cayenne_Pepper.jpg`.
- `ketharmad.jpg`: sample-card screenshot from `https://www.tisza.dev/ketharmad/K%C3%A9tharmad.html`.

Captured on 12 October 2026.
