# 🌌 3D Interactive Galaxy Animation

A stunning, mathematically driven 3D galaxy simulation built entirely in the browser. This project leverages procedural generation to render a massive, dynamic particle system featuring rotating spiral arms, vibrant color interpolation, and smooth 3D camera controls.

## 🚀 Live Demo
Experience the galaxy in real-time here: **[3D Galaxy Animation Live](https://pankajtiwari-art.github.io/Galaxy-Animation/)**

## ✨ Features
* **Massive Particle System:** Renders 100,000 individual stars and cosmic particles using `BufferGeometry` for a highly optimized, dense galactic core.
* **Procedural Generation:** Utilizes advanced mathematical logic to calculate gravitational spin, branch angles, and random particle scattering.
* **Dynamic Color Interpolation:** Smoothly blends an intense, fiery inner core with a deep cosmic blue outer rim using Three.js color lerping.
* **Interactive 3D Camera:** Features full `OrbitControls`, allowing users to intuitively pan, zoom, and orbit around the galaxy in real-time.
* **Smooth Auto-Animation:** Includes an automated rendering loop that gracefully rotates the camera and scene using trigonometric time-based functions.

## 🛠️ Technologies Used
* **HTML5 & CSS3:** For the fullscreen canvas layout and seamless structure.
* **JavaScript (ES6 Modules):** The core engine handling the mathematical algorithms and particle lifecycle.
* **Three.js (WebGL):** The powerful 3D library used to render the points, materials, and scene environment.

## ⚙️ How to Run Locally
If you want to run or modify this project on your local machine, follow these steps:

1. Clone this repository or download the ZIP file.
2. Navigate to the project directory.
3. **Important:** Because this project uses ES6 module imports from a CDN, **it must be run via a local web server**. Simply opening the HTML file directly in a browser will result in a CORS error.
4. Use an extension like **Live Server** in VS Code, or any local HTTP server of your choice.
5. Open the provided localhost URL in your browser and explore the galaxy!

## 👨‍💻 About the Author
**Pankaj Tiwari** I am a developer who creates games and builds dynamic websites. Driven by a deep interest in mastering advanced mathematics, physics, and quantum mechanics, I enjoy building complex, physics-based simulations like this one. I am also the author of two books, including *Control Psychology: The Illusionary Game*.

## 📄 License
This project is open-source and proudly licensed under the **GNU General Public License v3.0 (GPL-3.0)**.
