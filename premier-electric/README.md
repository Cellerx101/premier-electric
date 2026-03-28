# Premier Electric — Contractor Website

Single-page website for an electrical contracting business. Built with vanilla HTML/CSS/JS — no frameworks, no dependencies.

## Services Featured
- Commercial Electrical
- Electrical Panels & Draws
- Detach & Reset
- Maintenance & Troubleshooting
- EV Charger Installation

## Deploy to Netlify
1. Push this repo to GitHub
2. Log in to [Netlify](https://app.netlify.com)
3. Click **Add new site** → **Import an existing project** → select this repo
4. Deploy settings: leave defaults (publish directory: `/`)
5. Site is live

## Connect Custom Domain
1. Buy domain on [Namecheap](https://namecheap.com)
2. In Netlify: **Site Settings** → **Domain Management** → **Add custom domain**
3. Update nameservers in Namecheap to point to Netlify
4. SSL is automatic

## Contact Form Setup
The form currently logs to console. To make it send emails:

### Option A: Netlify Forms (easiest)
Add `netlify` attribute to the `<form>` tag:
```html
<form id="quoteForm" netlify onsubmit="handleSubmit(event)">
```

### Option B: Formspree (free tier)
1. Sign up at [formspree.io](https://formspree.io)
2. Create a form, get your endpoint
3. Update the form action to your Formspree URL

## Swapping Placeholder Content
- **Business name:** Search and replace `Premier Electric` / `PREMIERELECTRIC`
- **Phone:** Replace `(469) 555-1234`
- **Email:** Replace `info@premierelectric.com`
- **Stats:** Update the numbers in the hero section
- **Photos:** Drop images in `/images` and replace the gallery placeholder divs with `<img>` tags

## Stack
- HTML5 / CSS3 / Vanilla JS
- Google Fonts (Plus Jakarta Sans + Space Mono)
- Zero dependencies
- Fully responsive

## License
Private client work.
