# Build With Cy — Portfolio v2

Refined, conversion-focused portfolio for Cyrah Fajardo, Shopify Builder + E-commerce Implementation Specialist.

---

## Before Going Live — Required Steps

### 1. Connect the Contact Form
The form currently shows an error message until a backend is connected.
**Recommended: Formspree (free tier)**
1. Sign up at https://formspree.io
2. Create a new form and copy your endpoint (e.g. `https://formspree.io/f/xyzabcde`)
3. In `index.html`, find the comment `<!-- FORM INTEGRATION REQUIRED -->`
4. Replace the fake submit handler with a `fetch()` POST to your Formspree endpoint

### 2. Add Real Photos
Drop photos into the `images/` folder (one level up, in the parent `buildwithcy-portfolio/` folder).
The v2 page references them as `../images/filename.jpg`.

| File | What it is |
|------|-----------|
| `cyrah-hero.jpg` | Professional headshot — clear face, clean background |
| `cyrah-about.jpg` | Working or candid photo at desk |
| `drivecraft.jpg` | DriveCraft storefront screenshot (desktop, above the fold) |
| `pawpops.jpg` | PawPops store screenshot |
| `custom-ecommerce.jpg` | Custom system dashboard or storefront screenshot |

### 3. Add Google Analytics (optional)
Paste your GA4 snippet in the `<head>` before the closing `</head>` tag.
The `track()` function already calls `gtag()` if it's available.

### 4. Update the Privacy Notice
If the form stores user data (Formspree does), update the footer Privacy Notice link to point to a real privacy page or policy.

---

## Deploying to Netlify

1. Push your `buildwithcy-portfolio/` folder to GitHub
2. Log in to Netlify → Add new site → Import from GitHub
3. Set publish directory to `v2` (or move `v2/index.html` to root and rename)
4. Deploy

---

## Updating Content

All content is in `v2/index.html`. Sections are clearly commented:
- `<!-- HERO -->` — headline, copy, CTAs
- `<!-- EVIDENCE STRIP -->` — 3-step process strip
- `<!-- FEATURED CASE STUDY: DRIVECRAFT -->` — main case study
- `<!-- ADDITIONAL WORK -->` — PawPops + Custom System
- `<!-- WAYS TO WORK TOGETHER -->` — 3 service paths
- `<!-- MERCHANT PERSPECTIVE -->` — personal differentiator
- `<!-- STOREFRONT REVIEW DEMO -->` — annotated mockup
- `<!-- WORKING STANDARDS -->` — 6-stage process
- `<!-- AGENCY COLLABORATION -->` — agency section
- `<!-- ABOUT -->` — bio + details
- `<!-- FAQ -->` — 8 questions
- `<!-- CONTACT -->` — final inquiry form
- `<!-- FOOTER -->` — links + copyright
