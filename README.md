# chenxiyuan1.github.io

Static personal website for Chenxi (Chelsea) Yuan. Plain HTML + CSS, no build step.

## Files
- `index.html` — Home
- `research.html`, `publications.html`, `group.html`, `talks.html`, `teaching.html`
- `style.css` — shared styles and mobile layout
- `images/` — portrait, student and team photos, funder logos
- `files/` — put `CV.pdf` here (the CV button links to `files/CV.pdf`)
- `.nojekyll` — tells GitHub Pages to serve the files as-is

## Deploy
1. Back up the current site: in the repo, create a branch (e.g. `old-academicpages`).
2. On `main`, delete the old Jekyll files and copy everything from this folder into the repo root.
3. Add `files/CV.pdf`, commit, and push. The site updates at https://chenxiyuan1.github.io/ within a minute or two.

## Editing
- Text: open the `.html` file and edit the words directly.
- Publications: edit the `all` list near the bottom of `publications.html` (title, authors, venue, year, tags, link).
- News: edit the News section in `index.html`.
- Colors: background `#F1F2E4`, accent `#4E6A2E`.
