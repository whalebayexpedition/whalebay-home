# whalebay-home — company portal for whalebay.world

A two-page minimal portal site for Whalebay Expeditions (鲸湾探索):
- `index.html` — hero + 6 product boxes (Ilulissat, Nuuk, Peninsula, South Pole, Continent, Bespoke)
- `about/index.html` — philosophy, founders (王海宁 + 姚雪霏), 复古大帆船 safety story, book portfolio

## Tech stack
Single-file static HTML per page, all CSS+JS inline. No build step. No framework.
Fonts: Noto Sans SC (body), Noto Serif SC (display CN), Cinzel (display EN).

## Deploy
Cloudflare Pages → whalebay.world. See DEPLOY-NOTES.md.

## Sibling sites (same brand family, separate repos)
- arctic.whalebay.world  → arctic-app   (Ilulissat, Nuuk)
- antarctica.whalebay.world → antarctica-app (Peninsula, South Pole, Continent)

## Design system
Shared top bar + footer convention defined in
`/home/xuefei/Projects/docs/superpowers/specs/2026-05-14-website-restructure-design.md` §11.
Same snippet pasted verbatim into every sub-page across all three repos.

## Source content
`/home/xuefei/Projects/鲸湾探索_公司简介_设计.pdf` — founder bios, philosophy, safety, books.
