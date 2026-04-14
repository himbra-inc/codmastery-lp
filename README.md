# COD Mastery — Landing Page

> **Cash on Delivery infrastructure for ecommerce sellers and dropshippers operating in MENA & LATAM markets.**

Live at: [codmastery.com](https://codmastery.com)

---

## Overview

This repository contains the static landing page for **COD Mastery** — a platform that provides experienced ecommerce sellers and dropshippers with live access to Cash on Delivery (COD) infrastructure across 14+ markets in MENA and LATAM.

The site is built with vanilla HTML, CSS, and JavaScript — no frameworks, no build step required.

---

## Pages

| File | URL | Description |
|------|-----|-------------|
| `index.html` | `/` | Main landing page |
| `apply.html` | `/apply.html` | Multi-step application form |

---

## Features

- ⚡ Zero dependencies — pure HTML/CSS/JS
- 📱 Fully responsive (mobile-first)
- 🔍 SEO optimized — meta tags, Open Graph, Twitter Card, JSON-LD structured data
- 📋 Multi-step application form with Google Sheets integration
- 🎥 Embedded VSL (Video Sales Letter)
- 🌍 14+ active markets displayed (MENA + LATAM)

---

## Structure

```
codmastery-lp/
├── index.html          # Main landing page
├── apply.html          # Application form
├── logo.jpg.html       # Logo asset
├── vsl-final.mp4.html  # VSL video
├── robots.txt.html     # Robots configuration
└── proof-images/       # Infrastructure proof images
    ├── web_photo1.jpg.html
    ├── web_photo2.jpg.html
    ├── web_photo3.jpg.html
    ├── web_photo4.jpg.html
    ├── web_img1.jpg.html
    ├── web_img2.jpg.html
    ├── web_screen1.png.html
    ├── web_screen3.png.html
    ├── web_screen4.png.html
    └── web_screen6.png.html
```

---

## Application Form Fields

The `apply.html` form collects the following data (mapped to Google Sheets):

| Field | Name | Type |
|-------|------|------|
| Full Name | `full_name` | Text |
| Email | `email` | Email |
| WhatsApp | `whatsapp` | Tel |
| Country | `country` | Select |
| Experience | `experience` | Radio |
| Ad Spend | `adspend` | Radio |
| GCC/LATAM Markets | `markets` | Radio |
| Capital | `capital` | Radio |
| Target Market | `market_target` | Radio |
| Goal | `goal` | Textarea |
| Referral Source | `referral_source` | Select |

---

## Deployment

This is a static site — deploy to any static hosting provider:

- **GitHub Pages** — push to `main`, enable Pages in repo settings
- **Netlify / Vercel** — connect repo, deploy automatically
- **Custom server** — upload files directly, no build needed

---

## Active Markets

**MENA (9):** Saudi Arabia, UAE, Bahrain, Qatar, Oman, Lebanon, Iraq, Morocco, Kuwait

**LATAM (5):** Colombia, Ecuador, Mexico, Panama, Costa Rica

---

## License

Private. All rights reserved © COD Mastery.
