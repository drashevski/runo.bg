# Руно / Runo

Static website for **Runo** — handmade crafts from natural materials (wood, wool, jewelry, icons), based in Sofia, Bulgaria.

Live at: [runo.bg](https://runo.bg)

## Tech stack

- Plain HTML5, CSS3, and vanilla JavaScript — no build step required
- Bilingual (Bulgarian / English) via a client-side language toggle
- Hosted on GitHub Pages with a custom domain

## Project structure

```
runo.bg/
├── index.html                  # Single-page site
├── css/
│   └── style.css
├── images/
│   ├── favicon/                # Favicon + web manifest
│   ├── logo-cover/             # Logo and branding images
│   │   └── source/             # Illustrator & PDF source files (not published)
│   └── sample-products/        # Product photos used in the gallery
├── CNAME                       # Custom domain (runo.bg)
├── .nojekyll                   # Disables Jekyll processing on GitHub Pages
└── .gitignore
```

## Local development

No setup needed — just open `index.html` in a browser.

## Deployment

The site is deployed automatically by GitHub Pages on every push to `main`.
Custom domain is configured via the `CNAME` file and DNS records pointing to GitHub's servers.

## Pending configuration

Before the site is fully functional, the following placeholders need to be replaced in `index.html`:

| Placeholder | Location | What to replace with |
|---|---|---|
| `https://www.instagram.com/` | Nav, contact, footer | Actual Instagram profile URL |
| `https://www.facebook.com/` | Contact, footer | Actual Facebook page URL |
| `https://www.etsy.com/` | Nav, gallery, footer | Actual Etsy shop URL |
| `YOUR_WEB3FORMS_ACCESS_KEY` | Hidden `access_key` input in contact form | Access key from [web3forms.com](https://web3forms.com) |
