# Marrajo Holdings

Corporate website for Marrajo Holdings, a privately held investment and holding company.

A single, self-contained `index.html` with five views (Home, About, Investment Approach, Portfolio, Contact) routed by URL hash. Scroll choreography uses GSAP 3.12.5 and ScrollTrigger from cdnjs; with reduced motion, or if the CDN is unavailable, the page falls back to a complete static layout.

Photography is loaded from Pexels (free licence, credited in the site footer). To use your own images, replace the `images.pexels.com` URLs in `index.html`.

## Editing content

Open `index.html` and find the `EDITABLE CONTENT` block near the top of the script:

- `CONTACT`: email, telephone, office address, and an optional form `endpoint` (any service that accepts a JSON POST, such as Formspree). Until an endpoint is set, the contact form validates and shows the composed message but sends nothing.
- `SECTORS`: areas of interest shown on Home and Portfolio.
- `HOLDINGS`: add one object per confirmed holding to replace the reserved profile frames.

## Hosting

Served from GitHub Pages on the `main` branch root.
