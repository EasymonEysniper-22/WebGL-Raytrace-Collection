# WebGL-Raytrace-Collection

Photoreal WebGL ray-tracing FPS tech demo, built with [Three.js](https://github.com/mrdoob/three.js). Single file, zero local dependencies.

## NIGHTFALL — Photoreal FPS

A small-scope (single-room) but AAA-visual first-person shooter.

### Visual features (photoreal / ray-tracing feel)

- **Procedural PBR materials** — seamless, tileable textures generated at runtime (concrete, plaster, wood crates, rusted metal, brushed metal) with albedo / normal / roughness / metalness maps.
- **HDR pipeline** — ACES filmic tone mapping, HDR environment reflections.
- **Ray-tracing style effects** — SSAO ambient occlusion, bloom, volumetric god rays, floating dust motes, and a **planar screen-space mirror reflection** (wet-floor puddle) that reflects the live scene.
- **Film post-processing** — film grain, vignette, chromatic aberration.
- **Dynamic lighting** — low sun through a window, flickering hanging lamp, emissive panels.

### Gameplay

- WASD move · Mouse look · Left-click fire · Right-click aim (ADS) · R reload · Shift sprint · Space jump
- Procedurally synthesized audio (gunshot, reload, hit pings).
- Full gun feel: muzzle flash + dynamic light, recoil, ejected casings, tracers, bullet-hole decals, metal sparks / wood splinters / dust.
- Reactive targets: metal cans + wooden training dummies (3 hits to take down).

## Run

Open `index.html` in a browser (requires an internet connection for the Three.js CDN).

> Tip: open in a full browser tab (not an iframe preview) so pointer-lock mouse capture works.
