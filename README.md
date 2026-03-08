# Thimma Polymer – Corporate Website

A modern, professional B2B corporate website for **Thimma Polymer**, a polymer materials trading company.

## Overview

- **Tagline:** Strengthening Products Through Better Polymers.
- **Audience:** Plastic manufacturers, polymer compounders, automotive suppliers, packaging manufacturers, industrial buyers.

## Structure

| Page       | File         | Description                          |
|-----------|--------------|--------------------------------------|
| Home      | `index.html` | Hero, intro, products, partnership, why us, industries, CTA |
| About Us  | `about.html` | Company overview, mission, strengths, partnerships |
| Products  | `products.html` | Product categories with overview, applications, benefits |
| Industries| `industries.html` | Industries served with related materials |
| Contact   | `contact.html` | Contact info + enquiry form |

## Design

- **Colors:** Deep Polymer Blue `#0F3D5E`, Industrial Teal `#1F7A8C`, Energy Orange `#F29E38`, Light Gray White `#F6F8FA`, Dark Graphite `#1E1E1E`
- **Fonts:** Montserrat (headings/nav), Open Sans (body) via Google Fonts
- **Responsive:** Sticky header, mobile hamburger menu, stacked cards on small screens

## How to run

1. Open the project folder in a browser:
   - Double-click `index.html`, or
   - Use a local server, e.g. `npx serve .` or VS Code Live Server.
2. Navigate between pages via the header and footer links.

## Enquiry form

The contact form is front-end only. To receive enquiries you can:

- Use a form backend (e.g. Formspree, Netlify Forms) and set the form `action` and `method`.
- Connect to your own server/API and handle submission there.

## Customisation

- **Images:** Replace Unsplash URLs in the HTML with your own (hero, intro, industries). The partnership block has a “Partner Logo” placeholder.
- **SEO:** Update page titles and meta descriptions in each HTML `<head>` as needed.
- **Analytics:** Add your analytics script before `</body>` on each page.

## Files

```
├── index.html
├── about.html
├── products.html
├── industries.html
├── contact.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
└── README.md
```

© 2026 Thimma Polymer
