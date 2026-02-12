# 🌐 BudGo Creative - 3D Interactive Experience

[![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Threejs](https://img.shields.io/badge/threejs-black?style=for-the-badge&logo=three.js&logoColor=white)](https://threejs.org/)
[![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

> **"Pioneering digital experiences that fuse art with technology."**

## 🎯 Live Demo

**[🚀 View Live Demo →]([./[index.html]()](https://karimdavi.github.io/Creative-Web-Design/))**

---

---

## 🚀 Overview

**BudGo Creative** is a single-page immersive web experience that pushes the boundaries of standard HTML & CSS. It integrates a full 3D environment directly into the background of a modern landing page, allowing users to interact with and customize the visual elements in real-time.

Designed as a practice in **Creative Coding**, this project combines the utility of **Tailwind CSS** with the power of **Three.js** to create a "High-end design" studio aesthetic.

---

## ✨ Key Features

### 🎨 Visuals & UI
*   **Immersive 3D Background**: Features a rotating wireframe globe, a floating inner core, and a procedural animated wave grid.
*   **Glassmorphism Effects**: Modern, translucent UI elements that blend seamlessly with the 3D world.
*   **3D Flip Cards**: Interactive stats cards that rotate in 3D space on hover, revealing hidden details with a depth effect.

### 🛠️ Interactivity
*   **Real-Time Control Panel**: Includes a `lil-gui` dashboard (top right) allowing you to customize:
    *   🌊 **Wave Dynamics**: Speed, height, frequency, and grid size.
    *   🎨 **Colors**: Change the theme of the globe, grid, background, and text instantly.
    *   📐 **Geometry**: Toggle visibility of dots, lines, spheres, and adjust their sizes.
    *   ✍️ **Typography**: Adjust font sizes, spacing, and gradient text colors.

### 📱 Architecture
*   **Zero Build Step**: Runs directly in the browser using CDN links.
*   **Fully Responsive**: Adapts gracefully from desktop monitors to mobile screens.

---

## 🎮 How to Run

Since this project uses CDNs for all dependencies, there is **no installation required**.

### Option 1: Direct Open
Simply double-click `control-your-design.html` to open it in your default web browser.

### Option 2: Live Server (Recommended)
For the best experience (to avoid local CORS policies with some assets), use a local server:

1.  **VS Code Live Server**: Right-click the file and select "Open with Live Server".
2.  **Python**:
    ```bash
    # Run this in your terminal
    python3 -m http.server 8000
    ```
     Then visit `http://localhost:8000/control-your-design.html`

---

## 📂 File Structure

```text
Creative-Web-Design/
├── control-your-design.html  # The main entry point containing HTML, CSS, and JS
└── README.md                 # This file
```

---

## 🕹️ Controls Guide

Look for the **"Design Control"** panel in the top-right corner of the screen:

| Section | What it does |
| :--- | :--- |
| **Text Styles** | Customize the branding colors, headline size, and gradient text effects. |
| **Wave Sheet** | Control the animated floor grid. Try increasing `Wave Speed` for a stormier look! |
| **Sphere & Core** | Toggle the main globe and inner geometric shape. Change `Sphere Color` to match your mood. |
| **Background** | Change the scene background color. |

---

## 🤝 Contributing

Feel free to fork this project and experiment with the Three.js settings!

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

<div align="center">

**Created by ☠︎K!MO☠︎**


[Report Bug](https://github.com/) · [Request Feature](https://github.com/)

</div>
