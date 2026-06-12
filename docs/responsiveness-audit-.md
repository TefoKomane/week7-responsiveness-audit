# Responsiveness Audit Report

## Testing Devices

- Mobile: 375px
- Tablet: 768px
- Desktop: 1280px

---

## Issue 1: Hero Image Overflow

Problem:
The hero image had a fixed width of 1200px causing horizontal scrolling on smaller devices.

Fix:
Changed width to 100% and added max-width.

Result:
Image now scales properly on all screen sizes.

Screenshots:
- issue1-before.png
- issue1-after.png

---

## Issue 2: Menu Cards Overflow

Problem:
The card grid used fixed columns and overflowed on mobile screens.

Fix:
Used auto-fit and minmax for responsive grid behaviour.

Result:
Cards automatically resize and stack correctly.

Screenshots:
- issue2-before.png
- issue2-after.png

---

## Issue 3: Contact Section Too Wide

Problem:
Contact section width was fixed at 800px.

Fix:
Changed to width 100% and max-width 800px.

Result:
Section now fits mobile screens.

Screenshots:
- issue3-before.png
- issue3-after.png

---

## Issue 4: Footer Layout Breaks

Problem:
Footer content became cramped on smaller screens.

Fix:
Applied flex-direction column through media query.

Result:
Footer stacks correctly on mobile.

Screenshots:
- issue4-before.png
- issue4-after.png

---

## Issue 5: Navigation Overflow

Problem:
Navigation links could overflow on smaller screens.

Fix:
Added flex-wrap and centered layout.

Result:
Navigation wraps neatly on mobile.

Screenshots:
- issue5-before.png
- issue5-after.png