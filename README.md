# nicewebsite.tech

A responsive landing page that deploys to Cloudflare Workers Static Assets.

## Deploy

This project is configured for the Cloudflare **Workers** build command already shown in the dashboard:

- Build command: none
- Deploy command: `npx wrangler deploy`
- Root directory: `/`

Commit the files to the connected GitHub repository `FlameFragger414/my-website` on `main`. Cloudflare will automatically build and deploy after it can clone the repository. If necessary, select **Retry build** in the Cloudflare dashboard.

Edit `public/index.html` to customize the website.

## Custom domain

After successful deployment, go to Cloudflare Workers & Pages > my-website > Domains to connect `nicewebsite.tech`.
