# TODO - Responsive Website (FreshMart)

## Step 1: Understand & audit (done)
- Checked HTML pages: index, products, about, contact, enquiry.
- Inspected `assets/css/style.css` for responsiveness issues (duplicate CSS + large mobile block, fixed sizes, nav overflow risk).

## Step 2: Implement CSS responsiveness
- [x] Refactor `assets/css/style.css`:
  - [x] Remove duplicated mobile block content inside `@media (max-width: 520px)`.
  - [x] Keep base styles once; only add targeted mobile overrides.
  - [x] Fix any invalid/odd CSS (e.g., `display: absolute;`, broken background URL snippet).


## Step 3: Fluid layouts + images
- [x] Make hero height responsive (avoid fixed `height: 900px`).
- [x] Make all images fluid (`max-width:100%`, `height:auto`) and override specific fixed sizes for staff/cards.
- [x] Ensure text and sections wrap correctly with better padding/margins.


## Step 4: Mobile navigation
- [x] Choose navigation approach:
  - [x] CSS-only improvements (wrap/stack nav + reduce paddings/fonts at small widths)
  - OR [ ] Implement hamburger mobile menu (HTML edits across all pages)


## Step 5: Test
- [ ] Resize-test pages at 320px, 375px, 414px, 768px.
- [ ] Confirm no horizontal scrolling and readable layout.


## Step 6: Final check
- [ ] Ensure all pages look consistent and responsive.

