# KanaSprint

A kana reading practice app. The current version stores practice progress in this browser.

## Deploying to Cloudflare Workers
This repository is configured for Cloudflare Workers Static Assets. In Cloudflare's setup, use:
- Build command: leave blank
- Deploy command: `npx wrangler deploy`

## Cloud sync
The sign-in UI is included as a placeholder. To enable cross-device sync, create a Supabase project, configure authentication, add the project URL and anon key in `app.js`, and implement per-user progress storage with row-level security. Do not put a service-role key in browser code.

## Notes
This is an initial portfolio-ready prototype. Review and test the content and adaptive learning logic before inviting public users.
