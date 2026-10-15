# Crumb & Cocoa — Bakery & Confectionery Discovery & Exploration Platform

A production-ready, multi-page web platform for **Crumb & Cocoa** — the premier global discovery and exploration destination connecting pastry aficionados, bread connoisseurs, and dessert lovers with independent artisan bakeries, master chocolatiers, and heritage confectioners.

---

## 📁 File Structure

```
Bakery Confectionery Discovery & Exploration Platform/
├── assets/
│   ├── css/
│   │   ├── style.css        — Core styles, design tokens, responsive components, typography
│   │   ├── dark-mode.css    — Warm dark cocoa & roasted mocha night theme overrides
│   │   └── rtl.css          — Right-to-left layout and bidirectional mirroring
│   ├── js/
│   │   └── main.js          — Interactive modules: theme toggler, RTL switcher, gallery filtering, counters, forms
│   └── images/              — Visual branding and assets
├── pages/
│   ├── index.html           — Home Page (Discovery hero, artisan categories, signature collections, tasting reviews)
│   ├── about.html           — About Us (Curatorial mission, sourcing integrity, impact metrics, editorial team)
│   ├── services.html        — Bakery Directory & Tasting Passes (Categorized directory, tasting tour tiers)
│   ├── blog.html            — Bakehouse Journal (Lamination science, cocoa conching, heritage levain guides)
│   ├── contact.html         — Curator Desk & Bakery Submissions (Recommendations form, tasting HQ coordinates)
│   ├── login.html           — Explorer Portal Sign In (Saved bakeries & tasting notes access)
│   ├── coming-soon.html     — Mobile App Announcement (Neighborhood fresh oven radar & tasting passport)
│   └── 404.html             — Custom 404 Error Page (Lost crumb trail with discovery links)
└── README.md
```

---

## 🎨 Design System & Visual Identity

### Color Palette (Warm Artisan Bakery & Confectionery)
| Token | Hex Value | Role & Usage |
|-------|-----------|--------------|
| **Primary** | `#5B3427` | Warm Cocoa Brown — Headings, primary buttons, accents, footer background |
| **Secondary** | `#C58B55` | Caramel — Highlights, secondary badges, warm accents, hover borders |
| **Accent** | `#E9A0A8` | Soft Strawberry Pink — Pill tags, counter highlights, delicate badges |
| **Background** | `#FFF8F0` | Warm Cream — Main page background for warm, appetizing aesthetic |
| **Surface** | `#FFFFFF` | White — Elevated cards, modals, navigation background |
| **Main Text** | `#35241F` | Dark Cocoa — High-contrast, readable body & headline typography |
| **Secondary Text** | `#79665C` | Muted Brown — Subheadings, metadata, captions, card descriptions |

### Typography
- **Headings & Editorial Titles**: **Playfair Display** (Google Fonts serif with elegant high-contrast letterforms).
- **Body & UI Elements**: **DM Sans** (Google Fonts geometric sans-serif for clean readability and modern tactile feel).

---

## ✨ Features & Functionality

### Navigation & Layout
- Fixed sticky header with dynamic scroll shadow and blurred backdrop.
- Full mobile navigation drawer with touch-friendly navigation links.
- Global quick-access toggles for **Light / Dark Mode** and **RTL (Right-to-Left)** reading.

### Theme & Accessibility Systems
- 🌙 **Dark Mode**: Customized warm dark cocoa (`#1F1511`) and roasted mocha surface palette that maintains appetizing bakery warmth.
- 🔄 **Bidirectional RTL Support**: Complete CSS mirror mapping for Arabic, Hebrew, and Persian reading directions.
- ⚡ **Zero-dependency Javascript**: Native ES6 architecture with robust validation, counters, and carousel controls.

### Discovery & Exploration Utilities
- **Filterable Showcase Gallery**: Dynamic category sorting for Viennoiserie, Fine Chocolates, Artisan Sourdough, Custom Cakes, and Seasonal Confections.
- **Baking Schedule & Tasting Calendar**: Timed breakdown of morning oven pulls, afternoon entremet releases, and evening baguette crusting.
- **Bakery Submission Desk**: Interactive form allowing local pastry chefs and foodies to submit independent bakeries for curatorial review.
- **Client Toast Notifications**: Instant feedback on newsletter signup, contact inquiries, and wishlist interactions.

---

## 📖 Pages Overview

1. **Home (`index.html`)**
   - Immersive hero highlighting 500+ curated artisan bakeries.
   - Core discovery pillars: Viennoiserie, Fine Chocolates, Sourdough Breads, and Custom Cakes.
   - Filterable 8-item discovery gallery featuring top regional bakeries.
   - Verified tasting reviews from leading food critics and pastry chefs.

2. **About Us (`pages/about.html`)**
   - The Crumb & Cocoa discovery mission and 4 core values (Slow Craft, Honest Sourcing, Sensory Curiosity, Baker Community).
   - Global impact statistics (500+ bakeries, 2,400+ treats cataloged, 180+ chefs, 50,000+ explorers).
   - Profiles of chief tasting editors and sourdough sommeliers.

3. **Bakery Directory & Tasting Passes (`pages/services.html`)**
   - Multi-category discovery directory with badges, ratings, and specialties.
   - 3 Curated Exploration Passes: Weekend Explorer, Connoisseur Tasting Trail, and Atelier VIP Access.

4. **The Bakehouse Journal (`pages/blog.html`)**
   - Deep-dive guides into laminated dough honeycomb physics, single-origin cacao fermentation, wild levain hydration, and macaron foot chemistry.
   - Category filtering and search interface.

5. **Curator Desk & Contact (`pages/contact.html`)**
   - Direct inquiry and bakery nomination form with specialty selection.
   - Sensory Tasting HQ location details and visit guidelines.

6. **Explorer Portal (`pages/login.html`)**
   - Clean, secure authentication interface for saving bakeries, logging tasting notes, and accessing personalized discovery recommendations.

7. **Mobile App Announcement (`pages/coming-soon.html`)**
   - Preview of the forthcoming iOS & Android radar app featuring live neighborhood oven pull tracking.

8. **Lost Crumb Trail (`pages/404.html`)**
   - Playful, thematic 404 error experience pointing visitors back to discovery collections.

---

## 🚀 Getting Started

1. Open `index.html` directly in any modern web browser — no build tools, compilers, or server configurations required.
2. Web fonts and iconography load seamlessly via Google Fonts and Font Awesome CDN links.

---

*Curated with passion by the Crumb & Cocoa Editorial Collective.*
