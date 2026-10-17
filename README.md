# OrchLane website

Static site for [OrchLane](https://github.com/Orchlane/orchlane-site): fractional vCISO, CPO and CIO leadership.

- `site/` — the website (plain HTML/CSS, no build step). Edit `site/index.html`.
- `.github/workflows/pages.yml` — deploys `site/` to GitHub Pages on every push to `main`.

Preview locally: `python3 -m http.server -d site 8000`, then open http://localhost:8000.
