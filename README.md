# Roast-Mac Showcase

Static showcase site for **Roast-Mac** — a custom cross-platform replacement UI for ROAST-Master coffee roaster controller.

## What's inside
- `public/index.html` — Single-page showcase with embedded demo video and read-only recipe browser
- `public/demo.mp4` — 63-second UI walkthrough
- `public/recipes/` — 79 imported recipe JSON files (5 origins × 12 items × 5 roast levels)
- `public/recipes-index.json` — Pre-built tree index for the browser

## Deploy

### Vercel (one-click)
Click the button below after logging in to Vercel:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fnocturnecoffee%2Froast-mac-showcase)

Or via CLI:
```bash
vercel --prod
```

### Local preview
```bash
python3 -m http.server 3001 --directory public
```

## Limitation note
This is a **showcase only**. The actual control app must run on a computer on the same network as the roaster (Modbus TCP on 192.168.11.20:502). The showcase provides UI demo, recipe library browsing, and protocol documentation for fellow owners of the same machine.
