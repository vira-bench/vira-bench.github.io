# VIRA-Bench project page

Project website for **VIRA-Bench: Diagnosing Pedagogical Contingency Understanding in Online Tutoring Videos**, EMNLP 2026 Main Conference (Oral).

- Organization website: https://vira-bench.github.io/
- Existing project website: https://whwangovo.github.io/vira-bench/ (redirects to https://wangweihang.me/vira-bench/)
- Paper: [PDF](static/pdf/VIRA-Bench.pdf)

This repository currently contains the static project website and paper PDF. Benchmark code and data are not included. The arXiv, Code, and Data buttons retain their pending status until their destinations are available.

## Local preview

```bash
python3 -m http.server 8765
```

## Deployment

GitHub Pages publishes the root of the `main` branch in both repositories. No build step is required. `.nojekyll` preserves the static files.

- `origin`: `whwangovo/vira-bench`, the existing project website.
- `org-pages`: `vira-bench/vira-bench.github.io`, the organization website.

Both remotes share this local source. To publish an update to both sites after committing:

```bash
git push origin main
git push org-pages main
```

The organization website has no custom domain and uses `vira-bench.github.io` directly. The existing project website retains the personal site's custom-domain redirect.

Edit `index.html` and `static/css/style.css` for future website changes. The distribution and intervention charts are HTML/CSS.
