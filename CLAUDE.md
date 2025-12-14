# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Important Instructions

**Never write code without explicit permission from the user.** Always discuss and explain approaches before implementing anything.

## Project Overview

Single-page Hebrew (RTL) website for "אסף ליצור - רפואה סינית ויפנית" - a Chinese and Japanese medicine clinic. The site should feel traditional yet modern, calming yet professional.

## Technical Requirements

- Single `index.html` file with embedded CSS and JS
- Fully responsive (mobile-first approach)
- RTL (right-to-left) layout throughout
- Smooth scroll navigation
- Google Fonts: "Heebo" (weights: 300, 400, 500, 700)

### CSS Variables
```css
--color-primary: #A8C5A8;      /* Light sage green */
--color-primary-dark: #5B7B5B; /* Darker green for CTAs/hover */
--color-secondary: #D4C4B5;    /* Warm light brown/tan */
--color-secondary-dark: #B8A99A;
--color-text: #2D2D2D;         /* Dark charcoal */
--color-text-light: #5A5A5A;
--color-background: #FAFAF8;   /* Off-white/cream */
--color-white: #FFFFFF;
```

### Breakpoints
- Mobile: default
- Tablet: 768px
- Desktop: 1024px

## Site Structure (Single Page Sections)

1. **Hero** - Full viewport, business name, tagline, WhatsApp CTA
2. **אודות (About)** - Introduction, philosophy, credentials
3. **שירותים (Services)** - Card-based layout (דיקור, קינזיוטייפ, צמחי מרפא, מוקסה, כוסות רוח)
4. **תחומי טיפול (Treatment Areas)** - Conditions treated
5. **קליניקות (Locations)** - פרדס חנה (Sun, Mon, Thu) / תל אביב (Tue, Wed)
6. **צור קשר (Contact)** - Phone, email, WhatsApp button
7. **Footer** - Copyright, minimal

## Contact Information

- Phone: 052-322-2116
- Email: sefijoon@gmail.com
- WhatsApp: https://wa.me/972523222116?text=היי%20אסף%2C%20אשמח%20לקבוע%20תור

## Build Phases

1. Structure & Hero - HTML boilerplate, RTL, fonts, CSS variables, hero
2. About & Services - About section, service cards
3. Locations & Contact - Location cards, contact links
4. Navigation & Footer - Sticky nav, hamburger menu, smooth scroll
5. Polish & Animations - Hover effects, scroll animations, final tweaks

## Design Notes

- Traditional + Modern fusion
- Clean, minimalist layout
- Subtle Asian-inspired elements (not cliche)
- Generous whitespace
- Soft shadows and rounded corners
- Smooth, subtle animations

## Deployment

Ready for Vercel or GitHub Pages - no build step required.
