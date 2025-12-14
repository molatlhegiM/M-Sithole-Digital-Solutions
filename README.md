# M-Sithole Digital Solutions

M-Sithole Digital Solutions is a small full-service digital agency focused on helping local businesses establish and grow their online presence. We design and build modern, responsive websites and provide complementary digital services including branding, e-commerce development, app/software development, social media content, and digital marketing.

**Core Services**

- Branding & Graphic Design: Logo creation, business profiles, flyers, business cards and marketing collateral.
- Website Design & Development: Responsive brochure sites, small business websites, landing pages, and e-commerce stores with payment and shipping integration.
- App & Software Development: Mobile and web app projects tailored to business workflows.
- Digital Marketing & SEO: Strategy, social media content, campaign management, and basic on-page SEO services to improve visibility.
- Retainer Services: Monthly packages for ongoing content, social posting, and campaign optimization.

**Approach**

- Consult first: We start by understanding your goals and audience.
- Design with purpose: Visual identity and UX that supports conversions.
- Build to perform: Responsive, accessible, and easy-to-manage websites.
- Measure & iterate: Monitor results and refine campaigns.

**Site Structure (where to edit)**

- `index.html` — Main landing page and hero carousel, pricing and client slider.
- `about.html`, `service.html`, `contact.html`, `our-projects.html`, `our-team.html`, `explore-more.html`, `read-more.html`, `read-more - 2.html` — Other static pages.
- `css/style.css` — Primary stylesheet (site-wide styles). Some pages also contain small scoped styles inside their `<head>`.
- `img/` — All images and client logos used across the site.
- `js/main.js` — Main JavaScript file for interactive behaviors (carousel, menu, etc.).
- `vendor/` — Third-party libraries (Bootstrap, jQuery, Owl Carousel, Font Awesome, etc.).

**Run locally**

This is a static site. To preview it locally, open `index.html` in your browser or run a simple static server. Example (PowerShell):

```powershell
# If you have Python installed
python -m http.server 8000
# Then open http://localhost:8000 in your browser
```

Or use a Node-based static server:

```powershell
npx serve .
# or
npx http-server . -p 8000
```

**Deployment**

- Deploy to any static host: GitHub Pages, Netlify, Vercel, Firebase Hosting, or a traditional web host.
- If you prefer Firebase Hosting, initialize the project and run `firebase deploy` after configuration.

**Accessibility & SEO notes**

- Images include `alt` attributes; keep these descriptive and concise for accessibility and search engines.
- The site includes meta tags for Open Graph and Twitter Card information — update these on a per-page basis when appropriate.

**Editing content**

- Text and descriptions live directly in the HTML files under relevant sections (e.g., `<div class="des">` in `index.html`).
- For styling tweaks, prefer `css/style.css` to keep consistent appearance across pages.
- For large or repeated style changes, consider moving duplicated scoped styles into `css/style.css`.

**Contact & Business Info**

- Phone / WhatsApp: +27 64 243 6568
- Email: msitholeholdings@gmail.com
- Social: Links are included in the footer to Facebook, Instagram, Twitter, and LinkedIn.

**Next recommended steps before deployment**

- Finish the responsive checks and QA across devices (mobile, tablet, desktop).
- Test interactive elements: hero carousel, logo slider, menu dropdowns, and WhatsApp floating button on touch devices.
- Compress images for faster page load and enable caching headers via your host.
- Optionally add a small sitemap and robots.txt for SEO.

If you'd like, I can:

- Add a short deployment guide for Firebase, Netlify, or GitHub Pages.
- Produce a checklist of responsiveness fixes per page.
- Draft short marketing copy variations for the hero and service blurbs.

---

M-Sithole Digital Solutions — Professional web design, branding and digital marketing to help small businesses grow.