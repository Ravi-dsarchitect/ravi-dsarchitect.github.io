# Ravi Teja Pasupuleti — Portfolio

Personal portfolio site for **Ravi Teja Pasupuleti**, Senior AI Engineer.
Live at **https://ravi-dsarchitect.github.io**.

A single static page — no build step. Plain HTML/CSS with vanilla JS for the scroll
reveals, progress bar, card tilt, the interactive architecture-diagram switcher, and the
Three.js hero/particle scenes (loaded from CDN).

## Structure

```
index.html                     # the whole site
assets/ravi.png                # portrait used in the About section
.nojekyll                      # tell GitHub Pages to serve files as-is
ravi-teja-s-ai-portfolio-design/   # original Claude Design handoff bundle, kept for reference
```

The `ravi-teja-s-ai-portfolio-design/` folder is the original design handoff bundle exported
from [Claude Design](https://claude.ai/design) — the source of truth for the visuals. It is
not served by the site; `index.html` is a hand-built static implementation of that design.

## Develop locally

```bash
python -m http.server 8000
# open http://localhost:8000
```

## Deploy

Pushed to the `main` branch of the `ravi-dsarchitect.github.io` GitHub repo; GitHub Pages
serves it from the repo root.

## Contact

- Email — prt7036586@gmail.com
- LinkedIn — https://www.linkedin.com/in/teja01/
- GitHub — https://github.com/Ravi-dsarchitect
