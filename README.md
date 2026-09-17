# SECRET — privacy is normal

Single-page site for the $SECRET memecoin. Zcash-inspired, purple/orange, shielded-by-vibes.

- `index.html` — the whole site (no build step, no dependencies beyond Google Fonts)
- Community: [𝕏 @secretcoinzec](https://x.com/secretcoinzec)

## Run locally

Open `index.html` in a browser, or:

```
python3 -m http.server 8000
```

## Deploy

Any static host works — GitHub Pages, Netlify, Vercel, Cloudflare Pages. Just serve `index.html` at the root.

## Notes

- All motion is disabled under `prefers-reduced-motion`.
- The contract address lives in one place (`#caText` in `index.html`) — update it there when it's announced.
