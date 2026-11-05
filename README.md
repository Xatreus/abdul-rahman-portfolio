# Abdul Rahman — Portfolio

A responsive, dark-themed personal engineering portfolio for **AI Engineering · Generative AI · AI Agents · DevOps · Cloud Engineering**.

## Features

- Animated hero, ambient gradients and scrolling technology ticker
- Responsive navigation and mobile menu
- Project cards with category filters and interactive detail modals
- Skills and engineering capability sections
- Education and certification links
- Scroll-triggered reveal animations
- No backend, build step or API key required

## Run locally

Python:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

Or use the VS Code Live Server extension.

## Deploy

This is a static site. It can be deployed to GitHub Pages, Netlify or Vercel.

### GitHub Pages (this repository)

The portfolio is hosted from the repository root using GitHub Pages.

1. Open **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Select the `master` branch and the `/(root)` folder.
4. Save. GitHub Pages publishes the site at:

   <https://xatreus.github.io/abdul-rahman-portfolio/>

5. Future commits pushed to `master` are published automatically. Allow a few minutes for a deployment to complete.

Keep the custom domain field empty unless you own a domain and intend to configure it.

### Alternative: GitHub Actions deployment

A workflow is also included at `.github/workflows/deploy-pages.yml`. If you choose to use that workflow instead of branch-based publishing, change **Settings → Pages → Build and deployment → Source** to **GitHub Actions**. Do not configure both deployment methods as competing sources.

## Customize

- Project content and category filters: `script.js`
- Layout and visual design: `styles.css`
- Profile copy, links and page structure: `index.html`

## Accuracy notes

Project descriptions are based on the public repository READMEs and supplied resume. Project status and implementation details should be checked against each repository before presenting the site as a production portfolio. Cloud and deployment skills are presented as experience areas, not claims that every project is deployed to production.

## License

MIT
