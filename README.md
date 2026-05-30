# World Time Zone Converter

A fast, single-file web app to convert and compare time across any time zone worldwide.

- 🕐 **Live local clock** — auto-detects your time zone and ticks in real time
- 🔄 **Time converter** — convert any date/time between two zones (DST handled automatically)
- 🌍 **World clocks** — add/remove cities and watch them update live, with +1/−1 day badges
- 📈 **SEO-ready** — Open Graph + Twitter cards, JSON-LD (WebApplication + FAQ), sitemap & robots

## Tech

Pure HTML/CSS/JavaScript — no build step, no dependencies. All time-zone math uses the
browser's built-in `Intl` / IANA time-zone database.

## Local preview

Just open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy

Static site — deploys to Vercel (or any static host) with zero configuration.

---

🤖 Built with [Claude Code](https://claude.com/claude-code)
