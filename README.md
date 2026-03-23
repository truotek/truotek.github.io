# truotek.github.io

Truotek marketing site built with Astro and deployed to GitHub Pages.

## Local development

1. Install dependencies with `npm install`
2. Start the dev server with `npm run dev`
3. Build for production with `npm run build`
4. Preview the production build with `npm run preview`

## Deployment

The repository includes a GitHub Actions workflow at `.github/workflows/deploy.yml`
that builds the Astro site and deploys the `dist/` directory to GitHub Pages.

For the custom domain:

- `public/CNAME` is set to `truotek.com`
- `astro.config.mjs` uses `https://truotek.com` as the site URL

## First content tweaks to make

- Update the contact email in `src/pages/index.astro`
- Refine the service copy once your offerings are sharper
- Add case studies, testimonials, or a writing section later if you want more depth
