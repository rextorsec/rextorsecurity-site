# rextorsecurity.com

Holding page for **Rextor Security** (the firm behind [Rextor Audit](https://rextoraudit.com)) while the full site is under development.

- Static single `index.html` — no build step, no dependencies.
- Serves `/.well-known/security.txt`.
- Deploy: Vercel (project `rextorsecurity-site`), prod on push to `main`.
- DNS: Cloudflare (`rector@rectorspace.com` account) → Vercel records.
