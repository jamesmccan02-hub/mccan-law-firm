# mccan-law-firm
Website for McCan Law Firm specializing in recovering crypto assets for clients scammed in crypto. Professional legal services and expertise in crypto recovery.

## Deployment Instructions

### Primary Method: Vercel Deployment

1. **Sign up for Vercel**
   - Go to [vercel.com](https://vercel.com) and create a free account
   - Connect your GitHub account

2. **Import Repository**
   - Click "New Project" in Vercel dashboard
   - Select `mccan-law-firm` repository
   - Vercel will automatically detect it as a static site

3. **Configure Domain**
   - Add your custom domain in Project Settings > Domains
   - Follow DNS configuration instructions provided by Vercel

4. **Confirm HTTPS**
   - Vercel automatically provisions SSL certificates
   - Your site will be available at both vercel.app subdomain and custom domain
   - All traffic is automatically redirected to HTTPS

### Fallback Method: GitHub Pages

If Vercel is unavailable, the site can be deployed using GitHub Pages:

1. **Enable GitHub Pages**
   - Go to repository Settings > Pages
   - Source: Deploy from a branch
   - Branch: `main` / root

2. **Automated Deployment**
   - The `.github/workflows/deploy.yml` workflow handles automatic deployment
   - Every push to main triggers a new deployment
   - Site will be available at: `https://jamesmccan02-hub.github.io/mccan-law-firm/`

3. **Custom Domain (Optional)**
   - Add CNAME file to repository root with your domain
   - Configure DNS records with your domain provider
   - Enable "Enforce HTTPS" in repository settings
