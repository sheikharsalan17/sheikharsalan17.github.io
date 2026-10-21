# Academic homepage

A static, responsive homepage for Sheikh Arsalan-ul-Haque, published at [sheikharsalan17.github.io](https://sheikharsalan17.github.io/). The source repository is [sheikharsalan17/sheikharsalan17.github.io](https://github.com/sheikharsalan17/sheikharsalan17.github.io). There is no build step.

## Preview locally

From this folder, run:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

The stylesheet URL in every HTML page includes a content hash (`styles.css?v=…`). When changing CSS, update that hash in all four pages so returning visitors receive the new layout. Responsive images use `height: auto`; the portrait overrides this inside its cropped frame.

## Update the live site

Edit the files and push changes to the repository's `main` branch. GitHub Pages publishes from the repository root.

The site is self-contained: `index.html` is the homepage, `research.html`, `teaching.html`, and `visualizations.html` are the other pages. The CV and résumé PDFs in `assets/` are hosted copies of the CV and résumé. Replace these PDFs whenever their Overleaf versions are updated:

- `assets/academic-cv.pdf` comes from the general Dropbox-synced Overleaf file `Sheikh_ArsalanulHaque_CV/Academic CV.pdf` (July 2026).
- `assets/corporate-resume.pdf` comes from `Sheikh_ArsalanulHaque_CV/Corporate CV.pdf` (September 2026).


## Research figures and teaching evaluations

- `assets/figures/marriage-entry-schooling.png`: JMP blog figure, with Rounak Bose.
- `assets/figures/inheritance-marriage-timing.png`: pooled anticipation-sample marriage-timing figure, October 20, 2026.
- `assets/figures/inheritance-land-control.svg` and its mobile variant: paired-point comparison of descriptive involvement in inherited land among all recipients. Restyled October 21, 2026 from the October 20 person-level replication summary; PNG downloads are also included. All six categories and twelve percentages match the original aggregate results (392 usable responses for women, 913 for men).
- Course evaluation PDFs are split by course: ECON 103 (Delaware, Winter 2026) and ECON 240 (LUMS, Summer 2025). They preserve the original evaluation pages, including comments and scale notes.

The marriage-entry and marriage-timing images are unchanged copies of research outputs. The land-control chart is redrawn from verified aggregate counts; its desktop and phone layouts use the same data. Keep source notes, co-author attribution, sample definitions, and descriptive image alternatives in sync when replacing figures. The site intentionally has no downloadable JMP manuscript yet.
