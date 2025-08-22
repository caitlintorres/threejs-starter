# Three.js Starter – Spinning Cube

A simple starter project using [Three.js](https://threejs.org/) that renders a spinning cube with orbit controls.

![screenshot](screenshot.png)

---

## Features
- Three.js scene setup (scene, camera, renderer)
- OrbitControls (drag, zoom, pan)
- Directional + ambient light
- `DirectionalLightHelper` to visualize light direction
- `AxesHelper` to visualize world axes
- Responsive resize handling
- Animation loop with rotating cube

---

## Getting Started

### 1. Clone or download
Place the `index.html` file in a new folder.

### 2. Run a local server
Because the project uses ES modules, you **must** run it from a local server (not `file://`).

Examples:

```bash
# Python 3
python -m http.server

# Node.js (with http-server installed)
npx http-server
```

### 3. Open in browser

Visit:
```bash
http://localhost:8000
```
You should see a spinning cube.
Use your mouse to orbit (drag), zoom (wheel), and pan (right-drag).

---

## Controls

- Left-drag → Orbit around the scene
- Scroll wheel → Zoom in/out
- Right-drag → Pan
- Red square → Shows where the directional light is and the direction it shines
- AxesHelper → Red = X, Green = Y, Blue = Z

## Next Steps

- Replace the cube with other geometries (sphere, torus knot, etc.)
- Add textures (e.g. Earth map on a sphere)
- Add more lights and experiment with shadows
- Try loading a 3D model using GLTFLoader
