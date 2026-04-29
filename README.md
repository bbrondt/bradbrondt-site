# bradbrondt.com — Astro Starter

Personal brand website for Brad Brondt — mortgage loan officer, founder of Cerberus CRM and WebinarFuse.

## Stack
- [Astro](https://astro.build) v4
- Vanilla CSS (no framework — design tokens in `src/styles/global.css`)
- Fonts: Cabinet Grotesk (display) + Satoshi (body) via Fontshare CDN

## Getting Started

```bash
npm install
npm run dev
```

Site runs at `http://localhost:4321`

## Build for Production

```bash
npm run build
npm run preview
```

## Pages

| Page | File | Purpose |
|---|---|---|
| Home | `src/pages/index.astro` | Main landing page |
| About | `src/pages/about.astro` | Brad's story & credentials |
| Webinar | `src/pages/webinar.astro` | Home Buyer Readiness Webinar registration |
| Contact | `src/pages/contact.astro` | Contact info & FAQ |
| 404 | `src/pages/404.astro` | Not found page |

## TODO — Before Going Live

Search the codebase for `TODO:` comments. Key items:

- [ ] Replace `[ADD DATE HERE]` on homepage with real next webinar date
- [ ] Add your photo in `about.astro` and `webinar.astro`
- [ ] Replace placeholder testimonials with real client quotes
- [ ] Add real podcast logo images in the media bar
- [ ] Paste your WebinarFuse/registration embed code into `webinar.astro` inside `#webinar-embed`
- [ ] Update social media handles/URLs if any have changed
- [ ] Add real podcast names to the media bar
- [ ] Replace `[Client Name]` in testimonials with real names (with permission)
- [ ] Add `og-image.png` (1200x630) to `public/` for social sharing previews
- [ ] Add `apple-touch-icon.png` (180x180) to `public/`

## Deployment

### Vercel (Recommended — zero config)
1. Push to GitHub
2. Connect repo at [vercel.com](https://vercel.com)
3. Deploy — Vercel auto-detects Astro

### Netlify
1. Push to GitHub
2. Connect repo at [netlify.com](https://netlify.com)
3. Build command: `npm run build`
4. Publish directory: `dist`

### Custom domain
Set `bradbrondt.com` as your custom domain in Vercel or Netlify settings.

## Customization

### Colors
All colors are CSS custom properties in `src/styles/global.css` under `:root`. The primary accent is `--color-accent: #00d4d4` (cyan). Change this one value to update the accent color site-wide.

### Fonts
Fonts load from Fontshare CDN in `src/layouts/Base.astro`. Cabinet Grotesk is the display font, Satoshi is the body font.

### Adding pages
Create a new `.astro` file in `src/pages/`. Import `Base`, `Nav`, and `Footer` from the existing pages as a template.

## Brand Info

- **NMLS:** #242550
- **Company:** Acre Mortgage and Financial Inc. | NMLS #13988
- **DBA:** The Brondt Cook Group
- **Phone:** (856) 485-9603
- **Email:** bbrondt@acremortgage.com
- **Service area:** South Jersey + Philadelphia suburbs
