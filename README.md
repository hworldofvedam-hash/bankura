# Sri Sathya Sai Seva Organisation - Bankura District Portal

Official web portal for Sri Sathya Sai Seva Organisation, Bankura District, West Bengal.

## Quick Start (Local Development)

```bash
# 1. Install dependencies
npm install

# 2. Start dev server
npm run dev
```

## Deploying to Cloudflare Pages (Free Hosting)

1. Push this repository to GitHub.
2. Log in to Cloudflare Dashboard -> Workers & Pages -> Create application -> Pages -> Connect to Git.
3. Select this repository.
4. Set Build Settings:
   - Framework Preset: Vite
   - Build command: npm run build
   - Build output directory: dist
5. Click Save and Deploy. Your site will be live on a free *.pages.dev subdomain with free SSL.
6. To get a short custom subdomain, go to your project's Settings and change the project name,
   or add your own domain under the Domains tab.
