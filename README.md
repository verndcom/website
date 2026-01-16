# Vernd LLC Static Site

This is a lightweight static website for Vernd LLC.

## Deploy to GitHub Pages

Option A: Pages on a custom domain (recommended for vernd.com)
1. Create a repo (example: `vernd.com` or `vernd-site`).
2. Add these files to the repo root and push.
3. In GitHub: Settings -> Pages
   - Source: Deploy from a branch
   - Branch: `main` and folder `/ (root)`
4. Set Custom domain to `vernd.com`.
5. In DNS, add the records GitHub recommends for your setup.
6. Enable HTTPS in Pages after DNS is verified.

Option B: Project Pages (served under `/repo-name/`)
- This template uses root-style links, so it works best when served from the domain root.

## Edit content

- `index.html` Home
- `about.html` About
- `services.html` Services and products
- `careers.html` Careers
- `privacy.html` Privacy Policy
- `terms.html` Terms of Service
- `assets/style.css` Styling
- `assets/site.js` Mobile navigation
