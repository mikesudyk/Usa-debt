# US National Debt — Living Timeline

Interactive, expandable timeline of U.S. national debt history, the shift from gold/silver standards to managed fiat money, the role of wars, and the current and projected fiscal path.

Built as a family curriculum resource with age-tiered explanations (younger story level and older mechanism/reasoning level) inside each event.

## Features
- Vertical interactive timeline
- Filter by era
- Expandable cards with age-appropriate content
- Self-contained single HTML file (no build step)

## Deployment
Static site — works directly with Cloudflare Pages, GitHub Pages, Netlify, or any static host.

1. Push this repo to GitHub.
2. In Cloudflare: Workers & Pages → Create application → Pages → Connect to Git → select this repo.
3. Build settings: None / blank build command, output directory `/`.
4. Add custom domain if desired.

## Local preview
Open `index.html` in any browser.

## Updating
Edit `index.html` and push. Cloudflare Pages (or similar) will auto-deploy.
