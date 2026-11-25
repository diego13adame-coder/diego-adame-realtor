# Diego Adame, Realtor

Personal real estate page for **Diego Adame** (CA DRE 02145151), based in North Hollywood, CA 91605.

- **Call / Text:** 562-832-2366
- **Email:** diego@partner.realestate
- **TikTok:** [`@adame13realtor`](https://www.tiktok.com/@adame13realtor)
- **Languages:** English & Spanish (*Se habla español*)
- **Service Areas:** NoHo, Pico Rivera, Downey, Whittier, Norco

## Structure

- `index.html` — Responsive page with mobile above-the-fold Call & Text CTAs, `RealEstateAgent` JSON-LD, and Open Graph tags (zero analytics)
- `styles.css` — Responsive stylesheet tuned for mobile (390px) and desktop (1280px+)
- `assets/diego-adame-headshot.jpg` — Agent headshot
- `assets/og-image.png` — 1200×630 Open Graph preview image
- `assets/favicon.svg` — Site icon
- `scripts/verify.mjs` — Local static build & verification check

## Local verification

```bash
npm run build
```

Serve locally with any static server, e.g.:

```bash
npx serve .
# or
python3 -m http.server 4174
```
