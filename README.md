# TD Plumbing Solutions - Standalone

This is a 100% standalone build - no Lovable, no React, no tracking.

## What's removed:
- `events.js` (Lovable analytics)
- `flock.js` (Lovable telemetry)
- `index-Wr4Q3P_b.js` (React bundle) - content is now static HTML
- All `data-*` lovable attributes

## Structure:
- index.html - clean static site
- styles.css - Tailwind CSS compiled (original)
- assets/ - images

## To deploy:
Just upload the folder to any static host (Netlify, Vercel, Cloudflare Pages, cPanel, S3).

No build step needed.
