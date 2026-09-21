# Responsive Component Assignment

## 1. Semantic HTML and Accessibility

I rebuilt the product collection using semantic HTML elements such as `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`.

I also used a proper heading hierarchy with an `<h1>` for the main page heading, `<h2>` headings for major sections, and `<h3>` headings for individual products.

For accessibility, I added descriptive `alt` text to the product images so that screen-reader users can understand what the images represent. I also added descriptive labels to the Add to Cart buttons.

## 2. Box Model, Flexbox and CSS Grid

I used Flexbox for the navigation bar. The logo is positioned on the left while the navigation links are positioned on the right.

I used CSS Grid for the product collection. The layout changes according to the screen size:

* **375px:** 1 product column
* **768px:** 2 product columns
* **1280px:** 3 product columns

This demonstrates responsive, mobile-first design.

## 3. Tailwind CSS

I created a separate Tailwind CSS version of the product collection inside the `tailwind-version` folder.

I used Tailwind utility classes such as:

* `flex` for Flexbox
* `justify-between` to separate the navigation items
* `items-center` to vertically align items
* `grid` for CSS Grid
* `gap-4` for spacing between products
* `md:grid-cols-2` for two columns on medium screens
* `xl:grid-cols-3` for three columns on larger screens
* `p-4` for padding
* `font-bold` for bold text

I reviewed the generated Tailwind classes and made changes rather than using the AI-generated scaffold without checking the code.

## 4. Changes I Made to the AI Tailwind Scaffold

I made several changes to the original scaffold:

* Changed the brand name to **Royale Beni**.
* Added semantic HTML structure.
* Added `id` attributes to the Products, About, and Contact sections.
* Connected the navigation links to the correct sections.
* Added descriptive image `alt` text.
* Added descriptive labels to the product buttons.
* Added About and Contact sections.
* Used responsive Tailwind classes for the product grid.
* Reviewed and tested the Tailwind classes at different screen sizes.

## 5. Responsive Testing

I tested the page at the three required viewport sizes:

**375px — Mobile:**
The products displayed in one column.

**768px — Tablet:**
The products displayed in two columns.

**1280px — Desktop:**
The products displayed in three columns.

I saved screenshots of the three responsive layouts and included them in the GitHub repository.

## 6. GitHub Repository

My completed project is available here:

https://github.com/blessedgozie70-hub/responsive-component

