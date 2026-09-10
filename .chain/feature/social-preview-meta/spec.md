Add social link-preview metadata to the <head> of index.html.

Scope: index.html only. This repository is a single self-contained HTML file.

Required:
- Add Open Graph tags: og:type (website), og:title, og:description, og:url, og:site_name.
- Add Twitter Card tags: twitter:card, twitter:title, twitter:description.
- Reuse the existing <title> text (The Long Dusk) and the existing meta description verbatim; do not invent new copy.
- Use twitter:card value summary, NOT summary_large_image: this repository contains no image asset, so do not reference an og:image or twitter:image file that does not exist.
- Use https://ykq007.github.io/the-long-dusk-html/ for og:url.

Must not change:
- Any game logic, JavaScript, or CSS.
- The existing charset, viewport, theme-color, description meta tags, or the <title>.
- Any file other than index.html. Do not add build tooling, dependencies, or new files.

Verification: the page must still load and play identically; confirm the HTML parses and the new tags appear inside <head>. There is no test suite in this repository, so state plainly which checks you actually ran rather than reporting a test command you did not run.