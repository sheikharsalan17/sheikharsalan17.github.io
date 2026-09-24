# Academic homepage

A static, responsive homepage for Sheikh Arsalan-ul-Haque, published at [sheikharsalan17.github.io](https://sheikharsalan17.github.io/). The source repository is [sheikharsalan17/sheikharsalan17.github.io](https://github.com/sheikharsalan17/sheikharsalan17.github.io). There is no build step.

## Preview locally

From this folder, run:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Update the live site

Edit the files and push changes to the repository's `main` branch. GitHub Pages publishes from the repository root.

The site is self-contained: `index.html` is the homepage, `research.html` and `teaching.html` are the other pages, and the two PDFs in `assets/` are hosted copies of the CV and résumé. Replace these PDFs whenever their Overleaf versions are updated:

- `assets/academic-cv.pdf` comes from the Dropbox-synced Overleaf file `Sheikh_ArsalanulHaque_CV/Academic_CV_NBER_Workshop_2026.pdf` (September 2026).
- `assets/corporate-resume.pdf` comes from `Sheikh_ArsalanulHaque_CV/Corporate CV.pdf` (September 2026).
