# Senior PM Prep Tracker

A 12-week tracker for Senior PM / AI PM interview prep. It's a single HTML file with no build step and no dependencies.

## Features
- 6 phases with checkboxes and free resources (YouTube, courses, reading)
- Practice counters with targets: SQL, metric cases, mocks, referrals and more
- Study streak calendar (last 84 days)
- Notes, and backup/restore through copy-paste JSON

Progress is saved in your browser's `localStorage`.

## Run locally
Open `index.html` in a browser, or:

```bash
python3 -m http.server 8080
```

## Deploy
- **GitHub Pages:** Settings → Pages → deploy from the `main` branch, `/root`
- **Netlify / Vercel:** import the repo; there's no build command and the output directory is `/`
