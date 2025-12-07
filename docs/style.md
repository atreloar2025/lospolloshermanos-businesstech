# Style Guide

This document defines the visual standards and structures used throughout the website. All contributors should follow these guidelines to maintain consistency.

---

## Colors

All color values are taken directly from `styles.css`.

### Primary Colors

- Background Blue: `#05c7f2`
- Title Bar Blue: `#021f59`
- Main Red: `#f20530`
- Navbar Red: `#f20519`
- Navbar Hover Yellow: `#f2e205`
- Footer Background: `#333333`
- Neutral Light: `#fff8f0`
- Menu Header Red: `#b02a02`
- Menu Text Gray (dark): `#444`
- Menu Text Gray (medium): `#555`
- About Grid Yellow: `#fff350`
- White: `#ffffff`

---

## Typography

Web fonts imported from Google:

- `"Hanalei", system-ui` — used for main site title.
- `"Delius Swash Caps", cursive` — used for all other text.

Common sizes used across the site:

- Title Bar Heading: approximately 2rem
- Section Headings: 1.2–2rem
- Body Text: approximately 1rem
- Footer Text: approximately 0.9rem

---

## Layout

### Global

- Pages use centered content areas with max widths between 900–1200px.
- Flexbox and CSS Grid are used for layout throughout.
- Standard spacing includes section padding around 40px and gaps around 20px.

### Section Structures

- `index.html` uses `.hero` and `.content`.
- `about.html` uses `.about-grid`, `.restaurant-story`, `.profile-pic`, and `.gus-gallery`.
- `menu.html` uses `.menu-section`, `.menu-flex`, and `.menu-grid`.
- `contact.html` uses `.menu-section` and `.menu-item`.
- `thankyou.html` uses `.thankyou-section`.

Maintain these structures when adding new sections or pages.

---

## Images

- All images must be stored in the `images/` directory.
- Maintain existing sizes and ratios:
  - Menu images: landscape orientation, typically 180x120px or full-width grid images.
  - About page images: bordered with a red frame.
- All images must include descriptive `alt` text.

---

## Interactive Elements

### Navigation Bar

- Base background: `#f20519`
- Text color: white
- Hover background: `#f2e205`
- Hover text color: `#333333`

### Cards and Menu Items

- Background: white
- Border radius: approximately 12–16px
- Hover: slight scale increase and shadow

---

## Consistency Requirements

- Maintain indentation of 2 spaces.
- Do not change class names unless updating CSS.
- Use established spacing, structure, and image treatments.
- Keep typography and color usage consistent across all pages.
