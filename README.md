# LorenzoAicardi.github.io

Source for my personal portfolio site.

## Deploy on GitHub Pages

1. Create a new GitHub repository named exactly `LorenzoAicardi.github.io`.
2. Put `index.html` in the root of that repo and push it to the `main` branch.
3. In the repo, go to **Settings → Pages**, and under "Build and deployment" set:
   - Source: `Deploy from a branch`
   - Branch: `main`, folder `/ (root)`
4. Wait a minute or two — the site will be live at `https://LorenzoAicardi.github.io`.

## Before you publish, update these placeholders in `index.html`

- `your.email@example.com` in the Contact section (search for `mailto:`)
- `linkedin.com/in/your-linkedin` link in the Contact section
- The four project repository links (currently `href="#"`) — point them at the real GitHub repos
- Optional: swap the "Currently" line under About if you want it to name your employer

## Notes

- Single file, no build step — just `index.html`. The hero animation uses Three.js loaded from a CDN.
- Fonts are loaded from Google Fonts (Space Grotesk, Inter, IBM Plex Mono).
- Fully responsive; the hero canvas and project layout stack on mobile.
