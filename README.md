# Syphotron

Responsive static landing page for syphotron.com, using the approved mint-on-navy logo. Plain HTML and CSS; no installation, build dependencies, tracking, external fonts or backend.

## Cloudflare Pages deployment

1. In Cloudflare, open Workers & Pages and create a Pages project connected to this GitHub repository.
2. Production branch: main. Framework: None. Build command: exit 0. Build output directory: . (repository root).
3. Deploy and check the pages.dev address.
4. Open the project's Custom domains and add syphotron.com. Let Cloudflare complete the DNS setup. Check existing records before changing them.
5. Optionally add www.syphotron.com through the same flow, then create a redirect from www to the apex domain.

The repository does not automatically change DNS. Associate the domain with the Pages project before manually adding any CNAME.

Official docs:
- https://developers.cloudflare.com/pages/framework-guides/deploy-anything/
- https://developers.cloudflare.com/pages/configuration/custom-domains/

## Editing

Open index.html directly to preview. Edit copy in index.html and colors/layout in styles.css. The launch date is October 27, 2026. The logo is the approved generated raster artwork, framed with CSS for the header and symbol. Replace with production transparent/vector assets when available.

The page avoids unverified products, customer claims and nonfunctional signup forms. Add contact links when a working destination is confirmed.

All branding assets are supplied for Syphotron's use. No open-source license is granted.
