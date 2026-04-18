# mind.com.py

Website for mind.com.py, built with [Astro](https://astro.build) and deployed via GitHub Pages.

## Prerequisites

- Node.js >= 22.12.0

## Development

Install dependencies:

```sh
npm install
```

Start the dev server:

```sh
npm run dev
```

## Build

Build the static site for production:

```sh
npm run build
```

The output is generated in the `dist/` directory.

Preview the production build locally:

```sh
npm run preview
```

## Deployment

The site is automatically deployed to GitHub Pages on every push to `master` via the workflow in `.github/workflows/deploy.yml`.

### GitHub Pages setup

1. Go to the repo **Settings > Pages**
2. Set **Source** to **GitHub Actions**
3. Add a custom domain `mind.com.py` under **Custom domain** and enable **Enforce HTTPS**
4. Configure DNS with your provider:
   - `A` records pointing to GitHub Pages IPs (see [GitHub docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site))
   - `CNAME` record for `www` pointing to `simple-solutions-py.github.io`
