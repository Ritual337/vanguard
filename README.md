# Vanguard

A small friend group that met in [Warpath](https://warpath.lilith.com/official), the
modern-war strategy game by Lilith Games. One camp, one alliance, no membership form.

Published at **https://vngs.pages.dev/**.

## Pages

| File | What it is |
| --- | --- |
| `index.html` | Home and About: who the group is, and what Warpath is |
| `Ritual.html` | Standalone page |
| `R3dc0re.html` | Standalone page |

## Stack

Plain HTML, CSS and vanilla JS — no build step. Fonts come from Google Fonts and
`anime.js` from cdnjs. The design is monochrome by choice: grain, halftone canvas,
scanline, corner marks, UTC clock.

## Local preview

```sh
npm install
npm run dev        # http://localhost:4323
```

## Deploy

Cloudflare Pages, project `vngs`:

```sh
npm run deploy
```

The site is served straight from the repository root, so any static host works too.
