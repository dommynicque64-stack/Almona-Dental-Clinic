# Almona Dental Clinic Website

A modern, mobile-responsive, static marketing website for Almona Dental Clinic,
a dental clinic located at Kull Plaza, Twelfth St, Nairobi, Kenya.

## Structure
- `index.html` — main page (hero, about, services, why choose us, reviews, location, patient info, appointment form, contact, footer)
- `css/styles.css` — styling (solid colors only, no gradients, per brand guidelines)
- `js/main.js` — mobile nav, scroll animations, appointment form handling
- `images/` — site imagery

## Running locally
This is a fully static site — no build step required. To preview locally:

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deployment
Deployable as-is to any static host (Vercel, Netlify, GitHub Pages, etc.).
No environment variables or backend are required for the site to render.

Note: the appointment form currently runs client-side only (shows a success
message, does not send data anywhere). To actually receive submissions in
production, connect it to a form backend (e.g. Netlify Forms, Formspree, or
a custom API endpoint) and update `js/main.js` accordingly.

## Editable / pending clinic confirmation
- Exact list of dental services offered
- Full opening hours (only closing time, 8:30 PM, was provided)
- Official Google Business review link
