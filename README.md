# The Bottom Line

Landing site for **thebottomline.me** — by Tanaa Maul.

## Stack
Plain HTML/CSS/JS. No build step. Deployed on Vercel.

## Structure
- `index.html` — homepage (1:1 with Figma; assets embedded as base64 for portability)
- `my-work.html` / `case-studies.html` / `blog.html` — coming-soon placeholders
- `assets/` — icon PNGs (also embedded in HTML; folder kept for clarity / future use)
- `vercel.json` — clean URLs config

## Local preview
Just open `index.html` in a browser, or run a static server:
```bash
python3 -m http.server 8000
```

## Deploy
1. Push this repo to GitHub
2. Import the repo at https://vercel.com/new
3. Add `thebottomline.me` and `www.thebottomline.me` as custom domains
4. Point your DNS at Vercel

## Updating the WhatsApp link
In `index.html`, find `REPLACE_WITH_NUMBER` and replace with your number in international format with no `+` or spaces (e.g. `447712345678`).
