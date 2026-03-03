# CSS Animation Performance Scorer

> Paste your CSS and instantly get a performance grade (A–F) with actionable fixes.

🔗 **Live site:** https://richardlemon.github.io/css-animation-scorer/

## What it does

- Scores your CSS animations on a 0–100 scale
- Detects layout-triggering properties in @keyframes (top, left, width, height)
- Flags paint-triggering animations (background, box-shadow)
- Checks for missing `will-change` declarations
- Identifies infinite animations without GPU-safe properties
- Awards passes for correct use of `transform` and `opacity`

## Tech

Single-file SPA — zero dependencies, no build step, no CDN.  
Dark mode. Mobile-first. Pure HTML/CSS/JS.

## Built with

[![Built with SureThing](https://img.shields.io/badge/Built%20with-SureThing-7c6ff7)](https://surething.io)

---

Built by [Richard Lemon](https://richardlemon.com) · [surething.io](https://surething.io)
