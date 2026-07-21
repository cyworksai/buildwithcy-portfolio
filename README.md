# Build With Cy — Portfolio

Personal portfolio website for Cyrah Fajardo, Shopify Builder & E-commerce Implementation Specialist.

## Setup

1. Clone this repo
2. Open in VS Code
3. Make edits to `index.html`
4. Push to GitHub — Netlify auto-deploys

## To update content

All content is in `index.html`. Search for these to find what to edit:

- **Your photo** → find the 👩‍💻 emoji and replace with an `<img>` tag
- **Case studies** → search for `DRIVECRAFT`, `PAWPOPS`, `CUSTOM E-COMMERCE`
- **Testimonials** → search for `Awaiting verified testimonial`
- **Contact links** → search for `buildwithcy@gmail.com`

## To connect the contact form

1. Sign up at https://formspree.io
2. Create a new form and copy your endpoint URL
3. In `index.html`, find the `<form>` tag and add `action="YOUR_FORMSPREE_URL" method="POST"`
4. Remove the `e.preventDefault()` line in the script at the bottom

## Deployment

Connected to Netlify via GitHub. Every push to `main` triggers a redeploy automatically.
