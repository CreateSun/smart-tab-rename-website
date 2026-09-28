# Tab Rename landing page

A framework-free, bilingual static site designed for Cloudflare Pages.

## Local preview

```bash
npm install
npm run dev
```

## Deploy to Cloudflare Pages

The site is served directly from the repository root — there is no build step.

Continuous deployment is configured in the Cloudflare Pages project `tab-rename`,
connected to the `CreateSun/smart-tab-rename-website` GitHub repository. Pushing to
`main` publishes the site.

| Setting | Value |
| --- | --- |
| Build command | *(empty)* |
| Build output directory | `/` |
| Root directory (advanced) | *(empty)* |

To publish manually instead, log in with `npx wrangler login` and run
`npm run deploy` from this directory. Note that `npm run deploy` deploys the
working tree, so any uncommitted change is published too.

The Chrome Web Store buttons point to the extension's submitted store item. They become installable once the item is published by Chrome Web Store review.
