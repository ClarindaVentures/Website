# Clarinda Park Ventures Website

Static HTML/CSS corporate website for Clarinda Park Ventures Limited.

## Stack

Hand-written static HTML and CSS with no build step, no JavaScript dependencies, and a single Google Fonts stylesheet link. The site consists of five core pages:

- `index.html` — landing page
- `about.html` — company background
- `contact.html` — contact details (email only, no form)
- `terms.html` — terms of service
- `privacy.html` — privacy policy
- `styles.css` — shared stylesheet

## Deployment

Two options:

1. **Cloudflare Pages** (recommended): Connect this GitHub repository to Cloudflare Pages. Set build command to "none" and output directory to "/" (the project root). Pages will serve the HTML files directly without processing.

2. **GitHub Pages**: Push to the main branch; GitHub Pages will serve the site from the repository root. Configure the custom domain `clarindaparkventures.com` in GitHub Pages settings. DNS is already configured on Cloudflare.

## Pending Configuration

The following items are clearly marked as `PLACEHOLDER` in HTML comments and must be completed before production launch:

- Company description paragraph (legal description of Clarinda Park Ventures Limited)
- Registered office address
- CRO registration number (Companies Registration Office of Ireland)

Additionally, the `robots` meta tag is currently set to `noindex` to prevent search engine indexing until the site is ready for public access. Update once all placeholders are filled.

## Email Setup

The contact page includes a link to `hello@clarindaparkventures.com`. This address must be configured via Cloudflare Email Routing (or another email provider) to deliver messages to the intended mailbox.

## Domain

Domain: `clarindaparkventures.com`
DNS: Hosted on Cloudflare
