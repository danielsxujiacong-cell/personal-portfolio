# Daniel Personal Portfolio

Static HTML, CSS and native JavaScript portfolio. No build or package installation required.

## Preview

```powershell
python -m http.server 8767 --bind 127.0.0.1
```

## Release

Five sections: Hero, Featured Work, Selected Products, How I Build, About & Contact.
Real product screenshots are stored as WebP in `assets/`. GSAP, ScrollTrigger and Lenis are hosted locally; content remains available without JavaScript. Reduced motion disables scroll animation. Lenis runs on desktop wheel input and stops when idle.

GitHub Pages publishes `main` from the repository root. The custom domain https://danielxu.cn/ currently uses EdgeOne; its deployment must be verified separately from GitHub Pages.

## Verification

Use a browser at widths 1440, 1366, 390 and 320. Check image loading, navigation, reverse scrolling, overflow, console errors, reduced motion and missing script fallback. Check the staged diff before commit and push.
