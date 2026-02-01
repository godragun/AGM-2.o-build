# AGM 2.0 Build

**BCS AGM 26 - Interactive 3D Interface**

An interactive 3D web experience featuring the BCS AGM logo built with Three.js. Click on individual letters (A, G, M, S) to toggle their illumination.

**Background image with 3D** – The interface blends a custom vortex-style background with the interactive 3D model for an immersive visual experience.

![Background with 3D](vortexa%20background.png)

## Features

- **Interactive 3D Model** – Explore the BCS AGM 26 logo in 3D
- **Click-to-Illuminate** – Click any letter to turn its lighting on or off
- **Responsive Design** – Works on desktop and touch devices
- **Orbit Controls** – Zoom in/out to explore the model

## Quick Start

1. Clone this repository
2. Open `index.html` in a modern web browser, or serve the folder locally:

   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js (npx)
   npx serve
   ```

3. Navigate to `http://localhost:8000` (or the URL shown)

## Project Structure

```
AGM/
├── index.html          # Main application
├── BCS AGM 26 1.glb    # 3D model
├── BCS AGM 26.glb      # 3D model variant
├── bcs logo .png       # BCS logo
├── vortexa background.png
├── source/             # Source assets (Blender files, letter models)
├── textures/           # Model textures
└── README.md
```

## Tech Stack

- **Three.js** – 3D rendering
- **OrbitControls** – Camera controls
- **GLB/GLTF** – 3D model format

## License

All rights reserved. BCS AGM materials.
