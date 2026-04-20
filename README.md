# college-pitch

**FirstRole for Colleges** — The placement cell, reborn.

A premium, animated pitch deck for college TPOs and placement committees. Built with pure HTML/CSS/JS. Zero dependencies.

## 🚀 Live URL

[https://college-pitch.pages.dev](https://college-pitch.pages.dev)

## 📁 Structure

```
college-pitch/
├── index.html               ← Main pitch deck (12 slides)
├── FirstRole — Colleges.html  ← Source file
├── wrangler.toml            ← Cloudflare Pages config
├── _headers                 ← Security & cache headers
├── README.md
└── .github/
    └── workflows/
        └── deploy.yml       ← Auto-deploy on git push
```

## ⚡ Auto-Deploy Setup

Every push to `main` triggers an automatic Cloudflare Pages deployment via GitHub Actions.

### Required GitHub Secrets

Go to `Settings → Secrets → Actions` and add:

| Secret | Where to find it |
|---|---|
| `CLOUDFLARE_API_TOKEN` | CF Dashboard → My Profile → API Tokens → Create Token (use "Edit Cloudflare Pages" template) |
| `CLOUDFLARE_ACCOUNT_ID` | CF Dashboard → right sidebar → Account ID |

## 🛠️ Local Preview

Just open `index.html` in any browser — no build step required.
