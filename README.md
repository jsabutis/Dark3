# Dark3

A three.js and GSAP scratch scene: one rotating cube on a full-viewport canvas, with GSAP tweening the page background underneath it.

Open `index.html` directly, no build step. three.js r128 and GSAP 3.12 load from cdnjs, so the first run needs network.

- `index.html` - canvas element and the two CDN scripts
- `script.js` - scene, camera, renderer, and the animation loop
- `styles.css` - full-bleed canvas, no scrollbars

Resizing the window does not currently update the camera aspect or the renderer size.
