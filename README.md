# Toward the Science of Multi-Agent Communication — Web Edition

A static, blog-style web version of the survey *"Toward the Science of Multi-Agent
Communication: A Comprehensive Survey."*

**Live site:** https://yifang99.github.io/Communication-survey-host/

## Contents

- `index.html` — the full survey as a single readable page (sticky table of contents,
  MathJax-rendered equations, author–year citations, and a reference list).
- `style.css` — minimal blog styling.
- `assets/` — figures and comparison tables, typeset from the original LaTeX sources
  (TikZ diagrams and `booktabs` tables rendered to images; click any to enlarge).
- `paper.pdf` — the compiled PDF of the manuscript.

## How it was generated

The prose was converted from the LaTeX manuscript with [Pandoc](https://pandoc.org)
(MathJax for math, citeproc for citations). Figures and dense comparison tables were
compiled from their original TikZ / `tabular` sources with
[Tectonic](https://tectonic-typesetting.github.io/) and embedded as high-resolution
images, so they match the paper exactly.

## Enabling GitHub Pages

Repository **Settings → Pages → Build and deployment → Source: Deploy from a branch →
Branch: `main` / `/ (root)`**. The site is served from the repository root.
