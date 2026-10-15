# DiffMerge — WACV 2027

A responsive, interactive research project page for **Recovering Diversity in Distilled Diffusion Models via Low-Rank Policy-Optimized Merging**.

Authors: Hoigi Seo, Woojae Han, Joohoon Lee, Se Young Chun.

## Preview locally

Run `python3 -m http.server 4173 --directory dist`, then open http://localhost:4173.

## GitHub Pages

Live project page: https://seohoiki3215.github.io/DiffMerge_project_page/

Source repository: https://github.com/seohoiki3215/DiffMerge_project_page

Source is on `main`; GitHub Pages serves the `gh-pages` branch. The `dist/` folder is the complete static website; no build step is required.

After editing and committing the site, publish with:

```sh
git push origin main
git subtree push --prefix dist origin gh-pages
```

## Contents

- Real paper samples, extracted from the original figure assets corresponding to Figures 3–5.
- Nine-sample teacher/student/merge comparison with winter coat and handbag prompts.
- Model-family switch and quantitative results from Table 2.
- Interactive method explanation, figure enlargement, and BibTeX copying.
- Author homepage links; arXiv and Code are marked Coming soon.

The original PDF is not included in the site or repository. Intermediate extraction files are ignored. Figures and numbers come from the supplied manuscript; author names and WACV 2027 acceptance were supplied by the author. The copyable citation omits unpublished page numbers and DOI.

Update resource links in `dist/index.html` when arXiv and code are released. Content and layout live in `dist/index.html`, `dist/style.css`, and `dist/app.js`.

## Image quality

The diversity viewer uses winter coats and handbags from the supplied main and supplementary SDXL figure assets. All five methods have native 1536 × 1536 nine-image grids, giving consistent 512 × 512 individual samples. The top overview gallery offers freckled portraits and winter coats, with buttons and previous/next controls. Freckled portraits retain the original 180 × 180 per sample and are displayed as compact nine-image grids. The large diversity viewer keeps only the consistent 512 × 512 examples; refrigerators have been removed. Images are extracted directly and encoded as lossless WebP, without synthetic upscaling.

Baseball and red-haired portrait comparisons retain 1024 × 1024 pixels; bird and kite comparisons retain 540 × 540. The framework retains 5275 × 2447 pixels. Source PDF and PPTX files are not uploaded.
