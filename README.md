# Mzansi Eats - Responsive Design Audit

## Overview

This project was completed as part of the Week 7 Responsive Design Audit task. The goal was to test an existing webpage at different screen sizes, identify responsiveness issues, document the findings, and apply fixes to improve the user experience across devices.

## Objective

The page was tested using Chrome DevTools at the following screen sizes:

* Mobile: 375px
* Tablet: 768px
* Desktop: 1280px

The audit focused on finding layout problems, overflow issues, and elements that did not adapt properly to smaller screens.

## Technologies Used

* HTML
* CSS
* Chrome DevTools
* CSS Grid
* Flexbox
* Media Queries

## Issues Identified and Fixed

### 1. Missing Viewport Meta Tag

The page did not contain a viewport meta tag, causing mobile devices to display the page at an incorrect scale.

**Fix:** Added the viewport meta tag inside the `<head>` section.

### 2. Fixed Width Hero Image

The hero image used a fixed width of 1200px, creating horizontal scrolling on smaller screens.

**Fix:** Changed the image width to `100%` to make it responsive.

### 3. Rigid Menu Grid Layout

The menu cards used a fixed four-column grid layout that overflowed on mobile and tablet devices.

**Fix:** Replaced the fixed layout with a responsive CSS Grid using `auto-fit` and `minmax()`.

### 4. Contact Section Overflow

The contact section used fixed widths and a two-column layout that did not adapt well to smaller screens.

**Fix:** Converted fixed widths to flexible widths and added media queries to stack content vertically on smaller devices.


## Project Structure

```text
ResponsiveAuditPage/
│
├── docs/
│   └── responsiveness-audit.md
|   └── screenshots
├── responsive-audit-page.html
└── README.md
```

## Testing

The website was tested at:

* 375px (Mobile)
* 768px (Tablet)
* 1280px (Desktop)

After applying the fixes, the layout adapts correctly across all tested screen sizes without horizontal scrolling.

## Author

**Kazadi Mukendi**