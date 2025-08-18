# Order Summary Card

A clean, responsive "Order Summary" card built with semantic HTML and modern CSS. Mobile-first and accessibility-aware.

## Demo

> Open `index.html` in your browser.

## Features

- Semantic structure: `article`, `header`, `section`, `figure`, `footer`
- Design tokens via CSS custom properties
- Responsive layout with a mobile media query
- Hover states for interactive elements
- Accessible alt text and clear hierarchy

## Tech Stack

- HTML5
- CSS3 (custom properties, flexbox)
- No frameworks or JS required

## Project Structure

```plaintext
├── index.html
├── style.css
├── images/
│ ├── favicon-32x32.png
│ ├── icon-music.svg
│ ├── illustration-hero.svg
│ ├── pattern-background-desktop.svg
│ └── pattern-background-mobile.svg
├── design/
│ ├── desktop-design.jpg
│ ├── mobile-design.jpg
│ └── active-states.jpg
├── preview.jpg
├── README.md
├── practice-card.md
├── .gitignore
└── .git/
```

---

## 📝 Practice Card Exercise

## 1️⃣ Create the Project Structure

- Create a folder named `practice-card`.
- Inside the folder, add:
  - `index.html`
  - `style.css`
  - `images/` folder for assets.

## 2️⃣ Set up the HTML Page

- Use a `<main>` tag to wrap the card.
- Add an `<article>` element for the card with **id**:
  - `id="card"`

## 3️⃣ Card Image

- Add a `<figure>` containing the main card image.
- Class name for `<figure>`:
  - `class="card__media"`
- The image should represent the top section of the card.

## 4️⃣ Title and Description

- Add a `<header>` inside the card:
  - `class="card__header"`
- Inside the header:
  - `<h1>` title text: **"Order Summary"**
  - `<p>` description text:
    > You can now listen to millions of songs, audiobooks, and podcasts on any device anywhere you like!

## 5️⃣ Plan Section

- Use a `<section>` for the plan:
  - `class="card__plan"`
- Content inside this section:
  1. Plan icon image:
     - `class="plan__icon"`
  2. Plan details inside a `<div>`:
     - `class="plan__details"`
     - `<h2>`: **"Annual Plan"**
     - `<p>`: **"$59.99/year"**
  3. Change link:
     - `class="plan__change"`
     - Text: **"Change"**

## 6️⃣ Action Buttons

- Add a `<footer>` at the bottom of the card:
  - `class="card__actions"`
- Inside the footer, add two buttons:
  1. Primary button:
     - `class="btn btn--primary"`
     - Text: **"Proceed to Payment"**
  2. Secondary button:
     - `class="btn btn--secondary"`
     - Text: **"Cancel Order"**

## 7️⃣ Responsive / Mobile (Optional but Recommended)

- Create a **media query** for screens ≤ **600px** width.
- Reduce **padding** in `body` and internal sections.
- Change `.card__plan` layout to **vertical** stacking.
- Slightly reduce the icon and text sizes inside `.plan__details`.
- Make buttons take **full width (100%)** on mobile.
- _(Optional)_ Switch background to `pattern-background-mobile.svg`.

## 🎯 Your Task

- Write the HTML using the exact structure, classes, and IDs listed above.
- Write CSS to style colors, backgrounds, spacing, and layout according to the design you want.
- Keep all class names and IDs exactly as given for consistency.
