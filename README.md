# Goodesign — AI interior design and virtual staging, from one photo

[English](README.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Italiano](README.it.md) · [Español](README.es.md)

**Goodesign** ([www.goodesign.io](https://www.goodesign.io)) is an AI interior-design and virtual-staging website. You upload one photo of a room, choose a style or describe what you want, and get back a render of the same room with the change applied. It is built for the people who have to make a room convincing before it exists: agents listing an empty property, owners planning a renovation, stagers pitching a direction, and sellers who need photos that stop the scroll.

No source code lives here. This page exists to point at the product, explain what it actually does, and record the parts people keep asking about — the style library, the task pages, the pricing, the language coverage.

## Start here

| | |
|---|---|
| Product | [www.goodesign.io](https://www.goodesign.io) |
| Style library (34 looks) | [/styles](https://www.goodesign.io/styles) |
| Gallery of worked examples | [/gallery](https://www.goodesign.io/gallery) |
| What each task does | [/features](https://www.goodesign.io/features) |
| Plans and prices | [/pricing](https://www.goodesign.io/pricing) |
| How to write the brief | [/how-to-prompt](https://www.goodesign.io/how-to-prompt) |
| Knowledge hub (100 articles) | [/knowledge-hub](https://www.goodesign.io/knowledge-hub) |
| Help centre | [/help](https://www.goodesign.io/help) |
| Contact | [hello@goodesign.io](mailto:hello@goodesign.io) |

## What it does

**Restyle a room.** An empty or dated room, shown in a different direction. The library holds 34 named looks — Japandi, Scandinavian, Wabi Sabi, Mid Century, Boho, Industrial, Art Deco, Quiet Luxury, Mediterranean, Korean, Japanese Modern, Modern Chinese, Cream, Natural Wood, Maximalist and twenty more — or your own written brief.

**Change one thing, keep the rest.** The task pages are the point of difference. Instead of one open-ended "imagine this room" box, each job has its own page and its own controls:

| Job | Page |
|---|---|
| Stage an empty room | [virtual-staging](https://www.goodesign.io/virtual-staging) |
| Clear the room first | [empty-your-space](https://www.goodesign.io/empty-your-space) |
| Redesign a furnished room | [redesign-furnished-rooms](https://www.goodesign.io/redesign-furnished-rooms) |
| Keep the layout, change the piece | [swap-furniture-objects](https://www.goodesign.io/swap-furniture-objects) |
| Keep the piece, change the finish | [furniture-facelift](https://www.goodesign.io/furniture-facelift) |
| Add a missing item | [add-furniture-objects](https://www.goodesign.io/add-furniture-objects) |
| Remove an unwanted item | [object-removal](https://www.goodesign.io/object-removal) |
| Repaint a wall | [repaint-wall](https://www.goodesign.io/repaint-wall) |
| Change floors and surfaces | [restyle-surfaces](https://www.goodesign.io/restyle-surfaces) |
| Same room, daylight to dusk | [day-to-dusk](https://www.goodesign.io/day-to-dusk) |
| Replace a flat, grey sky | [sky-replacement](https://www.goodesign.io/sky-replacement) |
| Re-do the garden | [lawn-replacement](https://www.goodesign.io/lawn-replacement) |
| Add a pool | [add-pool](https://www.goodesign.io/add-pool) |
| Rebuild exterior structures | [render-exterior-structures](https://www.goodesign.io/render-exterior-structures) |
| Whole-home renovation preview | [interior-home-renovation](https://www.goodesign.io/interior-home-renovation) |
| Season and festive changes | [seasonal-reset](https://www.goodesign.io/seasonal-reset) · [festive-flip](https://www.goodesign.io/festive-flip) |
| Sharpen and enlarge a shot | [image-enhancement](https://www.goodesign.io/image-enhancement) · [image-upscale](https://www.goodesign.io/image-upscale) |
| Product and scene shots | [product-scenes](https://www.goodesign.io/product-scenes) · [merchant-product-visualizer](https://www.goodesign.io/merchant-product-visualizer) |

## Pricing

Credit-based. One credit buys one image; the free account starts with 5 credits and no card is required. Paid plans are monthly and cancel whenever you like.

| Plan | Per month |
|---|---|
| Free | $0 · 5 credits to start |
| Essential | $14 |
| Pro | $29 |
| Advanced | $49 |
| Agency | $99 |

Billing runs through Creem as merchant of record, with PayPal available as a direct option. Current figures are always on [/pricing](https://www.goodesign.io/pricing).

## Languages

The site serves seven locales. Every one of them carries the same 183 pages — the style library, the task pages, the knowledge hub, and the legal pages — with `hreflang` alternates and an `x-default`. The localized pages are reached through a path prefix, so a reader lands on their own language version of a page rather than on a translated stub.

| Locale | Entry point |
|---|---|
| English (default, no prefix) | [www.goodesign.io](https://www.goodesign.io) |
| 日本語 | [/ja](https://www.goodesign.io/ja) |
| 한국어 | [/ko](https://www.goodesign.io/ko) |
| Deutsch | [/de](https://www.goodesign.io/de) |
| Français | [/fr](https://www.goodesign.io/fr) |
| Español | [/es](https://www.goodesign.io/es) |
| العربية (right-to-left) | [/ar](https://www.goodesign.io/ar) |

Slugs stay in English across all locales, so `/ja/virtual-staging` and `/de/virtual-staging` are the same page in two languages.

## For builders, and for the bots

- **`llms.txt`** is published at [www.goodesign.io/llms.txt](https://www.goodesign.io/llms.txt), and the crawler policy in [robots.txt](https://www.goodesign.io/robots.txt) allows the major AI and answer-engine user agents rather than blocking them.
- **Structured data.** The pricing page ships a `Product`/`Offer` block with the five tiers and prices, so a model or a search engine reads the numbers instead of guessing them from markup.
- **Stack.** Next.js App Router with React Server Components and Tailwind CSS, a standalone build behind a reverse proxy and CDN. Per-locale content is served from static route directories, not from a cookie rewrite.
- **Not in this repository.** Application source, infrastructure addresses, keys, internal cost or model-tier detail, and anything about customer accounts. Ask before reusing any of the wording here.

## Contact

Questions about the product, or about this page: [hello@goodesign.io](mailto:hello@goodesign.io)

---

© Goodesign. All rights reserved. The text of this page and its translations may not be reproduced or redistributed without permission; linking to it is always fine.
