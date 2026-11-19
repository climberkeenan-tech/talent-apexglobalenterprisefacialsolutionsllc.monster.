# Apex Global Enterprise Facial Solutions LLC

A one-page parody website. The company is fictional, nothing is for sale, the buy button takes no money, and the page collects no information.

## Files

- `index.html`: the whole site in one file. No build step and no dependencies.
- `.nojekyll`: tells GitHub Pages to serve the files exactly as they are.
- `qr/`: a QR code for the live site address, as PNG and SVG.
- `poster/`: a printable poster. `apex-global-poster-letter.pdf` is US Letter for a home printer, `apex-global-poster-11x17.pdf` is 11x17 for a print shop, and `apex-global-poster-letter.png` is a preview. `apex-global-poster.html` is the source for both PDFs.

## Printing the poster

Print the PDF at 100% ("Actual size"), not "Fit to page", so the QR code stays at its tested size. To rebuild the Letter PDF from the HTML, open it in Chrome and print to PDF on Letter paper with margins set to None and background graphics on. For the 11x17 layout, change `data-size="letter"` to `data-size="tabloid"` on the `<html>` tag first and print on 11x17 paper.

## Publishing

GitHub Pages serves the `gh-pages` branch. To update the live site, push the new `index.html` to that branch.

## Custom domain

The site is currently served on its GitHub Pages address. To serve it on a custom domain instead:

1. Add a file named `CNAME` to the `gh-pages` branch containing only the domain name.
2. After that is live, point the domain's DNS at GitHub Pages.

Do the steps in that order, so the domain is claimed here before it points at GitHub.
