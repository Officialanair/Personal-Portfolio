# Aarav Nair — Portfolio Site

A static, self-contained one-page portfolio (adapted from the "Solid State" template by HTML5 UP, CC-BY 3.0).

## Contents
- `index.html` — the entire site (HTML/CSS/JS all inlined into one file; images embedded as base64). The only external dependencies are the jQuery 3.6.0 and Google Fonts CDN links in `<head>`/`<script>`.
- `resume.pdf` — resume file. The "Resume" links/buttons in the nav, hero, and footer point straight to this file with a `download` attribute, so clicking them downloads it directly. Keep the filename as `resume.pdf`, or update the three `href="resume.pdf"` references in `index.html` if you rename it.

## Deploying (e.g. GitHub Pages)
1. `git init`, add these files, commit, push to a GitHub repo.
2. In the repo settings, enable GitHub Pages for the branch/root you pushed to.
3. That's it — no build step, no dependencies to install.

## Updating content
Everything is in the one `index.html` file (search for section IDs like `#banner`, `#work`, `#experience`, `#leadership`, `#footer`, or the case-study sections `#view-hrtrends`, `#view-greenteam`, `#view-deepfake`). To swap the resume, replace `resume.pdf` with a new file of the same name.
