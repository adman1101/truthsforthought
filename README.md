# Truths for Thought – Faith, Love & Marriage

Welcome to the repository for **Truths for Thought**, the official website of Ralph Valdes — retired family-law attorney, marriage counselor, and author.

## Overview

This repository hosts the static website for Ralph Valdes's ministry, featuring the *Our Best for Him* book series, free devotional downloads, and booking information for speaking events. The site is built with pure HTML, CSS, and JavaScript, and is designed to be fully responsive and bilingual (English/Spanish).

Live Site: [https://adman1101.github.io/truthsforthought/](https://adman1101.github.io/truthsforthought/)

## Features

- **Bilingual Support:** Full English and Spanish translation toggle built into the site via JavaScript.
- **Book Catalog:** Showcases the 5 books in the *Our Best for Him* series with direct links to purchase on Gumroad.
- **Free Resources:** Offers a free 7-Day Devotional and Personalized Self-Proclamation for visitors.
- **Video Library:** Embedded video teachings and messages from Ralph Valdes.
- **Responsive Design:** Custom CSS ensuring a seamless experience across desktop, tablet, and mobile devices.

## About Ralph Valdes

Ralph Valdes spent four decades as a family-law attorney — sitting across from couples whose marriages were ending. He saw the same patterns over and over. He saw what happened when people stopped giving their best to God, to each other, and to their families. So he retired his law license — and picked up a pen.

His mission is simple: to help people draw closer to God, strengthen their relationships, and live with purpose and conviction.

## Development

The site is a single-page application (SPA) architecture contained entirely within `index.html`.

- **HTML:** Semantic structure for all sections (Home, Books, Videos, About, etc.).
- **CSS:** Embedded styling for layout, typography, and responsive media queries.
- **JavaScript:** Handles navigation, mobile menu toggling, dynamic rendering of book/video cards, and the English/Spanish language translation system.

### Language System
The site uses a custom JavaScript dictionary (`TR`) to store all text strings in both English and Spanish. The `applyLang()` function iterates through elements with specific `id` attributes and updates their text content or placeholders based on the selected language state.

## Deployment

This site is deployed automatically via **GitHub Pages**. Any commits pushed to the `main` branch will be reflected on the live site within minutes.

## License

All content, including text, images, and books, is the property of Ralph Valdes and Truths for Thought. All rights reserved.
