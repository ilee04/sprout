# Sprout

A responsive, interactive UI/UX concept for exploring sustainable home technologies. Built as an independent, AI-assisted portfolio project.

**Live website:** https://ilee04.github.io/sprout/

## Features

- Search, category filters, and renter-friendly filtering
- Two-question guided finder
- Side-by-side comparison of up to three concepts
- Browser-local saved shortlist
- Responsive layouts, labeled controls, visible keyboard focus, and native dialogs

## Run locally

Open `dist/index.html` in a modern browser. No installation or build is required. Fonts load from Google Fonts with local fallbacks. Saved choices use browser local storage when available.

## Project structure

- `dist/index.html`: page structure
- `dist/style.css`: responsive styling and illustrations
- `dist/app.js`: sample concepts and interactive flows
- `CASE-STUDY.md`: design rationale and proposed usability study

## Publish updates

GitHub Pages serves the root of the `gh-pages` branch. After committing changes on `main`, publish the website files with:

```sh
git push origin main
git subtree push --prefix dist origin gh-pages
```

## Project status

Product details are illustrative, not verified purchasing recommendations. Functional desktop and mobile checks were performed. User research and a full accessibility audit remain future work; no user research outcomes or environmental impact results are claimed.
