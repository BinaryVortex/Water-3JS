# Water-3JS

A stunning 3D water simulation built with Three.js, featuring realistic wave animations, dynamic reflections, particle effects, and post-processing bloom.

## 🌊 Demo

Experience the live demo: [https://binaryvortex.github.io/Water-3JS/](https://binaryvortex.github.io/Water-3JS/)

## ✨ Features

- **Realistic Water Shaders**: Custom vertex and fragment shaders for wave deformation, fresnel reflections, and color gradients.
- **Particle System**: Animated particles (bubbles/droplets) that interact with the water surface.
- **Post-Processing Effects**: Unreal Bloom Pass for enhanced lighting and visual appeal.
- **Interactive Controls**: Orbit controls for camera movement, and a GUI panel to tweak parameters in real-time.
- **Responsive Design**: Adapts to window resizing.
- **Performance Optimized**: Uses efficient noise functions and shader-based animations.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/BinaryVortex/Water-3JS.git
   ```
2. Open `index.html` in your web browser. No server required!

## 🛠️ Technologies Used

- **Three.js**: 3D graphics library
- **WebGL Shaders**: Custom GLSL vertex and fragment shaders
- **dat.GUI**: For interactive parameter controls
- **CDN Imports**: ES6 modules loaded from Skypack for simplicity

## 📸 Screenshots

![Water Simulation Screenshot](Screenshot%202025-10-26%20012418.png)

## 🎮 Controls

- **Mouse**: Orbit around the scene
- **GUI Panel**: Click the gear icon (top-right) to open the control panel and adjust:
  - Water properties (alpha, fresnel, wave amplitude, etc.)
  - Particle settings (count, speed, size)
  - Bloom effects (strength, radius, threshold)

## 📝 License

This project is open-source. Feel free to use, modify, and distribute.

## 👤 Author

Created by [BinaryVortex](https://github.com/BinaryVortex)