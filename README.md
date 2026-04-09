# BINGUTA — Future Innovations

**Defense Technology Venture Capital**  
Website: [binguta.com](https://binguta.com)

---

## Overview

Single-page marketing website for Binguta Future Innovations — a venture capital firm investing in next-generation defense and security technologies across NATO and EU markets.

---

## Tech Stack

- Pure HTML / CSS / Vanilla JS — zero frameworks, zero dependencies
- Google Fonts: Bebas Neue, Barlow, Barlow Condensed
- Hosted on: Netlify (primary) / Hostinger (production domain)

---

## Project Structure

```
binguta-fi/
│
├── index.html              # Main website (single page)
│
├── assets/
│   ├── images/             # All images go here
│   │   ├── hero/           # Hero section backgrounds
│   │   │   └── hero-bg.jpg
│   │   ├── focus/          # Focus area card images
│   │   │   ├── vtol.jpg
│   │   │   ├── fpv.jpg
│   │   │   ├── cuas.jpg
│   │   │   ├── radar.jpg
│   │   │   ├── dew.jpg
│   │   │   └── dualuse.jpg
│   │   └── logo/           # Logo files
│   │       ├── binguta-logo-dark.png
│   │       └── binguta-logo-light.png
│   │
│   ├── css/                # Reserved for future CSS split-out
│   └── fonts/              # Reserved for self-hosted fonts
│
├── .gitignore
└── README.md
```

---

## Sections

| # | Section | ID | Description |
|---|---|---|---|
| 1 | Navigation | — | Fixed top bar with CTA |
| 2 | Hero | `#home` | Full-screen headline + radar animation |
| 3 | Ticker | — | Scrolling focus area banner |
| 4 | Investment Thesis | `#thesis` | Dual-use / scalable / deployable |
| 5 | Focus Areas | `#focus` | 6-card investment verticals |
| 6 | NATO Mandate | `#mandate` | Built for NATO, scaled across Europe |
| 7 | Founder Criteria | `#approach` | What we look for in founders |
| 8 | CTA / Contact | `#contact` | Email capture |
| 9 | Footer | — | Links + contact |

---

## Deployment

### Netlify (recommended for preview/staging)
1. Connect this repo to Netlify
2. Build command: *(none — static site)*
3. Publish directory: `/` (root)
4. Auto-deploys on every push to `main`

### Hostinger (production)
1. Upload `index.html` + `assets/` to `public_html/`
2. Point domain DNS to Hostinger nameservers
3. Enable SSL in hPanel

---

## Adding Images

When AI-generated images are ready, place them in `assets/images/` per the structure above, then update `index.html`:

**Hero background:**
```html
<!-- In .hero-bg div, add: -->
background-image: url('assets/images/hero/hero-bg.jpg');
```

**Focus card images:**
```html
<!-- Replace emoji icon in each .fi block with: -->
<img src="assets/images/focus/vtol.jpg" class="fi-img" alt="VTOL Drone Systems">
```

---

## Brand

- **Primary color:** `#c8a96e` (gold)
- **Background:** `#020304` (near-black)
- **Accent:** `#7eb8d4` (steel blue)
- **Fonts:** Bebas Neue (display) · Barlow Condensed (labels) · Barlow (body)

---

## Roadmap

- [ ] Add AI-generated images to focus cards
- [ ] Add hero background image
- [ ] Connect contact form to backend (Formspree / Netlify Forms)
- [ ] Add portfolio companies section
- [ ] Add team / about page
- [ ] SEO meta tags + Open Graph images
- [ ] Analytics (Plausible / GA4)

---

*© 2026 Binguta Future Innovations. All rights reserved.*
