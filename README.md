# Valentine Card

<p align="center">An animated Valentine's Day card with particle heart animation</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

## Features

- **Beautiful Heart Animation**: Particles form and follow a mathematical heart shape
- **Fully Responsive**: Perfect on desktop, tablet, and mobile devices
- **High-DPI Support**: Crisp rendering on Retina and high-resolution displays
- **Performance Optimized**: 
  - Smooth 40fps animation with requestAnimationFrame
  - Automatic particle count adjustment for mobile devices
  - Pauses when browser tab is hidden to save battery
- **Modern Code**: ES6+, strict mode, proper memory management
- **Mobile-First**: Dynamic viewport handling with `100dvh` support

## Live Demo

[**View the Valentine Card →**](https://rkruk.github.io/valentine-card/)

## Mobile Optimizations

- Fewer particles on mobile for better performance (16 vs 32)
- Responsive heart sizing based on viewport
- Touch-friendly with proper viewport configuration
- Handles device rotation seamlessly

## 🛠Technical Details

- **Pure Vanilla JavaScript** - No dependencies
- **Canvas 2D Animation** - Hardware accelerated
- **Mathematical Heart Curve**: `x = 16sin³(t), y = 13cos(t) - 5cos(2t) - 2cos(3t) - cos(4t)`
- **Particle Physics**: Attraction forces, friction, and trail effects
- **High-DPI Scaling**: Automatic device pixel ratio detection

## Story

I found part of this code in one of my old backups and decided to transform it into a Valentine's card for my wife. The original animation was partially hidden, so I rewrote the animation system, added responsive design, and optimized it for modern web standards.

## Customization

The heart size, particle count, and colors can be easily adjusted in the JavaScript configuration section. The animation maintains the same visual style while being fully optimized for performance.

---

<p align="center">Made with ❤️ by Rafał Kruk</p>
