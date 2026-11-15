# Landing page — AI-built app launch audit (EN/TR)

Static, single file (index.html) + Tailwind via CDN. No build step.
Language: EN/TR toggle; `?lang=tr` or `?lang=en` forces a language; otherwise browser language.

## Before publishing, replace placeholders
- `{{BOOKING_URL}}` (2x) → e.g. Cal.com link
- `{{CONTACT_EMAIL}}` → contact address
- `{{UPWORK_URL}}` → https://www.upwork.com/freelancers/~01fc934a613be9241e
- Package prices are suggestions; edit to taste.

## Publish on GitHub Pages
1. Create a public repo, e.g. `aykutmayali/launch-audit` (or `aykutmayali.github.io` for a root URL).
2. Copy `index.html`, `.nojekyll`, `README.md` to the repo root; commit and push to `main`.
3. Repo → Settings → Pages → Source: "Deploy from a branch" → `main` / `(root)` → Save.
4. After ~1 min: https://aykutmayali.github.io/launch-audit/ (or https://aykutmayali.github.io/).
5. Optional custom domain: add a `CNAME` file with the domain, set DNS CNAME to `aykutmayali.github.io`, enable "Enforce HTTPS".

Note: Tailwind Play CDN is fine for a landing page; for production polish, swap to a compiled Tailwind CSS file later.
