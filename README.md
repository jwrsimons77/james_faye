# James Faye · Product Owner — Portfolio

Single-page portfolio site. No build step, no dependencies to install —
one self-contained `index.html` (Google Fonts is the only external resource).

## The parody password gate
The site opens with a tongue-in-cheek "Suspicious visitor ahead" screen.
Passphrase: **takedown** (change it in `index.html`, look for `GATE_PASS`).
Note: this is client-side only and cosmetic. Anyone can view-source it.
Real password protection on Netlify requires a paid plan.

## Run locally
Just open `index.html` in a browser, or:
```
npx serve .
```

## Deploy to Netlify

**Option A — drag and drop (fastest):**
1. Go to https://app.netlify.com/drop
2. Drag this whole folder onto the page
3. Done — Netlify gives you a live URL instantly (rename it under Site settings → Change site name)

**Option B — from Git (auto-deploys on every push):**
1. Push this repo to GitHub
2. In Netlify: Add new site → Import an existing project → pick the repo
3. Build command: *leave empty* · Publish directory: `.`
4. Deploy — every future `git push` redeploys automatically

## Custom domain
Netlify → Domain settings → Add custom domain, then follow the DNS instructions.
