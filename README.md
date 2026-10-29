# Daniel Xu Personal Portfolio

Static HTML, CSS and native JavaScript portfolio for 徐嘉聪 Daniel Xu. It presents the positioning **AI Automation Practitioner & Indie Developer** / **AI 自动化实践者 · 独立开发者**, project work, product previews, and the process from problem discovery to deployment. AI-assisted development is described transparently; no unsupported employment, client, revenue, or user-scale claims are made.

## Preview

```powershell
python -m http.server 8767 --bind 127.0.0.1
```

## Release

Five sections: Hero, Featured Work, Selected Products, How I Build, About & Contact. Real product screenshots are stored as WebP in `assets/`. GSAP, ScrollTrigger and Lenis are hosted locally; content remains available without JavaScript. Reduced motion disables scroll animation. Lenis runs on desktop wheel input and stops when idle.

GitHub Pages publishes `main` from the repository root. The custom domain https://danielxu.cn/ uses EdgeOne and must be verified separately after push. The official GitHub profile README is at https://github.com/danielsxujiacong-cell.

## Verification

No build pipeline. Check the static HTML, JSON-LD, links, robots.txt and sitemap.xml; preview at desktop and mobile widths before release.
