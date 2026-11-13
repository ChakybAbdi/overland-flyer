# The Overland Flyer

A cinematic Wild West train robbery, rendered in real time with raw WebGL in a single
HTML file. No three.js, no build step, no assets: every mesh, the terrain, the lighting
and the colour grade are generated in about 2,000 lines of hand-written JavaScript and GLSL.

**[Live demo](https://chakybabdi.github.io/overland-flyer/)**

## Controls

- **Drag** to look around
- **Scroll** to zoom
- **Space** to pause

## What's in it

- Procedural geometry: locomotive, express car, coaches and caboose, riders on horseback,
  mesas and cacti, all built from a small primitive mesh builder with per-object palettes
- Procedural desert terrain, rails and locomotive smoke
- Hand-written vertex and fragment shaders with warm cinematic grading
- Letterbox bars, vignette and an animated title card in CSS on top of the canvas

## Run locally

Open `index.html` in any modern browser. That's it.
