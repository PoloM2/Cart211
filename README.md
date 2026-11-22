# Addressing Surveillance

An interactive, multi-page web narrative exploring digital footprints, online profiling, and surveillance capitalism. Created for **CART 211** (Fall 2026).

## Live Website
Explore the live project here:  
**[https://polom2.github.io/Cart211/Final%20asst/index.html](https://polom2.github.io/Cart211/Final%20asst/index.html)**

## About the Project
*Addressing Surveillance* guides visitors through 10 pages examining how everyday online actions—clicks, searches, watch habits, and browsing patterns—are collected and turned into predictive user profiles. 

As the user progresses deeper into the experience, the website's visual design gradually degrades and distorts, mirroring the shift from casual, everyday internet browsing to invasive surveillance and algorithmic categorization.

## Key Features
* **Progressive Visual Distortion:** Five distinct CSS stylesheets (`styles1.css` through `styles5.css`) gradually shift the site's atmosphere every two pages—moving from a clean, neutral layout into high-contrast monochrome, misaligned typography, crimson surveillance overlays, and inverted imagery.
* **Interactive Digital Profile Builder:** Includes a self-reflection questionnaire examining how basic content, social media, and shopping habits reveal behavioral patterns.
* **Responsive Navigation:** Built with a mobile-friendly hamburger menu and persistent navigation controls (`HOME`, `EXPLORE`, `ABOUT` / `RESTART`, `NEXT`) to move smoothly through the narrative.

## Technologies Used
* **HTML5** (Semantic structure and accessible form elements)
* **CSS3** (Cascading stylesheet overrides via `@import`, Flexbox/Grid layouts, CSS filters, and transforms)
* **Vanilla JavaScript** (DOM manipulation for responsive mobile menu toggling)
* **Google Fonts & Font Awesome** (`Inter`, `Roboto`, and UI icons)

## Project Structure
```text
Final asst/
├── index.html           # Landing page & project introduction
├── page2.html - 10.html # Sequential narrative & interactive pages
├── styles1.css          # Base stylesheet (Pages 1–2)
├── styles2.css          # Subtle shift & left-aligned title distortion (Pages 3–4)
├── styles3.css          # Dark surveillance theme & eye background (Pages 5–6)
├── styles4.css          # High-contrast crimson glitch aesthetic (Pages 7–8)
├── styles5.css          # Maximum distortion & inverted visuals (Pages 9–10)
└── assets/              # Project imagery (digitalprofile.jpg, persona.jpg, eyes.jpg, etc.)
```

## How to Run Locally
1. Clone or download this repository:
   ```bash
   git clone https://github.com
   ```
2. Open `Final asst/index.html` in any modern web browser (or run with a local development server such as VS Code Live Server).

## Credits & References
* **Author:** Marko Anastasovski (CART 211, Fall 2026)
* **Theoretical Context:** Inspired by concepts of behavioral data and surveillance capitalism discussed by Shoshana Zuboff.
