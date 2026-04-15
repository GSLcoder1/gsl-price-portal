# GSL Price Portal

Garden State Lumber Products Corp. — Customer Price Portal

## Architecture
- **Single-file app**: `index.html` contains all React code, compiled in-browser via Babel
- **Backend**: Supabase (PostgreSQL) for product data, pricing tiers, settings
- **Hosting**: Netlify (auto-deploys from this repo)
- **No build step required** — just static file serving

## How to Update
1. Replace `index.html` with the new version
2. Commit and push to `main`
3. Netlify auto-deploys in ~30 seconds
4. Refresh your browser to see changes

## Local Testing
Just open `index.html` in any browser. It connects to Supabase directly.

## Version History
- **V20** (April 15, 2026) — Supabase backend, per-section pricing, S4S product line blocks, sticky markup bar
