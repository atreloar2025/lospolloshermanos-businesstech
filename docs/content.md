# Content Management Guide

This document explains how to edit and update content on the website. Follow these guidelines to maintain consistency across all pages.

---

## File Overview

The website contains these HTML files:

- `index.html`
- `about.html`
- `menu.html`
- `contact.html`
- `thankyou.html`

All pages use shared styling from `styles.css` and images in the `images/` directory.

---

## Editing Text Content

To edit text:

1. Open the appropriate HTML file.
2. Modify the text inside `<p>`, `<h1>`, `<h2>`, or `<h3>` tags.
3. Keep all class names and HTML tags unchanged.

Example:

```html
<p>Updated text goes here.</p>
```

## Editing Image Content

All images must be stored in the images/ directory.

```
To update an image:
<img src="images/filename.jpg" alt="description">
```

Requirements:

-   Use a meaningful alt description.
-   File names should not contain spaces.
-   Maintain existing class names so styling remains consistent.

---

## Adding New Menu Items

Menu items follow this structure:
```
<div class="menu-item">
  <img src="images/example.jpg" alt="description">
  <div class="menu-info">
    <h3>Item Name</h3>
    <p>Item description.</p>
    <p class="price">$0.00</p>
  </div>
</div>
```
Steps:

-   Copy an existing .menu-item block.
-   Paste it inside .menu-flex or .menu-grid, depending on the section.
-   Update the image, item name, item description, and price.

---

## Editing Staff Information (Contact Page)

Staff entries use this structure:
```
<div class="menu-item staff">
  <div class="menu-info">
    <h3>Name — Role<br>Email</h3>
  </div>
</div>
```
Modify the name, role, or email inside the \<h3> tag.

---

## Updating the Navigation Bar

Each HTML file contains its own navigation bar.
When adding a new page, update the \<ul> list on every page.

Example:
```
<li><a href="specials.html">Specials</a></li>
```
All navigation menus must remain consistent.

---

## Creating a New Page

-   Duplicate an existing HTML file.
-   Rename it (example: specials.html).
-   Update the \<title> tag inside \<head>.
-   Replace the main content inside \<main> or equivalent containers.
-   Add a link to the new page in the navigation bar on every page.
-   Add any images to the images/ directory as needed.

---

## Consistency Requirements

-   Maintain 2-space indentation.
-   Do not change class names unless updating the CSS.
-   Follow existing section layouts.
-   Use meaningful alt text.
-   Ensure the navigation bar remains consistent on all pages.
-   Keep writing style and formatting consistent across pages.

---