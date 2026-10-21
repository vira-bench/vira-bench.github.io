# VIRA-Bench project page

Project website for **VIRA-Bench: Diagnosing Pedagogical Contingency Understanding in Online Tutoring Videos**, EMNLP 2026 Main Conference (Oral).

- Website: https://whwangovo.github.io/vira-bench/
- Paper: [PDF](static/pdf/VIRA-Bench.pdf)

This repository currently contains the static project website and paper PDF. Benchmark code and data are not included. The arXiv, Code, and Data buttons retain their pending status until their destinations are available.

## Local preview

```bash
python3 -m http.server 8765
```

## Deployment

GitHub Pages publishes the root of the `main` branch. No build step is required. `.nojekyll` preserves the static files. Project Pages may inherit the custom domain of the owner's user site.

Edit `index.html` and `static/css/style.css` for future website changes. The distribution and intervention charts are HTML/CSS.
