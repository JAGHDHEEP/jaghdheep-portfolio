# Jaghdheep M — Portfolio

My portfolio of machine learning projects, hackathon wins, professional experience, research, leadership and education.

**Visit the portfolio:** [jaghdheep.github.io/jaghdheep-portfolio](https://jaghdheep.github.io/jaghdheep-portfolio/)

## Website

The complete static website lives in `dist/`. It includes separate case-study pages, a downloadable résumé, responsive layouts, self-hosted fonts and motion that respects reduced-motion preferences.

Built with HTML, CSS and JavaScript. No package installation or build step is required.

## Local preview

From the repository root:

```sh
python -m http.server 8765 --directory dist
```

Open `http://localhost:8765/`.

## Publish an update

GitHub Pages publishes the root of the `gh-pages` branch. After committing changes to `dist/` on `main`, run:

```sh
git push github main
git subtree push --prefix=dist github gh-pages
```

The remote named `github` should point to `https://github.com/JAGHDHEEP/jaghdheep-portfolio.git`.
