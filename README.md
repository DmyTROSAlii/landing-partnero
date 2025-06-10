# Partnero Landing Page

A modern, responsive single-page landing website for **Partnero** — a platform for managing partnership, affiliate, and referral programs. This project features a clean UI, interactive navigation, and modular CSS for easy customization.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Demo](#-demo)
- [Project Structure](#-project-structure)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [Usage](#-usage)
- [Customization](#-customization)
- [Examples](#-examples)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📝 Overview

**Partnero Landing Page** is a static HTML/CSS/JS project designed to showcase the features and pricing of the Partnero platform. It includes visually distinct sections for hero, features, testimonials, partnership types, pricing, and a call-to-action, all styled for responsiveness and clarity.

---

## ✨ Features

- Responsive design for desktop and mobile
- Burger menu for mobile navigation
- Modular CSS (components & sections)
- Clean, semantic HTML structure
- Interactive navigation overlay
- Modern UI with custom fonts and icons
- Easy to customize and extend

---

## 🚀 Demo

Open `index.html` in your browser to view the landing page.

---

## 📁 Project Structure

```
index.html
README.md
css/
  common.css
  fonts.css
  reset.css
  style.css
  components/
    advantage-item.css
    button.css
    container.css
    footer-nav.css
    main.css
    nav.css
    pricing-item.css
    title.css
  sections/
    advantages-section.css
    blog-section.css
    footer.css
    header.css
    hero-section.css
    main.css
    partnership-section.css
    pricing-section.css
    promo-section.css
img/
  jpg/
    IMAGE.jpg
  svg/
    arrow.svg
    glob.svg
    layers.svg
    linkedin.svg
    logo.svg
    ...
js/
  main.js
```

---

## 🛠 Technologies Used

- **HTML5** — semantic markup
- **CSS3** — modular, responsive styles
- **JavaScript (ES6)** — navigation interactivity
- **Google Fonts** — Inter, Roboto
- **SVG/JPG** — icons and images

---

## ⚙ Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/partnero-landing.git
   cd partnero-landing
   ```

2. **No build step required.**  
   All files are static and ready to use.

---

## ▶ Usage

- Open `index.html` directly in your browser.
- To serve locally (optional), use a static server:
  ```sh
  npx serve .
  # or
  python -m http.server
  ```

---

## 🖌 Customization

- **Content:**  
  Edit `index.html` to change text, images, or sections.
- **Styles:**  
  Modify or add CSS in `css/` or its subfolders for components and sections.
- **Images/Icons:**  
  Replace or add images in `img/jpg/` and SVGs in `img/svg/`.
- **JavaScript:**  
  Enhance interactivity in `js/main.js`.

---

## 💡 Examples

- **Change primary color:**  
  Edit color variables or values in `css/common.css`.
- **Add a new section:**  
  1. Create a new CSS file in `css/sections/`.
  2. Import it in `css/sections/main.css`.
  3. Add the HTML markup in `index.html`.

---

## 🤝 Contributing

Contributions are welcome!  
Fork the repo, create a branch, and submit a pull request.

---

## 📄 License

This project is open source and available under the MIT License.
