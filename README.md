# 🎮 Gamer Setup Portfolio

Welcome to my interactive web portfolio! This project was developed as a hands-on assignment to demonstrate 3D asset integration and front-end development capabilities. It consists of a web environment inspired by a sleek, dark-mode *Gamer Setup* with a *cyberpunk/neon* aesthetic, designed to seamlessly showcase my graphic and development work.

The site integrates a web-optimized interactive 3D model, real-time advanced vector animations, and a dynamic interface controlled entirely via JavaScript code.

---

## 💡 Features Description

This portfolio is fully interactive, utilizing native JavaScript logic to dynamically manipulate the environment and graphic components:

*   **🌓 Theme Toggle (Light/Dark Mode):** A global switch that overrides the CSS color palette in real time, shifting between a bright daytime layout and the ambient gamer dark mode.
*   **🔄 3D Rotation Animation:** A custom control that toggles the cinematic auto-rotation (`auto-rotate`) attribute of the monitor by manipulating the 3D element nodes via script.
*   **💡 Lighting Adjustments:** A dynamic button that alters the light exposure property of the 3D rendering to simulate switching ambient room lights on and off.
*   **🎨 RGB Color Customization:** A real-time color modifier that reconfigures the main CSS root variables, instantly mutating the setup's layout from cold tones to a vibrant Cyberpunk color scheme.

---

## 🔮 What is Blender?

**Blender** is a free and open-source 3D computer graphics software toolset used for creating animated films, visual effects, art, 3D-printed models, motion graphics, interactive 3D applications, and virtual reality. In this project, Blender was used as the core engine to model the low-poly monitor hardware, handle custom UV mapping, set up material textures, and export the final optimized asset into a web-ready `.glb` format.

---

## 🛠️ Technologies Used

*   **📐 3D Engine:** Blender 3D
*   **🌐 Web 3D Deployment:** Google `<model-viewer>` API (WebGL)
*   **🎬 Vector Animation:** Rive Runtime API
*   **🧠 Logic & Interactivity:** Native JavaScript (ES6+)
*   **🎨 Structure & Styling:** HTML5 & CSS3 (Glassmorphism & CSS Variables)

---

## 📁 Project Structure & Core Files

The project follows a clean and modular structure for the optimal management of multimedia resources and tridimensional assets:

```text
mi-portafolio/
│
├── assets/
│   ├── 3d/
│   │   └── monitor_interactivo.glb   <-- 3D Model exported from Blender
│   └── img/
│       └── mi-foto.jpg               <-- Student profile picture
│       └── rive-gif.jpg
│
├── index.html                        <-- Main HTML structure and JavaScript logic
├── style.css                         <-- Custom styling (Gamer theme & RGB palette)
🏫 Academic Context
📚 Course/Subject: Computer Graphics (Graficación)

👨‍🏫 Professor: Rodrigo Fidel Gaxiola Sosa

🤝 Credits & Acknowledgments
3D Asset Inspiration / Resources: Special thanks to the creator Heber Villalta for the reference guidelines/assets used during development.

👨‍💻 Author
Student: Rodrigo Santos Chale

Core Interests: Full-Stack Development (Flutter, Node.js) and Interactive Web Graphics.