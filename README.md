# CircuitRP DOJ Internal Site (Static)

This is a static single-page app built using React + Tailwind via CDN so it can be hosted directly on **GitHub Pages** (no build step required).

## How to deploy on GitHub Pages

1. Create a new GitHub repository and push these files to the `main` branch (or any branch).
2. In repository **Settings → Pages**, set source to the `main` branch and root (`/`). Save.
3. Your site will be published at `https://<your-username>.github.io/<repo-name>/` (allow a minute).

> If you prefer a production-ready build (React project with npm, local bundling), I can provide that too — but this static CDN approach is the quickest for GitHub Pages.

## Features
- Welcome page, DOJ Expungement Calculator, DOJ Library (store Google Doc links in localStorage).
- Works on desktop and mobile (responsive).
- Smooth micro-animations and classified watermark in header/footer.
