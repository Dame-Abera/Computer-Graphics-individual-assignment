# Computer-Graphics-individual-assignment
# 3D Product Viewer (Basic Mesh Edition)

**Name:** Dame Abera  
**ID:** UGR/0123/15

---

## Overview
This project is an interactive 3D Product Viewer built with [Three.js](https://threejs.org/). Users can explore a product (a chair, built from basic geometries) with both manual mouse controls and automatic camera rotation. The viewer demonstrates foundational computer graphics concepts: scene setup, mesh composition, lighting, raycasting, animation, and camera controls.

## Features
- **Scene Setup:** Perspective camera, WebGL renderer, and responsive canvas.
- **3D Product:** A chair built from boxes and cylinders, centered at the origin.
- **Lighting:** Ambient and directional lighting for realistic shading.
- **Mouse Interaction:**
  - Hover to highlight parts and see their name.
  - Click to briefly change color and show part name.
- **Camera Animation:**
  - Automatic rotation around the product.
  - User mouse controls (orbit, pan, zoom) pause auto-rotation.
- **No Build Tools Needed:** Works by simply opening `index.html` in your browser.

## How to Run
1. **Download or clone this repository.**
2. **Open the `3d-product-viewer` folder.**
3. **Double-click `index.html`** (or right-click and choose "Open with" → your browser).
   - _No npm, no server, no build tools required._
   - _No CI/CD, npx, or Vite required._

## File Structure
```
3d-product-viewer/
  index.html        # Main HTML file (loads Three.js from CDN)
  src/
    main.js         # All viewer logic (no imports required)
    style.css       # Modern, responsive styles
```

## Notes
- If you see a blank page, check your browser's console for errors.
- Make sure all files are in the correct folders as shown above.
- This project uses Three.js and OrbitControls via CDN for maximum compatibility.
- **No CI/CD, npx, or Vite is needed.**

## Credits
- [Three.js](https://threejs.org/)
- [OrbitControls](https://threejs.org/docs/#examples/en/controls/OrbitControls)

---
Enjoy exploring your 3D product!

