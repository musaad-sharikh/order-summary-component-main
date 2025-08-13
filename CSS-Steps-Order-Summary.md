# Order Summary Card – CSS Steps

## 1) Reset & Base

- Apply global reset for `box-sizing`, `margin`, and `padding`.
- Use a clean, readable font (e.g., "Open Sans").

## 2) Design Tokens

- Define all main colors in `:root` as CSS variables.
- Include base color, pale shades, and hover variants.

## 3) Page Layout

- Set body background color and background image (desktop pattern).
- Use Flexbox to center the card horizontally and vertically.
- Ensure `min-height: 100vh` for full screen height.

## 4) Card Container

- White background, rounded corners, and box shadow.
- Restrict maximum width and set responsive `width: 100%`.
- Hide overflow to keep media edges clean.

## 5) Media Section

- Make the top image span the full width of the card.
- Remove gaps with `display: block`.

## 6) Header

- Center-align heading and paragraph text.
- Style heading with bold, larger font and dark color.
- Style paragraph with lighter color for contrast.

## 7) Plan Section

- Use Flexbox for icon, details, and change link.
- Add background with very pale color and padding.
- Round corners and add spacing (`gap`).
- Style icon with fixed width and height.
- Bold the plan title and set a lighter color for the price.
- Make “Change” link bold, underlined, and add hover color transition.

## 8) Actions (Buttons)

- Stack buttons vertically with spacing.
- **Primary button:** background color, white text, rounded corners, hover effect.
- **Secondary button:** transparent background, muted text color, hover darkening.

## 9) Responsive Design

- For screens ≤ 600px:
  - Switch background image to mobile pattern.
  - Reduce padding and font sizes.
  - Stack plan section elements vertically.
  - Adjust gaps and text alignment for smaller viewports.
