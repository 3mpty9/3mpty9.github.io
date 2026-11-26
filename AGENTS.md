# Agent Guidelines

This repository is a single-page personal website with no build step.

- `index.html` holds all content and inline styles. Keep it plain HTML and CSS: no frameworks, no external scripts or fonts.
- `assets/img/` holds the photo, the publication figure and the institution logos; `assets/pdf/` holds the CV.
- To preview, open `index.html` in a browser or run `python3 -m http.server` in the repository root.
- Pushing to `main` publishes the site through `.github/workflows/deploy.yml`, which copies `index.html` and `assets/` to the `gh-pages` branch.
- Content must match the owner's CV. Do not add projects, numbers or claims that are not in it.
