# 📝 Practice Card Exercise

## 1️⃣ Create the Project Structure

- Create a folder named `practice-card`.
- Inside the folder, add:
  - `index.html`
  - `style.css`
  - `images/` folder for assets.

---

## 2️⃣ Set up the HTML Page

- Use a `<main>` tag to wrap the card.
- Add an `<article>` element for the card with **id**:
  - `id="card"`

---

## 3️⃣ Card Image

- Add a `<figure>` containing the main card image.
- Class name for `<figure>`:
  - `class="card__media"`
- The image should represent the top section of the card.

---

## 4️⃣ Title and Description

- Add a `<header>` inside the card:
  - `class="card__header"`
- Inside the header:
  - `<h1>` title text: **"Order Summary"**
  - `<p>` description text:
    > You can now listen to millions of songs, audiobooks, and podcasts on any device anywhere you like!

---

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

---

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

---

## 🎯 Your Task

- Write the HTML using the exact structure, classes, and IDs listed above.
- Write CSS to style colors, backgrounds, spacing, and layout according to the design you want.
- Keep all class names and IDs exactly as given for consistency.
