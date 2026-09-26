# Project context

## Goal

Present Daniel's AI, automation, and product design work as a scroll driven personal portfolio.

## Scope

- In scope: a static, single page portfolio with Intro, pinned 3D showcase, and Outro.
- Out of scope: frameworks, backend, CMS, login, and data storage.

## Constraints

- Keep the recovered `index.html` source and existing appearance intact.
- GSAP and ScrollTrigger drive desktop scroll narrative; Lenis is synchronized through the GSAP ticker.
- Spline Viewer remains replaceable in the marked source region; an empty URL keeps the CSS fallback visible.
- Public page content currently includes placeholder contact links.

## Key decisions

| Date | Decision | Reason |
| --- | --- | --- |
| 2026-09-26 | Restore the complete HTML snapshot from Codex session history | The original working copy was absent at its former location |

## Verification

Serve the directory with `python -m http.server 8767 --bind 127.0.0.1`. Loading mask dismissal, desktop Pin/Scrub, Lenis, cursor, mobile non-pinned layout, and browser console were verified on 2026-09-26.
