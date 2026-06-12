# Mzansi Eats - Responsive Design Audit & Fixes

## Project Overview
This project was completed as part of the iHub Africa Full Stack Web Development Programme (Week 7).

The goal was to audit an existing webpage for responsiveness issues across different screen sizes and apply fixes using CSS Flexbox, Grid, and Responsive Design principles.

---

## Audit Screen Sizes

The website was tested using Chrome DevTools at:

- Mobile: 375px
- Tablet: 768px
- Desktop: 1280px

---

## Responsiveness Issues Identified

### Issue 1: Hero Image Overflow
**Problem:**
- Hero image had a fixed width of 1200px.
- Caused horizontal scrolling on smaller screens.

**Fix Applied:**
```css
.hero img {
  width: 100%;
  height: auto;
}
Issue 2: Navigation Overflow

Problem:

Navigation links stayed in a single row.
Links overflowed on mobile devices.

Fix Applied:

header {
  flex-wrap: wrap;
}

nav {
  flex-wrap: wrap;
}
Issue 3: Menu Cards Not Responsive

Problem:

Grid used fixed-width columns.
Cards overflowed on smaller devices.

Fix Applied:

.card-grid {
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
}
Issue 4: Contact Section Too Wide

Problem:

Contact container had a fixed width of 800px.
Content overflowed on smaller screens.

Fix Applied:

.contact-inner {
  width: 100%;
  max-width: 800px;
}
Additional Improvements
Mobile Responsive Layout

Added media query for devices under 768px.

@media (max-width: 768px) {
  header {
    flex-direction: column;
  }

  .contact-grid {
    grid-template-columns: 1fr;
  }

  footer {
    flex-direction: column;
  }
}
Technologies Used
HTML5
CSS3
CSS Grid
Flexbox
Chrome DevTools
Git & GitHub
Git Workflow

The project was completed using feature branches and commits.

Example commits:

Audit documentation created
Hero image responsiveness fixed
Navigation responsiveness fixed
Card grid responsiveness fixed
Contact section responsiveness fixed
Mobile media queries added
Documentation updated
Author

Karabo Komane

iHub Africa Full Stack Web Development Programme

Week 7 - Responsive Design Audit
