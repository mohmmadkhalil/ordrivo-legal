# Ordrivo Courier — Legal Pages

Static privacy policy and terms of service pages for the Ordrivo Courier mobile app, hosted via
GitHub Pages. Content is kept in sync with the in-app legal screens
(`app/privacy.tsx` / `app/terms.tsx` in `ordrivo-courier2`).

- `index.html` — Privacy Policy
- `terms.html` — Terms of Service

## Publishing

GitHub Pages must be enabled once, manually, in this repo's **Settings → Pages**:
set **Source** to "Deploy from a branch", **Branch** to `main` / `(root)`, then save.
The site becomes available at `https://mohmmadkhalil.github.io/ordrivo-legal/` within a few
minutes.

## Updating

Edit the relevant `.html` file to match the current in-app copy, commit, and push to `main` —
GitHub Pages redeploys automatically on every push.
