# # Mzansi Eats - Responsiveness Audit

## Overview

This project focuses on auditing and improving the responsiveness of the Mzansi Eats food delivery website. The website was tested across different screen sizes to identify layout and usability issues. Responsive design fixes were then applied using CSS Flexbox, Grid, and media queries.

## Objectives

* Test the website on mobile, tablet, and desktop screen sizes.
* Identify responsiveness issues affecting the user experience.
* Apply CSS fixes to improve layout adaptability.
* Document findings and solutions in an audit report.

## Technologies Used

* HTML5
* CSS3
* Flexbox
* CSS Grid
* Chrome DevTools

## Screen Sizes Tested

| Device Type | Width  |
| ----------- | ------ |
| Mobile      | 375px  |
| Tablet      | 768px  |
| Desktop     | 1280px |

## Issues Identified

1. Hero image overflowed on smaller screens.
2. Menu cards used fixed-width columns causing horizontal scrolling.
3. Contact section had a fixed width that broke the layout on mobile devices.
4. Header and footer layouts became cramped on smaller screens.

## Fixes Applied

* Converted fixed image widths to responsive widths.
* Updated the card grid to use responsive CSS Grid properties.
* Replaced fixed-width containers with flexible layouts.
* Added media queries for mobile and tablet devices.
* Improved header and footer layouts using Flexbox.

## Project Structure

```text
project-folder/
│
├── index.html
├── docs/
│   └── responsiveness-audit.md
└── README.md
```

## How to Run

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Open the project folder.

3. Open `index.html` in your browser.

4. Use Chrome DevTools Device Toolbar to test responsiveness.

## Lessons Learned

Through this project, I gained practical experience in:

* Identifying common responsiveness issues.
* Using Flexbox and CSS Grid for adaptive layouts.
* Applying media queries for different screen sizes.
* Testing websites across multiple devices using Chrome DevTools.

## Author

**Kazadi Shadrack Mukendi**

Aspiring Full Stack Web Developer currently building skills in HTML, CSS, JavaScript, responsive design, and version control.