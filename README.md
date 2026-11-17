# Apex Global Enterprise Facial Solutions LLC

A one-page parody website. The company is fictional, nothing is for sale, the buy button takes no money, and the page collects no information.

## Files

- `index.html`: the whole site in one file. No build step and no dependencies.
- `.nojekyll`: tells GitHub Pages to serve the files exactly as they are.

## Publishing

GitHub Pages serves the `gh-pages` branch. To update the live site, push the new `index.html` to that branch.

## Custom domain

The site is currently served on its GitHub Pages address. To serve it on a custom domain instead:

1. Add a file named `CNAME` to the `gh-pages` branch containing only the domain name.
2. After that is live, point the domain's DNS at GitHub Pages.

Do the steps in that order, so the domain is claimed here before it points at GitHub.
