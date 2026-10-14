# antoniollanoa.github.io

My personal website — a one-page resume and professional portfolio for Antonio Jose Llano Aguilar.

## Structure

- `index.html` — the entire site (HTML, CSS, and JavaScript in a single file, no build step required).
- `assets/Antonio-Llano-Aguilar-Resume.pdf` — the downloadable resume linked from the "Download Resume" buttons.

## Deployment

This repository is served directly via [GitHub Pages](https://pages.github.com/). Any push to the `main` branch updates the live site at `https://antoniollanoa.github.io/` automatically — no build pipeline needed.

## Updating content

- Edit the relevant section in `index.html` (About, Experience, Education, Skills, Projects, Certifications, Contact).
- Replace `assets/Antonio-Llano-Aguilar-Resume.pdf` with an updated resume, keeping the same file name (or update the link paths in `index.html` if you rename it).
- To add a real headshot, replace the placeholder `<div class="avatar">` content in the hero section with an `<img>` tag (see the inline comment in `index.html`).
