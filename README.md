# SwiftHog App Store Website

Static website scaffold for GitHub Pages with the pages typically required by Apple App Store and Google Play submissions.

## Included pages

- `/` Home / product overview
- `/privacy/` Privacy Policy
- `/terms/` Terms of Use
- `/support/` Support and contact

## 1) Create a new public GitHub repository

Recommended repo name: `swifthog-site`

## 2) Copy this folder into that new repo

Copy all files from `app-store-site/` into the root of the new repository.

## 3) Enable GitHub Pages

In the new repo:

1. Go to **Settings** -> **Pages**
2. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
3. Save

## 4) Attach custom domain

This scaffold includes a `CNAME` file set to:

`swifthog.com`

In **Settings -> Pages**, set custom domain to `swifthog.com` and enable HTTPS.

## 5) DNS records at your domain registrar

For root domain (`swifthog.com`), point A records to GitHub Pages:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

Optional `www` subdomain CNAME:

- Host: `www`
- Value: `<your-github-username>.github.io`

Then configure forwarding/redirect from `www` to root (or vice versa) at your registrar if desired.

## 6) Replace placeholders

Before going live, update:

- `support@swifthog.com`
- Company/legal entity text
- Effective dates
- Product description details

## Suggested app-store links to submit

- Marketing URL: `https://swifthog.com`
- Privacy Policy URL: `https://swifthog.com/privacy/`
- Support URL: `https://swifthog.com/support/`

