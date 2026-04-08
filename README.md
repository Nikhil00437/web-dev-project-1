<div align="center">
  <img src="Screenshot 2026-04-08 223641.png" alt="Ember & Oak Logo" width="100" />
  
  # Ember & Oak — Landing Page
  
  **A premium, single-page business landing page designed for an upscale coffee shop and brunch café.**
  
  [View Live Demo](https://nikhil00437.github.io/web-dev-project-1/) · [Report Bug](https://github.com/Nikhil00437/web-dev-project-1/issues)

  ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
</div>

---

## ☕ About The Project

Ember & Oak is a fictional upscale café located in the Maplewood District. This project focuses on delivering a sophisticated, editorial-magazine aesthetic using earthy tones, highly polished typography, and smooth micro-interactions.

A key technical requirement of this project was that **all assets (including high-resolution photography) are embedded directly within the HTML file as Base64 strings**, resulting in a completely self-contained, single-file deployment.

### ✨ Features

- **Single-File Architecture**: The entire website, including CSS, JavaScript, and megabytes of image data, is housed entirely within a single `index.html` file.
- **Editorial Aesthetic**: Carefully curated color palette (espresso brown, warm cream, muted terracotta) paired with elegant typography (`Playfair Display` for headings, `Inter` for body).
- **Responsive Mobile-First Layout**: Fluid typography using CSS `clamp()` and a fully collapsible mobile hamburger navigation menu.
- **Scroll-Triggered Animations**: Implemented using the Vanilla JavaScript `IntersectionObserver` API to softly reveal text, fade in sections, and asynchronously trigger counter animations as the user scrolls.
- **Asymmetric Photo Gallery**: A custom CSS Grid layout showcasing coffee and brunch photography with rich hover overlay states.
- **Client-Side Form Validation**: The reservation form provides instant feedback for required fields (name, valid email, future dates, guest selection) and triggers a stylish success state without external libraries.

---

## 🛠 Tech Stack

- **HTML5**: Semantic tags and highly localized structure.
- **CSS3**: Vanilla CSS utilizing CSS Custom Properties (Variables) for theming, CSS Grid/Flexbox for advanced layouts, and optimized CSS keyframes/transitions for micro-animations.
- **Vanilla JavaScript**: Zero-dependency logic for the sticky navigation bar, mobile menu toggling, smooth scrolling, intersection observers, and interactive form handling.

---

## 🚀 Getting Started

To view the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Nikhil00437/web-dev-project-1.git
   ```
2. Navigate to the project directory:
   ```bash
   cd web-dev-project-1
   ```
3. Open `index.html` directly in your browser, or serve it using a local server (recommended due to base64 string sizes):
   ```bash
   # If you have Python installed:
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`

> **Note**: If you make modifications to the `index.html` file and open it locally, you may need to perform a "Hard Refresh" (`Ctrl + Shift + R` or `Cmd + Shift + R`) to force your browser to clear the cache and load the heavy single file.

---

## 📂 Project Structure

Inside the `index.html`, the document is modularized logically:
- `<!-- NAVBAR -->`: Sticky navigation and mobile menu logic.
- `<!-- HERO -->`: Atmospheric landing banner and dynamic scroll indicator.
- `<!-- ATMOSPHERE -->`: The "Our Story" section merging image and animated stats.
- `<!-- OFFERINGS -->`: The menu/services grid with custom SVG iconography.
- `<!-- GALLERY -->`: The asymmetric CSS Grid photo layout.
- `<!-- FORM -->`: The client-validated reservation table form.
- `<!-- FOOTER -->`: Quick links, hours, and contact details.
- `<script>`: Vanilla JS for observers and form handling at the bottom of the document.

---

<p align="center">
  <i>Designed and built for learning and demonstration purposes.</i><br>
  Built by <a href="https://github.com/Nikhil00437">Nikhil</a>
</p>
