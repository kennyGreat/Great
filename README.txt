# Vortexedge Technology Website

The official multi-page website for **Vortexedge Technology Limited** — covering our three core divisions: Digital Transformation & Technology, Procurement, and Real Estate.

🌐 Live site: [www.vortexedge.com.ng](https://www.vortexedge.com.ng)

---

## File Structure

```
vortexedge-site/
├── index.html                              Homepage
├── technology.html                         Technology & Digital Transformation
├── procurement.html                        Procurement Services
├── real-estate.html                        Real Estate Services
├── school-digital-transformation.html      School Digital Transformation System
├── business-digital-transformation.html    Business Digital Transformation System
└── assets/
    ├── css/
    │   └── style.css       Shared design system (colors, typography, layout)
    ├── js/
    │   └── script.js       Shared JavaScript (nav, counters, FAQ, animations)
    └── images/
        ├── logo.png
        ├── hero-databulge.png
        ├── hero-procurement.jpg
        └── hero-realestate.jpg
```

## Features

- Fintech-inspired green/gold design system
- Responsive, mobile-first layout
- Animated scroll reveals and counters
- FAQ accordion
- Numbered step-flow process sections
- Floating WhatsApp button
- Back-to-top button
- Font Awesome icons, Google Fonts (Inter + Sora)

## External Links

- Digital Assessment: https://kennygreat.github.io/assessment2/
- DataBulge: https://databulge.com/landing.html
- WhatsApp: https://wa.me/2347048069238

## Contact

**Vortexedge Technology Limited**
57 Kunai Street, Sabo Tasha, Kaduna
+234 704 806 9238
vortexedgelimited@gmail.com
www.vortexedge.com.ng

---

## Local Preview

No build step required — it's plain HTML/CSS/JS.

1. Clone or download this repo.
2. Open `index.html` directly in a browser, **or** serve it locally:
   ```bash
   python3 -m http.server 8000
   ```
   then visit `http://localhost:8000`.

## Deployment

This is a static site — any static host works.

**Existing domain (cPanel/FTP):** Upload all files and the `assets/` folder into `public_html`, keeping the folder structure intact.

**Netlify:** Drag the project folder onto [Netlify's manual deploy page](https://app.netlify.com/drop) for an instant live URL, then attach the custom domain in *Site settings → Domain management*.

**GitHub Pages:** Push this repo, then enable Pages in *Settings → Pages* with the source set to the `main` branch root.

## Customization

- **Colors & fonts:** edit the CSS variables in `:root` at the top of `assets/css/style.css`.
- **Content:** edit the relevant HTML file directly.
- **Images:** add new files to `assets/images/` and reference them in the HTML.
- **Contact info:** update phone/email/address across all HTML files' `<footer>` and hero sections.

---

© 2026 Vortexedge Technology Limited.
