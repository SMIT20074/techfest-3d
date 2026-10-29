# Techfest 3D: Step inside the core

An interactive 3D website for the Techfest CA Program "Build in 3D" task. Unofficial student concept.

## What it does
- **Scroll-driven camera:** a spline flight from outside the core, through its orbit ring, inside, and back out
- **Interactive core:** drag to spin, with inertia and mouse parallax
- **Six orbiting worlds:** hover a node for its label, click it (or use the buttons) and the core morphs into a new shape and recolours the whole page
- **Chapter colour transitions** driven by scroll, 2,200 additive particles, bloom-like halo
- Accessible: keyboard buttons for every node, skip link, reduced-motion mode, WebGL fallback
- Three.js 0.160 is vendored in `vendor/`, so no CDN is needed

## Run locally
```
python3 -m http.server 8000
```
Open http://localhost:8000 (ES modules need a server, not a double-click).

## Live demo
https://smit20074.github.io/techfest-3d/
