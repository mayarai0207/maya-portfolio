# Maya Rai — Portfolio

Single-page portfolio. Static site: no build step, no dependencies to install.

## Structure

- `index.html` — the whole design (About + Work views, four project overlays, password gates, scroll reveals)
- `support.js` — runtime that renders the page (self-contained, vendored here)
- `uploads/` — images and video
- `vercel.json` — clean URLs + long-lived caching for assets

## Deploying to Vercel

Import the repo. No framework preset, no build command, output directory `.` — Vercel serves it as static files.

## Local preview

```
python3 -m http.server 8000
```

Then open http://localhost:8000
