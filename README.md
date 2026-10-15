# DiffMerge — WACV 2027

A responsive, interactive research project page for **Recovering Diversity in Distilled Diffusion Models via Low-Rank Policy-Optimized Merging**.

Authors: Hoigi Seo, Woojae Han, Joohoon Lee, Se Young Chun.

## Preview locally

Run `python3 -m http.server 4173 --directory dist`, then open http://localhost:4173.

## Publish to GitHub Pages

The `dist/` folder is the complete static website. Copy its contents to your GitHub Pages publishing directory, or deploy `dist/` using a Pages workflow. No build step is required. Paths work under a repository subdirectory.

## Contents

- Real paper samples, cropped from Figures 3–5.
- Nine-sample teacher/student/merge comparison with two prompt families.
- Model-family switch and quantitative results from Table 2.
- Interactive method explanation, figure enlargement, and BibTeX copying.
- Author homepage links; arXiv and Code are marked Coming soon.

The original PDF is not included in the site or repository. Intermediate extraction files are ignored. Figures and numbers come from the supplied manuscript; author names and WACV 2027 acceptance were supplied by the author. The copyable citation omits unpublished page numbers and DOI.

Update resource links in `dist/index.html` when arXiv and code are released. Content and layout live in `dist/index.html`, `dist/style.css`, and `dist/app.js`.
