# kenly-web

Marketing landing page for **[kenly](https://pypi.org/project/kenly/)** — AI-guided codebase walkthroughs in your terminal.

- `index.html` — the full landing page (single self-contained file: HTML + CSS + JS, no build step, no dependencies)

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Any static host works (Cloudflare Pages, Netlify, GitHub Pages, Vercel). It's one file — point the host at this repo (or drag-drop `index.html`) and set the custom domain to **kenly.tech**.

Built to reuse kenly's own dark design system (chrome `#181818` / editor `#1f1f1f`, green `#4ec98a` accent, VS Code Dark+ syntax colors) so the site matches the product.
