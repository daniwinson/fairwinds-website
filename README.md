# Fairwinds Luxury Yacht Charter — Website

Static website (plain HTML + images). No build step required.

## Pages
- `index.html` — home (entry point)
- `fairwinds-patriciaann.html` — 47' PatriciaAnn
- `fairwinds-patron.html` — 73' Patron
- `fairwinds-cantius.html` — 50' Cantius
- `fairwinds-lessons.html` — Lessons
- `fairwinds-consulting.html` — Consulting
- `fairwinds-reviews.html` — Reviews
- `fairwinds-privacy.html` — Privacy Policy
- `fairwinds-terms.html` — Terms & Conditions

## Deploy to GitHub Pages
1. Create a new repository on GitHub.
2. Upload the entire contents of this folder to the repo (keep all files at the repo root so `index.html` sits at the top level).
3. In the repo: **Settings → Pages → Build and deployment**.
4. Set **Source** to "Deploy from a branch", choose your branch (e.g. `main`) and folder `/ (root)`, then **Save**.
5. Your site will publish at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Contact form
The charter inquiry form on `index.html` is wired to [Web3Forms](https://web3forms.com) and submits to your account automatically. It only works when the page is served over http(s) (i.e. once it's live on GitHub Pages) — not when opening the HTML file directly from disk.
