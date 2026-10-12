# Indian Festivals and Cultural Heritage Website

This repository contains the source code for a single-page website dedicated to exploring the rich tapestry of Indian festivals, cultural heritage, traditions, and regional celebrations[cite: 2].

## Overview

The website is designed to be a comprehensive, visually appealing exploration of Incredible India[cite: 2]. It is built using purely HTML and CSS, adhering to strict layout requirements without the use of preprocessors or complex frameworks[cite: 2, 3].

## Features

The single-page site is divided into several key sections to provide a thorough overview of Indian culture:

*   **Hero Section:** A welcoming header featuring a tricolor flag bar (saffron, white, and green)[cite: 2, 3], a navigation menu with a golden yellow logo ("🪔 Bharat Utsav")[cite: 2, 3], and a call-to-action button to explore festivals[cite: 2].
*   **Stats Band:** A quick overview of India's cultural scale, highlighting "100+ Major Festivals," "28 States Unique Celebrations," "8 Forms Classical Dance Arts," and "5000+ Years of Rich History"[cite: 2].
*   **Major Indian Festivals:** Detailed cards for significant festivals like Diwali, Holi, and Navratri/Durga Puja, complete with images, dates, descriptions, and key facts[cite: 2]. It also includes a section listing "More Celebrated Festivals" as distinct chips[cite: 2].
*   **Cultural Heritage:** An exploration of India's legacy, featuring a highlighted image (like the Taj Mahal)[cite: 2] and sections detailing UNESCO World Heritage Sites, Ancient Literature, Handicrafts and Art, and Yoga and Ayurveda[cite: 2].
*   **Regional Celebrations:** A grid breakdown of unique festivals and celebrations categorized by region: North, South, East, West, Northeast, and Central India[cite: 2].
*   **Arts and Cultural Traditions:** Highlights of India's sophisticated forms of expression, including Classical Dance Forms (with an image section), Classical Music, Traditional Crafts, Culinary Heritage, and Traditional Attire[cite: 2].
*   **About Incredible India:** A concluding section reflecting on the concept of "Unity in Diversity" (*"Anekta mein Ekta"*) and the deep significance of Indian festivals as living expressions of community spirit[cite: 2].

## Technologies Used

*   **HTML5:** Pure semantic HTML structure[cite: 2].
*   **CSS3:** Custom styling utilizing Flexbox and CSS Grid for layout[cite: 3].
*   **Typography:** The site uses the following custom fonts loaded via `@font-face`:
    *   `Space Grotesk`[cite: 3]
    *   `Unbounded`[cite: 3]

## Styling Notes

The CSS (`style.css`)[cite: 3] was crafted with specific constraints:
*   **Units:** Strict use of pixels (`px`) and percentages (`%`) for layout, explicitly avoiding `rem`, `em`, `vh`, or `vw` units[cite: 3].
*   **Interactions:** Hover effects have been omitted to keep the styling basic and straightforward.
*   **Responsiveness:** The layout relies on flexbox and grid fundamentals without the use of media queries.
*   **Color Palette:** The design incorporates a dark header and footer background (`#140800`) with golden yellow text (`#ffcc00`), alongside sections utilizing light gray (`#f0f0f0`), off-white (`#f9f9f9`), and vibrant accents like deep red (`#8b0000`) and saffron (`#FF9933`)[cite: 3].

## Setup

1.  Clone this repository to your local machine.
2.  Ensure you have the required font files located in:
    *   `/assets/fonts/Space_Grotesk/SpaceGrotesk-VariableFont_wght.ttf`[cite: 3]
    *   `/assets/fonts/Unbounded/Unbounded-VariableFont_wght.ttf`[cite: 3]
3.  Ensure you have the referenced image files (e.g., `diwali.jpg`, `holi.jpg`, `tajmahal.jpg`, etc.) in the appropriate `/assets/images/` directory[cite: 2].
4.  Open `index.html`[cite: 2] in your preferred web browser. No server or build process is required.