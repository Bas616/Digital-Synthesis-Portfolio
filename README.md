# Bas [616] // Digital Synthesis Portfolio

**[ VIEW LIVE PORTFOLIO ↗](https://bas616.github.io/Digital-Synthesis-Portfolio/)**

[![GitHub last commit](https://img.shields.io/github/last-commit/Bas616/Digital-Synthesis-Portfolio?style=for-the-badge&color=7df9ff&logo=github&logoColor=black)](https://github.com/Bas616/Digital-Synthesis-Portfolio/commits/main)
[![Languages](https://img.shields.io/github/languages/top/Bas616/Digital-Synthesis-Portfolio?style=for-the-badge&color=c77dff)](https://github.com/Bas616/Digital-Synthesis-Portfolio)
[![Status](https://img.shields.io/static/v1?label=status&message=dynamic-archive&color=ffc77d&style=for-the-badge)](https://github.com/Bas616)

![Portfolio Showcase GIF](https://drive.google.com/thumbnail?id=1tBmUJLT2Tckl0cZ2idjXSNUWOU4SYxFM)/nNote: The live version features interactive sounds and animations._

---

## I. Core Directive: A Living Manifesto

This repository hosts more than just a personal website; it contains a **living digital portfolio**, a synthesized entity designed to serve as an interactive log of my journey into Artificial Intelligence, Game Development, and the Philosophy of Technology. 

It is my **ChimeraCore Manifesto**—a public-facing node of `Project Chimera Genesis`.

The primary objective was not merely to list accomplishments, but to **fuse content with form**. The portfolio itself is an exhibit, built from the ground up to reflect a core philosophy: that a digital identity can be as complex, layered, and intentionally designed as a software system. The glitch effects, the retro-terminal aesthetic, the soundscape—every element is a deliberate choice, intended to create an immersive and authentic representation of my skills and thought processes.

This is where my code, my research, and my story converge.

## II. System Architecture & Features

This project is a self-contained **vanilla web application**, built with a focus on modern techniques and performance without reliance on heavy frameworks.

### Architectural Highlights:
*   **Single-Page Application (SPA):** The entire portfolio exists within a single `index.html` file, with JavaScript dynamically injecting content into section templates. This ensures rapid loading and seamless navigation.
*   **Modular Data Structure:** All portfolio content (personal info, project details, skills, etc.) is stored within a single structured JavaScript object (`portfolioData`). This decouples the data from the presentation layer, making updates efficient and systematic.
*   **CSS-Driven Thematics:** A comprehensive set of CSS variables (`:root`) defines a cohesive aesthetic matrix (colors, fonts, transitions), allowing for easy thematic changes and ensuring a consistent visual identity.

### Key Features:
*   **Immersive Ambience:** A multi-layered visual system combines a background image, animated scanlines, digital noise, and a vignette to create a retro-futuristic, "haunted terminal" atmosphere.
*   **Interactive Soundscape:** User actions such as clicks, hovers, and menu interactions trigger corresponding sound effects, while an ambient background track sets the mood. This functionality is opt-in, respecting the user's preferences.
*   **Dynamic Glitch & Text Effects:** Utilizes CSS animations (`@keyframes`) and JavaScript to generate procedural glitch effects on titles and other key text elements, enhancing the digital, sometimes unstable, theme.
*   **Responsive Design:** The layout adapts fluidly from desktop to mobile viewports, ensuring a consistent and accessible experience across all devices.
*   **Performance-Optimized:** All assets are preloaded, and content is injected dynamically after the initial page load to ensure a fast and smooth user experience. Lazy loading is implemented for images to optimize initial load times.

## III. Tech Stack

This project deliberately avoids external frameworks to demonstrate proficiency in core web technologies.

*   **Languages:** ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
*   **Fonts:**
    *   **Google Fonts:** `IBM Plex Mono` & `Noto Sans Thai` for primary text.
    *   **Custom Fonts:** `Onryou` & `IPAM` (loaded via `@font-face`) for specialized, thematic text.
*   **Tools & Libraries:**
    *   **Font Awesome:** For scalable vector icons.
*   **Hosting:**
    *   **GitHub Pages:** The portfolio is hosted directly from this repository.

## IV. Setup & Deployment

Since this is a self-contained project, deployment is straightforward.

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/Bas616/Digital-Synthesis-Portfolio.git
    ```
2.  **Open in Browser:**
    Navigate to the cloned directory and open the `index.html` file directly in any modern web browser.
3.  **GitHub Pages Deployment:**
    This repository is configured to deploy automatically via GitHub Pages. Any push to the `main` branch will trigger a new build and update the live site at `https://bas616.github.io/Digital-Synthesis-Portfolio/`.

---
_This portfolio is a dynamic entity and will continue to evolve alongside my projects and skills._
