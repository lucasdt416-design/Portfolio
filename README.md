# Lucas Thomas · Portfolio

**Live:** https://personal-portfolio-w6hr.onrender.com

A one-page portfolio built as a single scroll-driven particle world. One three.js particle system, driven by custom GLSL shaders, reshapes itself into a different scene for every section: data streams for StockPulse, an electric motor for UTSM, wind turbines for UTWind, a radar, a sonar cave, blueprint gears and more. Project screenshots and photos live inside the 3D scene as panels that dissolve in and out of the particles.

- Plain HTML, CSS and JavaScript in one file, no build step
- three.js r128 and hand-written shaders
- Responsive layout: on phones, scenes and panels anchor to the page layout
- Respects `prefers-reduced-motion`

## Run locally

WebGL won't load images from a page opened straight from disk, so serve the folder:

```
python3 -m http.server
```

Then open http://localhost:8000.
