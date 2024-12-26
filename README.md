# astro-cloudflare-pages-template

This is a template for Astro Cloudflare Pages.

## Getting Started

1. Rename the files in the project to the name of your app.

   ```bash
   pnpx replace-in-file "astro-cloudflare-pages-template.gtp.dev" "MY_DOMAIN" "./**/*.*" --verbose
   pnpx replace-in-file "astro-cloudflare-pages-template" "MY_APP" "./**/*.*" --verbose
   ```

2. Add the required environment variables to the `.env` file (see `.env.example` for reference).

3. If you're an external party and want to use this template, replace the `PUBLIC_FATHOM_SITE_ID` in the `wrangler.toml`
   file with your own Fathom site ID.

4. Install dependencies

   ```bash
   pnpm i
   ```
